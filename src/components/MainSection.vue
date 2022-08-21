<template>
    <div class="section">
        <section>
            <div class="container">
                <div class="left">
                    <h2>We are revolutionising your concept of comfort</h2>
                    <br>
                    <p>Created with a can do achievers mindset, A  self-onboarding application with features that open you to a new way </p>
                    <br>
                    <button class="button" style="font-size:17px;">Get Started</button>
                    <br>
                <div class="store">
                        <img src="@/assets/apple.png" alt="apple" style="padding-top:10px; margin-right:10px;">
                        <img src="@/assets/google.png" alt="google" style="padding-top:10px;">
                </div>
                </div>
                <div class="right">
                        <img src="@/assets/pexel1.png" alt="" class="img1">
                    
                    
                        <img src="@/assets/pexel2.png" alt="" class="img2">
                    
                    
                        <img src="@/assets/pexel3.png" alt="" class="img3">

                        <img src="@/assets/pexel4.png" alt="" class="img4">
                    
                </div>
            </div>


            <main>

                <div class="container-1">
                    <div class="text">
                        <h2>Work in the way that works for you!</h2>
                        <h4>What will you like to manage with Leapsail</h4>
                    </div>
                    <div class="clone">
                      <div class="tour"> 
                        <img src="@/assets/e1.png" alt="" class="dot">
                        <p class="one">Tour</p>
                        <img src="@/assets/icon.png" alt="" class="icon">
                      </div>
                      <div class="tour"> 
                        <img src="@/assets/e2.png" alt="" class="dot">
                        <p class="two">Webinar</p>
                        <img src="@/assets/icon.png" alt="" class="icon">
                      </div>
                      <div class="tour"> 
                        <img src="@/assets/e3.png" alt="" class="dot">
                        <p class="three">Educational</p>
                        <img src="@/assets/icon.png" alt="" class="icon">
                      </div>
                      <div class="tour"> 
                        <img src="@/assets/e4.png" alt="" class="dot">
                        <p class="four">Finance</p>
                        <img src="@/assets/icon.png" alt="" class="icon">
                      </div>
                      <div class="tour"> 
                        <img src="@/assets/e5.png" alt="" class="dot">
                        <p class="five">Investment</p>
                        <img src="@/assets/icon.png" alt="" class="icon">
                      </div>
                    </div>
                    <div class="cont">
                        <button class="button">Get Started</button>
                    </div>
                </div>


            </main>

            <div class="newpage">
                <div class="container-2">
                    <div class="image">
                        <img src="@/assets/Frame2.png" alt="">
                    </div>
                    <div class="rite">
                            <h1>Investment</h1>
                            <h3>Reap enticing rewards, Be confident in your Investment, because of the security we provide you</h3>
                            <h6 style="color:#f6b736; font-size:40px; padding-top:20px;" >Learn More</h6>
                    </div>
                </div>
                <div class="container-2">
                    <div class="lft">
                            <h2 class="pay">Pay Small Small</h2>
                            <h4 class="txt">No matter how solid your plans are sometimes you don't have all the money</h4>
                            <h4 style="color:#f6b736; font-size:40px;" class="ig">Learn More</h4>
                    </div>
                       <div class="image">
                        <img src="@/assets/Frame.png" alt="">
                    </div>
                </div>
                
            </div>
            
            <div class="why">
                <h4 style="font-weight:bolder; font-size:40px;">Why Leapsail</h4>
                <h1 style="
                    font-size:50px;
                    margin-left:115px;
                    color:grey;
                    font-weight:bolder;
                    font-family:Time new roman;
                    padding-top:20px;
                ">Excellent Customer relations? &nbsp; <b style="color:#f6b736;"> Of Course !</b></h1>
                </div>
        </section>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
.newpage{
    background: rgb(255, 245, 245);
}
.container-2{
    display: grid;
    grid-template-columns: 1fr 1fr;

}
 section .why{
    padding-top: 100px;
}
.container-2 .image{
    margin-left:100px;
    margin-top: 50px;
}
.container-2 .rite h1{
    margin-right: 70px;
}

.container-2 .rite h1,h3{
    margin-right:50px;
    margin-top:180px;
    font-size:60px;
    font-weight:700;
    padding-top:30px;
}
.container-2 .lft h2,h4{
    margin-left: 120px;
    margin-top:180px;
    font-size:60px;
    font-weight:700;
    padding-top:30px;
}
.section{
    background:  rgb(255, 255, 255);
}
.left{
    margin:50px 50px 0px 20px;
    box-sizing: border-box;
    position: relative;

}
.store{
    margin-right: 100px;
}
.left h2 {
    font-size: 60px;
    font-weight:700;
    margin:0;

}
.left p{
    font-weight:700;
    font-size:25px;
}
.right{
    position: relative;
    
}

 .img1{
    position: relative;
    width: 300px;
    
}

.img2{
    position:relative;
    width:200px;

}

.img3{
    position:relative;
    top:-60px;
    right: 100px;
    width:350px;
}
.img4{
    position: absolute;
    width:120px;
    bottom:-10px;
    left: 100px;
}
.container{
    display:grid;
    grid-template-columns: 1fr 1fr;

}
.container-1{
    margin-top:300px;
     background:  rgb(255, 255, 255);
}
.container-1 .text h2{
    text-align:center;
    font-size: 40px;
    font-weight:800;
    font-family:'Source Sans Pro', sans-serif; 
}
.text h4{
    text-align: center;
    padding-top:10px;
}
.container-1 .clone{
    display: flex;
    align-items: center;
    justify-content: center;
}
 .container-1 .clone .tour{
    position: relative;
    margin-top:60px;

}
.container-1 .clone .tour .dot{
    position: absolute;
    left:2px;

}
.container-1 .clone .tour .icon{
    margin-right: 60px;
}
.container-1 .clone .tour .one{
position: absolute;
top:3px;
left:100px;
font-size: 22px;
font-weight: 200px;
}
.container-1 .clone .tour .two{
position: absolute;
top:3px;
left:70px;
font-size: 22px;
font-weight: 200px;
}
.container-1 .clone .tour .three{
position: absolute;
top:3px;
left:40px;
font-size: 22px;
font-weight: 200px;
}
.container-1 .clone .tour .four{
position: absolute;
top:3px;
left:70px;
font-size: 22px;
font-weight: 200px;
}
.container-1 .clone .tour .five{
position: absolute;
top:3px;
left:50px;
font-size: 22px;
font-weight: 200px;
}
.container-1 .cont{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 80px;
}



</style>
