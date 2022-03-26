<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>man website</title>
    <style>
        body{
    background-image: url("images/nitish.jpg");
    background-repeat: no-repeat;
    width: 90%;

}
.continer{
    width: 100%;
    min-height: 100%;
    padding-left: 8%;
    padding-right: 8%;
    box-sizing: border-box;
    overflow: hidden;
    
}
.navbar{
width: 100%;
display: flex;
align-items: center;  
}
.logo{
width: 50px;
cursor: pointer;
margin: 30px 0;
}

.row{
    display: flex;
    justify-content: space-between;
    align-items:center ;
    margin: 100px 0;
}
.col-1{
    flex-basis: 30%;
    position: relative;
    margin-left: 10%;
}
.col-1 h2{
    font-size: 54px;
}
.col-1 h3{
    font-size: 34px;
    color: red;
    
    margin: 20px 0 10px
}
.col-1 p{
    font-size: 16px;
    color: #3d2786;
    font-weight: 100;
}
button{
    width: 40px;
    border: 0;
    padding: 12px 10px;
    color: #fff;
    background: linear-gradient(to right, #fb5283, #ff357f);
    border-radius: 6px;
    cursor: pointer;
    transition: width 1.5s;
}
button img{
    width: 90px;
    display: none;


}
button:hover img{
    display: block;
}
button:hover{
    width: 160px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.col-1::after{
    content: '' ;
    width: 10px;
    height: 57%;
    background: linear-gradient(to right, #fb5283, #ff357f);
    position: absolute;
    left: -40px;
    top: 8px;
}
col-2 {
   position: relative;
   flex-basis: 60%;
   display: flex;
   align-items: center;
}
.col-2 .controller{
  width: 90%;
}

.social{
    height: 13px;
    margin: 70px 0;
    cursor: pointer;
} 
.logo-1, .logo-2, .logo-3,
.logo-4, .logo-5, .logo-6 
{
    height: 50px;
    margin: 30px 0;
    cursor: pointer;
    margin: 16px;
   

}
.logo-1, .logo-2, .logo-3,
.logo-4, .logo-5, .logo-6 
{
     text-align: center;
}
    </style>
</head>
<body>
    <div class="continer">
        <div class="navbar">
            <img src="images/letter-n-icon-png-21901(1).png" class="logo">
            
        </div>
        <div class="row">
            <div class="col-1">
                <h2>This is Nitish Jangra! <br>in one word</h2>
                <h3>a learner</h3>
                <p>वाणी रसवती यस्य,यस्य श्रमवती क्रिया ।<br>
                    लक्ष्मी : दानवती यस्य,सफलं तस्य जीवितं ।।
                </p>
                <button type="button"><img src="images/emog.png" alt=""></button>
            </div>
            <div class="row">
                <div class="col-2">
                    <img src="mages/nitish.jpg" class="controller">
                </div>
                <div class="social">
                    <img src="images/face.png" class="logo-1">
                    <img src="images/bloges.png" class="logo-2">
                    <img src="images/email.png" class="logo-3">
                    <img src="images/insta.png" class="logo-4">
                    <img src="images/tryhack.webp" class="logo-5">
                    <img src="images/you.png" class="logo-6">
                </div>
            
        </div>
    </div>
</body>
</html>
