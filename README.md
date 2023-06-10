# landingpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>BEAUTY PRODUCTS & SALON website design</title>
</head>
<body>
    <section class="header">
        <nav>
            <a href="index.htm"><img src="images/logo.png" alt="" srcset=""></a>
            <div class="nav-links" id="navLinks">
                <i class="fa fa-times" onclick="hideMenu()"></i>
                <ul>
                    <li><a href="">HOME PAGE</a></li>
                    <li><a href="">ABOUT US</a></li>
                    <li><a href="">PRODUCTS</a></li>
                    <li><a href="">CONTACT US</a></li>
                </ul>
            </div>
            <i class="fa fa-bars" onclick="showMenu()"></i>

        </nav>
        <div class="text-box">
            <h1>BEAUTY PRODUCT'S & SALON</h1>
            <p class="text-box-info">Beauty Products are constituted mixtures of chemical compounds derived from either natural sources,or synthetically created ones.These are used for various purposes.those designed for personal care and skin care can be used to cleanse the skin and Salon is a place where your hair can be given special treatments to improve the appearance.</p>
            <a class="hero-btn" href="">Vist Us to know more</a>
        </div>
    </section>
    <!--PRODUCTS-->
    <section class="PRODUCTS">
        <h1>Available Products & Salon tretments</h1>
        <p>Available products:Foundation,Mascara,Concealer,Eyeshadow,Eyeliner,Blush,Face Primer,MAC Cosmetic,Highlighter,lip Liner,CC Cream,Setting Spray,Lip gloss.</p>
        <div class="row">
            <div class="PRODUCTS-col">
                <h3>Hairspa</h3>
                <p>Hairspa is an extensive process that involves deep cleansing,massaging,steaming and masking to make hair healthy and shiny.It is a procedure that tackles common hair concerns like dandruff,hair fall,damaged hair etc, while also making it strong and soft.</p>
            </div>
            <div class="PRODUCTS-col">
                <h3>Hair cut</h3>
                <p>The act or a process of cutting and sharping the hair.some cuts are like:Hi-tope fade,Comb over,Regular haircut,temple fade,Caesar cut,Layered cut,Crew cut,Bob with Bangs,U cuts,Long layered cut etc..</p>
            </div>
            <div class="PRODUCTS-col">
                <h3>Hair-Treatment</h3>
                <p>It refer to any means of managing common hair related problems such as hair fall,dryness,dandruff,frizzy hair,thinning hair,and so on. Some treatments are like Keratin treatment,Brazillan blowout,Keratin Express.</p>
            </div>
            </div>
        </div>
    </section>
    <!--Beauty-->
    <section class="Beauty">
        <h1>Our Beauty treatments</h1>
        <p>Hair-cutting,colouring and styling.</p>
        <p>Waxing and other forms of hair removal.</p>
        <p>Nail treatments</p>
        <p>Facials and skin care treatments.</p>
        <p>Tanning.</p>
        <p>Massages.</p>
        <div class="row">
            <div class="Beauty-col">
                <img src="/images/INDIA.png" alt="">
                <div class="layer">
                    <h3>INDIA</h3>
                </div>
            </div>
            <div class="Beauty-col">
                <img src="/images/ANDHRA PRADESH.png" alt="">
                <div class="layer">
                    <h3>ANDHRA PRADESH</h3>
                </div>
            </div>
            <div class="Beauty-col">
                <img src="/images/GUNTUR.png" alt="">
                <div class="layer">
                    <h3>GUNTUR</h3>
                </div>
            </div>
        </div>
    </section>
    <!--Call for more-->
    <section class="cfm">
        <h1>GO-THROUGH FOR VARIOUS BEATUY TIPS AND TREATMENTS <br> Anywhere from The World</h1>
        <a href="" class="hero-btn">CONTACT US</a>
        <p>If you have any questions or would like to make a purchase. <br> please contact us:<br>
        .Email:<br>beauty products@gmail.com <br>.Pno:123-456-5678<br>.Address:41-31India,AP.          </P>
    </section>
    <!--Footer-->
    <section class="footer">
        <h4>About Us</h4>
        <p>Beauty Products and Salon. <br> we can take care for your skin we give you healthy skin.<br>
so many treatments are available to improve your skin care. </P>
            <p>~by kshatriya Hyendavi Bai</p>
        </div>
        <div class="pic">
          <!DOCTYPE html>
<html>
    <head>
       <title>Display image</title>
    </head>
<body>
<H1>some beauty things</H1>
<p>
<img src="C:\Users\DELL\Downloads\20230609_112756.jpg" >
<img src="C:\Users\DELL\Downloads\20230609_112852.jpg">
</p> 
</p>
</p>
</body>
</html>
    
        </div>
<!--Javscript for Toggle Menu-->
    <script>
        var navLinks=document.getElementById("navLinks")
        function showMenu(){
            navLinks.style.righ="0";
        }
        function hideMenu(){
            navLinks.style.righ="-300px";
        }
    </script>
</body>
</html>
