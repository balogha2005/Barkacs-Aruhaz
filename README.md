# Lucky kávézó        <div class="footer">
            <footer class="container">
                <div class="row">
                    <div class="col-sm-6 col-lg-4 offset-lg-1">
                        <h1 class="mt-3">Kapcsolat</h1>
                        <ul>
                            <li><img src="./img/email.png" alt="Email logo">bobi@barkacs.hu</li>
                            <li><img src="./img/telefon.png" alt="Telefon logo">+36-1-123-45-67</li>
                            <li><p>Munkanapokon 09:00 - 16:00</p></li>
                        </ul>
                    </div>
                    <div class="col-sm-6 col-lg-4">
                        <h1 class="mt-3">B-OBI Magazin</h1>
                        <p>Iratkozzon fel a barkács magazinunkra!</p>
                        <form>
                            <div class="input-group mb-3">
                                <input type="text" id="email" class="form-control" placeholder="E-mail
                                " aria-label="E-mail" aria-describedby="button-addon2">
                                <div class="input-group-append">
                                    <button onclick="feliratkozas()" class="btn btn-success" type="button" id="button-addon2">Feliratkozom</button>
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
                <p class="text-center">Copyright © 1999 - 2023 B-OBI Kereskedelmi Kft.</p>
            </footer>
        </div>







        .footer{
    background-color: #096081;
    color: white;
    height: 30%;
    min-width: 125%;
}

footer li{
    list-style-type: none;
}

footer li>img{
    width: 15px;
    margin-right: 10px;
}

footer h2{
    font-size: 2em;
    text-align: left 10px;
}