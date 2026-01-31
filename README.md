# KINELEC
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Kine Scope Electronics</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root{
  --yellow:#fff1b8;
  --orange:#ffcc9c;
  --red:#d32f2f;
  --grey:#555;
  --white:#ffffff;
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Segoe UI, Times New Roman, sans-serif;
}

body{
  background:#f2f2f2;
  color:var(--grey);
  overflow-x:hidden;
}

/* ===== TOP LOGO BAR ===== */
.topbar{
  position:fixed;
  top:0;
  left:0;
  width:100%;
  padding:14px 40px;
  background:rgba(255,255,255,0.95);
  backdrop-filter:blur(6px);
  display:flex;
  align-items:center;
  z-index:100;
  box-shadow:0 2px 8px rgba(0,0,0,0.08);
}

.topbar img{
  height:48px;
}

.topbar span{
  margin-left:15px;
  font-weight:700;
  letter-spacing:1px;
  color:var(--red);
  font-size:1rem;
}

/* ===== HERO ===== */
.hero{
  height:100vh;
  padding-top:90px;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  background:
    radial-gradient(circle at top,var(--yellow),transparent 60%),
    linear-gradient(135deg,var(--yellow),var(--orange));
  animation:fadeIn 1.5s ease;
}

.hero h1{
  font-size:3.2rem;
  color:var(--red);
  letter-spacing:2px;
  animation:slideDown 1.2s ease;
}

.hero p{
  max-width:720px;
  margin:20px auto;
  font-size:1.2rem;
  animation:slideUp 1.2s ease;
}

/* ===== SECTIONS ===== */
section{
  padding:90px 10%;
  background:var(--white);
}

h2{
  font-size:2.2rem;
  color:#f57c00;
  margin-bottom:30px;
}

/* ===== SERVICES ===== */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:30px;
}

.box{
  background:#fafafa;
  padding:30px;
  border-radius:16px;
  border:1px solid #ddd;
  box-shadow:0 12px 30px rgba(0,0,0,.08);
  transition:.4s;
}

.box:hover{
  transform:translateY(-10px) scale(1.02);
}

/* ===== PRODUCTS ===== */
.product img{
  width:100%;
  height:200px;
  object-fit:cover;
  border-radius:12px;
  transition:.5s;
}

.product:hover img{
  transform:scale(1.08);
}

.product a{
  display:inline-block;
  margin-top:12px;
  color:var(--red);
  font-weight:600;
  text-decoration:none;
}





/* ===== FORM ===== */
form{
  max-width:700px;
}

input,textarea{
  width:100%;
  padding:15px;
  margin-bottom:18px;
  border-radius:10px;
  border:1px solid #ccc;
  font-size:1rem;
}

button{
  padding:15px 40px;
  background:linear-gradient(135deg,#fbc02d,#f57c00,#d32f2f);
  border:none;
  border-radius:30px;
  color:#fff;
  font-size:1rem;
  cursor:pointer;
  transition:.3s;
}

button:hover{
  transform:scale(1.05);
}

/* ===== FOOTER ===== */
footer{
  background:#eee;
  text-align:center;
  padding:40px;
  color:#777;
}

/* ===== ANIMATIONS ===== */
@keyframes fadeIn{
  from{opacity:0;}
  to{opacity:1;}
}

@keyframes slideDown{
  from{transform:translateY(-40px);opacity:0;}
  to{transform:translateY(0);opacity:1;}
}

@keyframes slideUp{
  from{transform:translateY(40px);opacity:0;}
  to{transform:translateY(0);opacity:1;}
}

.reveal{
  opacity:0;
  transform:translateY(40px);
  transition:1s;
}

.reveal.active{
  opacity:1;
  transform:none;
}
</style>
</head>

<body>

<!-- LOGO BAR -->
<div class="topbar">
  <img src="LOGO_KINELEC__jpg_file_-removebg-preview.png" >
  <span></span>
</div>

<!-- HERO -->
<div class="hero">
  <div>
    <h1>KINE SCOPE ELECTRONICS</h1>
    <p>
      Engineering intelligent electronic solutions with precision,
      energy, and future-ready design.
    </p>
  </div>
</div>

<section class="reveal">
<h2>About Us</h2>
<p>
Kine Scope Electronics delivers professional electronic and automation
solutions engineered for performance, reliability, and long-term value.
</p>
</section>

<section class="reveal">
<h2>What We Do</h2>
<div class="grid">
  <div class="box">
    <h3>Electronic Design</h3>
    <p>Custom electronics built with precision engineering.</p>
  </div>
  <div class="box">
    <h3>Automation & Control</h3>
    <p>Smart automation systems for modern industries.</p>
  </div>
  <div class="box">
    <h3>Intelligent Systems</h3>
    <p>Future-ready electronics with intelligent integration.</p>
  </div>
</div>
</section>

<section class="reveal">
<h2>Product Catalog</h2>
<div class="grid">

 <div class="box product">
    <img src="POE EXTENDER.jpg">
    <h4>PoE EXTENDER</h4>
    <p></p>
    <a href="poe extender.pdf" target="_blank"> Download PDF</a>
  </div>

  <div class="box product">
    <img src="ChatGPT Image Jan 14, 2026, 02_37_12 PM.png">
    <h4>Power Supply Units</h4>
    <p></p>
    <a href="CCTV POWER SUPPLY.pdf" target="_blank"> Download PDF</a>
  </div>

  <div class="box product">
    <img src="12 v dc ups.jpg">
    <h4>12 V DC UPS FOR Wi-Fi ROUTERS.</h4>
    <p></p>
    <a href="12 VOLT DC UPS.pdf" target="_blank"> Download PDF</a>
  </div>

  <div class="box product">
  <img src="Gemini_Generated_Image_ixvm62ixvm62ixvm-removebg-preview.png">
  <h4>OLT UPS</h4>
  <p></p>
  <a href="OLT UPS.pdf" target="_blank"> Download PDF</a>
 </div>

 <div class="box product">
   <img src="4FE+2FE_CAMERA_SOLUTION_-removebg-preview.png">
   <h4>CCTV PoE SOLUTIONS</h4>
   <p></p>
   <a href="(4+2)&(8+2) POE SOLUTION.pdf" target="_blank"> Download PDF</a>
 </div>

 <div class="box product"> 
   <h4>KINELEC</h4>
   <p>KINELEC ALL PRODUCT DETAILS.</p>
   <a href="catalogue.pdf" target="_blank"> Download PDF</a>
 </div>


</div>
</section>

<section class="reveal">
<h2>Enquiry Form</h2>
<form>
  <input type="text" placeholder="Your Name" required>
  <input type="contact" placeholder="Your Contact no." required>
  <input type="text" placeholder="Your Email">
  <textarea placeholder="Describe your requirement"></textarea>
  <button type="submit">Send Enquiry</button>
</form>
</section>

<footer>
© 2026 Kine Scope Electronics. All rights reserved.
</footer>

<script>
const reveals=document.querySelectorAll(".reveal");
window.addEventListener("scroll",()=>{
  reveals.forEach(el=>{
    const top=el.getBoundingClientRect().top;
    if(top<window.innerHeight-100){
      el.classList.add("active");
    }
  });
});
</script>

</body>
</html>
