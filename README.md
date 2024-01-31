<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <link rel="stylesheet" type="text/css" href="/style.css">
</head>

<body>

    <header>
        <h2 class="logo">Logo</h2>
        <nav class="navigation">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
            <button class="btnLogin-popup">Login</button>
        </nav>
    </header>
<!--icon copy from https://ionic.io/ionicons-->
    <div class="wrapper">
        <span class="icon-close">
            <ion-icon name="close"></ion-icon>
        </span>
        <div class="form-box login">
            <h2>Login</h2>
            <form action="#">
                <div class="input_box">
                    <span class="icon">
                        <ion-icon name="mail-outline"></ion-icon>
                    </span>
                    <input type="email" required>
                    <label >Email</label>
                </div>
                <div class="input_box">
                    <span class="icon">
                        <ion-icon name="lock-closed-outline"></ion-icon>
                    </span>
                    <input type="password" required>
                    <label>Password</label>
                </div>
                <div class="remember_forgot">
                    <label><input type="checkbox">
                    remember me</label>
                    <a href="#">forgot password?</a>
                </div>
                <button type="submit" class="btn">Login</button>
                <div class="login-register">
                <p>Want to create an account?
                    <a href="#" class="register-link">Register</a>
                </p>
                </div>
            </form>    
        </div>


        <div class="form-box register">
            <h2>Registration</h2>
            <form action="#">
                <div class="input_box">
                    <span class="icon">
                        <ion-icon name="person-circle-outline"></ion-icon>
                    </span>
                    <input type="text" required>
                    <label >Username</label>
                </div>
                <div class="input_box">
                    <span class="icon">
                        <ion-icon name="mail-outline"></ion-icon>
                    </span>
                    <input type="email" required>
                    <label >Email</label>                             
                </div>
                <div class="input_box">
                    <span class="icon">
                        <ion-icon name="lock-closed-outline"></ion-icon>
                    </span>
                    <input type="password" required>
                    <label>Password</label>
                </div>
                <div class="remember_forgot">
                    <label><input type="checkbox">
                    I agree with the terms and conditions.</label>
                </div>
                <button type="submit" class="btn">Register</button>
                <div class="login-register">
                <p>Already have an account?
                    <a href="#" class="login-link">Login</a>
                </p>
                </div>
            </form>    
        </div>
    </div>  

    <script src="script.js"></script>
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
</body>
</html>
