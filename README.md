# netflix-project
[6:25 pm, 12/04/2023] ....: <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Netflix</title>
</head>
<body>
    <header class="showcase">
        <div class="showcase-top">
            <img src="logo.png" alt="Netflix Logo">
            <a href="#" class="btn btn-rounded">Sign In</a>
        </div>
        <div class="showcase-content">
            <h1>Unlimited movies, TV shows and more.</h1>
            <h3>All of Netflix, starting at just ₹ 199.</h3>
            <p>Ready to watch? Enter your email to create or restart your membership.</p>
            <input type="email" name="email" id="mail" placeholder="Email address">
            <a href="#" class="btn btn-lg">GET STARTED ></a>
        </div>
    </header>

    <section class="style-cards">
        <div class="card-0">
            <img src="2.jpg" alt="Netflix Mobile">
            <div class="desc-0">
                <h1>Create profiles for kids.</h1>
                <h3>Send kids on adventures with their favourite characters in a space made just for them—free with your membership.</h3>
            </div>
        </div>
        <div class="card-1">
            <div class="desc-1">
                <h1>Enjoy on your TV.</h1>
                <h3>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</h3>
            </div>
            <img src="tv.png" alt="Netflix TV">
            <video class="video-1" autoplay="" playsinline="" muted="" loop=""><source src="1.m4v" type="video/mp4"></video>
        </div>
        <div class="card-2">
            <img src="3.jpg" alt="Netflix Mobile">
            <div class="desc-2">
                <h1>Download your shows to watch offline.</h1>
                <h3>Save your favourites easily and always have something to watch.</h3>
            </div>
        </div>
        <div class="card-3">
            <div class="desc-3">
                <h1>Watch everywhere.</h1>
                <h3>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</h3>
            </div>
            <img src="4.png" alt="Device-Pile-In">
            <video class="video-2" autoplay="" playsinline="" muted="" loop=""><source src="2.m4v" type="video/mp4"></video>
        </div>
    </section>

    <section class="lastsec">
        <div class="faq">
            <h1>Frequently Asked Questions</h1>
            <ul class="questions">
                <li>What is Netflix?</li>
                <li>How much does Netflix cost?</li>
                <li>Where can I watch?</li>
                <li>How do I cancel?</li>
                <li>What can I watch on Netflix?</li>
                <li>Is Netflix good for kids?</li>
            </ul>
            <p>Ready to watch? Enter your email to create or restart your membership.</p>
            <div class="input">
                <input type="email" name="email" placeholder="Email Address">
                <a href="#" class="btn-rounded"><button>GET STARTED ></button></a>
            </div>
        </div>
    </section>


    <footer class="footer">
        <p>Questions? Call 000-800-040-1843</p>
        <div class="footer-cols">
            <ul>
                <li><a href="#">FAQ</a></li>
                <li><a href="#">Investor Relations</a></li>
                <li><a href="#">Privacy</a></li>
                <li><a href="#">Speed Test</a></li>
            </ul>
            <ul>
                <li><a href="#">Help Centre</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Cookie Preferences</a></li>
                <li><a href="#">Watch for Free</a></li>
            </ul>
            <ul>
                <li><a href="#">Account</a></li>
                <li><a href="#">Ways to Watch</a></li>
                <li><a href="#">Corporate Information</a></li>
                <li><a href="#">Legal Notices</a></li>
            </ul>
            <ul>
                <li><a href="#">Media Centre</a></li>
                <li><a href="#">Terms of Use</a></li>
                <li><a href="#">Contact Us</a></li>
                <li><a href="#">Netflix Originals</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>
Footer
[6:25 pm, 12/04/2023] ....: :root{
    --primary-color: #e50914;
    --dark-color: #141414;
    --light-color: #f4f4f4;
}

*{
    margin: 0;
    padding: 0;
}

body{
    font-family: Arial, Helvetica, sans-serif;
    background: #000000;
    color: #999999;
}

ul{
    list-style: none;
}

h1,h2,h3,h4{
    color: #ffffff;
}

h3{
    font-weight: lighter;
}

a{
    color: #ffffff;
    text-decoration: none;
}

p{
    margin: 0.5rem 0;
    font-weight: bold;
    color: #ffffff;
}

img{
    width: 100%;
}

.showcase{
    width: 100%;
    height: 100vh;
    position: relative;
    background: url("1.jpg") no-repeat center center/cover;
}

.showcase::after{
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 1;
    background: rgba(0, 0, 0, 0.4);
    box-shadow: 120px 100px 250px #000000 , inset -120px -100px 250px #000000;
}

.showcase-top{
    position: relative;
    z-index: 2;
    height: 90px;
}

.showcase-top img{
    width: 140px;
    position: absolute;
    top: 50%;
    left: 0;
    transform: translate(40% , -50%);
}

.showcase-top a{
    position: absolute;
    top: 50%;
    right: 0;
    transform: translate(-60% , -50%);
}

.showcase-content{
    position: relative;
    margin: 0 26%;
    z-index: 2;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    align-items: center;
    margin-top: 9rem;
}

.showcase-content h1{
    font-weight: 700;
    font-size: 64px;
    margin: 0 30px;
    max-width: 800px;
    line-height: 74.5px;
}

.showcase-content h3{
    color: white;
    font-size: 25px;
    margin: 16px 0;
}

.showcase-content p{
    font-size: 19.2px;
    font-weight: 300;
    padding-top: 0.5rem;
    padding-bottom: 1rem;
}

.showcase-content input{
    position: absolute;
    left: 0;
    bottom: -8vh;
    width: 454px;
    height: 3rem;
    font-size: 1rem;
    padding-left: 0.5rem;
}

.btn{
    display: inline-block;
    background: var(--primary-color);
    color: white;
    padding: 0.5rem 1.2rem;
    font-size: 1rem;
    text-align: center;
    border: none;
    cursor: pointer;
    border-radius: 2px;
    margin-right: 0.5rem;
    outline: none;
    box-shadow: 0 5px 3px rgba(0, 0, 0, 0.45);
}

.btn:hover{
    opacity: 0.9;
}

.btn-rounded{
    border-radius: 5px;
}

.showcase-content .btn-lg{
    position: absolute;
    right: 0;
    bottom: -8vh;
    padding: 0.5rem 1.2rem;
    font-size: 1.5rem;
    text-transform: uppercase;
    height: 36px;
    width: 14rem;
}

.card-0 , 
.card-1,
.card-2,
.card-3{
    border-top: 8px rgb(69, 69, 69) solid;
    padding: 50px;
}

.card-0{
    position: relative;
    display: inline-grid;
    grid-template-columns: 40% 50%;
    text-align: left;
    align-items: center;
    padding: 25px 45px 50px;
}

.desc-0{
    padding-left: 100px;
}

.card-1{
    position: relative;
    display: inline-grid;
    grid-template-columns: 50% 40%;
    text-align: left;
    align-items: center;
    padding: 25px 45px 50px;
}

.desc-1{
    padding-left: 80px;
}

.style-cards h1{
    font-size: 3rem;
    padding: 1rem;
    padding-left: 0;
}

.style-cards h3{
    font-size: 1.6rem;
    line-height: 2rem;
}

.card-1 video{
    position: relative;
    width: 100%;
    height: 54%;
    grid-column: 2/2;
    grid-row: 1/2;
    z-index: -1;
}

.card-1 img{
    grid-column: 2/2;
    grid-row: 1/2;
}

.card-2{
    position: relative;
    display: inline-grid;
    grid-template-columns: 40% 50%;
    text-align: left;
    align-items: center;
    padding: 25px 45px 50px;
}

.desc-2{
    padding-left: 100px;
}

.card-3{
    position: relative;
    display: inline-grid;
    grid-template-columns: 50% 40%;
    text-align: left;
    align-items: center;
    padding: 25px 45px 50px;
}

.desc-3{
    padding-left: 80px;
    padding-right: 20px;
}

.card-3 img{
    width: 110%;
    grid-column: 2/2;
    grid-row: 1/2;
}

.card-3 video{
    position: relative;
    top: -87px;
    left: 125px;
    width: 65%;
    height: 78%;
    grid-column: 2/2;
    grid-row: 1/2;
    z-index: -1;
}

.faq{
    text-align: center;
}

.faq h1{
    padding-bottom: 40px;
    font-size: 3rem;
}

.questions{
    display: flex;
    flex-direction: column;
    flex-basis: 40%;
    align-items: center;
}

.questions li{
    padding: 20px 30px;
    margin: 5px;
    font-size: 1.6rem;
    background-color: #303030;
    color: white;
    text-align: left;
    width: 50%;
}

.faq p{
    padding-top: 60px;
    font-size: 1.2rem;
    font-weight: 200;
}

.input{
    display: inline-grid;
    align-items: center;
    grid-template-columns: 50% 40%;
}

.input input{
    width: 600px;
    height: 3rem;
}

.input button{
    height: 3.25rem;
    width: 320px;
    left: 20px;
    text-align: center;
    background-color: var(--primary-color);
    font-size: 1.5rem;
    padding: 15px 32px;
    border: none;
    border-radius: 2px;
    color: white;
}

.footer{
    max-width: 70%;
    margin: 1rem auto;
    overflow: auto;
}

.footer ,
.footer a{
    color: #999999;
    font-size: 0.9rem;
}

.footer p{
    margin-bottom: 1.5rem;
}

.footer .footer-cols{
    display: grid;
    grid-template-columns: repeat(4 , 1fr);
    grid-gap: 2rem;
}

.footer li{
    line-height: 2.4;
}
[6:25 pm, 12/04/2023] ....: <!DOCTYPE html>
<html lang="en">
    <head>
        <title>Netflix</title>
        <script src="./netflix.js" type="text/javascript"></script>
        <script src="./languageSwicher.js" type="text/javascript"></script>
        <link rel="stylesheet" href="netflixStyle.css">
    </head>
    <body onload="setUpLanguage()" onresize="updateView()">
        <div class="background-wrapper">
            <img class="background" src="https://assets.nflxext.com/ffe/siteui/vlv3/5039d301-b891-47b2-b755-553e5c874395/e792888a-2c70-4a78-9dfd-b8a26e767ae4/BR-en-20200210-popsignuptwoweeks-perspective_alpha_website_small.jpg" srcset="https://assets.nflxext.com/ffe/siteui/vlv3/5039d301-b891-47b2-b755-553e5c874395/e792888a-2c70-4a78-9dfd-b8a26e767ae4/BR-en-20200210-popsignuptwoweeks-perspective_alpha_website_small.jpg 1000w, https://assets.nflxext.com/ffe/siteui/vlv3/5039d301-b891-47b2-b755-553e5c874395/e792888a-2c70-4a78-9dfd-b8a26e767ae4/BR-en-20200210-popsignuptwoweeks-perspective_alpha_website_medium.jpg 1500w, https://assets.nflxext.com/ffe/siteui/vlv3/5039d301-b891-47b2-b755-553e5c874395/e792888a-2c70-4a78-9dfd-b8a26e767ae4/BR-en-20200210-popsignuptwoweeks-perspective_alpha_website_large.jpg 1800w" alt>
        </div>
        <div id="app">
            <div id="header">
                <a href="https://www.netflix.com/">
                    <img id="logo" src="https://logodownload.org/wp-content/uploads/2014/10/netflix-logo-5.png">
                </a>
            </div>
            <div id="container">
                <form id="log-in-form" action="" method="POST">
                    <div class="label-container">
                        <h2 id="sign-in-text"></h1>
                    </div>
        
                    <div class="box-container" id="email-container">
                        <input class="field" id="email-field" name="email" type="text" oninput="update('email-field', 'email-label', 'email-inputError')" onfocus="inputOnFocus('email-field', 'email-label', 'email-container')" onblur="inputOnBlur('email-field', 'email-label', 'email-container', 'email-inputError')" required>
                        <label class="label" id="email-label" for="email-field"></label>
                    </div>
                    <div class="inputError" id="email-inputError"></div>
                    <div class="box-container" id="pwd-container">
                        <input class="field" id="pwd-field" name="password" type="password" oninput="update('pwd-field', 'pwd-label', 'pwd-inputError')" onfocus="inputOnFocus('pwd-field', 'pwd-label', 'pwd-container')" onblur="inputOnBlur('pwd-field', 'pwd-label', 'pwd-container', 'pwd-inputError')" required>
                        <label class="label" id="pwd-label" for="pwd-field"></label>
                    </div>
                    <div class="inputError" id="pwd-inputError"></div>
                    <div class="box-container" id="login-button-container">
                        <input id="login-button" type="submit" value="Sign In">
                    </div>
                    <div class="checkbox-row">
                        <span class="checkbox-container" tabindex="0" id="checkbox" onclick="toggleCheckBox()" onblur="checkBoxOnBlur()">
                            <svg id="icon" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="check" class="svg-inline--fa fa-check fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M173.898 439.404l-166.4-166.4c-9.997-9.997-9.997-26.206 0-36.204l36.203-36.204c9.997-9.998 26.207-9.998 36.204 0L192 312.69 432.095 72.596c9.997-9.997 26.207-9.997 36.204 0l36.203 36.204c9.997 9.997 9.997 26.206 0 36.204l-294.4 294.401c-9.998 9.997-26.207 9.997-36.204-.001z"></path></svg>
                        </span>
                        <label id="remember-me-label" onclick="toggleCheckBox()"></label>
                        
                        <a href="https://www.netflix.com/br/LoginHelp">
                            <label id="help"></label>
                        </a>
                    </div>
                </form>
                <form action="" method="POST" class="fb-login-form">
                    <button class="fb-login-button" type="submit">
                        <div class="fb-login">
                            <img class="fb-icon" src="https://assets.nflxext.com/ffe/siteui/login/images/FB-f-Logo__blue_57.png">
                            <span class="fb-btn-text" id="fb-btn-text"></span>
                        </div>
                    </button>
                </form>
                <div class="sign-up">
                    <span id="sign-up"></span>
                    <a class="sign-up-link" id="sign-up-link" href="https://www.netflix.com/br-en/"></a>
                </div>
                <div class="reCAPTCHA">
                    <p id="reCAPTCHA-text">
                        <span id="reCAPInfo"></span>
                        <span class="learn-more-button">
                            <button id="learn-more" onclick="showTermsOfUse()"></button>
                        </span>
                    </p>
                    <div id="terms-of-use">
                        <span>
                            <span id="reCAP1"></span>
                            <a class="blue-link" id="reCAP2" href="https://policies.google.com/terms"></a>
                            <span id="reCAP3"></span>
                            <a class="blue-link" id="reCAP4" href="https://policies.google.com/terms"></a>
                            <span id="reCAP5"></span>
                        </span>
                    </div>
                </div>
            </div>
            <footer>
                <div class="footer" id="footer">
                    <p class="footer-header">
                        <span id="footer-header"></span>
                        <a class="footer-link">0800-761-4632</a>
                    </p>
                    <ul class="inline-footer-ul">
                        <li class="inline-footer-li">
                            <a class="footer-link" href="https://help.netflix.com/legal/giftterms" id="gift"></a>
                        </li>
                        <li class="inline-footer-li">
                            <a class="footer-link" href="https://help.netflix.com/legal/termsofuse" id="terms"></a>
                        </li>
                        <li class="inline-footer-li">
                            <a class="footer-link" href="https://help.netflix.com/legal/privacy" id="privacy"></a>
                        </li>
                    </ul>
                    <div class="language-selector-container">
                        <div class="language-selector-boundaries">
                            <select name="language" id="language-selector" onchange="loadTexts(getSelectedLanguage())">
                                <option value="en">English</option>
                                <option value="pt">Português</option>
                            </select>
                            <img class="globe-icon" src="https://climefish.eu/wp-content/uploads/sites/18/2017/08/icon-globe-400px.png">
                        </div>
                    </div>
                </div>
            </footer>
        </div>
    </body>
</html>
[6:25 pm, 12/04/2023] ....: body {
    position: relative;
    overflow-y: scroll;
    overflow-x: hidden;
    width: 100%;
    height: 1092.33px;
    margin: 0;
    padding: 0;
    font-family: Helvetica, Arial, sans-serif;
    display: block;
}

#app {
    position: absolute;
    margin: 0;
    top: 0;
    left: 0;
    padding: 0;
    width: 100%;
    height: 1092.33px;
    background-color: rgba(0, 0, 0, 0.6);
}

.background-wrapper {
    position: absolute;
    background-size: cover;
    height: 100%;
    min-height: 100vh;
    overflow: hidden;
    width: 100%;
    z-index: -1;
}

.background-wrapper .background {
    min-height: 100%;
    min-width: 100%;
}

#header {
    position: relative;
    width: 100vw;
    margin: 22.5px 0 20px 3vw;
}

#logo {
    height: auto;
    width: 167px;
}

#container {
    position: relative;
    display: block;
    background-color: rgba(0, 0, 0, 0.7);
    width: 314px;
    height: 575.33px;
    left: 50vw;
    margin-left: -233.5px;
    border-radius: 4px;
    padding: 60px 68px 40px 68px;
    margin-bottom: 90px;
}


#log-in-form {
    position: relative;
    display: block;
    width: 100%;
    height: 340.667px;
}

#sign-in-text {
    margin: 0;
    font-size: 32px;
    color: white;
}

.label-container {
    position: relative;
    display: block;
    width: 100%;
    margin-bottom: 28px;
}

.inputError {
    position: relative;
    top: -10px;
    padding: 0 3px 6px 3px;
    font-size: 13px;
    color: #E87C03;
}

.inputError#email-inputError, .inputError#pwd-inputError {
    display: none;
}

.box-container {
    position: relative;
    width: 100%;
    height: 50px;
    margin-bottom: 16px;
    border-radius: 4px;
    border-width: 0;
    background-color: #363636;
}

#login-button-container {
    margin-top: 40px;
    margin-bottom: 12px;
    height: 48px;
}

.field {
    position: relative;
    width: 274px;
    height: 32px;
    border-radius: 4px;
    outline: 0 none;
    border-width: 0;
    padding: 16px 20px 0 20px;
    color: white;
    background-color: transparent;
}

#login-button {
    position: relative;
    width: 100%;
    height: 100%;
    border-width: 0;
    border-radius: 4px;
    background-color: red;
    color: white;
    font-weight: bold;
    text-align: center;
    padding: 0;
    font-size: 16px;
}

.checkbox-row {
    position: relative;
    width: 100%;
    top: 2px;
    font-size: 13px;
}

.checkbox-container {
    position: absolute;
    background-color: white;
    outline: 0 none;
    opacity: 60%;
    border-radius: 2px;
    border-width: 0;
    width: 16px;
    height: 16px;
    padding: 0;
    margin: 0;
}

#icon {
    color: black;
    position: absolute;
    pointer-events: none;
    width: 12px;
    left: 50%;
    top: 50%;
    margin-left: -6px;
    margin-top: -6px;
}

input#remember-me:focus {
    opacity: 100%;
}

#remember-me-label {
    position: relative;
    color: white;
    opacity: 60%;
    user-select: none;
    width: max-content;
    margin: 0 0 0 20px;
}

#help {
    position: relative;
    cursor: pointer;
    text-align: right;
    float: right;
    color: white;
    text-decoration: none;
    opacity: 90%;
}

#help:hover {
    text-decoration: underline;
}

.label {
    position: absolute;
    cursor: text;
    user-select: none;
    font-size: 16px;
[6:25 pm, 12/04/2023] ....: opacity: 50%;
    font-family: Arial, Helvetica, sans-serif;
    left: 20px;
    top: 15px;
    color: white;
    transition: font-size 100ms ease, top 100ms ease, opacity 100ms ease;
}
.fb-login-form {
    position: relative;
    width: 100%;
    height: fit-content;
}
.fb-login-button {
    position: relative;
    display: block;
    margin: 16px 0 0 0;
    padding: 0;
    background: none;
    border-width: 0;
    height: 20px;
    cursor: pointer;
}
.fb-login {
    position: relative;
    padding: 0;
    margin: 0;
    height: fit-content;
    width: fit-content;
}
.fb-icon {
    position: relative;
    margin: 0 10px 0 0;
    padding: 0;
    width: 20px;
    height: 20px;
    vertical-align: middle;
    user-select: none;
}
.fb-btn-text {
    position: relative;
    color: #737373;
    font-size: 13px;
    font-weight: 500;
    user-select: none;
    left: -4px;
}

.sign-up {
    position: relative;
    width: 100%;
    margin: 16px 0 0 0;
    color: #737373;
}
.sign-up-link {
    color: white;
    text-decoration: none;
}

.sign-up-link:hover {
    text-decoration: underline;
}

.reCAPTCHA {
    position: relative;
    margin: 13px 0 0 0;
    width: 100%;
    height: 135.667px;
}
#reCAPTCHA-text {
    position: relative;
    text-align: left;
    font-size: 13px;
    color: #737373;
}

.learn-more-button {
    position: relative;
    margin: 0;
    padding: 0;
    height: fit-content;
    width: fit-content;
}
#learn-more {
    position: relative;
    background-color: transparent;
    border: none;
    color: #0071eb;
    cursor: pointer;
    display: inline;
    font-family: inherit;
    font-size: inherit;
    padding: 0;
    outline: 0 none;
}

#learn-more:hover {
    text-decoration: underline;
}

#terms-of-use {
    position: relative;
    visibility: hidden;
    width: 100%;
    text-align: left;
    font-family: inherit;
    font-size: 13px;
    color: #737373;
}

.blue-link {
    color: #0071eb;
    cursor: pointer;
    font-family: inherit;
    font-size: inherit;
    text-decoration: none;
}

.blue-link:hover {
    text-decoration: underline;
}

footer {
    position: absolute;
    width: 100vw;
    height: 236px;
    bottom: 0;
    background: rgba(0, 0, 0, 0.75);
}

.footer {
    position: relative;
    display: block;
    padding: 30px 0 30px 0;
    height: 148px;
    margin-left: 10.27vw;
    margin-right: 10.27vw;
    color: #999;
}

.footer-header {
    position: relative;
    padding: 0;
    width: 100%;
    margin: 0 0 30px 0;
    font-size: 1rem;
}

.inline-footer-ul {
    position: relative;
    width: 100%;
    padding: 0;
    margin: 0;
}

.inline-footer-li {
    display: inline-block;
    vertical-align: text-top;
    margin-top: 0;
    width: 18.26vw;
    min-width: fit-content;
    padding-right: 12px;
    list-style-type: none;
    font-size: 13px;
}

.footer-link {
    cursor: pointer;
    color: #999;
    text-decoration: none;
}

.footer-link:hover {
    text-decoration: underline;
}

.language-selector-container {
    position: relative;
    width: 100%;
    margin: 20px 0 0 0;
}

.language-selector-boundaries {
    position: absolute;
    display: inline-block;
    padding: 0;
    margin: 0;
    width: 137.33px;
    height: 48px;
    border: none;
    background: none;
}

#language-selector {
    position: absolute;
    -webkit-appearance: none;
    appearance: none;
    color: #999;
    padding: 12px 26px 12px 50px;
    background-color: black;
    font-size: 13px;
    text-align: left;
    text-decoration: none;
    border: 1px solid #333;
    width: 100%;
    height: 100%;
    text-indent: 0;
    line-height: 1.7;
}

.language-selector-boundaries:after {
    position: absolute;
    user-select: none;
    content: "";
    top: 20px;
    right: 8px;
    width: 0;
    height: 0;
    border: 6px solid transparent;
    border-color: #999 transparent transparent transparent;
}

#language-selector option {
    font-weight: normal;
    display: block;
    white-space: pre;
    min-height: 1.2em;
    padding: 0px 2px 1px;
}

.globe-icon {
    position: absolute;
    top: 12px;
    left: 12px;
    width: 25px;
}
[6:25 pm, 12/04/2023] ....: const ids = [
    "sign-in-text", 
    "email-label",
    "email-inputError",
    "pwd-label",
    "pwd-inputError",
    "remember-me-label",
    "help",
    "fb-btn-text",
    "sign-up",
    "sign-up-link",
    "reCAPInfo",
    "learn-more",
    "reCAP1",
    "reCAP2",
    "reCAP3",
    "reCAP4",
    "reCAP5",
    "footer-header",
    "gift",
    "terms",
    "privacy"
]

const labels = Object.freeze (
    {
        'en': [
            "Sign In",
            "Email or phone number",
            "Please enter a valid email or phone number.",
            "Password",
            "Your password must contain between 4 and 60 characters.",
            "Remember me",
            "Need help?",
            "Login with Facebook",
            "New to Netflix? ",
            "Sign up now.",
            "This page is protected by Google reCAPTCHA to ensure you're not a bot. ",
            "Learn more",
            "The information collected by Google reCAPTCHA is subject to the Google ",
            "Privacy Policy",
            " and ",
            "Terms of Service",
            ", and is used for providing, maintaining, and improving the reCAPTCHA service and for general security purposes (it is not used for personalized advertising by Google).",
            "Questions? Call ",
            "Gift Card Terms",
            "Terms of Use",
            "Privacy Statement",
        ],
        'pt': [
            "Entrar",
            "Email ou número de telefone",
            "Informe um email ou número de telefone válido.",
            "Senha",
            "A senha deve ter entre 4 e 60 caracteres.",
            "Lembrar-se de mim",
            "Precisa de ajuda?",
            "Conectar com o Facebook",
            "Novo por aqui? ",
            "Assine agora.",
            "Esta página é protegida pelo Google reCAPTCHA para garantir que você não é um robô. ",
            "Saiba mais",
            "As informações recolhidas pelo Google reCAPTCHA estão sujeitas à ",
            "Política de Privacidade",
            " e ",
            "Termos de Uso",
            ", e são usadas para oferecer, manter e melhorar o serviço reCAPTCHA e por questões de segurança (não são usadas para exibir anúncios personalizados pelo Google).",
            "Dúvidas? Ligue ",
            "Termos dos Cartões pré-pagos",
            "Termos de uso",
            "Declaração de privacidade",
        ],
    }
);

const loadTexts = function (lang) {
    let text = lang === 'pt' ? labels.pt : labels.en;
    for (let i = 0; i < ids.length; i++) {
        document.getElementById(ids[i]).innerHTML = text[i];
    }
    document.getElementById('login-button').value = text[0];
    document.lang = lang;
}

const getSelectedLanguage = function () {
    let selector = document.getElementById("language-selector");
    let value = selector.options[selector.selectedIndex].value;
    return value;
}

const getBrowserLanguage = function () {
    let lang = navigator.language || navigator.userLanguage;
    lang = lang.slice(0, 2);
    return lang;
}

const setSelectedLanguage = function (lang) {
    lang = lang === 'pt' ? lang : 'en';
    document.getElementById('language-selector').value = lang;
}

const setUpLanguage = function () {
    let lang = getBrowserLanguage();
    lang = lang.slice(0, 2);
    loadTexts(lang);
    setSelectedLanguage(lang);
}
[6:25 pm, 12/04/2023] ....: var email = "", pwd = "", checked = true;

const update = function (id, targetId, inputErrorId) {
    let newValue = document.getElementById(id).value;
    email = id === 'email-field' ? newValue : email;
    pwd = id === 'pwd-field' ? newValue : pwd;
    updateStyle(targetId);
    checkAndUpdate(id, inputErrorId);
    adjustLoginFormHeight();
}

const inputOnFocus = function (id, targetId, boxId) {
    updateStyle(targetId, document.getElementById(id).value);
    let box = document.getElementById(boxId);
    box.style.backgroundColor = 'rgb(70, 70, 70)';
}

const updateStyle = function (targetId) {
    let el = document.getElementById(targetId);
    el.style.top = '7px';
    el.style.fontSize = '10px';
    el.style.opacity = '50%';
}

const inputOnBlur = function (id, targetId, boxId, inputErrorId) {
    let el = document.getElementById(targetId);
    let field = document.getElementById(id);
    let box = document.getElementById(boxId);
    let value = field.value;
    box.style.backgroundColor = '#363636';
    if(value.toString().length === 0) {
        el.style.top = '15px';
        el.style.fontSize = '16px';
        el.style.opacity = '60%';
    }
    checkAndUpdate(id, inputErrorId);
    adjustLoginFormHeight();
}

const checkAndUpdate = function (id, inputErrorId) {
    let field = document.getElementById(id),
        inputError = document.getElementById(inputErrorId);

    if(!isValid(id)) {
        adjustLoginButtonContainer(id, 24)
        field.style.borderBottomWidth = '2px';
        field.style.borderBottomColor = '#E87C03';
        inputError.style.display = 'block';
    } else {
        adjustLoginButtonContainer(id);
        field.style.borderBottomWidth = '0';
        field.style.borderBottomColor = 'transparent';
        inputError.style.display = 'none';
    }
}

const adjustLoginButtonContainer = function (id, pixels = 40) {
    let px = pixels + 'px'
    if(id === 'pwd-field') {
        document.getElementById('login-button-container').style.marginTop = px;
    }
}
const isValid = function (elementId) {
    if(elementId === 'email-field') {
        let email_OK = false, emailArray = email.split('@');
        if (emailArray.length === 2) {
            if (emailArray[1].length > 1) {
                let innerEmailArray = emailArray[1].split('.');
                if (innerEmailArray.length > 1) {
                    if (innerEmailArray[1].length > 0) {
                        email_OK = true;
                    }
                }
            }
        }
        let phone_OK = ((!isNaN(email)) && (email.length > 7));
        return email_OK || phone_OK;
    }
    if(elementId === 'pwd-field') {
        return (pwd.length > 3 && pwd.length < 61);
    }
    return false;
}

const toggleCheckBox = function () {
    checked = !checked;
    document.getElementById('icon').style.display = checked ? 'inherit' : 'none';
    let checkbox = document.getElementById('checkbox');
    checkbox.focus();
    checkbox.style.opacity = '100%';
}

const checkBoxOnBlur = function () {
    checkbox.style.opacity = '60%';
}

const adjustLoginFormHeight = function () {
    let emailError = isHidden(document.getElementById('email-inputError')),
        pwdError = isHidden(document.getElementById('pwd-inputError'));
    document.getElementById('log-in-form').style.height = !emailError && !pwdError ? 'fit-content' : '340.667px';
}

const isHidden = function (el) {
    return (el.offsetParent === null)
}

const showTermsOfUse = function () {
    document.getElementById('learn-more').style.visibility = 'hidden';
    document.getElementById('terms-of-use').style.visibility = 'visible';
}

const updateView = function () {
    let viewWidth = window.innerWidth;
    if(viewWidth < 745) {
        document.getElementById('app').style.backgroundColor = 'black';
        document.getElementById('container').style.width = '87vw';
        document.getElementById('container').style.left = '0';
        document.getElementById('container').style.marginLeft = '0';
        document.getElementById('container').style.padding = '60px 5vw 40px 5vw';
        let inputFields = document.getElementsByClassName('field');
        let width = (viewWidth*0.87) - 40;
        for (let i = 0; i < inputFields.length; i++) {
            document.getElementById(inputFields[i].id).style.width = `${width}px`;
        };
    } else {
        document.getElementById('app').style.backgroundColor = 'rgba(0, 0, 0, 0.6)';
        document.getElementById('container').style.width = '314px';
        document.getElementById('container').style.left = '50vw';
        document.getElementById('container').style.marginLeft = '-233.5px';
        document.getElementById('container').style.padding = '60px 68px 40px 68px';
        let inputFields = document.getElementsByClassName('field');
        for (let i = 0; i < inputFields.length; i++) {
            document.getElementById(inputFields[i].id).style.width = '274px';
        };
    }
}
[6:25 pm, 12/04/2023] ....: public class MergeSort {

	public static void main(String[] args) {
		int[] arr = { 70, 50, 30, 10, 20, 40, 60 };

		int[] merged = mergeSort(arr, 0, arr.length - 1);

		for (int val : merged) {
			System.out.print(val + " ");
		}
	}

	public static int[] mergeTwoSortedArrays(int[] one, int[] two) {
		int[] sorted = new int[one.length + two.length];

		int i = 0;
		int j = 0;
		int k = 0;

		while (i < one.length && j < two.length) {
			if (one[i] < two[j]) {
				sorted[k] = one[i];
				k++;
				i++;
			} else {
				sorted[k] = two[j];
				k++;
				j++;
			}
		}

		if (i == one.length) {
			while (j < two.length) {
				sorted[k] = two[j];
				k++;
				j++;
			}
		}

		if (j == two.length) {
			while (i < one.length) {
				sorted[k] = one[i];
				k++;
				i++;
			}
		}

		return sorted;
	}

	public static int[] mergeSort(int[] arr, int lo, int hi) {
		if (lo == hi) {
			int[] br = new int[1];
			br[0] = arr[lo];

			return br;
		}

		int mid = (lo + hi) / 2;

		int[] fh = mergeSort(arr, lo, mid);
		int[] sh = mergeSort(arr, mid + 1, hi);

		int[] merged = mergeTwoSortedArrays(fh, sh);

		return merged;
	}

}
