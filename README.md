<!-- /Botão Whatsapp/ -->

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.13.0/css/all.css" integrity="sha384-Bfad6CLCknfcloXFOyFnlgtENryhrpZCe29RTifKEixXQZ38WheV+i/6YWSzkz3V" crossorigin="anonymous">
<a href="https://api.whatsapp.com/send/?phone=553135162930&text&type=phone_number&app_absent=0" class="float" target="_blank"><i class="fab fa-whatsapp my-float"></i></a>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

.float
{
position:fixed;
cursor:pointer;
display:block;
width:60px;
height:60px;
bottom:40px;
right:40px;
background-color:rgba(0,200,0,1);
color:white;
border-radius:50px;
text-align:center;
font-size:30px;
transition-duration: 0.5s;
animation:pulse 3s infinite;
z-index:9000;
}
.float:hover
{
background-color:rgba(0,150,0,1);
color:white;
}
.my-float
{
margin-top:15px;
}
@-webkit-keyframes pulse
{
0% {-webkit-box-shadow: 0 0 0 0 rgba(0,200,0, 1);}
70% {-webkit-box-shadow: 0 0 0 20px rgba(0,200,0, 0);}
100% {-webkit-box-shadow: 0 0 0 0 rgba(0,200,0, 0);}
}
</style>

<!-- /Botão Whatsapp/ -->

fbq('track', 'contact');
