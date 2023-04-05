<html>
    <head>
        <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">
    <link href="https://fonts.googleapis.com/css?family=Poppins:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i&display=swap" rel="stylesheet">

    <title>Библиотека за валидиране на лични данни на човек</title>

    <link rel="stylesheet" type="text/css" href="assets/css/bootstrap.min.css">

    <link rel="stylesheet" type="text/css" href="assets/css/font-awesome.css">

    <link rel="stylesheet" href="assets/css/style.css">
    </head>
 <body>


    <header class="header-area header-sticky">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <nav class="main-nav">
                        <!-- ***** Logo Start ***** -->
                        <a href="index.html" class="logo"><em>Библиотека за валидиране на лични данни на човек</em></a>
                        <!-- ***** Logo End ***** -->
          <ul class="nav">
                             <li><a href="index.php">Начало</a></li>
                            <li><a href="name.php" class="active">Валидиране по Име</a></li>
                            <li><a href="egn.php">Валидиране по ЕГН</a></li>
                            <li><a href="lnch.php">Валидиране по ЛНЧ</a></li> 
                            </ul>        
                        <a class='menu-trigger'>
                            <span>Menu</span>
                        </a>
                     </nav>
                </div>
            </div>
        </div>
    </header>
      <section class="section section-bg" id="call-to-action" style="background-image: url(assets/images/about-image-2-940x460.jpg)">
        <div class="container">
            <div class="row">
                <div class="col-lg-10 offset-lg-1">
                    <div class="cta-content">
                        <br>
                        <br>
                        
                 <form method="post" action="#"> 
                 </br>
                <p />
                  Име:  
               <input type="text" name="firstName" /> 
                  <p />
                  Презиме:   
                  <input type="text" name="secName" /> 
                  <p />
                  Фамилия:  
                  <input type="text" name="lastName" /> 
                  <p />
                <input type="submit" name="submit" value="Валидиране" /> 
                 </form> 
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <?php
    if (isset($_POST['submit'])){ 
        echo 'hii'; 
}
?>
 </body>
</html>