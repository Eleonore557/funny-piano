<template >

<div class="background"> 
    <div id="content">    
        <div class="div-emoji1">
            <div class="div-emoji2">The emoji piano</div>
        </div>
    
        <div class="piano text-center">
         
            <button class="Do"  type="button" @click.prevent="playSound('http://soundbible.com/mp3/Air Plane Ding-SoundBible.com-496729130.mp3')"></button>
            <button class="Re"  type="button"></button> 
            <button class="Mi"  type="button"></button> 
            <button class="Fa"  type="button"></button> 
            <button class="So"  type="button"></button> 
            <button class="La"  type="button"></button> 
            <button class="Si"  type="button"></button>
            <button class="Do1"  type="button"></button> 
            <button class="Re1"  type="button"></button> 
            <button class="Fa1"  type="button"></button> 
            <button class="Sol1" type="button"></button> 
            <button class="La1"  type="button"></button>  

            <p class="do">Do</p>
            <p class="re">Ré</p>
            <p class="mi">Mi</p>
            <p class="fa">Fa</p>
            <p class="so">So</p>
            <p class="la">La</p>
            <p class="si">Si</p>
            
        </div>
    </div>
</div>       
</template>      


    
<script>

export default {
methods: {
    playSound (sound) {
       
      if(sound) {
       
        var audio = new Audio(sound);
        audio.play();
      }
    }
  }

}
  
</script>







<style lang="postcss" scoped>

 

.do {
font-family: 'PT Mono', monospace;
color: rgba(255, 255, 255, 0.4);
font-size: 20px;
position: relative;
right: 222px;
top: -50%;
}
.re {
font-family: 'PT Mono', monospace;
color: rgba(255, 255, 255, 0.4);
font-size: 20px;
position: relative;
right: 145px;
    top: -60.7%;
}
.mi {
font-family: 'PT Mono', monospace;
color: rgba(255, 255, 255, 0.4);
font-size: 20px;
position: relative;
right: 71px;
    top: -71.4%;
}
.fa {
font-family: 'PT Mono', monospace;
color: rgba(255, 255, 255, 0.4);
font-size: 20px;
position: relative;
    right: -1px;
    top: -82%;
}
.so {
font-family: 'PT Mono', monospace;
color: rgba(255, 255, 255, 0.4);
font-size: 20px;
position: relative;
    right: -72px;
    top: -92.8%;
}
.la {
font-family: 'PT Mono', monospace;
color: rgba(255, 255, 255, 0.4);
font-size: 20px;
position: relative;
    right: -144px;
    top: -103.5%;
}
.si {
font-family: 'PT Mono', monospace;
color: rgba(255, 255, 255, 0.4);
font-size: 20px;
position: relative;
    right: -220px;
    top: -114%;
}



.Do1 {
    width: 30px;
    height: 184px;
    background: #000000;
    position: relative;
    border-radius: 0px 0px 5px 5px;
    right: 423px;
    top: -20.2%;
    outline:0;
}
.Re1 {
    width: 30px;
    height: 184px;
    background: #000000;
    position: relative;
    border-radius: 0px 0px 5px 5px;
    right: 63px;
    top: -89%;
    outline:0;
}
.Fa1 {
    width: 30px;
    height: 184px;
    background: #000000;
    position: relative;
    border-radius: 0px 0px 5px 5px;
    right: -53px;
    top: -89%;
    outline:0;
}
.Sol1 {
    width: 30px;
    height: 184px;
    background: #000000;
   position: relative;
    border-radius: 0px 0px 5px 5px;
    right: -96px;
    top: -89%;
    outline:0;
}
.La1 {
    width: 30px;
    height: 184px;
    background: #000000;
    position: relative;
    border-radius: 0px 0px 5px 5px;
    right: -140px;
    top: -89%;
    outline:0;
}

.Do{
    width: 69px;
    height:252px;
    background:#FFFFFF;
    border-radius:5px 0px 0px 5px;
    position:relative;
    outline:0;
    left: 0.8%;
    top: 4.5%;
}





.Re{
    width: 69px;
    height:252px;
    background:#FFFFFF;
    outline:0;
    position:relative;
    left: 1.6%;
    top: 4.5%;
}
 .Mi{
    width: 69px;
    height:252px;
    background:#FFFFFF;
    outline:0;
    position:relative;
    left: 2.3%;
    top: 4.5%;
}
.Fa{
    width: 69px;
    height:252px;
    background:#FFFFFF;
    outline:0;
    position:relative;
    left: 3.1%;
    top: 4.5%;
}
.So{
    width: 69px;
    height:252px;
    background:#FFFFFF;
    outline:0;
    position:relative;
    left: 3.8%;
    top: 4.5%;
}
.La{
    width: 69px;
    height:252px;
    background:#FFFFFF;
    outline:0;
    position:relative;
    left: 4.7%;
    top: 4.5%;
}
.Si{
    width: 69px;
    height:252px;
    background:#FFFFFF;
    border-radius:0px 5px 5px 0px;
    position:relative;
    outline:0;
    left: 5.5%;
    top: 4.5%;
} 

#content{
   display:flex;
   flex-direction:column;
   justify-content: space-between;
   align-items: center;
  
}

.piano{

background: #000000;
border-radius: 10px;
width: 531px;
height: 276px;
margin-top: 30em;
position : fixed;

}


.div-emoji1{


background: #111111;
border-radius: 10px;
width:332px;
height:60px;
margin-top: 5em;
position : fixed;
}

.div-emoji2{
font-family: 'PT Mono', monospace;
font-size: 30px;
text-align: center;
color: #FFFFFF;
line-height: 34px;
line-height: 60px;
}

.background{
background: linear-gradient(135deg, #FF9D6C 0%, #BB4E75 100%);
min-height: 400vh;
min-width: 100vh;

}
@import url('https://fonts.googleapis.com/css2?family=PT+Mono&display=swap');

.Do:hover {
    background:orange;
}
.Re:hover {
    background:orange;
}
.Mi:hover {
    background:orange;
}
.Fa:hover {
    background:orange;
}
.So:hover {
    background:orange;
}
.La:hover {
    background:orange;
}
.Si:hover {
    background:orange;
}
.Do1:hover {
    background:palevioletred;
}
.Re1:hover {
    background:palevioletred;
}
.Fa1:hover {
    background:palevioletred;
}
.Sol1:hover {
    background:palevioletred;
}
.La1:hover {
    background:palevioletred;
}

@media (max-width: 640px) {
    .piano {
        position: fixed;
        bottom: 5%;
    }
    .do {
        display:none;
    } 
    .re {
        display:none;
    }
    .mi {
        display:none;
    }
    .fa {
        display:none;
    }
    .so {
        display:none;
    }
    .la {
        display:none;
    }
    .si {
        display:none;
    }

}

</style>

     