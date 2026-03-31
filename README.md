[index (7).html](https://github.com/user-attachments/files/26391966/index.7.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aprenda Portugués Con la Biblia | Método BiblioLingua</title>
<meta name="description" content="Aprende portugués de forma conversacional usando la Biblia como libro de texto. Método BiblioLingua.">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;900&family=Lato:wght@300;400;700&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --gold: #C9A84C;
    --gold-light: #F0D080;
    --navy: #0A1F44;
    --navy-mid: #142952;
    --navy-light: #1E3A6E;
    --white: #FFFFFF;
    --text-light: #E8E0CC;
  }
  body { font-family: 'Lato', sans-serif; background: var(--navy); color: var(--white); line-height: 1.6; overflow-x: hidden; }

  .hero { background: linear-gradient(160deg, #0A1F44 0%, #142952 50%, #0D2B5A 100%); padding: 60px 20px 80px; text-align: center; position: relative; border-bottom: 3px solid var(--gold); }
  .hero::before { content: ''; position: absolute; top:0;left:0;right:0;bottom:0; background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='%23C9A84C' fill-opacity='0.04'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/svg%3E"); pointer-events:none; }
  .badge-top { display:inline-block; background:var(--gold); color:var(--navy); font-size:11px; font-weight:700; letter-spacing:2px; text-transform:uppercase; padding:6px 20px; border-radius:20px; margin-bottom:24px; position:relative; }
  .hero h1 { font-family:'Playfair Display',serif; font-size:clamp(30px,6vw,58px); font-weight:900; line-height:1.15; color:var(--white); margin-bottom:12px; position:relative; }
  .hero h1 span { color:var(--gold-light); }
  .hero .subtitle { font-size:clamp(16px,2.5vw,22px); color:var(--text-light); font-weight:300; max-width:680px; margin:0 auto 32px; position:relative; }
  .hero-tag { display:inline-block; border:1px solid var(--gold); color:var(--gold-light); font-size:14px; padding:6px 18px; border-radius:4px; margin-bottom:40px; font-style:italic; position:relative; }

  .price-box { background:rgba(201,168,76,0.08); border:2px solid var(--gold); border-radius:10px; padding:28px 36px; display:inline-block; margin:32px auto; text-align:center; position:relative; }
  .price-old { font-size:16px; color:#aaa; text-decoration:line-through; margin-bottom:4px; }
  .price-main { font-family:'Playfair Display',serif; font-size:54px; color:var(--gold-light); font-weight:900; line-height:1; }
  .price-desc { font-size:14px; color:var(--text-light); margin-top:6px; letter-spacing:1px; text-transform:uppercase; }

  .btn-hotmart { display:inline-block; background:linear-gradient(135deg,var(--gold) 0%,#E8B84B 50%,var(--gold) 100%); color:var(--navy); font-family:'Lato',sans-serif; font-size:18px; font-weight:700; padding:18px 42px; border-radius:6px; text-decoration:none; letter-spacing:0.5px; transition:transform 0.2s,opacity 0.2s; text-transform:uppercase; }
  .btn-hotmart:hover { transform:translateY(-2px); opacity:0.92; }
  .btn-whatsapp { display:inline-flex; align-items:center; gap:10px; background:#25D366; color:#fff; font-family:'Lato',sans-serif; font-size:16px; font-weight:700; padding:14px 32px; border-radius:6px; text-decoration:none; transition:transform 0.2s; }
  .btn-whatsapp:hover { transform:translateY(-2px); }
  .btn-email { display:inline-flex; align-items:center; gap:10px; background:transparent; color:var(--gold-light); font-family:'Lato',sans-serif; font-size:15px; font-weight:400; padding:12px 24px; border-radius:6px; text-decoration:none; border:1px solid var(--gold); transition:background 0.2s; }
  .btn-email:hover { background:rgba(201,168,76,0.1); }
  .btn-group { display:flex; flex-wrap:wrap; gap:16px; justify-content:center; align-items:center; }

  section { padding:70px 20px; }
  .section-inner { max-width:860px; margin:0 auto; }
  .section-title { font-family:'Playfair Display',serif; font-size:clamp(24px,4vw,38px); font-weight:700; text-align:center; margin-bottom:14px; color:var(--white); }
  .section-title span { color:var(--gold-light); }
  .gold-line { width:60px; height:3px; background:var(--gold); margin:0 auto 40px; border-radius:2px; }
  .divider { border:none; height:1px; background:linear-gradient(to right,transparent,var(--gold),transparent); max-width:600px; margin:0 auto; }

  .stats { background:linear-gradient(135deg,var(--navy-light),var(--navy-mid)); border-top:1px solid rgba(201,168,76,0.2); border-bottom:1px solid rgba(201,168,76,0.2); }
  .stats-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(160px,1fr)); gap:24px; text-align:center; }
  .stat-num { font-family:'Playfair Display',serif; font-size:44px; color:var(--gold-light); font-weight:900; line-height:1; margin-bottom:6px; }
  .stat-desc { font-size:13px; color:var(--text-light); text-transform:uppercase; letter-spacing:1px; }

  .para-quien { background:var(--navy-mid); }
  .cards-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:20px; margin-top:32px; }
  .card { background:rgba(255,255,255,0.04); border:1px solid rgba(201,168,76,0.3); border-radius:10px; padding:26px 22px; text-align:center; }
  .card-icon { font-size:32px; margin-bottom:12px; display:block; }
  .card h3 { font-family:'Playfair Display',serif; font-size:17px; color:var(--gold-light); margin-bottom:8px; }
  .card p { font-size:14px; color:var(--text-light); line-height:1.6; }

  .beneficios { background:var(--navy); }
  .benefit-list { list-style:none; margin-top:32px; }
  .benefit-list li { display:flex; align-items:flex-start; gap:16px; margin-bottom:22px; padding:20px 22px; background:rgba(255,255,255,0.03); border-left:3px solid var(--gold); border-radius:0 8px 8px 0; }
  .check { width:22px; height:22px; min-width:22px; background:var(--gold); border-radius:50%; display:flex; align-items:center; justify-content:center; font-size:13px; color:var(--navy); font-weight:700; margin-top:2px; }
  .benefit-list li p { font-size:15px; color:var(--text-light); line-height:1.6; }
  .benefit-list li strong { color:var(--gold-light); font-weight:700; }

  .testimonios { background:var(--navy-mid); }
  .testi-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(240px,1fr)); gap:20px; margin-top:36px; }
  .testi-card { background:rgba(255,255,255,0.04); border:1px solid rgba(201,168,76,0.25); border-radius:10px; padding:26px 22px; }
  .stars { color:var(--gold); font-size:16px; margin-bottom:12px; }
  .testi-card blockquote { font-size:15px; color:var(--text-light); font-style:italic; line-height:1.7; margin-bottom:14px; }
  .testi-card .author { font-size:13px; color:var(--gold); font-weight:700; text-transform:uppercase; letter-spacing:1px; }

  .cta-final { background:linear-gradient(160deg,#0D2B5A 0%,#0A1F44 100%); border-top:3px solid var(--gold); text-align:center; padding:80px 20px; }
  .cta-final h2 { font-family:'Playfair Display',serif; font-size:clamp(26px,5vw,44px); margin-bottom:16px; color:var(--white); }
  .cta-final h2 span { color:var(--gold-light); }
  .cta-sub { font-size:16px; color:var(--text-light); max-width:560px; margin:0 auto 36px; }

  .garantia { background:rgba(201,168,76,0.06); border:1px solid rgba(201,168,76,0.3); border-radius:12px; padding:28px 32px; display:flex; align-items:center; gap:22px; max-width:680px; margin:40px auto 0; text-align:left; }
  .garantia-icon { font-size:42px; min-width:50px; text-align:center; }
  .garantia h4 { font-family:'Playfair Display',serif; font-size:18px; color:var(--gold-light); margin-bottom:6px; }
  .garantia p { font-size:14px; color:var(--text-light); line-height:1.6; margin:0; }

  footer { background:#06101F; padding:28px 20px; text-align:center; border-top:1px solid rgba(201,168,76,0.15); }
  footer p { font-size:13px; color:#666; }
  footer a { color:var(--gold); text-decoration:none; }
  footer a:hover { color:var(--gold-light); }

  .wa-float { position:fixed; bottom:28px; right:28px; background:#25D366; color:white; width:58px; height:58px; border-radius:50%; display:flex; align-items:center; justify-content:center; text-decoration:none; z-index:999; box-shadow:0 4px 20px rgba(37,211,102,0.5); transition:transform 0.2s; }
  .wa-float:hover { transform:scale(1.1); }

  @media (max-width:600px) {
    .garantia { flex-direction:column; text-align:center; }
    .price-main { font-size:42px; }
    .price-box { padding:20px 24px; }
  }
</style>
</head>
<body>

<a class="wa-float" href="https://wa.me/5493755533627?text=Hola!%20Quiero%20saber%20m%C3%A1s%20sobre%20el%20curso%20Aprenda%20Portugu%C3%A9s%20con%20la%20Biblia" target="_blank" title="Escribinos por WhatsApp">
  <svg width="28" height="28" viewBox="0 0 24 24" fill="white"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
</a>

<section class="hero">
  <div class="section-inner">
    <span class="badge-top">✦ Método BiblioLingua ✦</span>
    <h1>Aprenda <span>Portugués</span><br>Con la Biblia</h1>
    <p class="subtitle">El método conversacional que transforma tu fe en fluencia — aprende uno de los idiomas más hermosos del mundo mientras creces en la Palabra de Dios.</p>
    <div class="hero-tag">"No solo aprendes un idioma, te transformas por dentro"</div>
    <div class="price-box">
      <div class="price-old">Valor regular: USD $197</div>
      <div class="price-main">$97</div>
      <div class="price-desc">Pago único · Acceso de por vida</div>
    </div>
    <br>
    <div class="btn-group">
      <a href="https://pay.hotmart.com/G91498219K" target="_blank" class="btn-hotmart">¡Quiero empezar ahora!</a>
    </div>
  </div>
</section>

<hr class="divider" style="margin-top:0;">

<section class="stats">
  <div class="section-inner">
    <div class="stats-grid">
      <div><div class="stat-num">280M+</div><div class="stat-desc">Hablantes de Portugués</div></div>
      <div><div class="stat-num">5°</div><div class="stat-desc">Idioma más hablado del mundo</div></div>
      <div><div class="stat-num">2 en 1</div><div class="stat-desc">Idioma + Crecimiento espiritual</div></div>
      <div><div class="stat-num">100%</div><div class="stat-desc">Método conversacional</div></div>
    </div>
  </div>
</section>

<section class="para-quien">
  <div class="section-inner">
    <h2 class="section-title">Este curso es para <span>ti</span> si...</h2>
    <div class="gold-line"></div>
    <div class="cards-grid">
      <div class="card">
        <span class="card-icon">✝️</span>
        <h3>Eres cristiano/a</h3>
        <p>Querés expandir tu ministerio, conectar con hermanos de habla portuguesa y profundizar en la Palabra de Dios.</p>
      </div>
      <div class="card">
        <span class="card-icon">💼</span>
        <h3>Hombre/Mujer de negocios</h3>
        <p>Brasil es la mayor economía de América Latina. Hablar portugués abre puertas que ningún otro idioma puede abrir.</p>
      </div>
      <div class="card">
        <span class="card-icon">✈️</span>
        <h3>Turista o viajero</h3>
        <p>Brasil, Portugal, Angola, Mozambique... un mundo entero te espera cuando hablás el idioma de esos pueblos.</p>
      </div>
      <div class="card">
        <span class="card-icon">🌱</span>
        <h3>Buscas crecer</h3>
        <p>Tenés entre 30 y 55 años y sabés que nunca es tarde para aprender, crecer y transformar tu vida con propósito.</p>
      </div>
    </div>
  </div>
</section>

<section class="beneficios">
  <div class="section-inner">
    <h2 class="section-title">¿Qué vas a <span>lograr</span>?</h2>
    <div class="gold-line"></div>
    <ul class="benefit-list">
      <li><span class="check">✓</span><p><strong>Hablar portugués con confianza</strong> desde las primeras semanas — el método conversacional BiblioLingua está diseñado para que aprendas hablando, no memorizando reglas aburridas.</p></li>
      <li><span class="check">✓</span><p><strong>Usar la Biblia como tu libro de texto</strong> — cada lección está basada en pasajes bíblicos reales, haciendo el aprendizaje significativo, memorable y espiritualmente enriquecedor.</p></li>
      <li><span class="check">✓</span><p><strong>Crecer en tu comunión con Dios</strong> — al leer, escuchar y hablar Su Palabra en otro idioma, tu fe se profundiza de formas que no imaginabas posibles.</p></li>
      <li><span class="check">✓</span><p><strong>Abrir nuevas puertas de ministerio</strong> — imaginá predicar, enseñar o servir en portugués a millones de personas en Brasil, Portugal y toda la comunidad lusófona del mundo.</p></li>
      <li><span class="check">✓</span><p><strong>Nuevas oportunidades de negocios y turismo</strong> — conectate con más de 280 millones de hablantes y accedé a mercados, relaciones y experiencias que hoy están cerradas para vos.</p></li>
      <li><span class="check">✓</span><p><strong>Aprender completamente a tu ritmo</strong> — acceso de por vida al material, desde cualquier dispositivo, en cualquier momento, sin presiones de horario ni fechas de vencimiento.</p></li>
    </ul>
  </div>
</section>

<hr class="divider">

<section class="testimonios">
  <div class="section-inner">
    <h2 class="section-title">Lo que dicen nuestros <span>alumnos</span></h2>
    <div class="gold-line"></div>
    <div class="testi-grid">
      <div class="testi-card">
        <div class="stars">★★★★★</div>
        <blockquote>"Nunca pensé que aprender portugués podría fortalecer tanto mi fe. Cada lección me acerca más a Dios y al idioma al mismo tiempo. Es simplemente increíble."</blockquote>
        <div class="author">— María G., Argentina</div>
      </div>
      <div class="testi-card">
        <div class="stars">★★★★★</div>
        <blockquote>"Como empresario, siempre supe que necesitaba el portugués. Este método me dio el idioma Y algo mucho más valioso: una conexión más profunda con mi fe y con Dios."</blockquote>
        <div class="author">— Carlos P., Colombia</div>
      </div>
      <div class="testi-card">
        <div class="stars">★★★★★</div>
        <blockquote>"En cuatro semanas pude tener mi primera conversación en portugués con un hermano de Brasil. La metodología es única — literalmente la Biblia como maestro."</blockquote>
        <div class="author">— Ana R., México</div>
      </div>
    </div>
  </div>
</section>

<section class="cta-final">
  <div class="section-inner">
    <h2>¿Listo para comenzar tu <span>nueva vida</span> en portugués?</h2>
    <p class="cta-sub">Una sola inversión de por vida. Un idioma hermoso. Una fe más profunda. Cientos de puertas nuevas. La decisión es tuya hoy.</p>
    <div class="price-box" style="margin-bottom:36px;">
      <div class="price-old">Valor regular: USD $197</div>
      <div class="price-main">$97</div>
      <div class="price-desc">Pago único · Acceso de por vida · Garantía de 7 días</div>
    </div>
    <div class="btn-group">
      <a href="https://pay.hotmart.com/G91498219K" target="_blank" class="btn-hotmart">Inscribirme ahora por $97</a>
      <a href="https://wa.me/5493755533627?text=Hola!%20Tengo%20preguntas%20sobre%20el%20curso%20Aprenda%20Portugu%C3%A9s%20con%20la%20Biblia" target="_blank" class="btn-whatsapp">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="white"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
        Consultar por WhatsApp
      </a>
      <a href="/cdn-cgi/l/email-protection#cabab8a5b3afa9beabb8a7abb98aada7aba3a6e4a9a5a7f5b9bfa8a0afa9bef789a5a4b9bfa6beabeff8fab9a5a8b8afeff8fa8bbab8afa4aeabeff8fa9aa5b8bebfadbfef89f9ef8bf3b9eff8faa9a5a4eff8faa6abeff8fa88a3a8a6a3ab" class="btn-email">✉ Escribir por Email</a>
    </div>
    <div class="garantia">
      <div class="garantia-icon">🛡️</div>
      <div>
        <h4>Garantía de 7 días sin ningún riesgo</h4>
        <p>Si en los primeros 7 días sentís que el curso no es para vos, te devolvemos el 100% de tu inversión. Sin preguntas, sin burocracia. Nuestra confianza está puesta en el método.</p>
      </div>
    </div>
  </div>
</section>

<footer>
  <p>© 2025 Aprenda Portugués Con la Biblia · Método BiblioLingua · Todos los derechos reservados</p>
  <p style="margin-top:10px;">
    <a href="https://wa.me/5493755533627" target="_blank">WhatsApp</a> &nbsp;·&nbsp;
    <a href="/cdn-cgi/l/email-protection#166664796f73756277647b776556717b777f7a3875797b">
