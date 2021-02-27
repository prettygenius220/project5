<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temi's Laundry</title>
    <style>
     *{
      text-decoration: none;
     list-style: none;
     margin: 0;
     padding: 0;
     }


   .temi{
    background-image: url(project5/image/image1.jpg);
    width: 100%;
    height: 100%;
    border: 2px solid brown;
    text-align: center;
    background-repeat: no-repeat;
    background-size: cover;

}

h1{
    color: royalblue;
    font-size: 70px;
    margin-top: 15%;
    font-family: Calibri;
}

a{
    float: right;
    margin-right: 5%;
    padding: 2%;
}

li{
    color: black;
    font-weight: bold;
}

li:hover{
    color: red;
    
}

.second{
    background-color: azure;
    width:100%;
    height: 50%;
    border: 2px solid grey;
    padding: 4%;
}

hr{
    width:80%;
    
}

h2{
    font-family: Calibri;
    font-weight: bold;

}

.first{
    font-size: 30px;
    font-family: Calibri;
    margin-top:20px;
    font-weight: bold;
    
}

.namey{
    margin-right: 45px;
    height: 25px;
    border-radius: 15px;
}

.third{
    font-size: 20px;
    font-family: Calibri;
    margin-right: 20px;
    
    
}

.pick{
    padding:10%;
    margin-top: 40px;
    margin-left: 7%;
}

.m{
    height: 25%;
    margin-top: 50px;
    width: 40%;
    border-radius: 10px;
}

button{
   padding:7px;
   margin-left: 35%;
   width: 10%;
   color: white;
   font-weight: bold;
   background-color: purple;
   border-radius: 10px;
   font-size: 25px;
   font-family: Calibri;
   text-align: center;

}

.pic{
    float: right;
    margin-top: -14%;
    margin-right:23%;

}

img{
     width:120%;
    height: 75%;
}
</style>
<body>
    <div class="temi">
        <nav>
            <ul>
                <a href="#">
                    <li>Pick up</li>
                </a>

                <a href="#">
                    <li>About us</li>
                </a>
                
                <a href="#">
                    <li>Call us</li>
                </a>
                
            </ul>
        </nav>
        <h1>TEMI's LAUNDRY SERVICE</h1>
    </div>

    <div class="second">
        <h2>Contact Us</h2>
        <hr>

        <form class="first" action="#">

            <label for="name">Name: </label>
            <input class="namey" type="text" id="name">

            <label for="phone">Phone: </label>
            <input class="namey" type="text" id="phone">

        </form>

        <form class="third" action="#">
            <p>
                <b>Issue :</b>    
                <input class="pick" type="checkbox" id="pickup">
                <label for="pickup">Pick up</label>

                <input class="pick" type="checkbox" id="delivery">
                <label for="delivery">Delivery</label>

                <input class="pick" type="checkbox" id="complain">
                <label for="complain">Complain</label>
            </p>

            <label for="message"><b>Message:</b> </label>
            <input class="m" type="text" id="message">
            
            
        </form>
        <button >Send</button>

        <div class="pic">
            <img src="project5/image/image2.jpg" alt="contact us">
        </div>
    </div>

    
</body>
</html>
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/prettygenius220/project5/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
