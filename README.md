<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>YOOK | صرافی دیجیتال</title>

<style>
*{box-sizing:border-box}
body{
margin:0;
font-family:Tahoma,Arial;
background:#080d18;
color:white;
}
header{
padding:22px 7%;
display:flex;
justify-content:space-between;
align-items:center;
border-bottom:1px solid #202b40;
}
.logo{
font-size:30px;
font-weight:bold;
color:#35d6a2;
}
nav a{
color:#ddd;
text-decoration:none;
margin:0 12px;
}
.hero{
text-align:center;
padding:75px 20px;
}
.hero h1{
font-size:45px;
color:#35d6a2;
}
.hero p{
color:#aab5c8;
line-height:2;
}
.box{
background:#121c2d;
border:1px solid #26364e;
border-radius:18px;
padding:30px;
max-width:500px;
margin:25px auto;
}
.price{
font-size:32px;
color:#35d6a2;
margin:20px;
}
button{
border:0;
padding:15px 35px;
border-radius:10px;
font-size:17px;
cursor:pointer;
margin:8px;
}
.buy{
background:#35d6a2;
color:#06130e;
}
.sell{
background:#394457;
color:#aaa;
}
.stats{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
margin:35px;
}
.stat{
background:#121c2d;
padding:25px;
border-radius:15px;
min-width:180px;
}
footer{
text-align:center;
padding:30px;
color:#8290a5;
}
</style>
</head>

<body>

<header>
<div class="logo">YOOK</div>
<nav>
<a href="#">خانه</a>
<a href="#market">بازار</a>
<a href="#about">درباره ما</a>
</nav>
</header>

<section class="hero">
<h1>به دنیای YOOK خوش آمدید</h1>
<p>
نسل جدید معاملات دارایی دیجیتال
<br>
ساده، سریع و هوشمند
</p>

<div class="box" id="market">
<h2>ارز دیجیتال YOOK</h2>
<div class="price">0.01 USDT</div>
<p>قیمت نمایشی اولیه</p>

<button class="buy" onclick="alert('خرید واقعی هنوز فعال نشده است')">
خرید YOOK
</button>

<button class="sell" disabled>
فروش به زودی
</button>

</div>

<div class="stats">
<div class="stat">
<h3>نام ارز</h3>
YOOK
</div>

<div class="stat">
<h3>نماد</h3>
YOOK
</div>

<div class="stat">
<h3>وضعیت فروش</h3>
غیرفعال
</div>
</div>
</section>

<section class="hero" id="about">
<h2>درباره YOOK</h2>
<p>
به پلتفرم اختصاصی YOOK خوش آمدید.
<br>
اطلاعات و امکانات جدید به زودی اضافه می‌شوند.
</p>
</section>

<footer>
© 2026 YOOK Digital Platform
</footer>

</body>
</html>
