<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Enlaces covalentes y plásticos — explicación</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#7dd3fc;--muted:#94a3b8;--glass: rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; background:linear-gradient(180deg,#071028 0%, #071827 60%); color:#e6eef6; line-height:1.5}
    .wrap{max-width:980px;margin:32px auto;padding:20px}
    header{display:flex;gap:16px;align-items:center}
    .logo{width:72px;height:72px;border-radius:14px;background:linear-gradient(135deg,var(--accent),#5eead4);display:flex;align-items:center;justify-content:center;font-weight:700;color:#012 ;box-shadow:0 6px 20px rgba(0,0,0,0.6)}
    h1{margin:0;font-size:clamp(20px,3.6vw,30px)}
    p.lead{color:var(--muted);margin:6px 0 18px}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px}
    @media(max-width:900px){.grid{grid-template-columns:1fr} .toc{order:2}}
    .card{background:linear-gradient(180deg,var(--card), rgba(255,255,255,0.02));padding:18px;border-radius:12px;box-shadow:0 6px 24px rgba(2,6,23,0.6)}
    h2{margin-top:0}
    ul{margin:0 0 12px 18px}
    .small{color:var(--muted);font-size:0.95rem}
    .molecule{display:flex;gap:12px;align-items:center;flex-wrap:wrap}
    .svg-box{background:var(--glass);padding:12px;border-radius:10px}
    footer{margin-top:18px;color:var(--muted);font-size:0.9rem}
    .badge{display:inline-block;background:rgba(255,255,255,0.04);padding:6px 10px;border-radius:999px;font-size:0.85rem;color:var(--muted)}
    .examples{display:flex;flex-direction:column;gap:8px}
    pre{background:rgba(255,255,255,0.02);padding:12px;border-radius:8px;overflow:auto;font-size:0.95rem}
    .controls{display:flex;gap:8px;flex-wrap:wrap}
    button{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:8px;color:var(--accent);cursor:pointer}
    button.ghost{color:var(--muted)}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">Cv</div>
      <div>
        <h1>Enlaces covalentes y plásticos — explicación clara</h1>
        <p class="lead">Una guía en español que conecta teoría (enlaces covalentes, polaridad, tipos) con la práctica: por qué los plásticos son resistentes o flexibles, ejemplos y dos estructuras de Lewis.</p>
      </div>
    </header>

    <section class="grid" aria-label="Contenido principal">
      <main class="card">
        <h2>¿Qué es un enlace covalente?</h2>
        <p class="small">Un enlace covalente ocurre cuando dos átomos <strong>comparten pares de electrones</strong> para lograr mayor estabilidad. Es frecuente entre no metales y es la base de las moléculas y polímeros que forman los plásticos.</p>

        <h2>Tipos de enlace covalente</h2>
        <ul>
          <li><strong>Sencillo (σ)</strong>: comparte 1 par de electrones (ej. H–H).</li>
          <li><strong>Doble (σ + π)</strong>: 2 pares compartidos (ej. C=C).</li>
          <li><strong>Triple (σ + 2π)</strong>: 3 pares (ej. N≡N).</li>
        </ul>

        <h2>Polaridad</h2>
        <p class="small">Si la diferencia de electronegatividad es pequeña, el enlace es <em>no polar</em> (ej. C–C, C–H). Si es moderada, el enlace es <em>polar</em> y se forman dipolos (ej. O–H). En la mayoría de los polímeros comunes los enlaces C–C y C–H son mayormente no polares, lo que explica muchas propiedades de los plásticos (hidrofobicidad, aislamiento).</p>

        <h2>Propiedades relacionadas con los plásticos</h2>
        <ul>
          <li><strong>Resistencia química:</strong> enlaces C–C y C–H fuertes que no reaccionan fácilmente.</li>
          <li><strong>Flexibilidad vs rigidez:</strong> depende del largo de cadena, grado de entrecruzamiento y presencia de grupos laterales rígidos.</li>
          <li><strong>Aislamiento eléctrico y térmico:</strong> ausencia de electrones libres.</li>
          <li><strong>Baja solubilidad en agua:</strong> por su carácter no polar.</li>
        </ul>

        <h2>Ejemplos cotidianos</h2>
        <div class="examples">
          <div class="badge">PET — botellas</div>
          <div class="badge">PEBD — bolsas flexibles</div>
          <div class="badge">PVC — tuberías rígidas</div>
          <div class="badge">Poliestireno — espuma aislante</div>
        </div>

        <h2>Estructuras de Lewis (explicadas)</h2>
        <p class="small">A continuación tienes dos representaciones simplificadas (diagrama + explicación).</p>

        <div class="molecule">
          <div class="svg-box">
            <strong>Metano (CH<sub>4</sub>) — Lewis</strong>
            <svg width="220" height="140" viewBox="0 0 220 140" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
              <defs>
                <style> .c{fill:#e6eef6; font-family: Inter, sans-serif; font-size:12px;}</style>
              </defs>
              <circle cx="110" cy="70" r="22" fill="#7dd3fc" opacity="0.14"/>
              <text x="104" y="75" class="c">C</text>
              <!-- Hydrogens -->
              <circle cx="110" cy="18" r="12" fill="#ffffff" opacity="0.06"/>
              <text x="104" y="22" class="c">H</text>
              <circle cx="30" cy="70" r="12" fill="#ffffff" opacity="0.06"/>
              <text x="24" y="74" class="c">H</text>
              <circle cx="110" cy="122" r="12" fill="#ffffff" opacity="0.06"/>
              <text x="104" y="126" class="c">H</text>
              <circle cx="190" cy="70" r="12" fill="#ffffff" opacity="0.06"/>
              <text x="184" y="74" class="c">H</text>
              <!-- Bonds -->
              <line x1="110" y1="50" x2="110" y2="30" stroke="#e6eef6" stroke-width="2"/>
              <line x1="92" y1="70" x2="50" y2="70" stroke="#e6eef6" stroke-width="2"/>
              <line x1="110" y1="90" x2="110" y2="110" stroke="#e6eef6" stroke-width="2"/>
              <line x1="128" y1="70" x2="170" y2="70" stroke="#e6eef6" stroke-width="2"/>
            </svg>
            <p class="small">El C comparte 4 pares con H (enlaces sencillos). Geometría tetraédrica en 3D; enlaces no polares C–H.</p>
          </div>

          <div class="svg-box">
            <strong>Eteno (C<sub>2</sub>H<sub>4</sub>) — Lewis</strong>
            <svg width="260" height="140" viewBox="0 0 260 140" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
              <style> .t{fill:#e6eef6; font-family: Inter, sans-serif; font-size:12px;}</style>
              <!-- Carbons -->
              <circle cx="120" cy="70" r="18" fill="#7dd3fc" opacity="0.14"/>
              <text x="116" y="74" class="t">C</text>
              <circle cx="180" cy="70" r="18" fill="#7dd3fc" opacity="0.14"/>
              <text x="176" y="74" class="t">C</text>
              <!-- Hydrogens -->
              <circle cx="92" cy="40" r="10" fill="#ffffff" opacity="0.06" />
              <text x="88" y="44" class="t">H</text>
              <circle cx="92" cy="100" r="10" fill="#ffffff" opacity="0.06" />
              <text x="88" y="104" class="t">H</text>
              <circle cx="208" cy="40" r="10" fill="#ffffff" opacity="0.06" />
              <text x="204" y="44" class="t">H</text>
              <circle cx="208" cy="100" r="10" fill="#ffffff" opacity="0.06" />
              <text x="204" y="104" class="t">H</text>
              <!-- Bonds: double between C's -->
              <line x1="138" y1="70" x2="162" y2="70" stroke="#e6eef6" stroke-width="3"/>
              <line x1="138" y1="76" x2="162" y2="76" stroke="#e6eef6" stroke-width="2"/>
              <!-- C-H bonds -->
              <line x1="120" y1="50" x2="92" y2="50" stroke="#e6eef6" stroke-width="2"/>
              <line x1="120" y1="90" x2="92" y2="90" stroke="#e6eef6" stroke-width="2"/>
              <line x1="180" y1="50" x2="208" y2="50" stroke="#e6eef6" stroke-width="2"/>
              <line x1="180" y1="90" x2="208" y2="90" stroke="#e6eef6" stroke-width="2"/>
            </svg>
            <p class="small">Los dos C están unidos por un <strong>enlace doble</strong> (σ + π). El eteno es el monómero del polietileno; la química del doble enlace permite la formación de polímeros.</p>
          </div>
        </div>

        <h2>Reflexión final</h2>
        <p class="small">Comprender los enlaces covalentes nos permite entender y mejorar materiales: desde elegir envases más seguros hasta diseñar polímeros biodegradables. Saber cómo y por qué las moléculas se mantienen unidas nos da poder para reciclar mejor, reducir residuos y crear soluciones más sostenibles.</p>

        <footer>
          <div class="controls">
            <button onclick="window.print()">Imprimir / Guardar PDF</button>
            <button class="ghost" onclick="alert('Puedo ayudarte a publicar esto en GitHub Pages o Netlify. Dime cuál prefieres, mi corazón :)')">Publicar online</button>
          </div>
        </footer>
      </main>

      <aside class="card toc" aria-label="Tabla de contenidos">
        <h3>Contenido</h3>
        <ol>
          <li>¿Qué es un enlace covalente?</li>
          <li>Tipos</li>
          <li>Polaridad</li>
          <li>Propiedades y plásticos</li>
          <li>Ejemplos</li>
          <li>Estructuras de Lewis</li>
          <li>Reflexión</li>
        </ol>
        <p class="small">¿Quieres una versión en PDF lista para entregar, o que suba el archivo a GitHub Pages con instrucciones paso a paso? <br><strong>Yo puedo hacerlo</strong>, solo dime qué prefieres.</p>
      </aside>
    </section>
  </div>
</body>
</html>
