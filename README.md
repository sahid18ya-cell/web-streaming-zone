<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Streaming Zone Panama SR — Celulares y accesorios</title>
  <meta name="description" content="Streaming Zone Panama SR — Venta de celulares, gadgets y accesorios. Precios claros y envíos a todo Panamá. Escríbenos por WhatsApp." />
  <meta property="og:title" content="Streaming Zone Panama SR" />
  <meta property="og:description" content="Celulares, gadgets y accesorios. Precios claros, envíos a todo Panamá." />
  <meta property="og:image" content="logo.png" />
  <meta name="theme-color" content="#0b0b0b" />

  <style>
    :root{
      --bg:#0b0b0b;
      --card:#141414;
      --muted:#bfbfbf;
      --accent:#00c853;
      --white:#ffffff;
      --radius:12px;
      --max-width:980px;
    }

    html,body{height:100%}
    body{
      margin:0;
      background:linear-gradient(180deg,#080808 0%,var(--bg)100%);
      color:var(--white);
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
      display:flex;
      justify-content:center;
      padding:24px;
    }

    .wrap{
      width:100%;
      max-width:var(--max-width);
    }

    header{
      text-align:center;
      padding:12px 10px 6px 10px;
    }

    .logo-row{
      display:inline-flex;
      gap:12px;
      align-items:center;
      justify-content:center;
    }

    .logo-row img{
      width:86px;
      height:86px;
      object-fit:contain;
      border-radius:14px;
      background:linear-gradient(135deg,#0f0f0f,#171717);
      box-shadow:0 8px 22px rgba(0,0,0,0.6);
    }

    h1{
      margin:0;
      font-size:20px;
      letter-spacing:0.2px;
    }

    .sub{
      margin-top:6px;
      color:var(--muted);
      font-size:14px;
    }

    .bio{
      margin:18px 0;
      display:flex;
      gap:12px;
      justify-content:center;
      flex-wrap:wrap;
    }

    .bio .pill{
      background:rgba(255,255,255,0.02);
      border:1px solid rgba(255,255,255,0.03);
      padding:10px 14px;
      border-radius:999px;
      font-size:14px;
      color:var(--muted);
      display:inline-flex;
      gap:8px;
      align-items:center;
    }

    main{ margin-top:6px; }

    .productos{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
      gap:18px;
      padding:8px;
    }

    .card{
      background:var(--card);
      border-radius:var(--radius);
      padding:12px;
      box-shadow:0 8px 22px rgba(0,0,0,0.5);
      transition:transform .16s ease, box-shadow .16s ease;
      display:flex;
      flex-direction:column;
      gap:8px;
      min-height:220px;
      justify-content:space-between;
    }

    .card:hover{ transform:translateY(-6px); box-shadow:0 16px 40px rgba(0,0,0,0.6); }

    .thumb{
      width:100%;
      aspect-ratio:16/12;
      border-radius:10px;
      overflow:hidden;
      background:linear-gradient(90deg,#0f0f0f,#191919);
      display:flex;
      align-items:center;
      justify-content:center;
    }

    .thumb img{ width:100%; height:100%; object-fit:cover; display:block; }

    .card h3{ margin:0; font-size:15px; color:var(--white); font-weight:600; }

    .price{ color:var(--accent); font-weight:700; margin-top:6px; }

    .contacto{ display:flex; justify-content:center; gap:12px; margin:18px 0; flex-wrap:wrap; }

    .btn-whatsapp{
      background:linear-gradient(90deg,#00b14f,#00c853);
      color:#021;
      text-decoration:none;
      padding:14px 20px;
      border-radius:999px;
      font-weight:700;
      display:inline-flex;
      gap:10px;
      align-items:center;
      box-shadow:0 10px 30px rgba(0,200,83,0.14);
    }

    .btn-secondary{
      background:transparent;
      border:1px solid rgba(255,255,255,0.06);
      color:var(--muted);
      padding:12px 14px;
      border-radius:999px;
      text-decoration:none;
      font-weight:600;
    }

    footer{ text-align:center; color:#8f8f8f; font-size:13px; margin-top:14px; padding-bottom:24px; }

    .float-wa{
      position:fixed; right:16px; bottom:16px; z-index:1200;
      background:linear-gradient(90deg,#00b14f,#00c853); color:#021;
      border-radius:999px; padding:10px 12px; box-shadow:0 12px 30px rgba(0,200,83,0.14);
    }

    .float-wa a{ color:inherit; text-decoration:none; display:flex; gap:8px; align-items:center; font-weight:700; }

    @media (max-width:540px){
      body{ padding:14px; }
      .logo-row img{ width:72px; height:72px; }
      h1{ font-size:18px; }
      .card{ min-height:200px; }
    }
  </style>
</head>
<body>
  <div class="wrap" id="app">
    <header>
      <div class="logo-row" role="img" aria-label="Logo de Streaming Zone Panama SR">
        <img src="logo.png" alt="Logo Streaming Zone Panama SR" id="logo" onerror="this.style.display='none'">
        <div style="text-align:left">
          <h1>Streaming Zone Panama SR</h1>
          <div class="sub">Celulares, gadgets y accesorios</div>
        </div>
      </div>
    </header>

    <section class="bio" aria-label="Servicios">
      <div class="pill">📱 Celulares, gadgets y accesorios</div>
      <div class="pill">💲 Precios claros y trato serio</div>
      <div class="pill">💬 Escríbenos sin compromiso</div>
      <div class="pill">🚛 Envíos a todo el país</div>
    </section>

    <main>
      <h2 style="text-align:left; margin:8px 4px; color:var(--muted); font-size:15px;">Productos destacados</h2>

      <section id="productos" class="productos" aria-live="polite">
        <!-- Renderiza productos desde JS -->
      </section>

      <div class="contacto" role="region" aria-label="Contacto">
        <a id="wa-main" class="btn-whatsapp" href="#" target="_blank" rel="noopener noreferrer" aria-label="Escríbanos por WhatsApp">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M20.52 3.48A11.88 11.88 0 0012.03.12a11.88 11.88 0 00-8.49 3.36A11.88 11.88 0 00.08 11.88c0 2.09.55 4.13 1.6 5.92L.12 23.9l6.27-1.66A11.88 11.88 0 0012.03 23.9h.01c2.09 0 4.13-.55 5.92-1.6a11.88 11.88 0 003.36-8.5 11.88 11.88 0 00-3.8-8.22z" fill="#fff" opacity="0.06"/><path d="M16.5 13.1c-.3-.15-1.75-.87-2.02-.97-.27-.1-.47-.15-.67.15s-.76.97-.93 1.17c-.17.2-.33.23-.64.08-.3-.15-1.26-.46-2.4-1.48-.89-.79-1.48-1.78-1.65-2.07-.17-.3 0-.46.12-.61.12-.12.27-.33.4-.5.13-.17.17-.28.27-.47.1-.18.05-.34-.02-.47-.07-.12-.67-1.63-.92-2.24-.24-.59-.49-.49-.67-.5-.17-.007-.37-.01-.57-.01s-.47.07-.71.34c-.24.26-.92.9-.92 2.19 0 1.28.94 2.52 1.07 2.69.12.17 1.84 3.04 4.45 4.26 3.1 1.44 3.1 0 3.66-.01.59-.01 1.97-.78 2.24-1.53.27-.75.27-1.39.19-1.53-.08-.14-.28-.22-.58-.37z" fill="#021"/></svg>
          Escríbanos por WhatsApp
        </a>

        <a href="#" class="btn-secondary" id="btn-refresh" title="Actualizar productos">Actualizar ahora</a>
      </div>
    </main>

    <footer>
      <div>© Streaming Zone Panama SR</div>
      <div style="margin-top:6px; color:var(--muted); font-size:12px;">Fácil de editar — Listo para GitHub Pages</div>
    </footer>
  </div>

  <div class="float-wa" aria-hidden="true">
    <a id="float-wa-link" href="#" target="_blank" rel="noopener noreferrer">
      <svg width="18" height="18" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M20.52 3.48A11.88 11.88 0 0012.03.12a11.88 11.88 0 00-8.49 3.36A11.88 11.88 0 00.08 11.88c0 2.09.55 4.13 1.6 5.92L.12 23.9l6.27-1.66A11.88 11.88 0 0012.03 23.9h.01c2.09 0 4.13-.55 5.92-1.6a11.88 11.88 0 003.36-8.5 11.88 11.88 0 00-3.8-8.22z" fill="#fff" opacity="0.06"/><path d="M16.5 13.1c-.3-.15-1.75-.87-2.02-.97-.27-.1-.47-.15-.67.15s-.76.97-.93 1.17c-.17.2-.33.23-.64.08-.3-.15-1.26-.46-2.4-1.48-.89-.79-1.48-1.78-1.65-2.07-.17-.3 0-.46.12-.61.12-.12.27-.33.4-.5.13-.17.17-.28.27-.47.1-.18.05-.34-.02-.47-.07-.12-.67-1.63-.92-2.24-.24-.59-.49-.49-.67-.5-.17-.007-.37-.01-.57-.01s-.47.07-.71.34c-.24.26-.92.9-.92 2.19 0 1.28.94 2.52 1.07 2.69.12.17 1.84 3.04 4.45 4.26 3.1 1.44 3.1 0 3.66-.01.59-.01 1.97-.78 2.24-1.53.27-.75.27-1.39.19-1.53-.08-.14-.28-.22-.58-.37z" fill="#021"/></svg>
      WhatsApp
    </a>
  </div>

  <script>
    // URL base de WhatsApp (con texto opcional)
    const WHATSAPP_URL = 'https://wa.me/50764507162?text=Hola%20Streaming%20Zone,%20tengo%20una%20consulta';

    document.getElementById('wa-main').href = WHATSAPP_URL;
    document.getElementById('float-wa-link').href = WHATSAPP_URL;

    // Productos por defecto (si no existiera products.json)
    const DEFAULT_PRODUCTS = [
      { id: 'p1', name: 'Redmi 15C Negro Ocaso', image: 'producto1.jpg', price: 'B/ 169' },
      { id: 'p2', name: 'Pods Pro 2', image: 'producto2.jpg', price: 'B/ 49' },
      { id: 'p3', name: 'Pods 4', image: 'producto3.jpg', price: 'B/ 39' }
    ];

    const productosEl = document.getElementById('productos');

    function escapeHtml(str){
      if(str === null || str === undefined) return '';
      return String(str).replace(/[&<>"']/g, s => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[s]));
    }

    function placeholderSvg(){
      return encodeURIComponent(`<svg xmlns='http://www.w3.org/2000/svg' width='400' height='300' viewBox='0 0 400 300'><rect width='100%' height='100%' fill='#111'/><text x='50%' y='50%' fill='#666' font-size='18' dominant-baseline='middle' text-anchor='middle'>Imagen no disponible</text></svg>`);
    }

    function createCard(p){
      const article = document.createElement('article');
      article.className = 'card';
      article.tabIndex = 0;
      article.innerHTML = `
        <div class="thumb">
          <img src="${escapeHtml(p.image)}" alt="${escapeHtml(p.name)}" loading="lazy" onerror="this.onerror=null;this.src='data:image/svg+xml;utf8,${placeholderSvg()}'">
        </div>
        <div>
          <h3>${escapeHtml(p.name)}</h3>
          ${p.price ? `<div class="price">${escapeHtml(p.price)}</div>` : ''}
        </div>
      `;
      return article;
    }

    function render(products){
      productosEl.innerHTML = '';
      if(!products || products.length === 0){
        productosEl.innerHTML = '<div style="color:var(--muted); padding:12px">No hay productos para mostrar.</div>';
        return;
      }
      const frag = document.createDocumentFragment();
      products.forEach(p => frag.appendChild(createCard(p)));
      productosEl.appendChild(frag);
    }

    async function loadProducts(){
      // intenta cargar products.json desde la raíz (haz push de products.json para actualizar sin tocar HTML)
      try{
        const res = await fetch('products.json', {cache:'no-store'});
        if(!res.ok) throw new Error('no-json');
        const json = await res.json();
        if(Array.isArray(json) && json.length) {
          render(json);
          return;
        }
      }catch(e){
        // fallback
      }
      render(DEFAULT_PRODUCTS);
    }

    // carga inicial y reintentos
    loadProducts();
    document.getElementById('btn-refresh').addEventListener('click', (e)=>{
      e.preventDefault();
      const btn = e.currentTarget;
      btn.textContent = 'Actualizando...';
      btn.setAttribute('aria-busy', 'true');
      loadProducts().finally(()=>{ setTimeout(()=>{ btn.textContent='Actualizar ahora'; btn.removeAttribute('aria-busy'); }, 800); });
    });

    // reintenta automáticamente cada 90s (útil si actualizas products.json en el repo)
    setInterval(loadProducts, 90000);
  </script>
</body>
</html>
