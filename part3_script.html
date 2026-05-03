<!-- KaTeX render script (loaded after content) -->
<script src="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.js"></script>

<script>
// ═══════════════════════════════════════════════════════════════════
//  DATA · 23 consultas
// ═══════════════════════════════════════════════════════════════════
const CONSULTAS = [
  { n:1, cat:'tab', date:'19 mar 2026 · 10:36', sort:20260319103, q:"¿Cómo se interpola para el punto 4 de la guía? Los datos de vapor sobrecalentado a 180 °C no están en la tabla.", a:"Los datos de vapor sobrecalentado a 180 °C no figuran directamente en las tablas. Se interpola linealmente entre los valores disponibles (160 °C y 200 °C, o los que correspondan) para obtener las propiedades en ese estado intermedio.", by:'alu', byName:'Alumno del grupo' },
  { n:2, cat:'tab', date:'19 mar 2026 · 10:43', sort:20260319104, q:"En el ejercicio 7, solo me dan presión y volumen específico. ¿Cómo sé en qué estado está el fluido?", a:"Hay que comparar el volumen específico dado con los valores de <strong>v<sub>f</sub></strong> (líquido saturado) y <strong>v<sub>g</sub></strong> (vapor saturado) a esa presión en la tabla. Si <strong>v<sub>f</sub> &lt; v &lt; v<sub>g</sub></strong>, el fluido es una mezcla líquido-vapor y se puede calcular el título <em>x</em> para determinar completamente el estado.", by:'alu', byName:'Alumno del grupo' },
  { n:3, cat:'tab', date:'31 mar 2026 · 11:57', sort:20260331115, q:"¿Qué tablas de Cengel vamos a usar a lo largo de la materia? ¿Tengo que imprimir todo el PDF?", a:"Solo se van a utilizar las tablas de <strong>agua</strong> y <strong>refrigerante</strong>. No hace falta imprimir todo el PDF.", by:'doc', byName:'Tete (docente)' },
  { n:4, cat:'1pp', date:'28 mar 2026 · 11:08', sort:20260328110, q:"En el primer principio para sistemas abiertos, la fórmula tiene un −(h<sub>e</sub>−h<sub>s</sub>). En el llenado de un tanque, como h<sub>e</sub> &gt; h<sub>s</sub>, el término queda negativo, y con Q=W=0 la variación de energía interna da negativa. ¿No debería aumentar?", a:"El error está en la interpretación del término: como es un <strong>delta</strong>, ΔH<sub>e–s</sub> = h<sub>s</sub> − h<sub>e</sub> (salida menos entrada), no al revés. Aplicando el 1° principio en régimen no estacionario con Q=W=0 queda <strong>ΔH<sub>e–s</sub> = −ΔU</strong>, lo que da variación de energía interna positiva — consistente con que el tanque se llena y su energía interna aumenta.", by:'doc', byName:'Tete (docente)' },
  { n:5, cat:'1pp', date:'28 mar 2026 · 18:44', sort:20260328184, q:"En el ejercicio 3.5, ¿cómo se plantea el 1° principio en el inciso 1? El trabajo no me queda bien y no entiendo cómo sacar el calor en el inciso 2.", a:"El error frecuente es sacar el volumen específico <strong>afuera de la integral del trabajo</strong>, cuando en el proceso 1–2 el volumen varía (el pistón sube al expandirse el aire). El volumen no es constante y no puede sacarse de la integral. La resolución correcta aparece en los apuntes compartidos en el grupo.", by:'alu', byName:'Alumnos del grupo' },
  { n:6, cat:'1pp', date:'4 abr 2026 · 16:10', sort:20260404161, q:"En el ejercicio del condensador con un río, puedo calcular el calor con el 1° principio, pero no entiendo cómo relacionarlo con la diferencia de temperatura del río.", a:"Es un <strong>intercambiador de calor</strong>: el calor que cede el vapor al condensarse es exactamente el que absorbe el agua del río. Como el agua es un líquido casi incompresible, se aplica: <strong>Q = ṁ<sub>río</sub> · c<sub>p,H₂O</sub> · ΔT</strong>. Es lo mismo que se vio al final de la clase de primer principio del viernes.", by:'doc', byName:'Tete (docente)' },
  { n:7, cat:'1pp', date:'1 may 2026 · 13:09', sort:20260501130, q:"Para calcular el W<sub>pistón</sub>, ¿uso ΔV del cilindro completo (5 m³ – 0 m³) o solo 2 m³ como dice la respuesta del cuestionario?", a:"El ΔV del cilindro es <strong>5 m³ − 0 m³ = 5 m³</strong>. La respuesta del cuestionario con 2 m³ tenía un error; fue corregida por los docentes durante la misma conversación.", by:'doc', byName:'Juan F. Aquino (docente)' },
  { n:8, cat:'ent', date:'17 abr 2026 · 17:14', sort:20260417171, q:"En un proceso adiabático reversible con <em>aire</em>, ¿qué tabla uso? Planteé s₁=s₂ pero tengo lío con las tablas. ¿Uso la A-17?", a:"El error fundamental fue tratar al <strong>aire como vapor sobrecalentado</strong>. El aire es un <strong>gas ideal</strong>: no se usan tablas, se aplican directamente las ecuaciones de gas ideal. Para un proceso isoentrópico (adiabático reversible), se usan las relaciones <strong>T₂/T₁ = (P₂/P₁)<sup>(k−1)/k</sup></strong> con k = Cp/Cv.", by:'doc', byName:'Tete (docente)' },
  { n:9, cat:'ent', date:'18 abr 2026 · 18:01', sort:20260418180, q:"En el ejercicio con el recipiente dividido en dos masas de aire a distintas condiciones, ¿cómo calculo el ΔS del universo si el sistema está partido?", a:"La variación de entropía del sistema total es la <strong>suma de las variaciones de cada masa por separado</strong>: ΔS<sub>total</sub> = ΔS<sub>m1</sub> + ΔS<sub>m2</sub>. Cada masa usa su estado inicial propio (T₁,P₁ y T₂,P₂) y el mismo estado final (T<sub>f</sub>,P<sub>f</sub>), aplicando la primera ecuación de ΔS de gas ideal a cada una.", by:'doc', byName:'Juan F. Aquino (docente)' },
  { n:10, cat:'ent', date:'18 abr 2026 · 18:39', sort:20260418183, q:"En el ejercicio con una resistencia eléctrica a temperatura constante, ¿la variación de entropía de la resistencia es cero? ¿Para qué sirve el dato de temperatura constante entonces?", a:"Correcto: en régimen estacionario la resistencia no cambia de estado, por lo que sus funciones de estado (U, H, S) no varían → <strong>ΔS<sub>resistencia</sub> = 0</strong>. Sin embargo, la conversión de trabajo eléctrico en calor es un proceso <strong>altamente irreversible</strong>. El dato de temperatura constante sirve para calcular la variación de entropía del <strong>medio que recibe el calor</strong>: ΔS<sub>medio</sub> = Q/T.", by:'doc', byName:'Juan F. Aquino (docente)' },
  { n:11, cat:'tab', date:'25 abr 2026 · 18:55', sort:20260425185, q:"Me dan C<sub>p</sub> con unidades de kJ/kg·°C. ¿Tengo que convertirlo a Kelvin para los cálculos?", a:"No hace falta convertir. Los calores específicos (C<sub>p</sub> y C<sub>v</sub>) se definen a partir de <strong>diferencias de temperatura (ΔT)</strong>. Como un grado Celsius y un Kelvin representan exactamente el mismo intervalo, el valor numérico es idéntico en ambas escalas.", by:'doc', byName:'Tete (docente)' },
  { n:12, cat:'2pp', date:'19 abr 2026 · 20:21', sort:20260419202, q:"¿Cómo se encara el ejercicio del ciclo de Carnot? No sé por dónde empezar.", a:"El ciclo de Carnot tiene <strong>4 evoluciones</strong>: 2 <strong>isotérmicas</strong> (con intercambio de calor reversible) y 2 <strong>isoentrópicas/adiabáticas</strong> (sin intercambio de calor). Para cada proceso hay que plantear las ecuaciones que correspondan. No es un ejercicio lineal: hay que ir proceso por proceso con lo que tiene sentido termodinámicamente.", by:'doc', byName:'Tete (docente)' },
  { n:13, cat:'2pp', date:'20 abr 2026 · 15:00', sort:20260420150, q:"No puedo plantear el proceso 2→3 del ciclo de Carnot porque no conozco ninguna propiedad en el punto 3. Tengo más incógnitas que ecuaciones.", a:"La guía 5 es más <strong>conceptual</strong> que las anteriores. El camino corto es usar directamente la ecuación de rendimiento del ciclo de Carnot: <strong>η = 1 − T<sub>L</sub>/T<sub>H</sub></strong> (diapositiva 6 de 2° principio). Combinada con la ecuación de gases ideales con volumen específico, el sistema de ecuaciones cierra sin necesidad de conocer todas las propiedades en cada punto.", by:'doc', byName:'Docentes (Tete + Juan)' },
  { n:14, cat:'2pp', date:'22 abr 2026 · 13:08', sort:20260422130, q:"En la fórmula de rendimiento del ciclo de Carnot η = 1 − T<sub>L</sub>/T<sub>H</sub>, ¿las temperaturas van en Celsius o en Kelvin?", a:"Siempre en <strong>Kelvin</strong>. Usar Celsius da resultados incorrectos porque la escala Celsius tiene un cero arbitrario. La única excepción donde se puede usar °C por comodidad es al anotar los datos iniciales en una tabla antes de operar. Para todos los cálculos: siempre Kelvin.", by:'doc', byName:'Juan F. Aquino (docente)' },
  { n:15, cat:'2pp', date:'27 abr 2026 · 19:22', sort:20260427192, q:"En el ejercicio 6.7 del ciclo de Carnot, ¿la expansión isotérmica puede salir de la campana de saturación hacia vapor sobrecalentado?", a:"Sí. En un ciclo de Carnot los procesos son <strong>ideales</strong>. La expansión isotérmica puede salir de la campana de saturación hacia vapor sobrecalentado, algo que en la práctica real sería imposible, pero que el ciclo ideal de Carnot acepta. El ciclo de Carnot no existe como tal en la realidad.", by:'alu', byName:'Alumno (confirmado por docente)' },
  { n:16, cat:'cic', date:'22 abr 2026 · 15:20', sort:20260422152, q:"¿La eficiencia isoentrópica de una bomba se calcula igual que la de un compresor (W<sub>rev</sub>/W<sub>irrev</sub>)? ¿Cómo calculo h₄ ideal?", a:"Sí: una <strong>bomba es un compresor para líquidos</strong>, la fórmula es la misma. Para h₄ ideal hay que definir un estado 4' con la <strong>misma presión de salida pero proceso isoentrópico</strong>, es decir: s<sub>4'</sub> = s<sub>3</sub>. Conociendo presión y entropía de 4', se sacan todas las demás propiedades de la tabla. El diagrama <strong>T-s</strong> es la herramienta visual clave para entender esto.", by:'doc', byName:'Juan F. Aquino (docente)' },
  { n:17, cat:'cic', date:'22 abr 2026 · 17:04', sort:20260422170, q:"¿Qué C<sub>p</sub> uso para calcular ΔH en agua y en aire? ¿Es válido ΔH = C<sub>p</sub> · ΔT para vapor sobrecalentado?", a:"⚠️ <strong>Falla conceptual grave</strong>: ΔH = C<sub>p</sub>·ΔT y ΔU = C<sub>v</sub>·ΔT solo son válidas para <strong>gases ideales</strong>. El <strong>vapor de agua no es gas ideal</strong>: hay que usar tablas termodinámicas para calcular variaciones de entalpía. Si hay dudas sobre si el aire o el vapor son gases ideales, hay que revisar la carpeta porque indica un problema conceptual de base.", by:'doc', byName:'Tete (docente)' },
  { n:18, cat:'cic', date:'2 may 2026 · 17:43', sort:20260502174, q:"¿Cómo se calcula el rendimiento isoentrópico de una turbina cuando el fluido es vapor de agua (no gas ideal)?", a:"Se aplica el <strong>1° principio en base a entalpías</strong>: η<sub>iso</sub> = ΔH<sub>real</sub> / ΔH<sub>ideal</sub> = (h<sub>ent</sub> − h<sub>sal,real</sub>) / (h<sub>ent</sub> − h<sub>sal,ideal</sub>). El estado de salida ideal se obtiene de la tabla termodinámica conociendo la presión de salida y la entropía de entrada (s<sub>sal,ideal</sub> = s<sub>ent</sub>).", by:'doc', byName:'Tete (docente)' },
  { n:19, cat:'cic', date:'2 may 2026 · 18:09', sort:20260502180, q:"En un ejercicio con pistón, aunque no me lo diga explícitamente, ¿puedo asumir que la presión inicial y final son iguales (P<sub>i</sub> = P<sub>f</sub>)?", a:"Sí. En termodinámica <strong>siempre se trabaja de estado de equilibrio a estado de equilibrio</strong>. Si el pistón está en equilibrio mecánico en ambos estados, las presiones del gas y la externa se igualan. Esto se puede asumir aunque el enunciado no lo diga explícitamente.", by:'doc', byName:'Tete (docente)' },
  { n:20, cat:'gen', date:'27 abr 2026 · 19:09', sort:20260427190, q:"¿Los ciclos de refrigeración entran para el parcial, incluyendo la parte teórica?", a:"Solo entra <strong>teoría de máquinas térmicas (MT) y máquinas frigoríficas (MF)</strong>. El parcial cubre eso en la parte teórica. No hay resolución de ejercicios numéricos de ciclos en el parcial.", by:'alu', byName:'Alumnos (confirmado por docentes)' },
  { n:21, cat:'exg', date:'30 abr 2026 · 12:12', sort:20260430121, q:"Para calcular ΔX del universo en un compresor, ¿debo incluir la exergía del trabajo que entrega el motor al compresor?", a:"Sí. El <strong>universo termodinámico incluye todo lo que participa</strong> en el proceso. Si el motor no está incluido, el proceso no ocurre. Hay que considerar la variación de exergía de todos los elementos: fluido del compresor + quien entrega el trabajo.", by:'doc', byName:'Tete (docente)' },
  { n:22, cat:'exg', date:'2 may 2026 · 10:55', sort:20260502105, q:'En el cálculo de ΔX del universo con una turbina, ¿qué "medio" recibe el trabajo mecánico? ¿Asumo que va al ambiente o a algo que lo aprovecha?', a:'<strong>Siempre hay algo que recibe el trabajo</strong>. El trabajo nunca se "libera al ambiente" como lo hace el calor. Ante la falta de datos, se asume que hay un receptor útil (ej. un generador eléctrico) que aumenta su exergía en ese monto. Lo que no se puede calcular es la variación de exergía del trabajo o calor propiamente dichos —son formas <em>dinámicas</em> de energía—; sí se puede calcular la de <strong>quienes los dan o reciben</strong>.', by:'doc', byName:'Juan F. Aquino (docente)' },
  { n:23, cat:'exg', date:'2 may 2026 · 18:18', sort:20260502181, q:'¿Cómo calculo la "destrucción de exergía" de un equipo específico (turbina o compresor)? ¿Es lo mismo que −T₀·ΔS del sistema?', a:'La destrucción de exergía es el <strong>módulo de la variación de exergía del universo</strong> (|ΔX<sub>universo</sub>|). Para calcularla solo de un equipo específico, se hace un <strong>"zoom in"</strong>: el universo pasa a ser solo ese equipo, el sistema es el fluido que pasa por él, y el medio es quien recibe (turbina) o entrega (compresor) el trabajo. Siempre se cumple: <strong>ΔX<sub>universo</sub> = −T<sub>0</sub>·ΔS<sub>universo</sub></strong>.', by:'doc', byName:'Tete (docente)' }
];

const TAG_LABEL = { tab:'Tablas', '1pp':'1° Principio', '2pp':'2° Principio', ent:'Entropía', exg:'Exergía', cic:'Ciclos / Máquinas', gen:'General' };
const TAG_CLASS = { tab:'tag-tab', '1pp':'tag-1pp', '2pp':'tag-2pp', ent:'tag-ent', exg:'tag-exg', cic:'tag-cic', gen:'tag-gen' };

// ═══════════════════════════════════════════════════════════════════
//  STATE
// ═══════════════════════════════════════════════════════════════════
const LS = {
  bookmarks: 'transfo_bookmarks',
  reviewed:  'transfo_reviewed',
  theme:     'transfo_theme'
};

let activeFilter = 'all';
let searchTerm = '';
let sortAsc = true;
let bookmarkOnly = false;
let bookmarks = readLS(LS.bookmarks, []);
let reviewed  = readLS(LS.reviewed, []);

function readLS(key, fallback) {
  try { return JSON.parse(localStorage.getItem(key)) || fallback; }
  catch(e) { return fallback; }
}
function writeLS(key, val) {
  try { localStorage.setItem(key, JSON.stringify(val)); } catch(e) {}
}

// ═══════════════════════════════════════════════════════════════════
//  RENDER · cards
// ═══════════════════════════════════════════════════════════════════
function renderCards() {
  const list = document.getElementById('cardList');
  let cards = [...CONSULTAS];
  cards.sort((a,b) => sortAsc ? b.sort - a.sort : a.sort - b.sort);

  list.innerHTML = cards.map(c => {
    const isBook = bookmarks.includes(c.n);
    const isRev  = reviewed.includes(c.n);
    return `
      <article class="card ${isBook?'bookmarked':''} ${isRev?'reviewed':''}" data-cat="${c.cat}" data-id="${c.n}">
        <div class="card-h">
          <div class="card-num">${String(c.n).padStart(2,'0')}</div>
          <div class="card-main">
            <div class="card-meta">
              <span class="card-date">${c.date}</span>
              <span class="tag ${TAG_CLASS[c.cat]}">${TAG_LABEL[c.cat]}</span>
            </div>
            <div class="card-q">${c.q}</div>
          </div>
          <div class="card-actions">
            <button class="icon-btn ${isBook?'active':''}" title="Marcar como favorita" onclick="event.stopPropagation();toggleBookmark(${c.n})" aria-label="Favorita">
              <svg viewBox="0 0 24 24" fill="${isBook?'currentColor':'none'}" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
            </button>
            <button class="icon-btn ${isRev?'checked':''}" title="Marcar como revisada" onclick="event.stopPropagation();toggleReviewed(${c.n})" aria-label="Revisada">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
            </button>
          </div>
          <div class="card-chev"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"/></svg></div>
        </div>
        <div class="card-body">
          <div class="card-body-inner">
            <div class="resp-label">Respuesta</div>
            <p class="resp-text">${c.a}</p>
            <div class="resp-by">
              <div class="resp-by-left">
                <div class="avatar avatar-${c.by}">${c.by==='doc'?'TT':'AL'}</div>
                <span class="by-text">${c.byName}</span>
              </div>
            </div>
          </div>
        </div>
      </article>
    `;
  }).join('');

  // Attach click handlers (delegated would be better, but this is fine)
  list.querySelectorAll('.card-h').forEach(h => {
    h.addEventListener('click', e => {
      if (e.target.closest('.icon-btn')) return;
      toggleCard(h.closest('.card'));
    });
  });
}

// ═══════════════════════════════════════════════════════════════════
//  CARD interaction
// ═══════════════════════════════════════════════════════════════════
function toggleCard(card) {
  const body = card.querySelector('.card-body');
  if (card.classList.contains('open')) {
    body.style.maxHeight = '0';
    card.classList.remove('open');
  } else {
    body.style.maxHeight = body.scrollHeight + 'px';
    card.classList.add('open');
  }
}

function expandAll() {
  document.querySelectorAll('#cardList .card:not(.hidden)').forEach(c => {
    const b = c.querySelector('.card-body');
    b.style.maxHeight = b.scrollHeight + 'px';
    c.classList.add('open');
  });
}
function collapseAll() {
  document.querySelectorAll('#cardList .card.open').forEach(c => {
    c.querySelector('.card-body').style.maxHeight = '0';
    c.classList.remove('open');
  });
}

// ═══════════════════════════════════════════════════════════════════
//  BOOKMARKS · REVIEWED
// ═══════════════════════════════════════════════════════════════════
function toggleBookmark(n) {
  const i = bookmarks.indexOf(n);
  if (i >= 0) bookmarks.splice(i,1); else bookmarks.push(n);
  writeLS(LS.bookmarks, bookmarks);
  renderCards();
  updateBookmarkUI();
  applyFilters();
}
function toggleReviewed(n) {
  const i = reviewed.indexOf(n);
  if (i >= 0) reviewed.splice(i,1); else reviewed.push(n);
  writeLS(LS.reviewed, reviewed);
  renderCards();
  updateProgress();
  applyFilters();
}
function updateBookmarkUI() {
  document.getElementById('bookCount').textContent = bookmarks.length;
}
function updateProgress() {
  const c = reviewed.length;
  document.getElementById('reviewedCount').textContent = c;
  document.getElementById('progressFill').style.width = (100 * c / 23) + '%';
}

// ═══════════════════════════════════════════════════════════════════
//  FILTERS · SEARCH · SORT
// ═══════════════════════════════════════════════════════════════════
function applyFilters() {
  const cards = document.querySelectorAll('#cardList .card');
  let visible = 0;
  cards.forEach(card => {
    const id = +card.dataset.id;
    const catMatch = activeFilter==='all' || card.dataset.cat===activeFilter;
    const bookMatch = !bookmarkOnly || bookmarks.includes(id);
    const text = card.textContent.toLowerCase();
    const searchMatch = !searchTerm || text.includes(searchTerm);
    if (catMatch && bookMatch && searchMatch) {
      card.classList.remove('hidden');
      if (searchTerm) highlight(card, searchTerm); else clearHighlight(card);
      visible++;
    } else {
      card.classList.add('hidden');
      clearHighlight(card);
      if (card.classList.contains('open')) {
        card.querySelector('.card-body').style.maxHeight='0';
        card.classList.remove('open');
      }
    }
  });
  document.getElementById('empty').style.display = visible===0 ? 'block':'none';
}

function highlight(card, term) {
  const els = card.querySelectorAll('.card-q, .resp-text');
  const re = new RegExp(`(${term.replace(/[.*+?^${}()|[\]\\]/g,'\\$&')})`,'gi');
  els.forEach(el => {
    if (!el._orig) el._orig = el.innerHTML;
    el.innerHTML = el._orig.replace(re,'<mark>$1</mark>');
  });
}
function clearHighlight(card) {
  card.querySelectorAll('.card-q, .resp-text').forEach(el => {
    if (el._orig) { el.innerHTML = el._orig; delete el._orig; }
  });
}

function toggleSort() {
  sortAsc = !sortAsc;
  document.getElementById('sortLabel').textContent = sortAsc ? 'Más reciente' : 'Más antigua';
  renderCards();
  applyFilters();
}

// ═══════════════════════════════════════════════════════════════════
//  HEATMAP rendering
// ═══════════════════════════════════════════════════════════════════
function renderHeatmap() {
  // Build a 7-row × 7-column grid: rows = days of week (Lun..Dom), cols = weeks
  // Week starts: Mon Mar 16, 23, 30, Apr 6, 13, 20, 27. Last week catches May 1-3
  const weekStarts = [
    new Date(2026,2,16), new Date(2026,2,23), new Date(2026,2,30),
    new Date(2026,3,6),  new Date(2026,3,13), new Date(2026,3,20),
    new Date(2026,3,27)
  ];

  // Count consultations per day
  const dayCount = {};
  CONSULTAS.forEach(c => {
    // parse "19 mar 2026" from c.date
    const m = c.date.match(/(\d+)\s+(\w+)\s+(\d+)/);
    if (!m) return;
    const months = { 'ene':0,'feb':1,'mar':2,'abr':3,'may':4,'jun':5 };
    const d = new Date(+m[3], months[m[2].slice(0,3).toLowerCase()], +m[1]);
    const key = d.toISOString().slice(0,10);
    dayCount[key] = (dayCount[key]||0)+1;
  });

  const dayNames = ['Lu','Ma','Mi','Ju','Vi','Sá','Do'];
  const monthHeader = weekStarts.map(d => {
    const month = d.toLocaleDateString('es',{ month:'short' }).replace('.','');
    return `<div style="font-size:9px;color:var(--t-3);text-align:center">${d.getDate()} ${month}</div>`;
  }).join('');

  let html = `<div style="display:grid;grid-template-columns:32px 1fr;gap:8px">
    <div></div>
    <div style="display:grid;grid-template-columns:repeat(${weekStarts.length},1fr);gap:3px;margin-bottom:6px">${monthHeader}</div>
    <div style="display:grid;grid-template-rows:repeat(7,1fr);gap:3px;font-size:9px;color:var(--t-3);text-align:right;align-items:center">
      ${dayNames.map(n=>`<div>${n}</div>`).join('')}
    </div>
    <div style="display:grid;grid-template-columns:repeat(${weekStarts.length},1fr);grid-template-rows:repeat(7,1fr);gap:3px">`;

  // For each week, for each day, output a cell
  for (let day = 0; day < 7; day++) {
    for (let week = 0; week < weekStarts.length; week++) {
      const d = new Date(weekStarts[week]);
      d.setDate(d.getDate() + day);
      const key = d.toISOString().slice(0,10);
      const cnt = dayCount[key] || 0;
      const lvl = Math.min(5, cnt);
      const dateStr = d.toLocaleDateString('es', { day:'numeric', month:'short' });
      const tip = cnt ? `${cnt} consulta${cnt>1?'s':''} · ${dateStr}` : `Sin consultas · ${dateStr}`;
      html += `<div class="heatmap-cell" data-count="${lvl}" title="${tip}" style="grid-row:${day+1};grid-column:${week+1}"></div>`;
    }
  }

  html += '</div></div>';
  document.getElementById('heatmap').innerHTML = html;
}

// ═══════════════════════════════════════════════════════════════════
//  DISTRIBUTION rendering
// ═══════════════════════════════════════════════════════════════════
function renderDistribution() {
  const counts = {};
  CONSULTAS.forEach(c => counts[c.cat] = (counts[c.cat]||0)+1);
  const max = Math.max(...Object.values(counts));
  const order = ['cic','2pp','1pp','tab','ent','exg','gen'];
  const list = document.getElementById('distList');
  list.innerHTML = order.filter(k=>counts[k]).map(k => {
    const c = counts[k];
    const dotClass = `dot-${k.replace('1pp','1pp').replace('2pp','2pp')}`;
    const barClass = `bar-${k}`;
    const pct = (c/max)*100;
    return `<div class="dist-row">
      <div class="dist-dot ${dotClass}"></div>
      <div>
        <div style="display:flex;justify-content:space-between;margin-bottom:4px;font-size:13px">
          <span style="color:var(--t-1)">${TAG_LABEL[k]}</span>
        </div>
        <div class="dist-bar-wrap"><div class="dist-bar ${barClass}" data-w="${pct}"></div></div>
      </div>
      <span>${c}</span>
    </div>`;
  }).join('');
  // animate bars
  setTimeout(()=>{ list.querySelectorAll('.dist-bar').forEach(b => b.style.width = b.dataset.w + '%'); }, 100);
}

// ═══════════════════════════════════════════════════════════════════
//  TABS
// ═══════════════════════════════════════════════════════════════════
function setupTabs() {
  document.querySelectorAll('.tab').forEach(tab => {
    tab.addEventListener('click', () => switchTab(tab.dataset.panel));
  });
}
function switchTab(name) {
  document.querySelectorAll('.tab').forEach(t => t.classList.toggle('active', t.dataset.panel===name));
  document.querySelectorAll('.panel').forEach(p => p.classList.toggle('active', p.id==='panel-'+name));
  // re-render distribution when switching to inicio (animation)
  if (name==='inicio') {
    setTimeout(()=>{ document.querySelectorAll('.dist-bar').forEach(b => b.style.width = b.dataset.w + '%'); }, 50);
  }
  if (name==='consultas') updateProgress();
}

// ═══════════════════════════════════════════════════════════════════
//  THEME
// ═══════════════════════════════════════════════════════════════════
function loadTheme() {
  const saved = localStorage.getItem(LS.theme) || 'dark';
  document.body.setAttribute('data-theme', saved);
  document.getElementById('iconMoon').style.display = saved==='dark' ? '' : 'none';
  document.getElementById('iconSun').style.display  = saved==='dark' ? 'none' : '';
}
function toggleTheme() {
  const cur = document.body.getAttribute('data-theme') || 'dark';
  const next = cur==='dark' ? 'light' : 'dark';
  document.body.setAttribute('data-theme', next);
  localStorage.setItem(LS.theme, next);
  document.getElementById('iconMoon').style.display = next==='dark' ? '' : 'none';
  document.getElementById('iconSun').style.display  = next==='dark' ? 'none' : '';
}

// ═══════════════════════════════════════════════════════════════════
//  COUNTERS animation
// ═══════════════════════════════════════════════════════════════════
function animateCounters() {
  document.querySelectorAll('[data-counter]').forEach(el => {
    const target = +el.dataset.counter;
    const dur = 900;
    const t0 = performance.now();
    function step(t) {
      const p = Math.min(1, (t - t0) / dur);
      const eased = 1 - Math.pow(1-p, 3);
      el.textContent = Math.round(target * eased);
      if (p < 1) requestAnimationFrame(step);
    }
    requestAnimationFrame(step);
  });
}

// ═══════════════════════════════════════════════════════════════════
//  KATEX rendering
// ═══════════════════════════════════════════════════════════════════
function renderKatex() {
  if (typeof katex === 'undefined') { setTimeout(renderKatex, 200); return; }
  document.querySelectorAll('.katex-eq').forEach(el => {
    if (el._katexed) return;
    try {
      katex.render(el.textContent, el, { throwOnError:false, displayMode:true });
      el._katexed = true;
    } catch(e) {
      // fallback: keep text
    }
  });
}

// ═══════════════════════════════════════════════════════════════════
//  DIAGRAMS · interactivity
// ═══════════════════════════════════════════════════════════════════
function setupDiagrams() {
  // ── P-v polytropic toggle ──
  const pvBtns = document.querySelectorAll('#panel-diagramas .diag-card:nth-of-type(2) .diag-toggle');
  const pvExpl = document.getElementById('pvExpl');
  const pvExplains = {
    'all':   'En todas las politrópicas el calor específico C permanece constante. El área bajo cada curva representa el trabajo de expansión <span class="formula-inline">W = ∫ P·dv</span>. Para la <strong>adiabática</strong>, además, vale <span class="formula-inline">P·v<sup>k</sup> = cte</span>.',
    'iso-p': '<strong>Isóbara (P = cte):</strong> trabajo de expansión <span class="formula-inline">W = P·ΔV</span>. Para gas ideal: <span class="formula-inline">ΔU = Cv·ΔT</span>, <span class="formula-inline">Q = ΔH = Cp·ΔT</span>.',
    'iso-v': '<strong>Isócora (v = cte):</strong> sin trabajo de expansión, <span class="formula-inline">W = 0</span>. Todo el calor entregado va a aumentar U: <span class="formula-inline">Q = ΔU = Cv·ΔT</span>.',
    'iso-t': '<strong>Isoterma (T = cte):</strong> para gas ideal, <span class="formula-inline">ΔU = ΔH = 0</span>, así que <span class="formula-inline">Q = W = R·T·ln(v₂/v₁)</span>.',
    'adiab': '<strong>Adiabática (Q = 0):</strong> <span class="formula-inline">P·v<sup>k</sup> = cte</span>, con k = Cp/Cv. Más empinada que la isoterma. <span class="formula-inline">W = −ΔU = −Cv·ΔT</span>.'
  };
  pvBtns.forEach(btn => {
    btn.addEventListener('click', () => {
      pvBtns.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');
      const proc = btn.dataset.proc;
      const svg = document.getElementById('svgPv');
      svg.querySelectorAll('.svg-curve, [class*="curve-"]').forEach(el => {
        el.classList.remove('dim','highlight');
        if (proc !== 'all' && el.getAttribute('data-proc') !== proc) el.classList.add('dim');
        if (proc !== 'all' && el.getAttribute('data-proc') === proc) el.classList.add('highlight');
      });
      pvExpl.innerHTML = pvExplains[proc];
    });
  });

  // ── Carnot step toggle ──
  const carBtns = document.querySelectorAll('#panel-diagramas .diag-card:nth-of-type(3) .diag-toggle');
  const carExpl = document.getElementById('carnotExpl');
  const carExplains = {
    'all': 'El <strong>área del rectángulo</strong> en T-s es el trabajo neto del ciclo. La eficiencia es <span class="formula-inline">η = 1 − T<sub>L</sub>/T<sub>H</sub></span>: depende solo de las temperaturas absolutas de los focos.',
    '12':  '<strong>1→2 · Expansión isotérmica a T<sub>H</sub>:</strong> el sistema recibe Q<sub>H</sub> de la fuente caliente. Como T es constante en gas ideal, <span class="formula-inline">ΔU = 0</span> y <span class="formula-inline">Q<sub>H</sub> = W</span>. La entropía aumenta.',
    '23':  '<strong>2→3 · Expansión adiabática reversible (isoentrópica):</strong> sin intercambio de calor, el sistema sigue produciendo trabajo a expensas de su energía interna. La temperatura cae de T<sub>H</sub> a T<sub>L</sub>. <span class="formula-inline">ΔS = 0</span>.',
    '34':  '<strong>3→4 · Compresión isotérmica a T<sub>L</sub>:</strong> el sistema cede Q<sub>L</sub> a la fuente fría. Se necesita trabajo de compresión. La entropía disminuye exactamente lo mismo que aumentó en 1→2.',
    '41':  '<strong>4→1 · Compresión adiabática reversible:</strong> sin intercambio de calor, se comprime el sistema hasta llevar T de T<sub>L</sub> a T<sub>H</sub>. Cierra el ciclo. <span class="formula-inline">ΔS = 0</span>.'
  };
  carBtns.forEach(btn => {
    btn.addEventListener('click', () => {
      carBtns.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');
      const step = btn.dataset.step;
      const svg = document.getElementById('svgCarnot');
      svg.querySelectorAll('.svg-curve, [data-step]').forEach(el => {
        if (el.tagName==='text') {
          if (step==='all') el.style.opacity = 1;
          else el.style.opacity = el.getAttribute('data-step')===step ? 1 : 0.18;
        } else {
          el.classList.remove('dim','highlight');
          if (step!=='all' && el.getAttribute('data-step')!==step) el.classList.add('dim');
          if (step!=='all' && el.getAttribute('data-step')===step) el.classList.add('highlight');
        }
      });
      // Net work area visibility
      const area = document.getElementById('netWorkArea');
      const lab = document.getElementById('netWorkLabel');
      if (step==='all') { area.style.opacity = 1; lab.style.opacity = 1; }
      else { area.style.opacity = 0.25; lab.style.opacity = 0.4; }
      carExpl.innerHTML = carExplains[step];
    });
  });

  // ── Saturation region ──
  const satBtns = document.querySelectorAll('#panel-diagramas .diag-card:nth-of-type(5) .diag-toggle');
  const satExpl = document.getElementById('satExpl');
  const satPositions = {
    'liq': { x:120, y:220, expl:'<strong>Líquido subenfriado</strong> (v &lt; v<sub>f</sub>): el fluido está completamente en fase líquida. Su temperatura es menor a la de saturación correspondiente a su presión. Las propiedades dependen poco de P y se aproximan por las de líquido saturado a la misma T.' },
    'mix': { x:280, y:240, expl:'<strong>Mezcla líquido-vapor</strong> (v<sub>f</sub> &lt; v &lt; v<sub>g</sub>): coexisten ambas fases en equilibrio. Definimos el título <span class="formula-inline">x = (v − v<sub>f</sub>) / (v<sub>g</sub> − v<sub>f</sub>)</span>, y cualquier propiedad se calcula como <span class="formula-inline">y = y<sub>f</sub> + x·(y<sub>g</sub> − y<sub>f</sub>)</span>.' },
    'vap': { x:490, y:220, expl:'<strong>Vapor sobrecalentado</strong> (v &gt; v<sub>g</sub>): solo hay fase vapor a una temperatura mayor a la de saturación. Las propiedades se obtienen de tablas de vapor sobrecalentado en función de P y T.' }
  };
  satBtns.forEach(btn => {
    btn.addEventListener('click', () => {
      satBtns.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');
      const region = btn.dataset.region;
      const pos = satPositions[region];
      const pt = document.getElementById('satPoint');
      pt.setAttribute('cx', pos.x);
      pt.setAttribute('cy', pos.y);
      satExpl.innerHTML = pos.expl;
    });
  });
}

// ═══════════════════════════════════════════════════════════════════
//  CALCULATORS
// ═══════════════════════════════════════════════════════════════════
function setupCalculators() {
  // ── Carnot ──
  const tH = document.getElementById('tHC');
  const tL = document.getElementById('tLC');
  function calcCarnot() {
    const TH = +tH.value, TL = +tL.value;
    const out = document.getElementById('carnotOut');
    const warn = document.getElementById('carnotWarn');
    const extra = document.getElementById('carnotExtra');
    if (!isFinite(TH) || !isFinite(TL) || TH<=0 || TL<=0) {
      out.innerHTML = '—'; warn.classList.remove('show');
      extra.textContent = 'Ingresá valores positivos en Kelvin';
      return;
    }
    if (TL >= TH) {
      out.innerHTML = '—';
      warn.classList.add('show');
      warn.innerHTML = '<strong>Atención:</strong> T<sub>L</sub> debe ser menor que T<sub>H</sub> para tener un ciclo de potencia.';
      extra.textContent = '';
      return;
    }
    const eta = 1 - TL/TH;
    out.innerHTML = `${eta.toFixed(3).replace('.',',')}<span class="calc-result-unit"> = ${(eta*100).toFixed(1).replace('.',',')} %</span>`;
    if (TH < 100 || TL < 100) {
      warn.classList.add('show');
      warn.innerHTML = '<strong>Atención:</strong> alguno de los valores parece estar en °C (T &lt; 100). El rendimiento de Carnot exige <strong>siempre</strong> Kelvin.';
    } else {
      warn.classList.remove('show');
    }
    extra.textContent = `η_máx teórico para esos focos · ningún ciclo real puede superarlo`;
  }
  [tH, tL].forEach(el => el.addEventListener('input', calcCarnot));
  calcCarnot();

  // ── Isoentrópica gas ideal ──
  const t1I = document.getElementById('t1I');
  const p1I = document.getElementById('p1I');
  const p2I = document.getElementById('p2I');
  const kI  = document.getElementById('kI');
  function calcIso() {
    const T1 = +t1I.value, P1 = +p1I.value, P2 = +p2I.value, k = +kI.value;
    const out = document.getElementById('isoOut');
    const extra = document.getElementById('isoExtra');
    if (!isFinite(T1) || !isFinite(P1) || !isFinite(P2) || !isFinite(k) || T1<=0 || P1<=0 || P2<=0 || k<=1) {
      out.innerHTML = '—'; extra.textContent = '';
      return;
    }
    const T2 = T1 * Math.pow(P2/P1, (k-1)/k);
    out.innerHTML = `${T2.toFixed(1).replace('.',',')}<span class="calc-result-unit"> K</span>`;
    const ratio = (P2/P1).toFixed(2).replace('.',',');
    const dT = (T2-T1).toFixed(1).replace('.',',');
    extra.innerHTML = `Relación de presiones: ${ratio} · ΔT = ${dT} K`;
  }
  [t1I, p1I, p2I, kI].forEach(el => el.addEventListener('input', calcIso));
  calcIso();

  // ── State identifier ──
  const vS = document.getElementById('vS');
  const vfS = document.getElementById('vfS');
  const vgS = document.getElementById('vgS');
  function calcState() {
    const v = +vS.value, vf = +vfS.value, vg = +vgS.value;
    const out = document.getElementById('stateOut');
    const lab = document.getElementById('stateLab');
    const extra = document.getElementById('stateExtra');
    if (!isFinite(v) || !isFinite(vf) || !isFinite(vg) || vf>=vg) {
      out.innerHTML = '—'; extra.textContent = 'Verificá v_f &lt; v_g';
      return;
    }
    if (v < vf) {
      out.innerHTML = 'Líquido subenfriado';
      lab.textContent = 'Estado · v < v_f';
      extra.innerHTML = `v está <strong style="color:var(--info)">${((vf-v)/vf*100).toFixed(1).replace('.',',')}%</strong> por debajo de v_f`;
    } else if (v > vg) {
      out.innerHTML = 'Vapor sobrecalentado';
      lab.textContent = 'Estado · v > v_g';
      extra.innerHTML = `v está <strong style="color:var(--warn)">${((v-vg)/vg*100).toFixed(1).replace('.',',')}%</strong> por encima de v_g`;
    } else {
      const x = (v - vf) / (vg - vf);
      out.innerHTML = 'Mezcla líquido-vapor';
      lab.textContent = 'Estado · v_f ≤ v ≤ v_g';
      extra.innerHTML = `Título <strong style="color:var(--a-2)">x = ${x.toFixed(4).replace('.',',')}</strong> · ${(x*100).toFixed(1).replace('.',',')}% vapor en masa`;
    }
  }
  [vS, vfS, vgS].forEach(el => el.addEventListener('input', calcState));
  calcState();

  // ── Linear interpolation ──
  const x1L = document.getElementById('x1L'), y1L = document.getElementById('y1L');
  const x2L = document.getElementById('x2L'), y2L = document.getElementById('y2L');
  const xT  = document.getElementById('xT');
  function calcLerp() {
    const x1 = +x1L.value, y1 = +y1L.value, x2 = +x2L.value, y2 = +y2L.value, x = +xT.value;
    const out = document.getElementById('lerpOut');
    const extra = document.getElementById('lerpExtra');
    if (!isFinite(x1)||!isFinite(y1)||!isFinite(x2)||!isFinite(y2)||!isFinite(x)||x1===x2) {
      out.innerHTML = '—'; extra.textContent = '';
      return;
    }
    const y = y1 + (y2 - y1) * (x - x1) / (x2 - x1);
    out.innerHTML = y.toFixed(2).replace('.',',');
    const pos = ((x - x1) / (x2 - x1)) * 100;
    let warn = '';
    if (pos < 0 || pos > 100) warn = ' · <span style="color:var(--warn)">⚠ extrapolación</span>';
    extra.innerHTML = `Posición proporcional: ${pos.toFixed(1).replace('.',',')}%${warn}`;
  }
  [x1L,y1L,x2L,y2L,xT].forEach(el => el.addEventListener('input', calcLerp));
  calcLerp();
}

// ═══════════════════════════════════════════════════════════════════
//  JUMPS · from theory pills, concept map, insight cards
// ═══════════════════════════════════════════════════════════════════
function setupJumps() {
  // Jump to specific consulta number
  document.querySelectorAll('[data-jump]').forEach(el => {
    el.addEventListener('click', e => {
      e.preventDefault();
      const n = +el.dataset.jump;
      switchTab('consultas');
      setTimeout(() => {
        // Reset filter
        activeFilter = 'all';
        bookmarkOnly = false;
        document.querySelectorAll('.filter-btn').forEach(b => b.classList.toggle('active', b.dataset.cat==='all'));
        searchTerm = '';
        document.getElementById('search').value = '';
        applyFilters();
        // Find and open
        const card = document.querySelector(`[data-id="${n}"]`);
        if (card) {
          card.scrollIntoView({ behavior:'smooth', block:'center' });
          if (!card.classList.contains('open')) toggleCard(card);
          card.style.transition = 'box-shadow 0.4s';
          card.style.boxShadow = '0 0 0 2px var(--a)';
          setTimeout(() => card.style.boxShadow = '', 1800);
        }
      }, 300);
    });
  });

  // Concept map → filter by category
  document.querySelectorAll('.map-node').forEach(node => {
    node.style.cursor = 'pointer';
    node.addEventListener('click', () => {
      const cat = node.dataset.jumpCat;
      switchTab('consultas');
      setTimeout(() => {
        activeFilter = cat;
        bookmarkOnly = false;
        document.querySelectorAll('.filter-btn').forEach(b => b.classList.toggle('active', b.dataset.cat===cat));
        searchTerm = '';
        document.getElementById('search').value = '';
        applyFilters();
      }, 300);
    });
  });
}

// ═══════════════════════════════════════════════════════════════════
//  FILTER button setup
// ═══════════════════════════════════════════════════════════════════
function setupFilters() {
  document.querySelectorAll('.filter-btn').forEach(btn => {
    btn.addEventListener('click', () => {
      if (btn.dataset.special === 'bookmarked') {
        bookmarkOnly = !bookmarkOnly;
        btn.classList.toggle('active', bookmarkOnly);
      } else {
        activeFilter = btn.dataset.cat;
        bookmarkOnly = false;
        document.querySelectorAll('.filter-btn').forEach(b => {
          if (!b.dataset.special) b.classList.toggle('active', b===btn);
          else b.classList.remove('active');
        });
      }
      applyFilters();
    });
  });
}

// ═══════════════════════════════════════════════════════════════════
//  SEARCH
// ═══════════════════════════════════════════════════════════════════
function setupSearch() {
  const search = document.getElementById('search');
  search.addEventListener('input', () => {
    searchTerm = search.value.toLowerCase().trim();
    applyFilters();
  });
}

// ═══════════════════════════════════════════════════════════════════
//  KEYBOARD shortcuts
// ═══════════════════════════════════════════════════════════════════
function setupKeyboard() {
  document.addEventListener('keydown', e => {
    if ((e.metaKey || e.ctrlKey) && e.key === 'k') {
      e.preventDefault();
      switchTab('consultas');
      setTimeout(() => document.getElementById('search').focus(), 100);
    }
    if (e.key === 'Escape') {
      const search = document.getElementById('search');
      if (document.activeElement === search) {
        search.value = '';
        searchTerm = '';
        applyFilters();
        search.blur();
      }
    }
    // Number keys 1-6 to switch tabs
    if (!e.metaKey && !e.ctrlKey && !e.altKey && document.activeElement.tagName !== 'INPUT') {
      const tabs = ['inicio','consultas','teoria','diagramas','calc','mapa'];
      const idx = +e.key - 1;
      if (idx >= 0 && idx < tabs.length) switchTab(tabs[idx]);
    }
  });
}

// ═══════════════════════════════════════════════════════════════════
//  INIT
// ═══════════════════════════════════════════════════════════════════
function init() {
  loadTheme();
  renderCards();
  renderHeatmap();
  renderDistribution();
  setupTabs();
  setupFilters();
  setupSearch();
  setupCalculators();
  setupDiagrams();
  setupJumps();
  setupKeyboard();
  updateBookmarkUI();
  updateProgress();
  applyFilters();
  animateCounters();
  setTimeout(renderKatex, 100);
  // re-trigger distribution animation when first viewing
  setTimeout(()=>{ document.querySelectorAll('.dist-bar').forEach(b => b.style.width = b.dataset.w + '%'); }, 200);
}

if (document.readyState === 'loading') {
  document.addEventListener('DOMContentLoaded', init);
} else {
  init();
}
</script>
