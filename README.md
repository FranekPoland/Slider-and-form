# zadanie1
Slider and form

<!DOCTYPE html>
<html lang="pl">

<head>
    <meta charset="utf-8">
    <link href="https://fonts.google.com/specimen/Roboto:100, 200, 300, 400">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!--from T. Klocek and http://blog.kamilbrenk.pl/meta-tag-viewport-kiedy-i-jak-uzywac/ -->
    <link rel="stylesheet" href="https://github.com/FranekPoland/zadanie1/blob/master/css">
</head>

<body>
    <div class="wrapper">
        <div class="main content">
            <div id="photos">
                <img class="photo" src="https://images.alphacoders.com/130/13003.jpg" alt="1">
                <img class="photo" src="https://images.alphacoders.com/395/39541.jpg" alt="2">
                <img class="photo" src="https://images.alphacoders.com/905/90503.jpg" alt="3">
                <img class="photo" src="https://images2.alphacoders.com/864/86410.jpg" alt="4">
                <img class="photo" src="https://images2.alphacoders.com/197/19762.jpg" alt="5">
                <div class="title">Slider and form</div>
                <div class="form">
                    <form class="formul">
                        <div>
                            <label for="content">Skąd się tutaj wziąłeś?</label>
                        </div>
                        <div>
                            <textarea for="content" rows="3" cols=50 id="content" name="content" placeholder="Tutaj możesz coś o sobie napisać"></textarea>
                        </div>
                        <div>
                            <input type="Submit" value="Dodaj">
                        </div>
                        <p>Kim chcesz zostać jak dorośniesz?</p>
                        <div>
                            <label>
                                <input type="radio" name="job">Strażak</label>
                        </div>
                        <div>
                            <label>
                                <input type="radio" name="job">Policjant</label>
                        </div>
                        <div>
                            <label>
                                <input type="radio" name="job">Lekarz</label>
                        </div>
                        <div>
                            <label>
                                <input type="radio" name="job" checked>Programista</label>
                        </div>
                        <div>
                            <label for="approval" class="question">Czy chcesz polecieć w kosmos?</label>
                        </div>
                        <div>
                            <label>
                                <input type="checkbox" name="approval">Zgadzam się</label>
                        </div>
                            <button class="btn" type="reset">RESET</button>
                            <button class="btn" type="submit">SUBMIT</button>
                    </form>
                    </div>
                </div>
            </div>
        </div>
</body>
