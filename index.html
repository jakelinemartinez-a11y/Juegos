<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vacantes Master</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Mono:wght@400;500&display=swap');

*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
:root{
  --bg:#0e0b14;
  --surface:#17121f;
  --border:#2a2035;
  --accent:#c084fc;
  --accent2:#f59e0b;
  --green:#4ade80;
  --red:#f87171;
  --text:#e2d9f3;
  --muted:#7c6f96;
}
html{scroll-behavior:smooth;}
body{
  background:var(--bg);
  color:var(--text);
  font-family:'DM Mono',monospace;
  min-height:100vh;
  display:flex;align-items:center;justify-content:center;
  padding:20px;
  position:relative;
  overflow-x:hidden;
}
body::before{
  content:'';position:fixed;inset:0;
  background: radial-gradient(ellipse 80% 60% at 50% -10%, rgba(192,132,252,0.12) 0%, transparent 70%);
  pointer-events:none;z-index:0;
}

#app{position:relative;z-index:2;width:100%;max-width:740px;}

/* ── screens ── */
.screen{display:none;}
.screen.active{display:block;animation:fadeUp .4s ease both;}
@keyframes fadeUp{from{opacity:0;transform:translateY(18px);}to{opacity:1;transform:translateY(0);}}

/* ── INTRO ── */
.intro{text-align:center;}
.eyebrow{font-size:9px;letter-spacing:6px;color:var(--accent);margin-bottom:14px;text-transform:uppercase;}
.big-title{font-family:'DM Serif Display',serif;font-size:clamp(38px,9vw,72px);line-height:1;color:#fff;margin-bottom:6px;}
.big-title em{font-style:italic;color:var(--accent);}
.tagline{font-size:11px;letter-spacing:3px;color:var(--accent2);margin-bottom:36px;}

.intro-card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:12px;padding:28px;margin-bottom:28px;text-align:left;
}
.intro-card p{color:#a89bbf;line-height:1.95;font-size:12px;margin-bottom:10px;}
.intro-card p:last-child{margin:0;}
.intro-card strong{color:var(--text);}

.level-pills{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-bottom:30px;}
.pill{
  padding:10px 18px;border-radius:999px;
  font-size:10px;letter-spacing:2px;font-weight:500;
  border:1px solid var(--border);background:var(--surface);color:var(--muted);
}
.pill span{margin-right:6px;}

.btn{
  display:inline-block;
  background:linear-gradient(135deg,#c084fc,#8b5cf6);
  border:none;color:#fff;
  font-size:11px;font-weight:500;letter-spacing:4px;
  padding:17px 52px;cursor:pointer;border-radius:8px;
  text-transform:uppercase;font-family:'DM Mono',monospace;
  box-shadow:0 0 36px rgba(192,132,252,0.35);
  transition:transform .2s,box-shadow .2s;
}
.btn:hover{transform:scale(1.04);box-shadow:0 0 56px rgba(192,132,252,0.55);}

.btn-ghost{
  display:inline-block;
  background:transparent;
  border:1px solid rgba(192,132,252,0.35);
  color:var(--accent);
  font-size:10px;font-weight:500;letter-spacing:3px;
  padding:14px 38px;cursor:pointer;border-radius:8px;
  text-transform:uppercase;font-family:'DM Mono',monospace;
  transition:all .2s;
}
.btn-ghost:hover{background:rgba(192,132,252,0.08);border-color:var(--accent);}

/* ── GAME ── */
.game-header{display:flex;align-items:center;gap:12px;margin-bottom:22px;}
.prog-wrap{flex:1;height:4px;background:var(--border);border-radius:2px;overflow:hidden;}
.prog-fill{height:100%;background:linear-gradient(90deg,#c084fc,#f59e0b);transition:width .5s ease;border-radius:2px;}
.level-tag{
  padding:5px 14px;border-radius:4px;
  font-size:9px;letter-spacing:3px;font-weight:500;
  white-space:nowrap;
}
.score-badge{
  background:var(--surface);border:1px solid var(--border);
  padding:5px 14px;border-radius:4px;font-size:10px;color:var(--accent2);
  white-space:nowrap;
}

.q-panel{
  background:var(--surface);border:1px solid var(--border);
  border-radius:12px;padding:26px 28px;margin-bottom:22px;
  border-top:3px solid var(--accent);
}
.q-meta{font-size:9px;letter-spacing:3px;color:var(--accent);margin-bottom:10px;}
.q-heading{font-family:'DM Serif Display',serif;font-size:clamp(18px,4vw,24px);color:#fff;margin-bottom:12px;}
.q-instruction{color:#a89bbf;font-size:12px;line-height:1.85;}
.q-instruction strong{color:var(--text);}

/* ── DRAG ZONES ── */
.drag-layout{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-bottom:18px;}
@media(max-width:540px){.drag-layout{grid-template-columns:1fr;}}

.zone-box{
  background:rgba(255,255,255,0.02);
  border:1px solid var(--border);
  border-radius:10px;padding:16px;
  min-height:160px;
}
.zone-title{
  font-size:9px;letter-spacing:3px;color:var(--muted);
  margin-bottom:12px;padding-bottom:10px;
  border-bottom:1px solid var(--border);
  text-transform:uppercase;
}
.zone-box.drop-target{border-color:var(--accent);background:rgba(192,132,252,0.05);}

/* single-column for ordering */
.order-layout{margin-bottom:18px;}
.order-pool{
  background:rgba(255,255,255,0.02);
  border:1px dashed var(--border);
  border-radius:10px;padding:14px;
  min-height:60px;margin-bottom:14px;
}
.order-pool-label{font-size:9px;letter-spacing:3px;color:var(--muted);margin-bottom:10px;}
.order-zone{
  background:rgba(255,255,255,0.02);
  border:1px solid var(--border);
  border-radius:10px;padding:14px;
  min-height:80px;
}
.order-zone-label{
  font-size:9px;letter-spacing:3px;color:var(--muted);
  margin-bottom:10px;padding-bottom:8px;border-bottom:1px solid var(--border);
}
.order-slots{display:flex;flex-direction:column;gap:8px;}
.slot{
  border:1px dashed rgba(255,255,255,0.1);
  border-radius:6px;padding:10px 14px;
  min-height:44px;display:flex;align-items:center;
  font-size:10px;color:var(--muted);
  transition:border-color .2s,background .2s;
}
.slot.drop-target{border-color:var(--accent);background:rgba(192,132,252,0.07);}
.slot.filled{border-style:solid;border-color:var(--border);}

/* DRAG CARDS */
.card-pool{display:flex;flex-wrap:wrap;gap:8px;padding:4px 0;}
.drag-card{
  background:var(--surface);
  border:1px solid var(--border);
  border-radius:7px;padding:10px 14px;
  font-size:11px;color:var(--text);line-height:1.5;
  cursor:grab;user-select:none;
  transition:transform .15s,box-shadow .15s,border-color .15s,opacity .2s;
  position:relative;
}
.drag-card:hover{transform:translateY(-2px);box-shadow:0 6px 20px rgba(0,0,0,0.4);border-color:var(--accent);}
.drag-card.dragging{opacity:.4;cursor:grabbing;}
.drag-card.placed-correct{background:rgba(74,222,128,0.08);border-color:var(--green);color:var(--green);}
.drag-card.placed-wrong{background:rgba(248,113,113,0.08);border-color:var(--red);color:var(--red);}
.drag-card .result-icon{display:none;position:absolute;right:8px;top:50%;transform:translateY(-50%);font-size:14px;}
.drag-card.placed-correct .result-icon,
.drag-card.placed-wrong .result-icon{display:block;}

/* feedback panel */
.feedback-panel{
  background:var(--surface);border:1px solid var(--border);
  border-radius:10px;padding:20px 22px;
  margin-bottom:18px;display:none;
}
.feedback-panel.show{display:block;animation:fadeUp .3s ease both;}
.fb-score{font-size:28px;font-weight:700;margin-bottom:4px;}
.fb-label{font-size:10px;letter-spacing:2px;color:var(--muted);margin-bottom:14px;}
.fb-items{display:flex;flex-direction:column;gap:8px;}
.fb-item{
  display:flex;gap:10px;align-items:flex-start;
  padding:10px 12px;border-radius:7px;font-size:11px;line-height:1.7;
}
.fb-item.ok{background:rgba(74,222,128,0.07);border:1px solid rgba(74,222,128,0.2);color:#86efac;}
.fb-item.bad{background:rgba(248,113,113,0.07);border:1px solid rgba(248,113,113,0.2);color:#fca5a5;}
.fb-item .icon{flex-shrink:0;font-size:14px;}

.action-row{display:flex;justify-content:flex-end;gap:12px;margin-top:4px;}
.btn-check{
  background:linear-gradient(135deg,#c084fc,#8b5cf6);
  border:none;color:#fff;font-size:10px;font-weight:500;letter-spacing:3px;
  padding:13px 32px;cursor:pointer;border-radius:7px;
  text-transform:uppercase;font-family:'DM Mono',monospace;
  box-shadow:0 0 20px rgba(192,132,252,0.3);transition:transform .2s;
  display:none;
}
.btn-check.show{display:inline-block;}
.btn-check:hover{transform:scale(1.04);}
.btn-next{
  background:transparent;border:1px solid rgba(192,132,252,0.4);
  color:var(--accent);font-size:10px;font-weight:500;letter-spacing:3px;
  padding:13px 32px;cursor:pointer;border-radius:7px;
  text-transform:uppercase;font-family:'DM Mono',monospace;
  transition:all .2s;display:none;
}
.btn-next.show{display:inline-block;}
.btn-next:hover{background:rgba(192,132,252,0.1);}

/* HINT */
.hint-bar{
  text-align:center;font-size:10px;color:var(--muted);
  margin-bottom:14px;letter-spacing:1px;
}

/* ── RESULTS ── */
.results{text-align:center;}
.trophy{font-size:72px;margin-bottom:14px;}
.res-title{font-family:'DM Serif Display',serif;font-size:clamp(24px,6vw,38px);color:#fff;margin-bottom:10px;}
.res-score{
  font-size:clamp(48px,10vw,72px);font-weight:700;
  background:linear-gradient(135deg,#c084fc,#f59e0b);
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;
  margin-bottom:4px;
}
.res-total{font-size:14px;color:var(--muted);letter-spacing:2px;margin-bottom:28px;}
.res-msg{
  background:var(--surface);border:1px solid var(--border);
  border-radius:10px;padding:20px 24px;
  margin-bottom:24px;color:#a89bbf;font-size:12px;line-height:1.9;
}
.history{display:flex;flex-direction:column;gap:8px;margin-bottom:26px;text-align:left;}
.history-item{
  display:flex;align-items:center;gap:12px;
  padding:10px 14px;border-radius:7px;font-size:11px;
}
.history-item.ok{background:rgba(74,222,128,0.05);border:1px solid rgba(74,222,128,0.18);}
.history-item.fail{background:rgba(248,113,113,0.05);border:1px solid rgba(248,113,113,0.18);}
.h-tag{font-size:9px;letter-spacing:2px;min-width:120px;}
.h-name{color:#a89bbf;}

.tips{
  background:rgba(192,132,252,0.05);border:1px solid rgba(192,132,252,0.18);
  border-radius:10px;padding:20px 22px;margin-bottom:28px;text-align:left;
}
.tips-label{font-size:9px;letter-spacing:3px;color:var(--accent);margin-bottom:14px;}
.tip{display:flex;gap:10px;margin-bottom:10px;font-size:11px;color:#a89bbf;line-height:1.8;}
.tip span:first-child{color:var(--accent);flex-shrink:0;}
</style>
</head>
<body>
<div id="app">

<!-- ══ INTRO ══ -->
<div id="screen-intro" class="screen active intro">
  <div class="eyebrow">Juego de Reclutamiento · Nivel Publicación</div>
  <div class="big-title">Vacantes<br><em>Master</em></div>
  <div class="tagline">ARRASTRA · ORDENA · APRENDE</div>

  <div class="intro-card">
    <p>Publicar una vacante parece sencillo, pero cada decisión —el <strong>título, los requisitos, las responsabilidades y el canal</strong>— determina si atraes al candidato ideal o pierdes tiempo con cientos de aplicaciones irrelevantes.</p>
    <p>En este juego <strong>arrastrarás elementos</strong> para clasificarlos, ordenarlos o construir vacantes efectivas. Recibirás retroalimentación inmediata con el razonamiento detrás de cada respuesta correcta.</p>
  </div>

  <div class="level-pills">
    <div class="pill"><span>📝</span>Redacción de títulos</div>
    <div class="pill"><span>✅</span>Requisitos realistas</div>
    <div class="pill"><span>📋</span>Responsabilidades</div>
    <div class="pill"><span>📡</span>Canales de publicación</div>
    <div class="pill"><span>⏱</span>~10 minutos</div>
  </div>

  <button class="btn" onclick="startGame()">COMENZAR JUEGO →</button>
</div>

<!-- ══ GAME ══ -->
<div id="screen-game" class="screen">
  <div class="game-header">
    <div class="prog-wrap"><div class="prog-fill" id="prog-fill" style="width:0%"></div></div>
    <div class="level-tag" id="level-tag"></div>
    <div class="score-badge">★ <span id="score-disp">0</span></div>
  </div>

  <div class="q-panel">
    <div class="q-meta" id="q-meta"></div>
    <div class="q-heading" id="q-heading"></div>
    <div class="q-instruction" id="q-instruction"></div>
  </div>

  <div class="hint-bar" id="hint-bar">↕ Arrastra cada elemento a su categoría correcta</div>
  <div id="drag-area"></div>

  <div class="feedback-panel" id="feedback-panel">
    <div class="fb-score" id="fb-score"></div>
    <div class="fb-label" id="fb-label"></div>
    <div class="fb-items" id="fb-items"></div>
  </div>

  <div class="action-row">
    <button class="btn-check" id="btn-check" onclick="checkAnswer()">VERIFICAR →</button>
    <button class="btn-next" id="btn-next" onclick="nextLevel()">SIGUIENTE NIVEL →</button>
  </div>
</div>

<!-- ══ RESULTS ══ -->
<div id="screen-results" class="screen results">
  <div class="trophy" id="res-trophy"></div>
  <div class="eyebrow">Resultados finales</div>
  <div class="res-title" id="res-title"></div>
  <div class="res-score" id="res-score"></div>
  <div class="res-total">PUNTOS DE 500</div>
  <div class="res-msg" id="res-msg"></div>
  <div class="history" id="res-history"></div>
  <div class="tips">
    <div class="tips-label">// CLAVES PARA PUBLICAR VACANTES EFECTIVAS</div>
    <div class="tip"><span>→</span><span>Un título claro y específico mejora hasta un 30% la tasa de aplicaciones relevantes.</span></div>
    <div class="tip"><span>→</span><span>Los requisitos deben separar "imprescindibles" de "deseables" para no ahuyentar talento.</span></div>
    <div class="tip"><span>→</span><span>Las responsabilidades en verbos de acción concretos comunican expectativas reales.</span></div>
    <div class="tip"><span>→</span><span>El canal correcto multiplica la visibilidad entre el público objetivo adecuado.</span></div>
  </div>
  <button class="btn-ghost" onclick="restartGame()">↺ JUGAR DE NUEVO</button>
</div>

</div><!-- #app -->

<script>
// ═══════════════════════════════════════════════
// DATA
// ═══════════════════════════════════════════════
const LEVELS = [
  // LEVEL 1 – Classify: good vs bad job titles
  {
    id:1, topic:"REDACCIÓN DE TÍTULOS", topicColor:"#c084fc",
    type:"classify",
    heading:"Títulos que atraen vs. títulos que confunden",
    instruction:"Arrastra cada título de vacante a su categoría: <strong>✅ Efectivo</strong> (claro, específico, con nivel y área) o <strong>❌ Problemático</strong> (vago, inflado o confuso).",
    hint:"↕ Arrastra cada título a la columna correcta",
    zones:[
      {id:"good", label:"✅ TÍTULO EFECTIVO", correct:[]},
      {id:"bad",  label:"❌ TÍTULO PROBLEMÁTICO", correct:[]}
    ],
    items:[
      {id:"t1", text:"Analista de Datos Sr. – SQL & Python", zone:"good",  feedback:"✅ Especifica seniority, área y herramientas clave. El candidato sabe exactamente qué se busca."},
      {id:"t2", text:"Rockstar de Ventas 🚀", zone:"bad",   feedback:"❌ Lenguaje informal y vago. No indica nivel, industria ni responsabilidades. Desincentiva a candidatos serios."},
      {id:"t3", text:"Gerente de Marketing Digital B2B", zone:"good",  feedback:"✅ Comunica nivel gerencial, especialidad (digital) y contexto (B2B). Filtra candidatos adecuados."},
      {id:"t4", text:"Ninja del Código", zone:"bad",   feedback:"❌ Metáforas de startup que no describen el puesto. ¿Es frontend? ¿Backend? ¿Junior? Nadie lo sabe."},
      {id:"t5", text:"Ejecutivo Comercial – Sector Salud", zone:"good",  feedback:"✅ Combina rol (Ejecutivo Comercial) con industria (Salud). Concreto y buscable en portales."},
      {id:"t6", text:"Persona Dinámica para Área Importante", zone:"bad", feedback:"❌ Completamente genérico. No tiene área, nivel ni función. Ningún candidato relevante buscará esto."},
    ],
    points:100
  },

  // LEVEL 2 – Classify: realistic vs unrealistic requirements
  {
    id:2, topic:"REQUISITOS REALISTAS", topicColor:"#f59e0b",
    type:"classify",
    heading:"Requisitos que filtran vs. requisitos que espantan",
    instruction:"Clasifica cada requisito como <strong>✅ Realista</strong> (necesario y razonable para el puesto) o <strong>❌ Irrealista</strong> (exagerado o contraproducente).<br><br><em>Contexto: puesto de Analista de Marketing Digital, nivel semi-senior.</em>",
    hint:"↕ Clasifica si el requisito es razonable para este perfil",
    zones:[
      {id:"real",   label:"✅ REQUISITO REALISTA",   correct:[]},
      {id:"unreal", label:"❌ REQUISITO IRREALISTA", correct:[]}
    ],
    items:[
      {id:"r1", text:"3-5 años de experiencia en marketing digital", zone:"real",   feedback:"✅ Rango razonable para un perfil semi-senior. Específico sin ser restrictivo."},
      {id:"r2", text:"15 años de experiencia en redes sociales",     zone:"unreal", feedback:"❌ Las redes sociales modernas tienen menos de 15 años. Requisito matemáticamente imposible."},
      {id:"r3", text:"Dominio de Google Ads y Meta Ads",             zone:"real",   feedback:"✅ Herramientas estándar y verificables para marketing digital. Requisito técnico concreto."},
      {id:"r4", text:"MBA obligatorio de universidad Top 10 mundial", zone:"unreal", feedback:"❌ Sobrecalificación innecesaria para un analista. Excluye talento valioso sin razón de negocio."},
      {id:"r5", text:"Inglés intermedio para lectura de reportes",   zone:"real",   feedback:"✅ Nivel específico con justificación clara. No pide 'inglés nativo' sin necesidad real."},
      {id:"r6", text:"Disponibilidad 24/7 incluyendo fines de semana", zone:"unreal",feedback:"❌ Sin justificación específica del negocio, este requisito viola el equilibrio trabajo-vida y aleja candidatos."},
    ],
    points:100
  },

  // LEVEL 3 – Order the responsibilities correctly
  {
    id:3, topic:"DESCRIPCIÓN DE RESPONSABILIDADES", topicColor:"#34d399",
    type:"order",
    heading:"Ordena las responsabilidades de mayor a menor impacto",
    instruction:"Una buena descripción de puesto prioriza las responsabilidades <strong>de mayor a menor impacto estratégico</strong>. Arrastra las tarjetas al orden correcto (1 = más importante, 5 = complementaria).<br><br><em>Puesto: Especialista en Adquisición de Talento.</em>",
    hint:"↕ Arrastra las responsabilidades del 1 (más importante) al 5",
    correctOrder:["resp3","resp1","resp5","resp2","resp4"],
    items:[
      {id:"resp1", text:"Coordinar y agendar entrevistas con hiring managers"},
      {id:"resp2", text:"Actualizar métricas semanales en el ATS"},
      {id:"resp3", text:"Diseñar y ejecutar estrategias de atracción de talento para posiciones críticas"},
      {id:"resp4", text:"Participar en ferias de empleo universitarias"},
      {id:"resp5", text:"Gestionar el proceso completo de selección: screening, entrevistas y oferta"},
    ],
    feedbacks:[
      "✅ 1°: La estrategia de atracción es el core del rol. Define el éxito del área.",
      "✅ 2°: Gestionar el proceso completo es la responsabilidad operativa principal.",
      "✅ 3°: Coordinar entrevistas es clave pero de soporte al proceso principal.",
      "✅ 4°: Las métricas son importantes pero son actividad de seguimiento, no estratégica.",
      "✅ 5°: Las ferias son complementarias — valiosas pero de menor impacto cotidiano.",
    ],
    points:100
  },

  // LEVEL 4 – Classify: right vs wrong channel
  {
    id:4, topic:"CANALES DE PUBLICACIÓN", topicColor:"#60a5fa",
    type:"classify",
    heading:"Canal correcto para cada perfil",
    instruction:"Arrastra cada perfil de candidato al <strong>canal más efectivo</strong> para encontrarlo. Un perfil puede tener más de un canal válido, pero elige el más estratégico.",
    hint:"↕ Arrastra cada perfil al canal más efectivo para ese talento",
    zones:[
      {id:"linkedin",  label:"💼 LINKEDIN / PORTALES",  correct:[]},
      {id:"github",    label:"💻 GITHUB / COMUNIDADES TÉCNICAS", correct:[]},
      {id:"referidos", label:"🤝 REFERIDOS / NETWORKING", correct:[]},
      {id:"campus",    label:"🎓 CAMPUS / BOLSAS UNIVERSITARIAS", correct:[]},
    ],
    items:[
      {id:"c1", text:"Desarrollador especialista en ciberseguridad ofensiva (perfil escaso)", zone:"github",    feedback:"✅ GitHub y foros como HackerOne concentran a estos especialistas. LinkedIn tiene poca oferta para perfiles tan técnicos."},
      {id:"c2", text:"Practicante de Recursos Humanos – primer empleo",                      zone:"campus",    feedback:"✅ Las bolsas universitarias y ferias de campus son el canal natural para perfiles sin experiencia laboral."},
      {id:"c3", text:"Director Financiero para empresa Series B",                            zone:"referidos", feedback:"✅ Posiciones C-level rara vez se cubren por portales abiertos. El networking ejecutivo y headhunters especializados son la vía."},
      {id:"c4", text:"Analista de Marketing Digital con 2 años de experiencia",              zone:"linkedin",  feedback:"✅ LinkedIn y portales como OCC o Indeed son ideales para perfiles medios con experiencia verificable y activos en la búsqueda."},
    ],
    points:100
  },

  // LEVEL 5 – Classify: elements of a good job posting
  {
    id:5, topic:"ANATOMÍA DE UNA VACANTE", topicColor:"#f472b6",
    type:"classify",
    heading:"Construye una vacante completa y efectiva",
    instruction:"Una vacante de calidad tiene secciones bien definidas. Arrastra cada elemento al bloque al que pertenece dentro de la publicación.",
    hint:"↕ Clasifica cada elemento en la sección correcta de la vacante",
    zones:[
      {id:"empresa",  label:"🏢 SOBRE LA EMPRESA",        correct:[]},
      {id:"rol",      label:"🎯 DESCRIPCIÓN DEL ROL",      correct:[]},
      {id:"requi",    label:"📋 REQUISITOS",               correct:[]},
      {id:"oferta",   label:"💰 LO QUE OFRECEMOS",        correct:[]},
    ],
    items:[
      {id:"e1", text:"Startup de fintech fundada en 2019, presente en 5 países de LATAM",         zone:"empresa", feedback:"✅ Contexto de la empresa: tamaño, sector, trayectoria. Ayuda al candidato a evaluar fit cultural."},
      {id:"e2", text:"Liderar el equipo de producto y definir el roadmap trimestral",              zone:"rol",     feedback:"✅ Responsabilidad principal del rol. Va en la sección descriptiva del puesto."},
      {id:"e3", text:"Experiencia mínima de 4 años en gestión de productos digitales",             zone:"requi",   feedback:"✅ Requisito de experiencia. Pertenece a la sección de requisitos para filtrar aplicantes."},
      {id:"e4", text:"Salario: $45,000-$55,000 MXN + bono anual de desempeño",                   zone:"oferta",  feedback:"✅ La transparencia salarial aumenta hasta 40% las aplicaciones de candidatos relevantes."},
      {id:"e5", text:"Cultura de trabajo remoto con 2 días presenciales opcionales al mes",       zone:"oferta",  feedback:"✅ Beneficios de flexibilidad laboral. Son parte de la propuesta de valor al candidato."},
      {id:"e6", text:"Inglés avanzado requerido (reuniones con equipo en EUA)",                   zone:"requi",   feedback:"✅ Requisito con justificación clara. La razón de negocio hace el requisito más creíble y aceptado."},
    ],
    points:100
  }
];

// ═══════════════════════════════════════════════
// STATE
// ═══════════════════════════════════════════════
let currentLevel = 0;
let totalScore   = 0;
let levelResults = []; // {topic, color, points, max}
let dragSrc      = null;
let placements   = {};   // itemId → zoneId  (classify)
let orderArr     = [];   // ordered item ids (order)

// ═══════════════════════════════════════════════
// NAVIGATION
// ═══════════════════════════════════════════════
function showScreen(id){
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  const el=document.getElementById('screen-'+id);
  el.classList.add('active');
  el.style.animation='none';el.offsetHeight;el.style.animation='';
}
function startGame(){currentLevel=0;totalScore=0;levelResults=[];renderLevel();showScreen('game');}
function restartGame(){showScreen('intro');}

// ═══════════════════════════════════════════════
// RENDER
// ═══════════════════════════════════════════════
function renderLevel(){
  const lv=LEVELS[currentLevel];
  placements={};orderArr=[];

  // header
  document.getElementById('prog-fill').style.width=((currentLevel/LEVELS.length)*100)+'%';
  const tag=document.getElementById('level-tag');
  tag.textContent=lv.topic;
  tag.style.color=lv.topicColor;
  tag.style.border='1px solid '+lv.topicColor+'44';
  tag.style.background=lv.topicColor+'11';
  document.getElementById('score-disp').textContent=totalScore;
  document.getElementById('q-meta').style.color=lv.topicColor;
  document.getElementById('q-meta').textContent='NIVEL '+(currentLevel+1)+' / '+LEVELS.length+' · '+lv.topic;
  document.getElementById('q-heading').textContent=lv.heading;
  document.getElementById('q-instruction').innerHTML=lv.instruction;
  document.getElementById('hint-bar').textContent=lv.hint;

  // hide feedback & buttons
  document.getElementById('feedback-panel').classList.remove('show');
  document.getElementById('feedback-panel').style.display='none';
  document.getElementById('btn-check').classList.remove('show');
  document.getElementById('btn-next').classList.remove('show');

  const area=document.getElementById('drag-area');
  area.innerHTML='';

  if(lv.type==='classify') renderClassify(lv,area);
  else if(lv.type==='order') renderOrder(lv,area);
}

// ── CLASSIFY ──
function renderClassify(lv,area){
  // pool
  const poolWrap=document.createElement('div');
  poolWrap.style.cssText='background:rgba(255,255,255,0.02);border:1px dashed rgba(255,255,255,0.1);border-radius:10px;padding:14px 16px;margin-bottom:16px;';
  const poolLabel=document.createElement('div');
  poolLabel.style.cssText='font-size:9px;letter-spacing:3px;color:var(--muted);margin-bottom:10px;';
  poolLabel.textContent='ELEMENTOS — ARRASTRA A SU CATEGORÍA';
  poolWrap.appendChild(poolLabel);
  const pool=document.createElement('div');
  pool.id='pool';
  pool.className='card-pool';
  lv.items.forEach(item=>{
    pool.appendChild(makeCard(item.id,item.text));
    placements[item.id]=null;
  });
  poolWrap.appendChild(pool);
  area.appendChild(poolWrap);

  // zones grid
  const grid=document.createElement('div');
  grid.className='drag-layout';
  lv.zones.forEach(z=>{
    const box=document.createElement('div');
    box.className='zone-box';
    box.id='zone-'+z.id;
    box.dataset.zone=z.id;
    const title=document.createElement('div');
    title.className='zone-title';title.textContent=z.label;
    box.appendChild(title);
    const inner=document.createElement('div');
    inner.id='zone-inner-'+z.id;
    inner.className='card-pool';
    inner.style.flexDirection='column';
    box.appendChild(inner);
    setupDropZone(box);
    grid.appendChild(box);
  });
  area.appendChild(grid);
}

// ── ORDER ──
function renderOrder(lv,area){
  const wrap=document.createElement('div');
  wrap.className='order-layout';

  // pool
  const poolDiv=document.createElement('div');
  poolDiv.className='order-pool';
  const poolLbl=document.createElement('div');
  poolLbl.className='order-pool-label';
  poolLbl.textContent='RESPONSABILIDADES — ARRASTRA AL ORDEN CORRECTO ↓';
  poolDiv.appendChild(poolLbl);
  const pool=document.createElement('div');
  pool.id='pool';pool.className='card-pool';
  pool.style.flexDirection='column';
  // shuffle
  const shuffled=[...lv.items].sort(()=>Math.random()-.5);
  shuffled.forEach(item=>{
    pool.appendChild(makeCard(item.id,item.text));
  });
  poolDiv.appendChild(pool);
  wrap.appendChild(poolDiv);

  // slots
  const slotDiv=document.createElement('div');
  slotDiv.className='order-zone';
  const slotLbl=document.createElement('div');
  slotLbl.className='order-zone-label';
  slotLbl.textContent='ORDEN DE PRIORIDAD (1 = MÁS IMPORTANTE)';
  slotDiv.appendChild(slotLbl);
  const slotsWrap=document.createElement('div');
  slotsWrap.className='order-slots';
  for(let i=0;i<lv.items.length;i++){
    const sl=document.createElement('div');
    sl.className='slot';
    sl.id='slot-'+i;
    sl.dataset.slot=i;
    sl.innerHTML='<span style="color:var(--muted);font-size:10px;">'+( i+1 )+'&nbsp;&nbsp;Arrastra aquí…</span>';
    setupSlotDrop(sl);
    slotsWrap.appendChild(sl);
  }
  slotDiv.appendChild(slotsWrap);
  wrap.appendChild(slotDiv);
  area.appendChild(wrap);
}

// ═══════════════════════════════════════════════
// CARD FACTORY
// ═══════════════════════════════════════════════
function makeCard(id,text){
  const c=document.createElement('div');
  c.className='drag-card';
  c.id='card-'+id;
  c.dataset.itemId=id;
  c.draggable=true;
  c.innerHTML=text+'<span class="result-icon"></span>';
  c.addEventListener('dragstart',onDragStart);
  c.addEventListener('dragend',onDragEnd);
  // touch
  c.addEventListener('touchstart',onTouchStart,{passive:true});
  c.addEventListener('touchmove',onTouchMove,{passive:false});
  c.addEventListener('touchend',onTouchEnd);
  return c;
}

// ═══════════════════════════════════════════════
// DRAG — Desktop
// ═══════════════════════════════════════════════
function onDragStart(e){dragSrc=this;this.classList.add('dragging');e.dataTransfer.effectAllowed='move';}
function onDragEnd(){this.classList.remove('dragging');dragSrc=null;checkCanVerify();}

function setupDropZone(el){
  el.addEventListener('dragover',e=>{e.preventDefault();el.classList.add('drop-target');});
  el.addEventListener('dragleave',()=>el.classList.remove('drop-target'));
  el.addEventListener('drop',e=>{
    e.preventDefault();el.classList.remove('drop-target');
    if(!dragSrc)return;
    const itemId=dragSrc.dataset.itemId;
    const zoneId=el.dataset.zone;
    // remove from previous zone or pool
    dragSrc.parentNode && dragSrc.parentNode.removeChild(dragSrc);
    document.getElementById('zone-inner-'+zoneId).appendChild(dragSrc);
    placements[itemId]=zoneId;
    checkCanVerify();
  });
}

function setupSlotDrop(el){
  el.addEventListener('dragover',e=>{e.preventDefault();el.classList.add('drop-target');});
  el.addEventListener('dragleave',()=>el.classList.remove('drop-target'));
  el.addEventListener('drop',e=>{
    e.preventDefault();el.classList.remove('drop-target');
    if(!dragSrc)return;
    const slotIdx=parseInt(el.dataset.slot);
    const itemId=dragSrc.dataset.itemId;
    // if slot occupied, send occupant back to pool
    const existing=el.querySelector('.drag-card');
    if(existing){
      const pool=document.getElementById('pool');
      existing.parentNode.removeChild(existing);
      pool.appendChild(existing);
      // remove from orderArr
      const pos=orderArr.indexOf(existing.dataset.itemId);
      if(pos>-1)orderArr.splice(pos,1);
    }
    // remove card from wherever it was
    const prevSlotIdx=orderArr.indexOf(itemId);
    if(prevSlotIdx>-1){
      // it was in another slot — clear that slot visually
      const prevSlotEl=document.getElementById('slot-'+prevSlotIdx);
      prevSlotEl.innerHTML='<span style="color:var(--muted);font-size:10px;">'+(prevSlotIdx+1)+'&nbsp;&nbsp;Arrastra aquí…</span>';
      setupSlotDrop(prevSlotEl);
      orderArr[prevSlotIdx]=null;
    } else {
      dragSrc.parentNode && dragSrc.parentNode.removeChild(dragSrc);
    }
    el.innerHTML='';
    el.appendChild(dragSrc);
    el.classList.add('filled');
    // update orderArr
    while(orderArr.length<=slotIdx)orderArr.push(null);
    orderArr[slotIdx]=itemId;
    checkCanVerify();
  });
}

// ═══════════════════════════════════════════════
// TOUCH — Mobile
// ═══════════════════════════════════════════════
let touchCard=null,touchClone=null,touchOffX=0,touchOffY=0;
function onTouchStart(e){
  touchCard=this;
  const t=e.touches[0];
  const r=this.getBoundingClientRect();
  touchOffX=t.clientX-r.left;touchOffY=t.clientY-r.top;
  touchClone=this.cloneNode(true);
  touchClone.style.cssText=`position:fixed;width:${r.width}px;opacity:.85;z-index:9999;pointer-events:none;left:${r.left}px;top:${r.top}px;`;
  document.body.appendChild(touchClone);
}
function onTouchMove(e){
  if(!touchClone)return;
  e.preventDefault();
  const t=e.touches[0];
  touchClone.style.left=(t.clientX-touchOffX)+'px';
  touchClone.style.top=(t.clientY-touchOffY)+'px';
}
function onTouchEnd(e){
  if(!touchClone){return;}
  const t=e.changedTouches[0];
  document.body.removeChild(touchClone);touchClone=null;
  const target=document.elementFromPoint(t.clientX,t.clientY);
  if(!target){dragSrc=touchCard;touchCard=null;return;}
  const zone=target.closest('[data-zone]');
  const slot=target.closest('[data-slot]');
  if(zone){dragSrc=touchCard;simulateDrop(zone);}
  else if(slot){dragSrc=touchCard;simulateSlotDrop(slot);}
  touchCard=null;dragSrc=null;checkCanVerify();
}
function simulateDrop(el){
  if(!dragSrc)return;
  const itemId=dragSrc.dataset.itemId;
  const zoneId=el.dataset.zone;
  dragSrc.parentNode&&dragSrc.parentNode.removeChild(dragSrc);
  document.getElementById('zone-inner-'+zoneId).appendChild(dragSrc);
  placements[itemId]=zoneId;
}
function simulateSlotDrop(el){
  if(!dragSrc)return;
  const slotIdx=parseInt(el.dataset.slot);
  const itemId=dragSrc.dataset.itemId;
  const existing=el.querySelector('.drag-card');
  if(existing){
    document.getElementById('pool').appendChild(existing);
    const pos=orderArr.indexOf(existing.dataset.itemId);
    if(pos>-1)orderArr.splice(pos,1);
  }
  const prevIdx=orderArr.indexOf(itemId);
  if(prevIdx>-1){
    const ps=document.getElementById('slot-'+prevIdx);
    ps.innerHTML='<span style="color:var(--muted);font-size:10px;">'+(prevIdx+1)+'&nbsp;&nbsp;Arrastra aquí…</span>';
    setupSlotDrop(ps);orderArr[prevIdx]=null;
  } else {
    dragSrc.parentNode&&dragSrc.parentNode.removeChild(dragSrc);
  }
  el.innerHTML='';el.appendChild(dragSrc);el.classList.add('filled');
  while(orderArr.length<=slotIdx)orderArr.push(null);
  orderArr[slotIdx]=itemId;
}

// ═══════════════════════════════════════════════
// VERIFY
// ═══════════════════════════════════════════════
function checkCanVerify(){
  const lv=LEVELS[currentLevel];
  let ready=false;
  if(lv.type==='classify'){
    ready=Object.values(placements).every(v=>v!==null);
  } else if(lv.type==='order'){
    ready=orderArr.filter(Boolean).length===lv.items.length;
  }
  const btn=document.getElementById('btn-check');
  if(ready)btn.classList.add('show'); else btn.classList.remove('show');
}

function checkAnswer(){
  const lv=LEVELS[currentLevel];
  const fp=document.getElementById('feedback-panel');
  const fi=document.getElementById('fb-items');
  fi.innerHTML='';
  let correct=0,total=0;

  if(lv.type==='classify'){
    lv.items.forEach(item=>{
      total++;
      const userZone=placements[item.id];
      const ok=userZone===item.zone;
      if(ok)correct++;
      // style card
      const card=document.getElementById('card-'+item.id);
      card.classList.add(ok?'placed-correct':'placed-wrong');
      card.querySelector('.result-icon').textContent=ok?'✓':'✗';
      card.style.pointerEvents='none';
      // feedback row
      const row=document.createElement('div');
      row.className='fb-item '+(ok?'ok':'bad');
      row.innerHTML=`<span class="icon">${ok?'✅':'❌'}</span><span>${item.feedback}</span>`;
      fi.appendChild(row);
    });
  } else if(lv.type==='order'){
    const correct_order=lv.correctOrder;
    // score: +1 per correct position
    // Allow ±1 tolerance? No — exact order for learning
    correct_order.forEach((id,idx)=>{
      total++;
      const userPos=orderArr.indexOf(id);
      const ok=userPos===idx;
      if(ok)correct++;
      const card=document.getElementById('card-'+id);
      if(card){
        card.classList.add(ok?'placed-correct':'placed-wrong');
        card.querySelector('.result-icon').textContent=ok?'✓':'✗';
        card.style.pointerEvents='none';
      }
    });
    lv.feedbacks.forEach((fb,i)=>{
      const ok=orderArr[i]===lv.correctOrder[i];
      const row=document.createElement('div');
      row.className='fb-item '+(ok?'ok':'bad');
      row.innerHTML=`<span class="icon">${ok?'✅':'❌'}</span><span>${fb}</span>`;
      fi.appendChild(row);
    });
  }

  const pct=Math.round((correct/total)*100);
  const pts=Math.round((correct/total)*lv.points);
  totalScore+=pts;
  document.getElementById('score-disp').textContent=totalScore;

  document.getElementById('fb-score').textContent=correct+'/'+total+' correctos — '+pts+' pts';
  document.getElementById('fb-score').style.color=pct>=70?'var(--green)':pct>=40?'var(--accent2)':'var(--red)';
  document.getElementById('fb-label').textContent=pct>=80?'¡Excelente trabajo!':pct>=50?'Buen intento, revisa los detalles':'Revisa las explicaciones para reforzar';

  fp.style.display='block';fp.classList.add('show');
  document.getElementById('btn-check').classList.remove('show');
  document.getElementById('btn-next').classList.add('show');
  document.getElementById('btn-next').textContent=
    currentLevel+1>=LEVELS.length?'VER RESULTADOS →':'SIGUIENTE NIVEL →';

  levelResults.push({topic:lv.topic,color:lv.topicColor,pts,max:lv.points,correct,total});
}

function nextLevel(){
  currentLevel++;
  if(currentLevel>=LEVELS.length){showResults();return;}
  renderLevel();
  document.getElementById('screen-game').scrollIntoView({behavior:'smooth'});
}

// ═══════════════════════════════════════════════
// RESULTS
// ═══════════════════════════════════════════════
function showResults(){
  const pct=Math.round((totalScore/500)*100);
  const tiers=[
    {min:85,trophy:'🏆',title:'Experta/o en Publicación de Vacantes',msg:'¡Dominas el arte de publicar vacantes efectivas! Tu capacidad para crear títulos claros, definir requisitos realistas, priorizar responsabilidades y elegir los canales correctos te pone en el top de los reclutadores.'},
    {min:60,trophy:'📈',title:'Reclutador/a en Crecimiento',msg:'Tienes sólidas bases en publicación de vacantes. Con práctica en la redacción de requisitos y en la elección estratégica de canales llegarás al siguiente nivel rápidamente.'},
    {min:0, trophy:'🌱',title:'Reclutador/a en Formación',msg:'Cada nivel fue un aprendizaje. La publicación de vacantes efectiva es una habilidad que se construye con práctica. ¡Vuelve a jugar para reforzar los conceptos!'}
  ];
  const tier=tiers.find(t=>pct>=t.min);
  document.getElementById('res-trophy').textContent=tier.trophy;
  document.getElementById('res-title').textContent=tier.title;
  document.getElementById('res-score').textContent=totalScore;
  document.getElementById('res-msg').textContent=tier.msg;

  const hist=document.getElementById('res-history');
  hist.innerHTML='';
  levelResults.forEach(r=>{
    const ok=r.pts/r.max>=0.7;
    const d=document.createElement('div');
    d.className='history-item '+(ok?'ok':'fail');
    d.innerHTML=`<span style="font-size:16px">${ok?'✅':'❌'}</span>
      <span class="h-tag" style="color:${r.color}">${r.topic}</span>
      <span class="h-name">${r.correct}/${r.total} correctos · ${r.pts} pts</span>`;
    hist.appendChild(d);
  });

  document.getElementById('prog-fill').style.width='100%';
  showScreen('results');
}
</script>
</body>
</html>
