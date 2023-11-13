<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website HTML CSS Only | Codehal</title>
    <link rel="stylesheet" href="style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

*::selection {
    background: #00abf0;
    color: #081b29;
}

body {
    background-color: #081b29;
}

.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 20px 10%;
    background: transparent;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

.logo {
    position: relative;
    font-size: 25px;
    color: #ffffff;
    text-decoration: none;
    font-weight: 600;
}

.navbar a {
    font-size: 18px;
    color: #ffffff;
    text-decoration: none;
    font-weight: 500;
    margin-left: 35px;
    transition: .3s;
}

.navbar a:hover,
.navbar a.active {
    color: #00abf0;
}




.MQ-box {
  position: absolute;
  top: 155%;
  left: 5%;
  background-color: #081b29;
  border-radius: 50px;
  padding: 10px;
  width: 230px;
  height: 290px;
  cursor: pointer;
  transition: 1s;
  opacity: 0.1;
}

.MQ-box:hover {
  opacity: 1;
  box-shadow: 1px 1px 100px #00abf0
}

.MQ-pg {
  position: relative;
  top: 25%;
  margin-top: 7%;
  color: white;
}

.MQ-sa {
    position: absolute;
    top: 10%;
    left:20%;
 color: white;
}
.MQ-img {
  position: absolute;
  left: 60%;
  width: 90px;
  height: 90px;
  border-radius: 50px;
}



.WZIR-box {
  position: absolute;
  top: 155%;
  left: 29%;
  background-color: #081b29;
  border-radius: 50px;
  padding: 10px;
  width: 230px;
  height: 290px;
  cursor: pointer;
  transition: 1s;
  opacity: 0.1;
}

.WZIR-box:hover {
  opacity: 1;
  box-shadow: 1px 1px 100px #00abf0;  
}

.WZIR-pg {
  position: relative;
  top: 32%;
  margin-top: 7%;
  color: white;
}

.WZIR-sa {
    position: absolute;
    left: 50px;
 color: white;
}
.WZIR-img {
  position: absolute;
  left: 60%;
  width: 90px;
  height: 90px;
  border-radius: 50px;
}



.MR-box {
  position: absolute;
  top: 155%;
  left: 52%;
  background-color: #081b29;
  border-radius: 50px;
  padding: 10px;
  width: 230px;
  height: 290px;
  cursor: pointer;
  transition: 1s;
  opacity: 0.1;
}

.MR-box:hover {
  opacity: 1;
  box-shadow: 1px 1px 100px #00abf0 
}

.MR-pg {
  position: relative;
  top: 32%;
  margin-top: 7%;
  color: white;
}

.MR-sa {
    position: absolute;
    left: 50px;
 color: white;
}
.MR-img {
  position: absolute;
  left: 60%;
  width: 90px;
  height: 90px;
  border-radius: 50px;
}



.RUS-box {
  position: absolute;
  top: 155%;
  left: 75%;
  background-color: #081b29;
  border-radius: 50px;
  padding: 10px;
  width: 230px;
  height: 290px;
  cursor: pointer;
  transition: 1s;
  opacity: 0.1;
}

.RUS-box:hover {
  opacity: 1;
  box-shadow: 1px 1px 100px #00abf0 
}

.RUS-pg {
  position: relative;
  top: 32%;
  margin-top: 5%;
  color: white;
}

.RUS-sa {
    position: absolute;
    left: 50px;
 color: white;
}
.RUS-img {
  position: absolute;
  left: 60%;
  width: 90px;
  height: 90px;
  border-radius: 50px;
}



</style>

<body>

    <header class="header">
        <a href="#" class="logo">قــروب المــطــانـيـخ
        </a>

        <nav class="navbar">
            <a href="#" class="active">Home</a>
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Portfolio</a>
            <a href="#">Contact</a>
        </nav>

        
<div class="MQ-box">
       <img class="MQ-img" src="https://cdn.discordapp.com/attachments/993742700429983774/1170046201337491537/IMG_0746.jpg?ex=6560d7f0&is=654e62f0&hm=2749b96534d0bf55d1e8e537a0e162df355e55118c974df8c9d69d2418b495cb&">
       <p class="MQ-sa">SANJI_IXI</p>
       <p class="MQ-pg">Pedophile</p>
       <p class="MQ-pg">Gladiator player</p>
       <p class="MQ-pg">big nigger</p>
       <p class="MQ-pg">شايبنا</p>
    </div>
    
<div class="WZIR-box">
    <img class="WZIR-img" src="https://cdn.discordapp.com/attachments/952890780094193695/1167923967131140167/IMG_9749.jpg?ex=656259f4&is=654fe4f4&hm=e6f1d377e95e6f659ef5c80a5cc4c92185732df91846789478ce56485ac42dad">
     <p class="WZIR-sa">WZIR</p>
     <p class="WZIR-pg">N-WORD PASS</p>
     <p class="WZIR-pg">3nze</p>
     <p class="WZIR-pg">Slave owner</p>
     <p class="WZIR-pg">onion</p>
    </div>
    
    
<div class="MR-box">
    <img class="MR-img" src="https://cdn.discordapp.com/attachments/1173239760563748864/1173239841031458836/Mr_Gamr211_as_png.png?ex=65633bbf&is=6550c6bf&hm=79c9fdb53a78bce1f6f1e3424e5d47da09ddb3d088b4d411bb456e543c4defa2&">
     <p class="MR-sa">Mr_Gamr211</p>
     <p class="MR-pg">No life</p>
     <p class="MR-pg">Overwatch player</p>
     <p class="MR-pg">Fat</p>
     <p class="MR-pg">Slave</p>
    </div>
    
    
<div class="RUS-box">
    <img class="RUS-img" src="https://cdn.discordapp.com/attachments/817089871159361536/1173243304834498560/image.png?ex=65633ef9&is=6550c9f9&hm=7d7ed4ddd1caf2daeb5aaeaa6258ee60dd9e8b7c91713483843a93982d266ec3&">
     <p class="RUS-sa">WARIO69</p>
     <p class="RUS-pg">مرحبًا! أنا أستخدم واتساب</p>
     <p class="RUS-pg">قحطاني</p>
     <p class="RUS-pg">كل البنات يتمنونه</p>
     <p class="RUS-pg">يصلي ويصوم</p>
     <p class="RUS-pg">gril sniffer</p>
    </div>
    
    
    
    </header>

</body>

</html>
