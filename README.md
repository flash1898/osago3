<!DOCTYPE html>
<html>
<head>
</body>
<body bgcolor="#bbe4fc">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: "arial", sans-serif;
 
  transition: background-color: #bbe4fc;
}

.sidenav {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 0;
  top: 1;
  left: 0;
  background-color: #039be4;
  overflow-x: hidden;
  transition: 0.5s;
  padding-top: 60px;
  border-radius: 0px 10px / 10px;
}

.sidenav a {
  padding: 8px 8px 8px 32px;
  text-decoration: none;
  font-size: 20px;
  color: white;
  display: block;
  transition: 1.5s;
    border-radius: 3px 3px / 3px;
}

.sidenav a:hover {
  color: #bbe4fc;
}

.sidenav .closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 50px;
}

#main {
  transition: margin-left .5s;
  padding: 3x;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
</style>
</head>
<body>

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href="#">О нас</a>
  <a href="https://dkbm-web.autoins.ru/dkbm-web-1.0/policyInfo.htm">Проверить в РСА</a>
    <p></p>
    <a href="tel: +74951234567">8 (800) 000-00-00</a>
  <a href="mailto: info@e-osago.shop">info@e-osago.shop</a>
</div>

<div id="main">

 
  <span style="font-size:23px; font-weight: bold; cursor:pointer; color: #039be4" onclick="openNav()">&#9776;   </span>
</div>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "auto";
  document.getElementById("main").style.marginLeft = "10px";
  document.body.style.backgroundColor = "#bbe4fc";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
  document.getElementById("main").style.marginLeft= "0";
  document.body.style.backgroundColor = "#bbe4fc";
}
</script>


</body>
</html>
<script src="https://www.banki.ru/static/bundles/ui-2018/EosagoBundle/eosago/scripts/widget-main-eosago.js" id="bankiru_main_eosago_widget" data-config="%7B%22attributes%22%3A%7B%22width%22%3A%22100%25%22%2C%22height%22%3A%22100%25%22%2C%22scrolling%22%3A%22yes%22%7D%2C%22source%22%3A%22a88197d7-b382-4427-8ead-96806e74fde0%22%7D"></script>
</body>

</html>
