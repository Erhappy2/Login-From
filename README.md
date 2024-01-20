<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="login.css">
	 <style>
        body {
    margin: 0;
    padding: 0;
    align-items: center;
    background-image: url(login-From/happy.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    height: 100vh;
}
.main-container{
    display: inline-flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: rgb(78, 78, 247);
    max-width: 30%;
    position: absolute;
    top: 5%;
    bottom: 5%;
    left: 15%;
    right: 15%;
    margin: auto;
    border-radius: 30px;
    box-shadow: 0px 0px 28px 20px;
    color: white;

}
img {
    /* width: 111px; */
    object-fit: cover;
    max-width: 100%;
    border-radius: 50%;
}
.user-image {
    width: 35%;
    object-fit: cover;
}
.container {
    display: inline-flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 5px 20px;
}
.detalis-continer {
    display: inline-flex;
    flex-direction: column;
}
.detalis-continer {
    display: inline-flex;
    flex-direction: column;
    width: 100%;
    margin-top: 20px;
}   
.cancel-container {
    width: 100%;
    margin: 16px 0;
    display: inline-flex;
    justify-content: space-between;
    padding: 12px 20px;
}
label {
    /* background: aqua; */
    margin-top: 15px;
    margin-bottom: 5px;
}
.submit-button{
    margin-top: 15px;
}
input {
    font-size: 16px;
    border: none;
    outline: none;
    font-family: -webkit-body;
    padding: 10px;
    border-radius: 30px;
}
label {
    /* background: aqua; */
    margin-top: 15px;
    margin-bottom: 9px;
    margin-left: 2px;
    font-size: 16px;
}
.submit-button {
    margin-top: 15px;
    font-size: 16px;
    padding: 10px;
    border: none;
    border-radius: 20px;
}
button.cancelbtn {
    font-size: 15px;
    padding: 10px 33px;
    border-radius: 30px;
    background-color: #fc4343;
}
.cancel-container span {
    font-size: 18px;
    padding: 10px 20px;
}
    </style>
</head>
<body>
    <div class="main-container">
        <h2>Login from</h2>
        <form action="/action_page.php"  method="post">
            <div class="container">
                <div class="user-image">
                    <img src="login-From/user-img.jpg" alt="user-img">
                </div>
                <div class="detalis-continer">
                    <label for="Uname"><B>Username</B></label>
                    <input type="text" placeholder="Enter Your Username" required>
                    <label for="password"> <B>Password</B></label>
                    <input type="password" placeholder="Enter Your Password" required>
                    <Button class="submit-button" type="submit">Login</Button>
                    <label>
                        <input type="checkbox" name="remember">Remember me
                    </label>
                </div>
                <div class="cancel-container" >
                    <button type="button" class="cancelbtn">Cancel</button>
                    <span>Forget <a href="#">Password</a></span>
                </div>
            </div>
    </div>
    
</form>
</body>
</html>
