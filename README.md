<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no" />
  <title>Easy Service Jodhpur — AC, Geyser & Washing Machine Repair</title>
  <meta name="description" content="Easy Service Jodhpur — 24/7 AC repair, geyser service, washing machine repair, electrician and plumbing. Call or WhatsApp to book. Expert: Javed Khan." />
  <meta name="keywords" content="AC service, AC repair, geyser service and repairing, washing machine repair, electrician service, Jodhpur" />
  <meta name="theme-color" content="#1a1f4b" />

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg1:#1a1f4b;
      --bg2:#2b4c7e;
      --accent1:#39a1ff;
      --accent2:#6a60ff;
      --glass: rgba(255,255,255,0.06);
      --muted: rgba(255,255,255,0.85);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Roboto,Arial,sans-serif;-webkit-font-smoothing:antialiased}
    body{
      display:flex;
      flex-direction:column;
      min-height:100vh;
      background: linear-gradient(180deg,var(--bg1),var(--bg2));
      color:#fff;
      text-align:center;
    }

    /* Header / phone safe area */
    header{
      padding:18px 20px 8px;
      font-weight:800;
      font-size:18px;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }
    .brand{display:flex;gap:12px;align-items:center}
    .logo{
      width:44px;height:44px;border-radius:10px;
      background:linear-gradient(135deg,var(--accent1),var(--accent2));
      display:flex;align-items:center;justify-content:center;font-weight:900;color:#fff;
    }
    .menu{opacity:0.9;font-size:20px}

    /* Main screen */
    .screen{
      flex:1;
      display:flex;
      flex-direction:column;
      align-items:center;
      justify-content:center;
      padding:6vh 20px 110px;
    }
    h1{font-size:22px;margin:6px 0;font-weight:800}
    p.lead{margin:0 0 18px;color:var(--muted);line-height:1.35;max-width:420px}

    /* Pill buttons */
    .pills{width:100%;max-width:420px;display:flex;flex-direction:column;gap:16px;margin-top:6px}
    .pill{
      display:inline-block;padding:14px 18px;border-radius:999px;
      font-weight:800;color:#fff;text-decoration:none;
      background:linear-gradient(90deg,var(--accent1),var(--accent2));
      box-shadow:0 12px 30px rgba(0,0,0,0.25);
      min-width:220px;
    }
    .pill.secondary{
      background:transparent;border:1px solid rgba(255,255,255,0.08);
      box-shadow:none;font-weight:700;color:var(--muted)
    }

    .info{margin-top:18px;max-width:420px}
    .info h3{margin:6px 0 6px}
    .info p{margin:0;color:rgba(255,255,255,0.86)}

    /* Dots nav style */
    .dots{display:flex;gap:10px;margin-top:22px}
    .dot{width:12px;height:12px;border-radius:50%;background:rgba(255,255,255,0.2)}
    .dot.active{background:linear-gradient(90deg,#7bd6ff,#ffd86a);box-shadow:0 8px 20px rgba(0,0,0,0.25)}

    /* Booking slide-up panel */
    .panel{
      position:fixed;
      left:0;right:0;
      bottom:-2px;
      padding:16px 18px 28px;
      background: linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.02));
      backdrop-filter: blur(8px);
      border-top-left-radius:18px;
      border-top-right-radius:18px;
      box-shadow: 0 -18px 40px rgba(0,0,0,0.45);
      transform: translateY(110%);
      transition: transform .36s cubic-bezier(.22,.9,.32,1);
      z-index:40;
    }
    .panel.open{transform: translateY(0);}
    .panel .handle{width:36px;height:4px;background:rgba(255,255,255,0.22);border-radius:999px;margin:6px auto}
    .panel h4{margin:8px 0 6px;font-size:18px}
    input,select,textarea{
      width:100%;padding:12px;border-radius:10px;border:0;background:var(--glass);color:#fff;margin-top:8px;font-size:15px;
    }
    .row{display:flex;gap:8px}
    .btn-row{display:flex;gap:8px;margin-top:12px}
    .btn{flex:1;padding:12px;border-radius:10px;border:0;font-weight:800}
    .btn.primary{background:linear-gradient(90deg,var(--accent1),var(--accent2));color:#fff}
    .btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.12);color:#fff}

    /* Floating WhatsApp button */
    .whatsapp{
      position:fixed;right:16px;bottom:18px;width:56px;height:56px;border-radius:999px;
      background:#25D366;color:#fff;display:flex;align-items:center;justify-content:center;
      box-shadow:0 12px 36px rgba(0,0,0,0.35);z-index:60;text-decoration:none;font-size:22px;
    }

    footer{padding:14px 10px;color:rgba(255,255,255,0.7);font-size:13px;text-align:center}

    @media(min-width:800px){
      body{text-align:center}
      .screen{padding-top:12vh;padding-bottom:120px}
      .panel{left:50%;max-width:420px;transform:translate(-50%,110%);border-radius:14px}
      .panel.open{transform:translate(-50%,0)}
    }
  </style>
</head>
<body>

  <header>
    <div class="brand">
      <div class="logo">ES</div>
      <div style="text-align:left">
        <div style="font-weight:900">Easy Service</div>
        <div style="font-size:12px;opacity:0.9">Jodhpur • 24/7</div>
      </div>
    </div>
    <div class="menu" aria-hidden="true">☰</div>
  </header>

  <div class="screen" role="main">
    <h1>AC, Geyser & Washing Machine Repair</h1>
    <p class="lead">Fast 24/7 service at your doorstep. Expert technician: <strong>Javed Khan</strong>.</p>

    <div class="pills" role="navigation" aria-label="Quick services">
      <a href="#book" class="pill" id="bookAC" data-service="AC Service">Book AC Service</a>
      <a href="#book" class="pill" id="bookGeyser" data-service="Geyser Service">Geyser Service & Repair</a>
      <a href="#book" class="pill" id="bookWash" data-service="Washing Machine Service">Washing Machine Repair</a>
      <a href="tel:+918387984425" class="pill secondary">Call: +91 83879 84425</a>
    </div>

    <div class="info" aria-hidden="false">
      <h3>Trusted technicians</h3>
      <p>Uniformed, background-checked, equipped with parts. Transparent pricing and short warranty on workmanship.</p>
    </div>

    <div class="dots" aria-hidden="true">
      <span class="dot"></span>
      <span class="dot"></span>
      <span class="dot active"></span>
      <span class="dot"></span>
    </div>
  </div>

  <!-- Slide-up booking panel -->
  <div class="panel" id="panel" role="dialog" aria-hidden="true" aria-labelledby="panelTitle">
    <div class="handle" aria-hidden="true"></div>
    <h4 id="panelTitle">Request a Visit</h4>

    <form id="bookingForm" autocomplete="off">
      <label class="sr-only" for="svc">Service</label>
      <select id="svc" name="service" aria-label="Choose service">
        <option>AC Service</option>
        <option>Geyser Service</option>
        <option>Washing Machine Service</option>
        <option>Electrician</option>
        <option>Plumbing</option>
      </select>

      <div class="row">
        <input id="bname" name="name" type="text" placeholder="Your name" required aria-required="true" />
        <input id="bphone" name="phone" type="tel" inputmode="tel" pattern="[0-9]*" placeholder="Phone (10 digits)" required aria-required="true" />
      </div>

      <div class="row">
        <input id="bdate" name="date" type="date" />
        <input id="btime" name="time" type="time" />
      </div>

      <textarea id="bnotes" name="notes" rows="3" placeholder="Address / landmark / issue (optional)"></textarea>

      <div class="btn-row" role="group" aria-label="Booking actions">
        <button type="submit" class="btn primary">Request Visit</button>
        <button type="button" id="cancelPanel" class="btn ghost">Cancel</button>
      </div>
    </form>
  </div>

  <!-- Floating WhatsApp button -->
  <a id="whatsappBtn" class="whatsapp" href="https://wa.me/918387984425?text=Hello%20Easy%20Service,%20I%20need%20help" target="_blank" rel="noopener" aria-label="Chat on WhatsApp">
    <!-- simple WhatsApp icon (SVG) -->
    <svg width="26" height="26" viewBox="0 0 24 24" fill="none" aria-hidden="true" xmlns="http://www.w3.org/2000/svg">
      <path d="M20.5 3.5C18.9 2 16.8 1 14.5 1 8 1 2.8 6.2 2.8 12.7c0 1.9.5 3.6 1.5 5.2L2 22l3.4-1.1C7.3 21.5 8.9 22 10.8 22 17.3 22 22.5 16.8 22.5 10.3 22.5 8 21.5 5.9 20 4.3L20.5 3.5z" fill="#fff" opacity="0.06"/>
      <path d="M16.2 14.2c-.3-.1-1.8-.9-2-.9-.4 0-.6.1-.9.4-.3.3-1 .8-1.5 1.1-.6.3-1 .2-1.5-.5-.4-.6-1.5-2-1.5-2.6 0-.6.7-1 .9-1.2.2-.1.5-.3.8-.5.3-.2.5-.3.6-.6.1-.3 0-.6-.1-.9-.1-.3-.9-2.1-1.2-2.9-.3-.7-.7-.6-1-.6-.3 0-.6 0-.9 0-.3 0-.7.1-1 .6s-1.3 1.7-1.3 3.9 1.3 4.5 1.5 4.8c.2.3 2 3.1 5 4.2 3 .9 3.3.6 3.9.5.5-.1 1.8-.7 2-1.5.2-.8.2-1.5.1-1.6-.1-.2-.4-.3-.8-.4z" fill="#fff"/>
    </svg>
  </a>

  <footer>© Easy Service — Jodhpur · 24/7</footer>

  <script>
    /* Panel open/close and quick service buttons */
    (function(){
      const panel = document.getElementById('panel');
      const svc = document.getElementById('svc');
      const openAC = document.getElementById('bookAC');
      const openGeyser = document.getElementById('bookGeyser');
      const openWash = document.getElementById('bookWash');
      const cancelBtn = document.getElementById('cancelPanel');
      const bookingForm = document.getElementById('bookingForm');
      const whatsappBtn = document.getElementById('whatsappBtn');

      function openPanel(service){
        if(service) svc.value = service;
        panel.classList.add('open');
        panel.setAttribute('aria-hidden','false');
        setTimeout(()=> document.getElementById('bname').focus(), 250);
        // update WhatsApp prefill with service
        updateWhatsappHref(service || svc.value);
      }
      function closePanel(){
        panel.classList.remove('open');
        panel.setAttribute('aria-hidden','true');
        updateWhatsappHref(); // reset to default
      }

      openAC.addEventListener('click', function(e){ e.preventDefault(); openPanel('AC Service'); });
      openGeyser.addEventListener('click', function(e){ e.preventDefault(); openPanel('Geyser Service'); });
      openWash.addEventListener('click', function(e){ e.preventDefault(); openPanel('Washing Machine Service'); });
      cancelBtn.addEventListener('click', function(){ closePanel(); });

      panel.addEventListener('click', function(e){
        // if clicking on background area of panel (not the form), close
        if(e.target === panel) closePanel();
      });

      bookingForm.addEventListener('submit', function(e){
        e.preventDefault();
        const name = document.getElementById('bname').value.trim();
        const phone = document.getElementById('bphone').value.trim();
        if(!name || !/^\d{10}$/.test(phone)){
          alert('Please enter your name and a valid 10-digit phone number.');
          return;
        }
        const data = {
          service: svc.value,
          name,
          phone,
          date: document.getElementById('bdate').value,
          time: document.getElementById('btime').value,
          notes: document.getElementById('bnotes').value,
          createdAt: new Date().toISOString()
        };
        // save locally for demo (replace with backend later)
        const arr = JSON.parse(localStorage.getItem('es_bookings') || '[]');
        arr.unshift(data);
        localStorage.setItem('es_bookings', JSON.stringify(arr));
        alert('Thanks ' + name + '. Your request has been received. We will call to confirm.');
        bookingForm.reset();
        closePanel();
      });

      // Update WhatsApp link to include chosen service and optional name/phone
      function updateWhatsappHref(service){
        const base = 'https://wa.me/918387984425';
        const name = encodeURIComponent(document.getElementById('bname').value.trim() || '');
        const phone = encodeURIComponent(document.getElementById('bphone').value.trim() || '');
        const svcText = encodeURIComponent(service || svc.value || 'Service');
        let text = 'Hello Easy Service, I need ' + svcText;
        if(name) text += '. My name is ' + name;
        if(phone) text += ' (' + phone + ')';
        whatsappBtn.href = base + '?text=' + encodeURIComponent(text);
      }

      // Keep WhatsApp link in sync when user types name/phone/service
      document.getElementById('bname').addEventListener('input', ()=> updateWhatsappHref());
      document.getElementById('bphone').addEventListener('input', ()=> updateWhatsappHref());
      svc.addEventListener('change', ()=> updateWhatsappHref());

      // set default WA href on load
      updateWhatsappHref();

      // remove 300ms delay on mobile taps
      document.addEventListener('touchstart', function(){}, {passive:true});
    })();
  </script>
</body>
</html>
