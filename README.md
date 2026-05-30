[esteticaPñ2.html](https://github.com/user-attachments/files/28428483/esteticaPn2.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Piñaretes — Calidad y Belleza</title>
<link href="https://i.pinimg.com/736x/4b/25/63/4b2563c7fee6051e631d680fbd00af8e.jpg">
<style>
:root {
  --rose: #E8A0A8;
  --rose-light: #F5D5D9;
  --rose-pale: #FDF0F1;
  --rose-deep: #C4737C;
  --rose-dark: #8B4A52;
  --cream: #FBF6F3;
  --warm-white: #FEFAF8;
  --text-dark: #3D2428;
  --text-mid: #7A4C52;
  --text-soft: #B08890;
  --gold: #D4A574;
  --gold-light: #EDD9B8;
}
* { margin: 0; padding: 0; box-sizing: border-box; }
html { scroll-behavior: smooth; }
body { font-family: 'Jost', sans-serif; background: var(--warm-white); color: var(--text-dark); overflow-x: hidden; }

nav {
  position: fixed; top: 0; left: 0; right: 0; z-index: 100;
  background: rgba(253, 240, 241, 0.93); backdrop-filter: blur(12px);
  border-bottom: 1px solid var(--rose-light);
  padding: 0 3rem; height: 72px;
  display: flex; align-items: center; justify-content: space-between;
}
.nav-logo { display: flex; align-items: center; gap: 10px; text-decoration: none; }
.nav-logo img { height: 46px; width: auto; }
.nav-links { display: flex; gap: 2.5rem; list-style: none; }
.nav-links a { text-decoration: none; font-size: 12px; font-weight: 400; letter-spacing: 0.12em; text-transform: uppercase; color: var(--text-mid); transition: color 0.2s; }
.nav-links a:hover { color: var(--rose-deep); }
.nav-cta { background: var(--rose-deep) !important; color: white !important; padding: 10px 22px; border-radius: 40px; }
.nav-cta:hover { background: var(--rose-dark) !important; color: white !important; }

.hero {
  min-height: 100vh; background: var(--rose-pale);
  display: grid; grid-template-columns: 1fr 1fr;
  align-items: center; padding: 100px 5rem 4rem;
  position: relative; overflow: hidden;
}
.hero::before {
  content: ''; position: absolute; top: -100px; right: -80px;
  width: 550px; height: 550px; border-radius: 50%;
  background: var(--rose-light); opacity: 0.35;
}
.hero::after {
  content: ''; position: absolute; bottom: -60px; left: 28%;
  width: 320px; height: 320px; border-radius: 50%;
  background: var(--gold-light); opacity: 0.22;
}
.hero-content { position: relative; z-index: 2; }
.hero-tag {
  display: inline-block; font-size: 11px; letter-spacing: 0.18em;
  text-transform: uppercase; color: var(--rose-deep);
  background: white; border: 1px solid var(--rose-light);
  padding: 7px 18px; border-radius: 30px; margin-bottom: 2rem;
}
.hero h1 {
  font-family: 'Cormorant Garamond', serif; font-size: clamp(3rem, 5vw, 5rem);
  font-weight: 300; line-height: 1.1; color: var(--text-dark); margin-bottom: 1.5rem;
}
.hero h1 em { font-style: italic; color: var(--rose-deep); }
.hero-desc {
  font-size: 16px; font-weight: 300; line-height: 1.85; color: var(--text-mid);
  max-width: 440px; margin-bottom: 2.5rem;
}
.hero-btns { display: flex; gap: 1rem; flex-wrap: wrap; }
.btn-primary {
  display: inline-flex; align-items: center; gap: 8px;
  background: var(--rose-deep); color: white; padding: 14px 28px;
  border-radius: 40px; text-decoration: none; font-size: 13px; font-weight: 500;
  letter-spacing: 0.05em; transition: background 0.2s, transform 0.2s;
}
.btn-primary:hover { background: var(--rose-dark); transform: translateY(-1px); }
.btn-secondary {
  display: inline-flex; align-items: center; gap: 8px; background: transparent;
  color: var(--rose-deep); padding: 14px 28px; border-radius: 40px;
  border: 1.5px solid var(--rose); text-decoration: none; font-size: 13px;
  transition: all 0.2s;
}
.btn-secondary:hover { background: var(--rose-light); }
.hero-visual { position: relative; z-index: 2; display: flex; justify-content: center; }
.hero-logo-display {
  width: 340px; height: 340px; background: white; border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  box-shadow: 0 40px 80px rgba(196,115,124,0.15), 0 8px 24px rgba(196,115,124,0.1);
  animation: float 6s ease-in-out infinite;
}
.hero-logo-display img { width: 260px; height: auto; }
@keyframes float { 0%,100% { transform: translateY(0); } 50% { transform: translateY(-12px); } }
.hero-stats { margin-top: 3rem; display: flex; gap: 2.5rem; }
.stat-num { font-family: 'Cormorant Garamond', serif; font-size: 2.2rem; font-weight: 600; color: var(--rose-deep); display: block; }
.stat-label { font-size: 11px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--text-soft); }

section { padding: 6rem 5rem; }
.section-divider { height: 1px; background: linear-gradient(to right, transparent, var(--rose-light), transparent); margin: 0 5rem; }
.section-header { text-align: center; margin-bottom: 4rem; }
.section-tag { display: inline-block; font-size: 11px; letter-spacing: 0.18em; text-transform: uppercase; color: var(--rose-deep); margin-bottom: 1rem; }
.section-tag::before { content: '— '; }
.section-tag::after { content: ' —'; }
.section-header h2 { font-family: 'Cormorant Garamond', serif; font-size: clamp(2.2rem, 3.5vw, 3.2rem); font-weight: 300; color: var(--text-dark); line-height: 1.2; }
.section-header h2 em { font-style: italic; color: var(--rose-deep); }
.section-header p { font-size: 15px; font-weight: 300; color: var(--text-mid); max-width: 520px; margin: 1rem auto 0; line-height: 1.8; }

.services-bg { background: var(--cream); }
.services-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 2rem; }
.service-card {
  background: white; border-radius: 20px; padding: 2.5rem 2rem;
  border: 1px solid var(--rose-light); transition: transform 0.3s, box-shadow 0.3s;
  position: relative; overflow: hidden;
}
.service-card::before {
  content: ''; position: absolute; top: 0; left: 0; right: 0; height: 3px;
  background: linear-gradient(to right, var(--rose), var(--rose-deep));
  transform: scaleX(0); transform-origin: left; transition: transform 0.4s;
}
.service-card:hover { transform: translateY(-6px); box-shadow: 0 20px 50px rgba(196,115,124,0.12); }
.service-card:hover::before { transform: scaleX(1); }
.service-icon { width: 54px; height: 54px; background: var(--rose-pale); border-radius: 14px; display: flex; align-items: center; justify-content: center; margin-bottom: 1.5rem; font-size: 26px; }
.service-card h3 { font-family: 'Cormorant Garamond', serif; font-size: 1.5rem; font-weight: 400; color: var(--text-dark); margin-bottom: 0.75rem; }
.service-card p { font-size: 14px; font-weight: 300; color: var(--text-mid); line-height: 1.75; margin-bottom: 1.5rem; }
.service-list { list-style: none; display: flex; flex-direction: column; gap: 0.5rem; }
.service-list li { font-size: 13px; color: var(--text-mid); display: flex; align-items: center; gap: 8px; }
.service-list li::before { content: '✦'; color: var(--rose); font-size: 10px; }

.about-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 5rem; align-items: center; }
.about-card-big { background: var(--rose-pale); border-radius: 24px; padding: 3rem; border: 1px solid var(--rose-light); text-align: center; }
.about-card-big img { width: 170px; height: auto; margin-bottom: 1.5rem; }
.about-card-big p { font-family: 'Cormorant Garamond', serif; font-size: 1.55rem; font-style: italic; color: var(--rose-deep); line-height: 1.4; }
.about-visual { position: relative; }
.about-badge {
  position: absolute; bottom: -20px; right: -20px;
  background: var(--rose-deep); color: white; border-radius: 16px;
  padding: 1.2rem 1.5rem; text-align: center;
  box-shadow: 0 8px 24px rgba(196,115,124,0.3);
}
.about-badge strong { font-family: 'Cormorant Garamond', serif; font-size: 2rem; font-weight: 600; display: block; }
.about-badge span { font-size: 11px; letter-spacing: 0.08em; text-transform: uppercase; opacity: 0.85; }
.about-content h2 { font-family: 'Cormorant Garamond', serif; font-size: clamp(2rem, 3vw, 2.8rem); font-weight: 300; line-height: 1.2; color: var(--text-dark); margin-bottom: 1.5rem; }
.about-content h2 em { font-style: italic; color: var(--rose-deep); }
.about-content p { font-size: 15px; font-weight: 300; color: var(--text-mid); line-height: 1.85; margin-bottom: 1.5rem; }
.about-pillars { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; margin-top: 2rem; }
.pillar { background: var(--rose-pale); border-radius: 14px; padding: 1.2rem; border: 1px solid var(--rose-light); }
.pillar-icon { font-size: 22px; margin-bottom: 0.5rem; display: block; }
.pillar h4 { font-size: 14px; font-weight: 500; color: var(--text-dark); margin-bottom: 0.3rem; }
.pillar p { font-size: 12px; color: var(--text-soft); line-height: 1.5; }

.treatments-bg { background: var(--rose-pale); }
.treatments-grid { display: grid; grid-template-columns: repeat(2,1fr); gap: 1.5rem; }
.treatment-card {
  background: white; border-radius: 18px; padding: 2rem;
  border: 1px solid var(--rose-light);
  display: grid; grid-template-columns: auto 1fr; gap: 1.5rem; align-items: start;
  transition: box-shadow 0.3s;
}
.treatment-card:hover { box-shadow: 0 12px 40px rgba(196,115,124,0.1); }
.treatment-num { font-family: 'Cormorant Garamond', serif; font-size: 3rem; font-weight: 300; color: var(--rose-light); line-height: 1; min-width: 48px; text-align: right; }
.treatment-tag { display: inline-block; background: var(--rose-pale); color: var(--rose-deep); font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase; padding: 4px 10px; border-radius: 20px; margin-bottom: 0.5rem; border: 1px solid var(--rose-light); }
.treatment-content h3 { font-family: 'Cormorant Garamond', serif; font-size: 1.3rem; font-weight: 400; color: var(--text-dark); margin-bottom: 0.5rem; }
.treatment-content p { font-size: 13px; font-weight: 300; color: var(--text-mid); line-height: 1.7; }

.nutrition-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 5rem; align-items: center; }
.nutrition-content h2 { font-family: 'Cormorant Garamond', serif; font-size: clamp(2rem, 3vw, 2.8rem); font-weight: 300; line-height: 1.2; color: var(--text-dark); margin-bottom: 1.5rem; }
.nutrition-content h2 em { font-style: italic; color: var(--rose-deep); }
.nutrition-content > p { font-size: 15px; font-weight: 300; color: var(--text-mid); line-height: 1.85; margin-bottom: 2rem; }
.nutrition-items { display: flex; flex-direction: column; gap: 1rem; }
.nutrition-item { display: flex; align-items: center; gap: 1rem; padding: 1rem 1.25rem; background: var(--rose-pale); border-radius: 14px; border: 1px solid var(--rose-light); }
.nutrition-item-icon { width: 40px; height: 40px; background: white; border-radius: 10px; display: flex; align-items: center; justify-content: center; font-size: 20px; flex-shrink: 0; }
.nutrition-item-text h4 { font-size: 14px; font-weight: 500; color: var(--text-dark); }
.nutrition-item-text p { font-size: 12px; color: var(--text-soft); line-height: 1.4; }
.nutrition-visual { background: var(--rose-pale); border-radius: 24px; padding: 2.5rem; border: 1px solid var(--rose-light); text-align: center; }
.nutrition-quote { font-family: 'Cormorant Garamond', serif; font-size: 1.5rem; font-style: italic; color: var(--rose-deep); line-height: 1.5; margin-bottom: 2rem; }
.nutrition-circle { width: 160px; height: 160px; background: white; border-radius: 50%; margin: 0 auto 1.5rem; display: flex; flex-direction: column; align-items: center; justify-content: center; border: 2px solid var(--rose-light); font-family: 'Cormorant Garamond', serif; }
.nutrition-circle strong { font-size: 2.8rem; font-weight: 600; color: var(--rose-deep); line-height: 1; }
.nutrition-circle span { font-size: 12px; color: var(--text-soft); text-align: center; line-height: 1.3; padding: 0 1rem; }
.nutrition-note { font-size: 14px; color: var(--text-soft); font-weight: 300; line-height: 1.7; }

.process-bg { background: var(--cream); }
.process-steps { display: grid; grid-template-columns: repeat(4,1fr); gap: 0; position: relative; }
.process-steps::before { content: ''; position: absolute; top: 28px; left: 12%; right: 12%; height: 1px; background: linear-gradient(to right, var(--rose-light), var(--rose), var(--rose-light)); }
.process-step { text-align: center; padding: 0 1.5rem; }
.process-num { width: 56px; height: 56px; background: var(--cream); border: 2px solid var(--rose); border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 1.5rem; font-family: 'Cormorant Garamond', serif; font-size: 1.4rem; font-weight: 400; color: var(--rose-deep); position: relative; z-index: 1; }
.process-step h3 { font-family: 'Cormorant Garamond', serif; font-size: 1.2rem; font-weight: 400; color: var(--text-dark); margin-bottom: 0.5rem; }
.process-step p { font-size: 13px; color: var(--text-soft); line-height: 1.6; font-weight: 300; }

.contact-bg { background: var(--rose-dark); }
.contact-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 5rem; align-items: center; }
.contact-content h2 { font-family: 'Cormorant Garamond', serif; font-size: clamp(2.2rem, 3.5vw, 3.2rem); font-weight: 300; color: white; line-height: 1.2; margin-bottom: 1.5rem; }
.contact-content h2 em { font-style: italic; color: var(--rose-light); }
.contact-content > p { font-size: 15px; font-weight: 300; color: rgba(255,255,255,0.75); line-height: 1.8; margin-bottom: 2rem; }
.whatsapp-btn { display: inline-flex; align-items: center; gap: 12px; background: #25D366; color: white; padding: 16px 32px; border-radius: 50px; text-decoration: none; font-size: 15px; font-weight: 500; letter-spacing: 0.02em; transition: all 0.2s; box-shadow: 0 8px 24px rgba(37,211,102,0.35); }
.whatsapp-btn:hover { transform: translateY(-2px); box-shadow: 0 12px 32px rgba(37,211,102,0.45); background: #20BC5A; }
.whatsapp-icon { width: 28px; height: 28px; flex-shrink: 0; }
.contact-info-cards { display: flex; flex-direction: column; gap: 1rem; margin-top: 2.5rem; }
.contact-info-card { display: flex; align-items: center; gap: 1rem; background: rgba(255,255,255,0.08); border-radius: 14px; padding: 1rem 1.25rem; border: 1px solid rgba(255,255,255,0.15); }
.contact-info-card-icon { font-size: 22px; width: 44px; height: 44px; background: rgba(255,255,255,0.12); border-radius: 10px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
.contact-info-card h4 { font-size: 12px; font-weight: 500; color: rgba(255,255,255,0.9); letter-spacing: 0.08em; text-transform: uppercase; margin-bottom: 0.2rem; }
.contact-info-card p { font-size: 14px; color: rgba(255,255,255,0.7); }
.contact-form-side { background: white; border-radius: 24px; padding: 2.5rem; }
.contact-form-side h3 { font-family: 'Cormorant Garamond', serif; font-size: 1.8rem; font-weight: 400; color: var(--text-dark); margin-bottom: 1.75rem; }
.form-group { margin-bottom: 1.25rem; }
.form-group label { display: block; font-size: 11px; font-weight: 500; letter-spacing: 0.12em; text-transform: uppercase; color: var(--text-soft); margin-bottom: 0.5rem; }
.form-group input, .form-group select, .form-group textarea { width: 100%; padding: 12px 16px; border: 1.5px solid var(--rose-light); border-radius: 12px; font-family: 'Jost', sans-serif; font-size: 14px; font-weight: 300; color: var(--text-dark); background: var(--warm-white); outline: none; transition: border-color 0.2s; }
.form-group input:focus, .form-group select:focus, .form-group textarea:focus { border-color: var(--rose); background: white; }
.form-group textarea { resize: none; height: 100px; }
.form-submit { width: 100%; padding: 14px; background: var(--rose-deep); color: white; border: none; border-radius: 50px; font-family: 'Jost', sans-serif; font-size: 13px; font-weight: 500; letter-spacing: 0.08em; text-transform: uppercase; cursor: pointer; transition: background 0.2s, transform 0.2s; margin-top: 0.5rem; }
.form-submit:hover { background: var(--rose-dark); transform: translateY(-1px); }

footer { background: var(--text-dark); padding: 3rem 5rem; display: grid; grid-template-columns: auto 1fr auto; align-items: center; gap: 2rem; }
footer img { height: 40px; filter: brightness(0) invert(1) opacity(0.6); }
footer p { font-size: 12px; color: rgba(255,255,255,0.4); text-align: center; line-height: 1.6; }
.footer-links { display: flex; gap: 2rem; list-style: none; }
.footer-links a { font-size: 12px; color: rgba(255,255,255,0.45); text-decoration: none; letter-spacing: 0.08em; text-transform: uppercase; transition: color 0.2s; }
.footer-links a:hover { color: var(--rose-light); }

@keyframes fadeInUp { from { opacity: 0; transform: translateY(28px); } to { opacity: 1; transform: translateY(0); } }
.hero-content > * { opacity: 0; animation: fadeInUp 0.8s ease forwards; }
.hero-tag { animation-delay: 0.1s; }
.hero h1 { animation-delay: 0.25s; }
.hero-desc { animation-delay: 0.4s; }
.hero-btns { animation-delay: 0.55s; }
.hero-stats { animation-delay: 0.7s; }
.hero-visual { opacity: 0; animation: fadeInUp 1s 0.3s ease forwards; }
</style>
</head>
<body>

<nav>
  <a href="#" class="nav-logo">
    <img src="Diseño_sin_título.png" alt="Piñaretes">
  </a>
  <ul class="nav-links">
    <li><a href="#servicios">Servicios</a></li>
    <li><a href="#tratamientos">Tratamientos</a></li>
    <li><a href="#nutricion">Nutrición</a></li>
    <li><a href="#nosotros">Nosotros</a></li>
    <li><a href="#contacto" class="nav-cta">Reservar cita</a></li>
  </ul>
</nav>

<section class="hero">
  <div class="hero-content">
    <span class="hero-tag">✦ Estética Integral · Armenia, Quindío</span>
    <h1>Belleza que<br>nace desde <em>adentro</em></h1>
    <p class="hero-desc">Tratamientos faciales, corporales y asesoría nutricional diseñados para realzar tu bienestar de manera integral y sostenible.</p>
    <div class="hero-btns">
      <a href="#contacto" class="btn-primary">Agendar cita →</a>
      <a href="#servicios" class="btn-secondary">Ver servicios</a>
    </div>
    <div class="hero-stats">
      <div class="stat-item">
        <span class="stat-num">+500</span>
        <span class="stat-label">Clientes felices</span>
      </div>
      <div class="stat-item">
        <span class="stat-num">8+</span>
        <span class="stat-label">Años de experiencia</span>
      </div>
      <div class="stat-item">
        <span class="stat-num">30+</span>
        <span class="stat-label">Tratamientos</span>
      </div>
    </div>
  </div>
  <div class="hero-visual">
    <div class="hero-logo-display">
      <img src="Diseño_sin_título.png" alt="Piñaretes Calidad y Belleza">
    </div>
  </div>
</section>

<section id="servicios" class="services-bg">
  <div class="section-header">
    <span class="section-tag">Nuestros servicios</span>
    <h2>Tres pilares de tu <em>bienestar</em></h2>
    <p>Un enfoque integral que cuida tu rostro, tu cuerpo y tu nutrición para resultados visibles y duraderos.</p>
  </div>
  <div class="services-grid">
    <div class="service-card">
      <div class="service-icon">🌸</div>
      <h3>Tratamientos Faciales</h3>
      <p>Protocolos personalizados para cada tipo de piel, desde hidratación profunda hasta rejuvenecimiento avanzado.</p>
      <ul class="service-list">
        <li>Hidratación y luminosidad</li>
        <li>Limpieza profunda y exfoliación</li>
        <li>Tratamiento de manchas y acné</li>
        <li>Lifting facial sin cirugía</li>
        <li>Microdermoabrasión</li>
        <li>Radiofrecuencia facial</li>
      </ul>
    </div>
    <div class="service-card">
      <div class="service-icon">✨</div>
      <h3>Tratamientos Corporales</h3>
      <p>Rituales y terapias diseñados para moldear, tonificar y revitalizar tu cuerpo de adentro hacia afuera.</p>
      <ul class="service-list">
        <li>Masajes relajantes y terapéuticos</li>
        <li>Reducción de medidas</li>
        <li>Tratamiento anticelulitis</li>
        <li>Envolturas y exfoliaciones</li>
        <li>Drenaje linfático</li>
        <li>Cavitación y radiofrecuencia</li>
      </ul>
    </div>
    <div class="service-card">
      <div class="service-icon">🥗</div>
      <h3>Cuidados Nutricionales</h3>
      <p>Asesoría alimenticia que potencia tus resultados estéticos y mejora tu calidad de vida desde la nutrición.</p>
      <ul class="service-list">
        <li>Planes alimenticios personalizados</li>
        <li>Orientación en suplementación</li>
        <li>Control de peso saludable</li>
        <li>Nutrición anti-inflamatoria</li>
        <li>Hábitos para la belleza interior</li>
        <li>Seguimiento y ajuste mensual</li>
      </ul>
    </div>
  </div>
</section>

<div class="section-divider"></div>

<section id="nosotros">
  <div class="about-grid">
    <div class="about-visual">
      <div class="about-card-big">
        <img src="Diseño_sin_título.png" alt="Piñaretes">
        <p>"La belleza verdadera florece cuando cuidas tu cuerpo, tu mente y tu alma."</p>
      </div>
      <div class="about-badge">
        <strong>100%</strong>
        <span>Bienestar<br>integral</span>
      </div>
    </div>
    <div class="about-content">
      <h2>Somos <em>Piñaretes</em><br>Calidad y Belleza</h2>
      <p>Somos un centro estético integral ubicado en calarca, Quindío, comprometidos con realzar tu belleza natural a través de tratamientos de alta calidad y un enfoque holístico del bienestar.</p>
      <p>Nuestro equipo de especialistas combina técnicas avanzadas con productos de primera línea para ofrecerte resultados visibles, seguros y duraderos.</p>
      <div class="about-pillars">
        <div class="pillar">
          <span class="pillar-icon">💎</span>
          <h4>Calidad Premium</h4>
          <p>Productos y equipos de última generación</p>
        </div>
        <div class="pillar">
          <span class="pillar-icon">🌿</span>
          <h4>Enfoque Natural</h4>
          <p>Tratamientos en armonía con tu cuerpo</p>
        </div>
        <div class="pillar">
          <span class="pillar-icon">🤝</span>
          <h4>Atención Personalizada</h4>
          <p>Cada plan diseñado para ti</p>
        </div>
        <div class="pillar">
          <span class="pillar-icon">✅</span>
          <h4>Resultados Reales</h4>
          <p>Seguimiento continuo de tu progreso</p>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="tratamientos" class="treatments-bg">
  <div class="section-header">
    <span class="section-tag">Tratamientos destacados</span>
    <h2>Protocolos que <em>transforman</em></h2>
    <p>Cada tratamiento es una experiencia diseñada específicamente para tus necesidades y objetivos estéticos.</p>
  </div>
  <div class="treatments-grid">
    <div class="treatment-card">
      <span class="treatment-num">01</span>
      <div class="treatment-content">
        <span class="treatment-tag">Facial</span>
        <h3>Limpieza Facial Profunda</h3>
        <p>Ritual completo que elimina impurezas, puntos negros y células muertas, dejando tu piel radiante y purificada.</p>
      </div>
    </div>
    <div class="treatment-card">
      <span class="treatment-num">02</span>
      <div class="treatment-content">
        <span class="treatment-tag">Facial</span>
        <h3>Rejuvenecimiento con Radiofrecuencia</h3>
        <p>Estimula la producción de colágeno y elastina para recuperar firmeza y reducir líneas de expresión de forma no invasiva.</p>
      </div>
    </div>
    <div class="treatment-card">
      <span class="treatment-num">03</span>
      <div class="treatment-content">
        <span class="treatment-tag">Corporal</span>
        <h3>Cavitación y Moldeo Corporal</h3>
        <p>Tecnología de ultrasonido que actúa sobre la grasa localizada para reducir medidas de forma segura y efectiva.</p>
      </div>
    </div>
    <div class="treatment-card">
      <span class="treatment-num">04</span>
      <div class="treatment-content">
        <span class="treatment-tag">Corporal</span>
        <h3>Drenaje Linfático Manual</h3>
        <p>Masaje especializado que activa el sistema linfático, reduce retención de líquidos y mejora la circulación corporal.</p>
      </div>
    </div>
    <div class="treatment-card">
      <span class="treatment-num">05</span>
      <div class="treatment-content">
        <span class="treatment-tag">Facial</span>
        <h3>Tratamiento Despigmentante</h3>
        <p>Protocolo activo para reducir manchas, unificar el tono de la piel y devolverte una tez clara y homogénea.</p>
      </div>
    </div>
    <div class="treatment-card">
      <span class="treatment-num">06</span>
      <div class="treatment-content">
        <span class="treatment-tag">Corporal</span>
        <h3>Envoltura Reductora</h3>
        <p>Técnica con activos termogénicos y reductores para perder medidas y tonificar la piel de manera progresiva.</p>
      </div>
    </div>
  </div>
</section>

<section id="nutricion">
  <div class="nutrition-grid">
    <div class="nutrition-content">
      <h2>Belleza que <em>comienza</em><br>en tu alimentación</h2>
      <p>La nutrición es el fundamento invisible de toda belleza real. En Piñaretes integramos la asesoría alimenticia como parte esencial de cada plan estético, porque los mejores resultados se logran cuando cuidas tu cuerpo por dentro y por fuera.</p>
      <div class="nutrition-items">
        <div class="nutrition-item">
          <div class="nutrition-item-icon">🥗</div>
          <div class="nutrition-item-text">
            <h4>Plan alimenticio personalizado</h4>
            <p>Diseñado según tus objetivos, estilo de vida y condición física.</p>
          </div>
        </div>
        <div class="nutrition-item">
          <div class="nutrition-item-icon">💊</div>
          <div class="nutrition-item-text">
            <h4>Orientación en suplementación</h4>
            <p>Colágeno, vitaminas y antioxidantes para potenciar tus tratamientos.</p>
          </div>
        </div>
        <div class="nutrition-item">
          <div class="nutrition-item-icon">📊</div>
          <div class="nutrition-item-text">
            <h4>Seguimiento mensual</h4>
            <p>Control de avance y ajuste del plan según tus resultados.</p>
          </div>
        </div>
        <div class="nutrition-item">
          <div class="nutrition-item-icon">🌟</div>
          <div class="nutrition-item-text">
            <h4>Hábitos para la belleza interior</h4>
            <p>Tips de hidratación, sueño y bienestar que complementan tus cuidados.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="nutrition-visual">
      <p class="nutrition-quote">"Lo que comes se refleja en tu piel, tu cabello y tu energía."</p>
      <div class="nutrition-circle">
        <strong>360°</strong>
        <span>Cuidado<br>integral</span>
      </div>
      <p class="nutrition-note">Combinamos estética avanzada con nutrición consciente para un bienestar completo y sostenible en el tiempo.</p>
    </div>
  </div>
</section>

<section class="process-bg">
  <div class="section-header">
    <span class="section-tag">¿Cómo funciona?</span>
    <h2>Tu camino hacia la <em>transformación</em></h2>
  </div>
  <div class="process-steps">
    <div class="process-step">
      <div class="process-num">1</div>
      <h3>Consulta inicial</h3>
      <p>Evaluamos tu piel, cuerpo y objetivos para diseñar el plan ideal para ti.</p>
    </div>
    <div class="process-step">
      <div class="process-num">2</div>
      <h3>Plan personalizado</h3>
      <p>Creamos un protocolo de tratamientos y guía nutricional a tu medida.</p>
    </div>
    <div class="process-step">
      <div class="process-num">3</div>
      <h3>Tratamientos</h3>
      <p>Sesiones guiadas con seguimiento constante de tu evolución.</p>
    </div>
    <div class="process-step">
      <div class="process-num">4</div>
      <h3>Resultados reales</h3>
      <p>Belleza visible, duradera y en armonía con tu bienestar general.</p>
    </div>
  </div>
</section>

<section id="contacto" class="contact-bg">
  <div class="contact-grid">
    <div class="contact-content">
      <h2>Comienza tu <em>transformación</em> hoy</h2>
      <p>Estamos aquí para acompañarte en cada paso de tu camino hacia una versión más radiante de ti. Contáctanos y agendamos tu cita.</p>
      <a href="https://wa.me/573233549880?text=Hola%20Piñaretes%2C%20me%20gustaría%20agendar%20una%20cita%20para%20un%20tratamiento." class="whatsapp-btn" target="_blank">
        <svg class="whatsapp-icon" viewBox="0 0 24 24" fill="currentColor">
          <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413Z"/>
        </svg>
        Escríbenos por WhatsApp
      </a>
      <div class="contact-info-cards">
        <div class="contact-info-card">
          <div class="contact-info-card-icon">📍</div>
          <div>
            <h4>Ubicación</h4>
            <p> Calarca, Quindío, Colombia - Barrio gaitan Mz Z etapa V casa #2</p>
          </div>
        </div>
        <div class="contact-info-card">
          <div class="contact-info-card-icon">📱</div>
          <div>
            <h4>WhatsApp</h4>
            <p>+57 323 354 9880</p>
          </div>
        </div>
        <div class="contact-info-card">
          <div class="contact-info-card-icon">🕐</div>
          <div>
            <h4>Horario de atención</h4>
            <p>Lun – Sáb: 8:00 am – 6:00 pm</p>
          </div>
        </div>
      </div>
    </div>
    <div class="contact-form-side">
      <h3>Agenda tu consulta</h3>
      <div class="form-group">
        <label>Nombre completo</label>
        <input type="text" id="f-name" placeholder="Tu nombre">
      </div>
      <div class="form-group">
        <label>Número de WhatsApp</label>
        <input type="tel" id="f-phone" placeholder="+57 000 000 0000">
      </div>
      <div class="form-group">
        <label>Servicio de interés</label>
        <select id="f-service">
          <option value="">Selecciona un servicio</option>
          <option>Tratamiento facial</option>
          <option>Tratamiento corporal</option>
          <option>Asesoría nutricional</option>
          <option>Plan integral completo</option>
        </select>
      </div>
      <div class="form-group">
        <label>Mensaje (opcional)</label>
        <textarea id="f-msg" placeholder="Cuéntanos sobre tus objetivos o preguntas..."></textarea>
      </div>
      <button class="form-submit" onclick="sendWhatsApp()">Enviar por WhatsApp ✦</button>
    </div>
  </div>
</section>

<footer>
  <img src="Diseño_sin_título.png" alt="Piñaretes">
  <p>© 2025 Piñaretes · Calidad y Belleza<br>Armenia, Quindío, Colombia</p>
  <ul class="footer-links">
    <li><a href="#servicios">Servicios</a></li>
    <li><a href="#nosotros">Nosotros</a></li>
    <li><a href="#contacto">Contacto</a></li>
  </ul>
</footer>

<script>
function sendWhatsApp() {
  var name = document.getElementById('f-name').value;
  var service = document.getElementById('f-service').value;
  var msg = document.getElementById('f-msg').value;
  var text = 'Hola Piñaretes 🌸, me gustaría agendar una consulta.';
  if (name) text += '\n\nMi nombre es: ' + name;
  if (service) text += '\nServicio de interés: ' + service;
  if (msg) text += '\nMensaje: ' + msg;
  window.open('https://wa.me/573233549880?text=' + encodeURIComponent(text), '_blank');
}
</script>
</body>
</html>
