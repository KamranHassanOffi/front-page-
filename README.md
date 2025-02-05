<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./class.css">
</head>
<body>
    <div class="container">
        <header>
             <nav class="navbar">
                <div class="info">
                    <div class="logo"><img src="./nexcent.png" height="30px"></div>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Features</a></li>
                        <li><a href="#">Community</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Pricing</a></li>
                        <li><button >Register now</button></li>
                    </ul>
                </div>
             </nav>
        </header>
        <section class="hero">
            
            <div class="text-content">
                <h1>Lessons and insights <br> <span>From 8 Years</span></h1>
                <p>Where to grow your business as a photographer: site or social media?</p>
                <button>Register</button>
                
            </div>
            <img src="./Illustration.png" alt="Illustration">
            
        </section>  
        <div class="page">
            <div class="active"></div>
            <div></div>
            <div></div>
        </div>
    </div>
     <div class="mid">
         <div class="start">
            <h1>Our Clients</h1>
            <p>we have been working with some fortune 500+ clients</p>
         </div>
        <div class="brand ">
            <a href="#"><img src="./Logo.png "></a>
            <a href="#"><img src="./Logo (1).png"></a>
            <a href="#"><img src="/Logo (2).png"></a>
            <a href="#"><img src="/Logo (3).png"></a>
            <a href="#"><img src="/Logo (4).png"></a>
            <a href="#"><img src="/Logo (5).png"></a>
           <a href="#"><img src="/Logo (2).png"></a>
        </div>

        <div class="manage">
            <h1>Manage Your entire community </h1>
            <h1>in a single system</h1>
            <p>who is nexcent suitable for?</p>
        </div>  
          
     </div>

    <div class="card-container">
        <div class="cards">
            <div class="card-content">
              <img src="./Icon (2).png" alt="">
              <h1>Membership</h1>
              <h1>Organizarion</h1>
              <p>Our membership management software provides full automation of membership renewals and payments</p>
             </div>
        </div>
    
        <div class="cards">
              <div class="card-content">
                 <img src="./Icon.png" alt="">
                 <h1>National</h1>
                 <h1> Associations</h1>
                 <p>Our membership management software provides full automation of membership renewals and payments</p>
              </div>
        </div>
    
        <div class="cards">
             <div class="card-content">
                 <img src="/Icon (1).png" alt="">
                 <h1>Clubs And</h1>
                 <h1> Groups</h1>
                 <p>Our membership management software provides full automation of membership renewals and payments</p>
             </div>
        </div>
    </div>

    <div class="semi-mid">
         <div class="text1">
            <h1>Pellentesque suscipit fringilla libero eu.</h1>
            <button>Get a Demo </button>

         </div>
    </div>

    <footer>
        <div class="end">
            <div class="text2">
                <img  src="./nexcent.png" width="700px">
                <p>Copyright © 2020 Landify UI Kit.</p>
                <p>All rights reserved</p>
                <ul class="except">
                   <li><a href="#"><img src="./insta.png" ></a></li>
                   <li><a href="#"><img src="./gol.png" ></a></li>
                   <li><a href="#"><img src="./twitter.png" ></a></li>
                   <li><a href="#"><img src="./Social Icons.png" ></a></li>
                </ul>
               
            </div>

            <div class="text2">
                <h3>Company</h3>
                <ul>
                     <li><a href="#">about us</a></li>
                     <li><a href="#">Blog</a></li>
                     <li><a href="#">Contact us</a></li>
                     <li><a href="#">pricing</a></li>
                     <li><a href="#">Testimonials</a></li>
                </ul>
            </div>

            <div>
                <h3>Support</h3>
                <ul>
                  <li><a href="#">Help center</a></li>
                  <li><a href="#">Terms of service</a></li>
                  <li><a href="#">Legal</a></li>
                  <li><a href="#">Privacy policy</a></li>
                  <li><a href="#">Status</a></li>
                </ul>
              </div>
            <div class="text2">
                <h3>Stay up to date</h3>
                <form class="btn2">
                    <input type="email" placeholder="Your email address">
                    <button  type="submit"><img src="./Vector.png" ></button>
                </form>
            </div>
                
            </div>
        </div>
    </footer>


     

</body>
</html>







*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.container{
    background-color: #F5F7FA;
}
.navbar{
    background-color:white;
    padding: 15px 30px;
    border-radius: 5px;
    padding-left: 15px;
    padding-right: 15px;
    width: 100%;
}
.info{
  display: flex;
  align-items: center;
  justify-content: space-around;
}
.info li{
    list-style: none;
    font-size: 18px;
    display: inline-block;
}
.info a{
    font-weight: bold;
    text-decoration: none;
    margin-right: 40px;
    color: black;
    font-size: 15px;
}
button{
    background-color: green;
    padding: 10px;
    border-radius: 5px;
    border: none;
    color: white;
    cursor: pointer;
}
.hero{
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-top: 100px;
}
.text-content {
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center; 
    align-items: flex-start; 
    gap: 10px; 
    font-size: 30px;
}
.text-content button{
    margin-top: 20px;
    border-radius: 5px;
    padding: 10px;
    width: 100px;
}
.text-content p{
   font-size: 15px;
  color: gray;
}
.text-content span{
    color: green;
}
.hero img{
    width: 40%;
    max-width: 500px;
}
.page{
    display: flex;
    justify-content: center;
    margin-top: 10px;
}
.page div{
    width: 10px;
    height: 10px;
    background-color: gray;
    border-radius: 50%;
    margin: 10px 5px;
}
.page div.active{
    background-color: green;
}

.brand{
  display: flex;
  justify-content: space-evenly;
  margin-top: 30px;
  height: 30px;
  
  
}
.start{
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    margin-top: 30px;
    gap: 10px;
}
.start h1{
    color: #4D4D4D;
    font-weight: bold;
    
}
.start p{
    color: #717171;
}
.mid{
    display: flex;
    flex-direction: column;
    gap: 30px;
    margin-left: 10px;
    margin-right:10px ;
    
}
.manage{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 40px;
    color: #4D4D4D; 
    
    
}
.manage p{
    color: #717171;
    margin-top:10px ;
}
.card-container{
    display: flex;
    justify-content: center;
    flex-wrap:wrap ;
    gap: 25px;
    margin-top: 100px;
   
}
.cards{
    width: 500px;
    border-radius: 10px;
    box-shadow: 0px 5px 10px rgb(70, 71, 71);
    cursor: pointer;
}
.card-content{
   display: flex;
   justify-content: center;
   align-items: center;
   flex-direction: column;
   text-align: center;
    
    
}
.card-content p{
    font-size: 18px;
    margin-top: 10px;
    margin-bottom: 20px;
}
.card-content img{
    height: 90px;
    margin-top: 10px;
    margin-bottom: 10px;
    
}
.semi-mid{
    margin-top: 10px;
    margin-bottom: 5px;
    background-color:#F5F7FA;
    padding: 10px;
}
.text1{
    display: flex;
    margin-top: 60px;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    gap: 40px;
    
}
footer {
    background-color: #1E242B;
    color: white;
    padding: 40px 80px;
    
}

.end {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    align-items: flex-start;
    gap: 120px;
}

.text2 {
    flex: 1;
    min-width: 200px;
}

.text2 img {
    width: 120px;
    margin-bottom: 10px;
}

.text2 p {
    margin: 5px 0;
    font-size: 14px;
    color: #ccc;
}


.except {
    list-style: none;
    display: flex;
    gap: 15px;
    padding: 0;
    margin-top: 15px;
}

.except li {
    display: inline-block;
    margin-top: 10px;
}

.except li a img {
    width: 24px;
    height: 24px;
   
}


h3 {
    font-size: 25px;
    margin-bottom: 15px;
    color: white;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    margin-bottom: 8px;
}

ul li a {
    text-decoration: none;
    color: #bbb;
    font-size: 14px;
    transition: color 0.3s ease;
}



form {
    display: flex;
    align-items: center;
    background: #2C333A;
    border-radius: 5px;
    padding: 5px;
    margin-top: 10px;
}

input[type="email"] {
    border: none;
    background: transparent;
    padding: 8px;
    flex: 1;
    color: white;
    outline: none;
}

input::placeholder {
    color: #bbb;
}

button {
    background: transparent;
    border: none;
    color: white;
    font-size: 18px;
    cursor: pointer;
}
.btn2 button img {
    width: 100%;
    height: 100%;
    object-fit: contain; 
}
