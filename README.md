<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>BS PRACTICE</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <!-- .container-fluid#backdrop>.container -->
    <div class="container-fluid" id="backdrop">
        <div class="container">
            <!-- header.row>.col-md-12>h1.text-uppercase{[header]} -->
            <header class="row">
                <div class="col-md-12">
                    <h1 class="text-uppercase">[header]</h1>
                </div>
            </header>
            <!-- nav.row>.col-md-12>h1.text-uppercase{[nav]} -->
            <nav class="row">
                <div class="col-md-12">
                    <h1 class="text-uppercase">[nav]</h1>
                </div>
            </nav>
            <!-- .row>main.col-md-8+aside.col-md-4 -->
            <div class="row">
                <main class="col-md-8">
                    <!--  h1.text-uppercase{[content]} -->
                    <h1 class="text-uppercase">[content]</h1>
                </main>
                <aside class="col-md-4">
                    <!--  h1.text-uppercase{[content]} -->
                    <h1 class="text-uppercase">[aside]</h1>
                </aside>
            </div>
            <!-- section.row>(.col-md-3.promo>h3{[promo $]})*4 -->
            <section class="row">
                <div class="col-md-3 promo">
                    <h3>[promo 1]</h3>
                </div>
                <div class="col-md-3 promo">
                    <h3>[promo 2]</h3>
                </div>
                <div class="col-md-3 promo">
                    <h3>[promo 3]</h3>
                </div>
                <div class="col-md-3 promo">
                    <h3>[promo 4]</h3>
                </div>
            </section>
            <!-- footer.row>.col-md-12>h1.text-uppercase{footer} -->
            <footer class="row">
                <div class="col-md-12">
                    <h1 class="text-uppercase">footer</h1>
                </div>
            </footer>
    </div>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
</body>
</html>
