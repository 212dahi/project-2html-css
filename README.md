# project-2html-css
------------------html----------------------------------

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8"> 
  <title>The dream of morocco</title> 
  <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <div id="headre"> 
     <div id="text"> <img src="images/dream.png"  > </div>
     <div id="ruessia" > <img src="images/fifa.png" > </div>
     <div id="maroc"> <img src="images/frmf.png"  > </div>
     </div>
    <div id="rect">
            <div id="rectangle"><img src=" images/rectangle.png" > </div> 
            <div id="inst"><a href="https://www.instagram.com/otmane.allaoui"> <img src="images/insta.png" id="insta">  </a>     </div>
            <div id="yout"> <a href="https://www.youtube.com/channel/UCb7Q-852IL1FVcc-X2pCacw?view_as=subscriber"> <img src="images/yout.png" id="youta"></a><     </div>
            <div id="fb"><a href="https://www.facebook.com/otman.alloui"> <img src="images/fb.png" class="fb"> </a>     </div>
            <div id="home"><img src="images/hom.png" id="hom" ></div>
            <div id="news"> <img src="images/news.png" id="new"> </div>
            <div id="team"><img src="images/team.png" id="teame"> </div>

    </div>
    <div id="millieux">
       <img src="images/back2.png" id="millieuxe">
       <div id="gouche">
         <h4>Preparation </h4>
        <div id="tim"> 
         <img src="images/eqii.jpg" id="eqi">
         <ul>
           <li>match amicale serbia VS morocco</li>
           <li>match amicale  uzbakistan VS morocco</li>
           <li>Camp preparation before the start of competitions</li>
         </ul>
        </div> 
          </div>
        <h5>News </h5>  
       <div class="droite">
          <div calss="hrr">
          <p id="hrrr"> National voter Herve Ronard asked about the conditions<br/>
            of the Moroccan professional Ghanem Saiss, a professional in Wolverhampton,<br/>
            England, who renewed his muscle injury, which has been suffering recently,
           </p> 
            <img src="images/hrv.jpg" id="hrvi"> 
          </div>
          <div class="syss">
             <p id ="sysss" > National voter Herri Ronar is intensifying his contacts with a number of professionals<br/>
              and is monitor ng a number of them from Senegal, where he lives only a few days before announcing <br>
              the list that will face Serbia and Uzbekistan amicably.
             </p>
             <img src="images/saisse.jpg" id="saiss">
          </div>
           
        </div>
             <h6>Sources</h6>
             <p id="ftt"> <a href="https://www.almountakhab.com" id="almont"> 'almountakhab' </a> <br/> <br/>
                  <a href="https://almarssadpro.com/index.php/ar/en/lions-d-atlass" id="almont"> 'almarssadpro'</a>
             </p>
        <div id="fin">
         <a href="https://otmani.98far@gmail.com" id="fin1">email:otmani.98far@gmail.com </a> <p id="fin2"> Otmane Allaoui</p>
        </div>
    </div>
 
</body>
</html>


---------------------css--------------------------css----------------css-------------------------------css-----------------
body{
    background: url('images/backround.jpg');
    background-size:50%;
    margin:0px;
}

#headre{
    background: url('images/headree.png');
    background-repeat: no-repeat;
    margin:auto;
    margin-top:0px;
    position:relative;
    width:1000px;
    height: 280px;
    
}

#rectangle img
{

    margin-top: -282px;
    left:175px;
    position:absolute;
}

#text img
{
    margin-top:50px;
    position:absolute;
    left: 292px;
}

#ruessia img
{
    margin-top:17px;
    position:absolute;
    float:left;
    left:44px;
}
#maroc img
{
    margin-top:143px;
    position:absolute;
    float:left;
    left:878px;

}
#insta{
    position:absolute;
    float:left;
    left:852px;
}
#youta{
    position:absolute;
    float:left;
    left:912px;

}
.fb{
    position:absolute;
    float:left;
    left:966px;
    top:275px;
}
#hom{
    position:absolute;
    float:left;
    left:175px;
    top:275px;
    text-decoration: underline;
}
#new{
    position:absolute;
    float:left;
    left:271px;
    top:275px;
    text-decoration: underline;

}
#teame{
    position:absolute;
    float:left;
    left:373px;
    top:275px;
    text-decoration: underline;

}
#millieuxe{
    

    position:absolute;
    top:332px;
    float:left;
    left:175px;
}
h4{
font-size:40px;
float: left;
left:185px;
position:absolute;
top:280px;
color:#00FF87;
}
#tim{
    border:4px #76766f ridge ;
    width:450px;
    height:400px;
    top:380px;
    position:absolute;
    float: left;
    left:185px;


}
 #eqi{
    position:absolute;
    border: 3px #282828 ridge;
    width:435px;
    height:300px;
    border-radius: 10px;
    box-shadow: 6px 6px 6px #76766f;
}
ul{
    top:300px;
    font-size:20px;
    position:absolute;
    color:white;
    border-radius: 10px;
    box-shadow: 6px 6px 6px #D3C58D;
}

h4:hover{
  text-decoration: underline;
  color:#D3C58D;  
}
h5{
   position:absolute;
   top:260px;
   float:left;
   left:912px;
   font-size:40px;
   color:#00FF87;
}
h5:hover{
  text-decoration: underline;
  color:#D3C58D;  
}
.droite{
    border:4px #76766f ridge ;
    width:510px;
    height:600px;
    top:380px;
    position:absolute;
    float: left;
    left:640px;

}
#hrvi{
    position:absolute;
    border: 3px #282828 ridge;
    width:200px;
    height:200px;
    border-radius: 10px;
    top:1px;
    float:left;
    left:304px;
}
.hrr{
    position:absolute;
    top:405px;
    color:white;
    font-size: 10px;

}
#hrrr{
    position:absolute;
    margin-top:1px;
    color:white;
    font-size: 20px;
    width:290px;
    height: 200px;
    border-radius: 10px;
    box-shadow: 6px 6px 6px #D3C58D;
    border: 3px #282828 ridge;
}
#saiss{
    position:absolute; 
    border: 3px #282828 ridge;
    width:500px;
    height: 250px;
    border-radius: 10px;
    margin-top:210px;
}
#sysss{
    position:absolute;
    top:446px;
    color:white;
    font-size:20px;
    border-radius: 10px;
    box-shadow: 3px 6px 6px #D3C58D;
    border: 3px #282828 ridge;

}
h6{
   position: absolute; 
   margin:auto;
   font-size:40px;
   color:#00FF87; 
   margin-top:490px;
   margin:left;
   left:185px;
}
h6:hover{
  text-decoration: underline;
  color:#D3C58D;  
}
#ftt{
    position: absolute;
    font-size: 30px;
    margin-top:530px;
    left:185px;
    color:#E90052;
   }
#almont{
    color:#E90052;
}
#ftt :focus{
    color:#D3C58D;
}

#fin1{
    position:absolute;
    margin-left:220px;
    margin-top:710px;
    border-radius: 10px;
    box-shadow: 3px 6px 6px #D3C58D;
    border: 3px #282828 ridge;
    color:#F94510;
    height:100px
    height:20px;
    width:220px;
    background-color: #38003C;
}
#fin2{
    position:absolute;
    margin-left: 750px;
    margin-top:710px;
    border-radius: 10px;
    box-shadow: 3px 6px 6px#38003C #D3C58D;
    border: 3px #282828 ridge;
    color:#F94510;
    height:20px
    width:500px;
    background-color: #38003C;
}
#fin1:focus{
    color:#D3C58D;
}








