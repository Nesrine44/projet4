<template>
 <div class="profil">
<header class="header">
<h1></h1>
</header>

<body>

  <div class="container">


    <div class="form-group row">
    <div class="col-sm-1" style="background-color:#35B86A;"><a class="text" th:href="@{/match}">
    <span> 17h30</span>
    </br> Mar.11</a>
    </a><img src="static/img/capture5.png"></div>
    <div class="col-sm-11" style="background-color:#F4F4F4;">
    <ul class="tolist1" v-for="match1 in match1s">{{match1}}</ul>
    <ul class="tolistgris" v-for="humeur1 in humeur1s">{{humeur1}}</ul>
    <ul class="tolistcontact" v-for="contact1 in contact1s">{{contact1}}</ul>
    <ul class="tolistheure" v-for="heure1 in heure1s">{{heure1}}
    <img  src="static/img/capture1.png" class="img-circle navbar-right"  width="30" height="30"></ul></div>
    </div>



  <div class="form-group row">
  <div class="col-sm-1" style="background-color:#666666;"><a class="text" th:href="@{/match}">
  <span>18h </span></br> Mar.11 </a>
  <img src="static/img/capture6.png"></div>
  <div class="col-sm-11" style="background-color:#F4F4F4;">
  <ul class="tolist2" v-for="match2 in match2s">{{match2}}</ul>
  <ul class="tolistgris" v-for="humeur2 in humeur2s">{{humeur2}}</ul>
  <ul class="tolistcontact" v-for="contact2 in contact2s">{{contact2}}</ul>
   <ul class="tolistheure" v-for="heure2 in heure2s">{{heure2}}
  <img src="static/img/capture2.png" class="img-circle navbar-right" alt="Cinque Terre" width="30" height="30"></ul></div>
  </div>


<div class="form-group row">
<div class="col-sm-1" style="background-color:#35B86A;"><a class="text" th:href="@{/match}">
<span>18h</span> </br> Mar.11</a>
<img src="static/img/capture5.png"></div>
<div class="col-sm-11" style="background-color:#F4F4F4;">
<ul class="tolist3" v-for="match3 in match3s">{{match3}}</ul>
<ul class="tolistgris" v-for="humeur3 in humeur3s">{{humeur3}}</ul>
<ul class="tolistcontact" v-for="contact3 in contact3s">{{contact3}}</ul>
<ul class="tolistheure" v-for="heure3 in heure3s">{{heure3}}
<img src="static/img/capture3.png" class="img-circle navbar-right" alt="Cinque Terre" width="30" height="30"></ul></div>
</div>


<div class="form-group row">
<div class="col-sm-1" style="background-color:	#FFBA47;"><a  class="text" th:href="@{/match}">
<span>18h </span></br> Mar.11 </a></div>
<div class="col-sm-11" style="background-color:#F4F4F4;">
<ul class="tolist4" v-for="match4 in match4s">{{match4}}</ul>
<ul class="tolistgris" v-for="humeur4 in humeur4s">{{humeur4}}</ul>
<ul class="tolistcontact" v-for="contact4 in contact4s">{{contact4}}</ul>
<ul class="tolistheure" v-for="heure4 in heure4s">{{heure4}}
<img src="static/img/capture4.png" class="img-circle navbar-right" alt="Cinque Terre" width="30" height="30"></ul></div>
</div>



<div class="form-group row">
<div class="col-sm-1" style="background-color:#35B86A;"><a class="text" th:href="@{/match}">
<span> 17h30</span></br> Mar.11</a>
</a><img src="static/img/capture5.png"></div>
<div class="col-sm-11" style="background-color:#F4F4F4;">
<ul class="tolist1" v-for="match1 in match1s">{{match1}}</ul>
<ul class="tolistgris" v-for="humeur1 in humeur1s">{{humeur1}}</ul>
<ul class="tolistcontact" v-for="contact1 in contact1s">{{contact1}}</ul>
<ul class="tolistheure" v-for="heure1 in heure1s">{{heure1}}
<img  src="static/img/capture1.png" class="img-circle navbar-right"  width="30" height="30"></ul></div>
</div>



<div class="form-group row">
<div class="col-sm-1" style="background-color:#666666;"><a class="text" th:href="@{/match}">
<span>18h </span></br> Mar.11 </a>
<img src="static/img/capture6.png"></div>
<div class="col-sm-11" style="background-color:#F4F4F4;">
<ul class="tolist2" v-for="match2 in match2s">{{match2}}</ul>
<ul class="tolistgris" v-for="humeur2 in humeur2s">{{humeur2}}</ul>
<ul class="tolistcontact" v-for="contact2 in contact2s">{{contact2}}</ul>
<ul class="tolistheure" v-for="heure2 in heure2s">{{heure2}}
<img src="static/img/capture2.png" class="img-circle navbar-right" alt="Cinque Terre" width="30" height="30"></ul></div>
</div>
</div>

</body>
<div>

<footer class="navbar-fixed-bottom">
<div class="icon-bar">

  <a href="#"><span><i class="glyphicon glyphicon-user"></i></br> Profil </span></a>
  <a href="#"><i class="glyphicon glyphicon-list"></i></br> Programe </a>
  <a href="#"><i class="glyphicon glyphicon-list-alt"></i></br> Mes Matchs </a>
  <a href="#"><i class="glyphicon glyphicon-plus-sign"></i></br> Créer</a>
</div>

</footer>
</div>
</div>

 </div>


</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      match1s: ['Urban Soccer Aubervilliers'],
      match2s: ['Le five Bezon'],
      match3s: ['Hops Factory Paris'],
      match4s: ['Cours Niox'],


      humeur1s:['#5vs5#Expert#Bon exprit'],
      humeur2s:['#5vs5#Expert#Bon exprit'],
      humeur3s:['#5vs5#Expert#Bon exprit'],
      humeur4s:['#5vs5#Expert#Bon exprit'],

         contact1s:['Benoit de Krank'],
         contact2s:['Bouss Nait'],
         contact3s:['Soulange Benaudet'],
         contact4s:['Martin Bernard'],

         heure1s:['8€-1h30'],
         heure2s:['COMPLET'],
         heure3s:['8€-1h30'],
         heure4s:['4€-1h30'],
  }}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


nav  {
   list-style-type: none;
   padding: 0;
}
 .navbar-right {
    float: right!important;
    margin-right: 50px;
    margin-top:-10px;
}
.text{

  color:#fff;
  line-height:5px;
}
.text span{

  font-family:serif;
  color:#fff;
   font-size:18px;
  line-height:5px;
  font-Weight: Bold;
}
.form-group row {
  margin: 0;
  padding: 0;
}
.col-sm-1 {
   background-color: #259E06;
    border: 1px solid white;

    padding: 20px 0px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 14px;
    cursor: pointer;
    display: block;
    width:60px;
	  height:100px;
	  background:#069;
	  -webkit-border-radius:150px / 100px;
	  -moz-border-radius:150px / 100px;
    -o-border-radius:150px / 100px;
     border-radius:20px;
     color-text:#fff;
}
.tolist1{

  font-family:Arial;
  font-Weight: Bold;
  color:#70AC90;
  font-size:15px;

}
.tolist2{
  color:#676767;
  font-family:Arial;
  font-Weight: Bold;
  font-size:15px;
}
.tolist3{
  color:#70AC90;
  font-family:Arial;
  font-Weight: Bold;
  font-size:15px;
}
.tolist4{
 color:#FFBB54;
 font-family:Arial;
 font-Weight: Bold;
 font-size:15px;
}

.tolistgris{
  color:#CFCFCF;
  font-family:Arial;
    }
.tolistcontact{
  color:#939393;
  font-family:Arial;
    }
.tolistheure{
  color:#A8A8A8;
  font-family:Arial;
    }

  .col-sm-11 {
  height:100px;
	background:#069;
  -webkit-border-radius:150px / 100px;
	-moz-border-radius:150px / 100px;
  -o-border-radius:150px / 100px;
  border-radius:10px;
  display:block;
  line-height:10px;
  padding:15px;
}
/**footer .icon-bar**/

body {margin:0;}

.icon-bar {
    width: 130%;
    display:block;
    background-color: #F0F0F3;
    overflow: auto;
}

.icon-bar a {
    float: left;
    width: 20%;
    text-align: center;
    padding: 5px 0;
    transition: all 0.3s ease;
    color: #9D9D9D;
    font-size: 14px;
    font-family:Arial;
}

.icon-bar a:hover {
    background-color: #2199CD;
}

.active {
    background-color: #2397D1;
}

span i {
  padding: 1px 1px;
     display: inline-block;
    -moz-border-radius: 100px;
    -webkit-border-radius: 100px;
    border-radius: 90px;
    -moz-box-shadow: 0px 0px 2px #888;
    -webkit-box-shadow: 0px 0px 2px #888;
     box-shadow: 0px 0px 2px #888;
     }


</style>
