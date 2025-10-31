<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Atithi Multi Cuisine Restaurant</title>
<meta name="description" content="Atithi Multi Cuisine Restaurant — Greenland Chowk, Tokha Road. Order via WhatsApp or call 9851346924.">
<style>
:root{--red:#d32f2f;--dark:#222;--muted:#666;--bg:#fff}
*{box-sizing:border-box}
body{font-family:Inter, Arial, sans-serif;margin:0;background:var(--bg);color:var(--dark);line-height:1.5}
header{background:var(--red);color:#fff;padding:18px 20px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap}
.brand{display:flex;gap:12px;align-items:center}
.brand img{width:64px;height:64px;border-radius:8px;object-fit:cover;border:3px solid rgba(255,255,255,0.12)}
.brand h1{margin:0;font-size:20px}
nav{display:flex;gap:10px}
nav a{color:#fff;text-decoration:none;padding:8px 10px;border-radius:8px;font-weight:700}
.hero{padding:40px 20px;background:linear-gradient(180deg,rgba(211,47,47,0.06),rgba(255,255,255,0));display:flex;gap:20px;align-items:center;flex-wrap:wrap}
.hero .left{flex:1;min-width:260px}
.hero h2{margin:0 0 12px;font-size:28px;color:var(--red)}
.hero p{margin:0 0 16px;color:var(--muted)}
.btn{display:inline-block;padding:10px 14px;border-radius:8px;text-decoration:none;font-weight:800}
.btn.wh{background:#25D366;color:#fff}
.btn.call{background:#fff;color:var(--red);border:2px solid var(--red)}

.container{padding:18px 20px}
.grid{display:grid;grid-template-columns:1fr 340px;gap:20px}
@media (max-width:900px){.grid{grid-template-columns:1fr}nav{width:100%;margin-top:10px;order:3}header{align-items:flex-start}}

.card{background:#fff;padding:14px;border-radius:10px;box-shadow:0 6px 18px rgba(0,0,0,0.06)}

/* Menu */
.menu-category{margin-bottom:18px}
.menu-category h3{margin:0 0 8px;color:var(--red);padding:8px 10px;border-radius:8px;font-weight:800;background:rgba(211,47,47,0.04)}
.item{display:flex;gap:12px;padding:10px;border-bottom:1px dashed #eee;align-items:center}
.thumb{width:96px;height:72px;border-radius:8px;overflow:hidden;background:#f4f4f4;flex-shrink:0}
.thumb img{width:100%;height:100%;object-fit:cover}
.meta h4{margin:0;font-size:16px}
.meta p{margin:6px 0 0;color:var(--muted);font-size:14px}
.price{font-weight:800;color:var(--red)}

.aside-actions{display:flex;flex-direction:column;gap:10px;margin-top:12px}
.aside-actions a{display:block;text-align:center;padding:10px;border-radius:8px;text-decoration:none;font-weight:800}
.aside-actions .wa{background:#25D366;color:#fff}
.aside-actions .call{background:#fff;color:var(--red);border:2px solid var(--red)}

/* Footer */
footer{padding:18px 20px;text-align:center;color:var(--muted);font-size:14px;background:#fff6f6;margin-top:20px}
</style>
</head>
<body>
<header>
  <div class="brand">
    <img src="images/logo-placeholder.png" alt="Atithi Logo">
    <div>
      <h1>Atithi Multi Cuisine Restaurant</h1>
      <div style="font-size:13px;color:#ffecec">Greenland Chowk, Tokha Road, Kathmandu</div>
    </div>
  </div>
  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
    <a href="#offers">Offers</a>
  </nav>
</header>

<section id="home" class="hero">
  <div class="left">
    <h2>Welcome to Atithi — Taste the best of multi-cuisine delights</h2>
    <p>Fresh ingredients, generous portions, and friendly service. Order for delivery or pickup. Free delivery within 6 km.</p>
    <a class="btn wh" href="https://wa.me/9851346924?text=Hi%20Atithi%20-%20I%20want%20to%20order" target="_blank">Order on WhatsApp</a>
    <a class="btn call" href="tel:+9779851346924">Call Now</a>
  </div>
  <div style="min-width:260px">
    <img src="images/hero-placeholder.jpg" alt="Delicious food" style="width:320px;max-width:100%;border-radius:10px;box-shadow:0 8px 20px rgba(0,0,0,0.08)">
  </div>
</section>

<div class="container">
  <div class="grid">
    <main>
      <section id="menu">
        <h2 style="margin-top:0;color:var(--red)">Full Menu</h2>

        <!-- FRIDAY SPECIAL -->
        <div class="menu-category">
          <h3>FRIDAY SPECIAL</h3>
          <div class="item">
            <div class="thumb"><img src="images/fried-chicken.jpg" alt="Crunchy Fried Chicken"></div>
            <div class="meta"><h4>CRUNCHY FRIED CHICKEN 8PCS BUCKET</h4><p>Special crispy bucket for sharing</p></div>
            <div style="margin-left:auto;text-align:right"><div class="price">Rs. 999</div></div>
          </div>
        </div>

        <!-- WEDNESDAY SPECIAL -->
        <div class="menu-category">
          <h3>WEDNESDAY SPECIAL</h3>
          <div class="item">
            <div class="thumb"><img src="images/wings.jpg" alt="Crispy Wings"></div>
            <div class="meta"><h4>CRISPY WINGS 20 PCS BUCKET</h4></div>
            <div style="margin-left:auto;text-align:right"><div class="price">Rs. 999</div></div>
          </div>
        </div>

        <!-- VEG GRAVY -->
        <div class="menu-category">
          <h3>VEG GRAVY</h3>
          <div class="item"><div class="thumb"><img src="images/dal-tadka.jpg" alt=""></div><div class="meta"><h4>DAL TADKA</h4><p>Served hot with rice or roti</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 270</div></div></div>
          <div class="item"><div class="thumb"><img src="images/dal-makhani.jpg" alt=""></div><div class="meta"><h4>DAL MAKHANI</h4><p>Creamy and richly spiced</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 400</div></div></div>
          <div class="item"><div class="thumb"><img src="images/rajma.jpg" alt=""></div><div class="meta"><h4>RAJMA</h4><p>Homestyle rajma with aromatic spices</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 270</div></div></div>
          <div class="item"><div class="thumb"><img src="images/mixed-veg.jpg" alt=""></div><div class="meta"><h4>MIXED VEG</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 340</div></div></div>
          <div class="item"><div class="thumb"><img src="images/matar-paneer.jpg" alt=""></div><div class="meta"><h4>MATAR PANEER</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 340</div></div></div>
          <div class="item"><div class="thumb"><img src="images/paneer-butter.jpg" alt=""></div><div class="meta"><h4>PANEER BUTTER MASALA</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 470</div></div></div>
        </div>

        <!-- CHICKEN GRAVY -->
        <div class="menu-category">
          <h3>CHICKEN & MUTTON GRAVY</h3>
          <div class="item"><div class="thumb"><img src="images/chicken-curry.jpg" alt=""></div><div class="meta"><h4>CHICKEN CURRY</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 340</div></div></div>
          <div class="item"><div class="thumb"><img src="images/mutton-curry.jpg" alt=""></div><div class="meta"><h4>MUTTON CURRY</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 470</div></div></div>
          <div class="item"><div class="thumb"><img src="images/butter-chicken.jpg" alt=""></div><div class="meta"><h4>BUTTER CHICKEN</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 470</div></div></div>
          <div class="item"><div class="thumb"><img src="images/chicken-rara.jpg" alt=""></div><div class="meta"><h4>CHICKEN RARA</h4><p>Chef's special spicy preparation</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 530</div></div></div>
        </div>

        <!-- ROTI NAAN -->
        <div class="menu-category">
          <h3>ROTI • NAAN</h3>
          <div class="item"><div class="thumb"><img src="images/tandoori-roti.jpg" alt=""></div><div class="meta"><h4>TANDOORI ROTI</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 50</div></div></div>
          <div class="item"><div class="thumb"><img src="images/butter-naan.jpg" alt=""></div><div class="meta"><h4>BUTTER NAAN</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 90</div></div></div>
          <div class="item"><div class="thumb"><img src="images/garlic-naan.jpg" alt=""></div><div class="meta"><h4>GARLIC NAAN</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 140</div></div></div>
        </div>

        <!-- VEG SNACKS -->
        <div class="menu-category">
          <h3>VEG SNACKS</h3>
          <div class="item"><div class="thumb"><img src="images/french-fries.jpg" alt=""></div><div class="meta"><h4>FRENCH FRIES</h4><p>Lightly salted</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 299</div></div></div>
          <div class="item"><div class="thumb"><img src="images/masala-fries.jpg" alt=""></div><div class="meta"><h4>MASALA FRIES</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 349</div></div></div>
          <div class="item"><div class="thumb"><img src="images/paneer-tikka.jpg" alt=""></div><div class="meta"><h4>PANEER TIKKA</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 549</div></div></div>
        </div>

        <!-- CHICKEN SNACKS -->
        <div class="menu-category">
          <h3>CHICKEN SNACKS</h3>
          <div class="item"><div class="thumb"><img src="images/chilly-chicken.jpg" alt=""></div><div class="meta"><h4>CHILLY CHICKEN</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 399</div></div></div>
          <div class="item"><div class="thumb"><img src="images/lollypop.jpg" alt=""></div><div class="meta"><h4>CHICKEN LOLLYPOP</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 399</div></div></div>
          <div class="item"><div class="thumb"><img src="images/chicken-tikka.jpg" alt=""></div><div class="meta"><h4>CHICKEN TIKKA</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 599</div></div></div>
        </div>

        <!-- ATITHI SPECIAL -->
        <div class="menu-category">
          <h3>ATITHI SPECIAL</h3>
          <div class="item"><div class="thumb"><img src="images/pork-ribs.jpg" alt=""></div><div class="meta"><h4>PORK RIBS</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 499</div></div></div>
          <div class="item"><div class="thumb"><img src="images/mutton-bhutan.jpg" alt=""></div><div class="meta"><h4>MUTTON BHUTAN</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 399</div></div></div>
        </div>

        <!-- BIRYANI -->
        <div class="menu-category">
          <h3>BIRYANI</h3>
          <div class="item"><div class="thumb"><img src="images/veg-biryani.jpg" alt=""></div><div class="meta"><h4>VEG DUM BIRYANI</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 500</div></div></div>
          <div class="item"><div class="thumb"><img src="images/chicken-biryani.jpg" alt=""></div><div class="meta"><h4>CHICKEN DUM BIRYANI</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 600</div></div></div>
          <div class="item"><div class="thumb"><img src="images/mutton-biryani.jpg" alt=""></div><div class="meta"><h4>MUTTON DUM BIRYANI</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 750</div></div></div>
        </div>

        <!-- SALAD -->
        <div class="menu-category">
          <h3>SALAD</h3>
          <div class="item"><div class="thumb"><img src="images/chicken-salad.jpg" alt=""></div><div class="meta"><h4>SPICY CHICKEN SALAD</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 300</div></div></div>
          <div class="item"><div class="thumb"><img src="images/fruit-salad.jpg" alt=""></div><div class="meta"><h4>FRUIT SALAD</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 450</div></div></div>
        </div>

        <!-- MOMO -->
        <div class="menu-category">
          <h3>MOMO</h3>
          <div class="item"><div class="thumb"><img src="images/steam-momo.jpg" alt=""></div><div class="meta"><h4>STEAM MOMO</h4><p>Raj / Mushroom / Buff / Chicken available</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 200 - 280</div></div></div>
          <div class="item"><div class="thumb"><img src="images/kothey.jpg" alt=""></div><div class="meta"><h4>KOTHEY MOMO</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 250 - 299</div></div></div>
        </div>

        <!-- SEKUWA -->
        <div class="menu-category">
          <h3>SEKUWA</h3>
          <div class="item"><div class="thumb"><img src="images/chicken-sekuwa.jpg" alt=""></div><div class="meta"><h4>CHICKEN SEKUWA</h4><p>Plate / Half Kg / Full Kg available</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 399 / 799 / 1499</div></div></div>
        </div>

        <!-- CHINESE -->
        <div class="menu-category">
          <h3>CHINESE</h3>
          <div class="item"><div class="thumb"><img src="images/hakka-noodles.jpg" alt=""></div><div class="meta"><h4>HAKKA NOODLES</h4><p>Veg / Egg / Chicken / Mix</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 249 - 325</div></div></div>
        </div>

        <!-- FISH & SEAFOOD -->
        <div class="menu-category">
          <h3>FISH & SEAFOOD</h3>
          <div class="item"><div class="thumb"><img src="images/fish-amritsari.jpg" alt=""></div><div class="meta"><h4>FISH AMRITSARI</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 399</div></div></div>
          <div class="item"><div class="thumb"><img src="images/golden-prawns.jpg" alt=""></div><div class="meta"><h4>GOLDEN FRIED PRAWNS</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 699</div></div></div>
        </div>

        <!-- FRIED CHICKEN -->
        <div class="menu-category">
          <h3>FRIED CHICKEN</h3>
          <div class="item"><div class="thumb"><img src="images/fried-2pc.jpg" alt=""></div><div class="meta"><h4>FRIED CHICKEN — 2 / 4 / 6 / 8 PCS</h4><p>2pc Rs.450 | 4pc Rs.799 | 6pc Rs.1099 | 8pc Rs.1400</p></div><div style="margin-left:auto;text-align:right"><div class="price">See sizes</div></div></div>
          <div class="item"><div class="thumb"><img src="images/popcorn.jpg" alt=""></div><div class="meta"><h4>CHICKEN POPCORN</h4></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 299</div></div></div>
        </div>

        <!-- PASTA & FASTFOOD -->
        <div class="menu-category">
          <h3>PASTA • SANDWICH • BURGER • WRAP</h3>
          <div class="item"><div class="thumb"><img src="images/pasta.jpg" alt=""></div><div class="meta"><h4>CARBONARA / ARRABBIATA / AGLIO E OLIO</h4><p>Veg Rs.349 | Chicken Rs.399</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 349 - 399</div></div></div>
          <div class="item"><div class="thumb"><img src="images/burger.jpg" alt=""></div><div class="meta"><h4>BURGER / SANDWICH / WRAP</h4><p>Veg Rs.299 | Chicken Rs.349</p></div><div style="margin-left:auto;text-align:right"><div class="price">Rs. 299 - 349</div></div></div>
        </div>

        <!-- OFFERS -->
        <div id="offers" class="menu-category">
          <h3>OFFERS & SPECIALS</h3>
          <div class="item" style="background:linear-gradient(90deg,#fff7f6,#fffefa)"><div class="meta"><h4>Friday Offer</h4><p>Crispy Fried Chicken 8pcs bucket at Rs.1099</p></div></div>
          <div class="item" style="background:linear-gradient(90deg,#fff7f6,#fffefa)"><div class="meta"><h4>Tuesday Offer</h4><p>Crispy Chicken Wings 20pcs at Rs.999</p></div></div>
        </div>

      </section>

      <section id="about" style="margin-top:18px">
        <h2 style="color:var(--red)">About Us</h2>
        <div class="card">
          <p>Atithi Multi Cuisine Restaurant brings you a wide range of Nepali, Indian and Continental dishes made from fresh ingredients. Our chefs cook with heart and serve with warmth — Atithi Devo Bhava.</p>
        </div>
      </section>

    </main>

    <aside>
      <div class="card">
        <h3>Contact & Order</h3>
        <ul style="list-style:none;padding:0;margin:0">
          <li><strong>Phone:</strong> 01-5914639</li>
          <li><strong>Mobile / WhatsApp:</strong> <a href="https://wa.me/9851346924">9851346924</a></li>
          <li><strong>Address:</strong> Greenland Chowk, Tokha Road, Kathmandu, Nepal</li>
          <li><strong>Hours:</strong> 11:00 AM - 11:00 PM</li>
          <li><strong>Delivery:</strong> Free within 6 km; partners: Foodmandu, Hello Service Nepal</li>
        </ul>
        <div class="aside-actions">
          <a class="wa" href="https://wa.me/9851346924?text=Hi%20Atithi%20-%20I%20want%20to%20order" target="_blank">Order on WhatsApp</a>
          <a class="call" href="tel:+9779851346924">Call Now</a>
        </div>
      </div>

      <div style="height:16px"></div>

      <div class="card">
        <h3>Location</h3>
        <iframe src="https://www.google.com/maps?q=Greenland+Chowk+Tokha+Road+Kathmandu&output=embed" width="100%" height="200" style="border:0;border-radius:8px" allowfullscreen loading="lazy"></iframe>
      </div>

      <div style="height:16px"></div>

      <div class="card">
        <h3>Policies</h3>
        <p style="margin:6px 0;color:var(--muted)">Orders accepted via WhatsApp or Call. Cancellation within 10 minutes for full refund (if pre-paid). Delivery times may vary. For full Terms & Conditions, contact us.</p>
      </div>
    </aside>
  </div>
</div>

<footer id="contact">
  <div style="padding:12px 8px">Email: atithimulticuisinerestaurant@gmail.com • Domain: atithimulticuisine.com.np</div>
  <div style="padding:6px 8px;color:var(--muted)">© <span id="year"></span> Atithi Multi Cuisine Restaurant. All rights reserved.</div>
</footer>

<script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
