<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1" />
  <title>Easy Service Jodhpur — AC, Geyser, Washing Machine & Electrical Repair</title>
  <meta name="description" content="Easy Service Jodhpur — 24/7 AC repair, geyser service, washing machine repair, electrician and plumbing. Professional technicians. Call or WhatsApp now!" />
  <meta name="keywords" content="AC service, AC repair, geyser service, geyser repair, washing machine service, washing machine repair, electrician service, plumbing service, Jodhpur" />
  <meta name="theme-color" content="#0f2347" />
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="default">
  <link rel="manifest" href="/manifest.json">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --accent:#0f2347;--accent-2:#0b5f73;--bg:#f4f6f8;--card:#ffffff;--muted:#556075;
      --cta-height:52px; --gutter:14px; --radius:12px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{font-family:Inter,system-ui,Roboto,Arial,sans-serif;background:linear-gradient(180deg,var(--bg),#eef3f6);margin:0;color:var(--accent);-webkit-font-smoothing:antialiased;line-height:1.45}

    /* header */
    header{background:var(--card);padding:12px var(--gutter);display:flex;justify-content:space-between;align-items:center;position:sticky;top:0;z-index:60;border-bottom:1px solid rgba(15,23,42,0.06)}
    .brand{display:flex;gap:10px;align-items:center}
    .logo{width:44px;height:44px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent-2));color:white;display:flex;align-items:center;justify-content:center;font-weight:900}
    nav{display:flex;gap:8px;align-items:center}
    nav a{color:var(--muted);text-decoration:none;padding:8px 10px;border-radius:8px;font-weight:700;font-size:14px}

    /* layout */
    .container{max-width:980px;margin:16px auto;padding:0 var(--gutter)}
    .hero{display:flex;flex-wrap:wrap;gap:18px;align-items:flex-start}
    .hero-left{flex:1;min-width:240px}
    h1{font-size:20px;margin:0 0 10px}
    .lead{color:var(--muted);margin:0 0 12px}

    /* quick services */
    .quick-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:12px}
    .service-card{background:var(--card);padding:12px;border-radius:10px;box-shadow:0 6px 20px rgba(11,37,71,0.04);text-align:center;min-height:110px;display:flex;flex-direction:column;justify-content:space-between}
    .service-card h4{margin:6px 0 4px;font-size:15px}
    .service-card p{margin:0;color:var(--muted);font-size:13px}
    .service-card button{margin-top:8px;background:var(--accent);color:#fff;padding:10px;border-radius:8px;border:0;font-weight:700}

    /* cards + forms */
    .card{background:var(--card);padding:12px;border-radius:var(--radius);box-shadow:0 6px 20px rgba(11,37,71,0.04)}
    input,select,textarea{width:100%;padding:12px;border-radius:10px;border:1px solid rgba(15,23,42,0.06);font-size:15px}
    .form-row{display:flex;gap:8px;flex-wrap:wrap}
    .small{color:var(--muted);font-size:14px}

    /* reviews */
    .reviews-list{display:grid;gap:10px;margin-top:8px}
    .review-card{background:var(--card);padding:12px;border-radius:10px;border:1px solid #eef2f6}

    /* sticky action footer for mobile */
    .bottom-action{position:fixed;left:12px;right:12px;bottom:12px;height:var(--cta-height);display:flex;gap:8px;align-items:center;z-index:80}
    .btn-call{flex:0 0 56px;background:#25D366;color:#fff;border-radius:12px;display:flex;align-items:center;justify-content:center;font-weight:800;text-decoration:none}
    .btn-book{flex:1;background:var(--accent);color:#fff;border-radius:12px;display:flex;align-items:center;justify-content:center;font-weight:800;text-decoration:none}

    /* accessible larger tap targets */
    button, .cta, .btn-call, .btn-book{touch-action:manipulation}

    /* responsive */
    @media(min-width:900px){ h1{font-size:26px} .bottom-action{display:none} }
    @media(max-width:480px){ .logo{width:40px;height:40px} input,select,textarea{padding:14px;font-size:16px} .service-card{min-height:120px} }
  </style>
</head>
<body>
  <header>
    <div class="brand"><div class="logo">ES</div><div><strong>Easy Service</strong><div class="small">24/7 Technicians — Jodhpur</div></div></div>
    <nav aria-label="Main navigation">
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#reviews">Reviews</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="container" id="app">
    <section id="home" class="hero">
      <div class="hero-left">
        <h1>Reliable AC, Geyser, Washing Machine & Electrical Services</h1>
        <p class="lead">Fast response, trained technicians and transparent pricing. Expert technician: <strong style="color:var(--accent-2)">Javed Khan</strong>.</p>

        <div style="margin:10px 0" class="quick-grid" role="list">
          <div class="service-card" role="listitem">
            <div>
              <h4>AC Service</h4>
              <p class="small">Repair, gas refill & installations — from ₹500</p>
            </div>
            <button data-service="AC Service" class="quick-btn">Book</button>
          </div>

          <div class="service-card" role="listitem">
            <div>
              <h4>Geyser Service & Repair</h4>
              <p class="small">Element, thermostat & leak repair — from ₹500</p>
            </div>
            <button data-service="Geyser Service" class="quick-btn">Book</button>
          </div>

          <div class="service-card" role="listitem">
            <div>
              <h4>Washing Machine Repair</h4>
              <p class="small">Motor, belt, inlet valve, diagnostics — from ₹450</p>
            </div>
            <button data-service="Washing Machine Service" class="quick-btn">Book</button>
          </div>

          <div class="service-card" role="listitem">
            <div>
              <h4>Electrician</h4>
              <p class="small">Wiring, MCB, light/fan installation — from ₹400</p>
            </div>
            <button data-service="Electrician" class="quick-btn">Book</button>
          </div>
        </div>

        <div style="margin-top:14px">
          <a href="#contact" class="cta">Book a Service</a>
        </div>

      </div>

      <aside style="width:320px;max-width:40%" class="card" aria-labelledby="quick-title">
        <h3 id="quick-title">Quick Book</h3>
        <form id="bookingForm">
          <label class="small">Service</label>
          <select id="service" aria-label="Service select">
            <option>AC Service</option>
            <option>Geyser Service</option>
            <option>Washing Machine Service</option>
            <option>Electrician</option>
            <option>Plumbing</option>
          </select>

          <div class="form-row" style="margin-top:8px">
            <input id="name" type="text" placeholder="Your name" required />
            <input id="phone" type="tel" inputmode="tel" pattern="[0-9]{10}" placeholder="Phone (10 digits)" required />
          </div>

          <div class="form-row" style="margin-top:8px">
            <input id="date" type="date" />
            <input id="time" type="time" />
          </div>

          <textarea id="notes" rows="3" placeholder="Issue / landmark (optional)" style="margin-top:8px"></textarea>
          <div style="margin-top:10px;display:flex;gap:8px;align-items:center">
            <div style="font-size:13px;color:var(--muted)">Visiting: <strong>₹300</strong></div>
            <button type="submit" class="cta" style="margin-left:auto;min-height:var(--cta-height);line-height:1">Request</button>
          </div>
        </form>

        <div style="margin-top:12px;font-size:13px;color:var(--muted)">Or call/WhatsApp directly:</div>
        <div style="display:flex;gap:8px;margin-top:8px">
          <a class="btn-call" href="tel:+918387984425" aria-label="Call">📞</a>
          <a class="btn-book" href="https://wa.me/918387984425?text=Hello%20Easy%20Service" target="_blank" rel="noopener">WhatsApp</a>
        </div>
      </aside>
    </section>

    <section id="reviews" style="margin-top:18px">
      <h2>Customer reviews</h2>
      <div class="reviews-list card" id="reviewsList" aria-live="polite"></div>
      <div style="margin-top:10px" class="card">
        <h4>Leave a review</h4>
        <form id="reviewForm">
          <input id="rname" type="text" placeholder="Your name" required />
          <input id="rphone" type="tel" inputmode="tel" placeholder="10-digit phone" required />
          <select id="rservice" style="margin-top:8px">
            <option>AC Service</option>
            <option>Geyser Service</option>
            <option>Washing Machine Service</option>
            <option>Electrician</option>
            <option>Plumbing</option>
          </select>
          <textarea id="rtext" rows="3" placeholder="Write your review" style="margin-top:8px"></textarea>
          <div style="margin-top:8px;display:flex;align-items:center;gap:8px">
            <label class="small">Rating</label>
            <select id="rrating"><option value="5">5</option><option value="4">4</option><option value="3">3</option><option value="2">2</option><option value="1">1</option></select>
            <button class="cta" style="margin-left:auto">Submit review</button>
          </div>
        </form>
      </div>
    </section>

    <section id="services" style="margin-top:18px">
      <h2>Services & Starting Prices</h2>
      <div class="quick-grid" style="margin-top:8px">
        <div class="card"><h4>AC Service & Repair</h4><p class="small">From ₹500 — gas refill, filters, compressor</p></div>
        <div class="card"><h4>Geyser Service</h4><p class="small">From ₹500 — element, valve, thermostat</p></div>
        <div class="card"><h4>Washing Machine</h4><p class="small">From ₹450 — motor, belt, inlet valve</p></div>
        <div class="card"><h4>Electrician</h4><p class="small">From ₹400 — wiring, switchboards</p></div>
        <div class="card"><h4>Plumbing</h4><p class="small">From ₹300 — leak repair, fittings</p></div>
      </div>
    </section>

    <section id="contact" style="margin-top:18px">
      <h2>Contact</h2>
      <div class="card">
        <p class="small">239 Mohan Nagar, B BJS Colony, Jodhpur</p>
        <p class="small">Call: <a href="tel:+918387984425">+91 83879 84425</a></p>
        <p class="small">Email: <a href="mailto:nkhan6796@gmail.com">nkhan6796@gmail.com</a></p>
      </div>
    </section>

  </main>

  <!-- Bottom action bar - friendly for Android / mobile -->
  <div class="bottom-action" role="region" aria-label="Quick actions">
    <a class="btn-call" href="tel:+918387984425">📞</a>
    <a class="btn-book" id="openBooking">Book Now</a>
  </div>

  <footer style="text-align:center;padding:18px;color:var(--muted);margin-top:18px">© Easy Service — Jodhpur</footer>

  <script>
    // Service worker registration (optional; improves PWA behaviour on Android)
    if('serviceWorker' in navigator){
      navigator.serviceWorker?.register('/sw.js').catch(()=>{/* sw optional */});
    }

    // handle quick buttons to prefill booking form and open contact section on mobile
    document.querySelectorAll('.quick-btn').forEach(btn=>btn.addEventListener('click', ()=>{
      const svc = btn.dataset.service;
      const sel = document.getElementById('service'); if(sel) sel.value = svc;
      // focus name for quick input
      const nm = document.getElementById('name'); if(nm){ nm.focus(); }
      // scroll booking into view on small screens
      document.getElementById('bookingForm')?.scrollIntoView({behavior:'smooth',block:'center'});
    }));

    // bottom bar Book Now behaviour
    document.getElementById('openBooking').addEventListener('click', ()=>{
      // on mobile open contact / booking
      location.hash = '#contact';
      setTimeout(()=>{ document.getElementById('name')?.focus(); },350);
    });

    // booking form handling (local demo)
    document.getElementById('bookingForm')?.addEventListener('submit', e=>{
      e.preventDefault();
      const name=document.getElementById('name').value.trim();
      const phone=document.getElementById('phone').value.trim();
      if(!name||!/^\d{10}$/.test(phone)){ alert('Please enter a valid name and 10-digit phone'); return; }
      const data={service:document.getElementById('service').value,name,phone,date:document.getElementById('date').value,time:document.getElementById('time').value,notes:document.getElementById('notes').value,createdAt:new Date().toISOString()};
      const reqs=JSON.parse(localStorage.getItem('es_bookings')||'[]'); reqs.unshift(data); localStorage.setItem('es_bookings', JSON.stringify(reqs));
      alert('Thanks '+name+', we received your request and will contact you.');
      e.target.reset();
    });

    // reviews handling (local only) with simple sanitization
    function escapeHtml(s){ return (s||'').replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":"&#39;"})[c]); }
    const reviewForm=document.getElementById('reviewForm');
    const reviewsList=document.getElementById('reviewsList');
    function renderReviews(){
      const arr=JSON.parse(localStorage.getItem('es_reviews')||'[]'); reviewsList.innerHTML='';
      if(!arr.length){ reviewsList.innerHTML='<div class="small">No reviews yet. Be the first!</div>'; return; }
      arr.forEach(r=>{
        const d=document.createElement('div'); d.className='review-card';
        d.innerHTML=`<strong>${escapeHtml(r.name)}</strong> <div class="small">${escapeHtml(r.service)}</div><div class="rating">${'★'.repeat(r.rating)}${'☆'.repeat(5-r.rating)}</div><div class="small">${escapeHtml(r.text)}</div>`;
        reviewsList.appendChild(d);
      });
    }
    reviewForm?.addEventListener('submit', e=>{
      e.preventDefault();
      const name=document.getElementById('rname').value.trim();
      const phone=document.getElementById('rphone').value.trim();
      const text=document.getElementById('rtext').value.trim();
      const rating=parseInt(document.getElementById('rrating').value,10)||5;
      const service=document.getElementById('rservice').value;
      if(!name||!/^\d{10}$/.test(phone)||!text) return alert('Please fill all fields correctly');
      const arr=JSON.parse(localStorage.getItem('es_reviews')||'[]'); arr.unshift({name,phone,service,text,rating,createdAt:new Date().toISOString()}); localStorage.setItem('es_reviews',JSON.stringify(arr)); reviewForm.reset(); renderReviews(); alert('Thanks — your review was submitted.');
    });
    renderReviews();

    // improve touch targets for Android: ensure tap delay removed (fastclick-like)
    document.addEventListener('touchstart', function(){}, {passive:true});

    // simple analytics hint (no network calls) - track clicks locally
    (function(){ window._esClicks = 0; document.addEventListener('click', ()=> window._esClicks++); })();
  </script>
</body>
</html>
