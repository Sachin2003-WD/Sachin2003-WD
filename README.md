# 👋 Hey, I'm Sachin Kudatini  

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=8A2BE2&center=true&vCenter=true&width=500&lines=Web+Developer+%7C+AI+Learner;Frontend+Developer+%7C+Anime+Enthusiast" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Sachin2003-WD&label=Profile+Views&color=8A2BE2&style=flat-square" alt="Profile Views" />
</p>

---

## 💫 About Me  

- 🚀 Building: **Mentoring System**, **Browzify**  
- 🧠 Focused on: **AI**, **Streamlit**, **Cloud**, and **Full Stack Development**  
- 🎬 Anime Enthusiast — *Naruto*, *Death Note*, *Solo Leveling*, *Demon Slayer*  
- 📫 Reach me at: **cksachin94@gmail.com**  
- 💼 Connect: [LinkedIn](https://www.linkedin.com/in/sachin-c-k-991005280/)

---

## ⚙️ Tech Stack  

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,python,streamlit,git,github" />
</p>

---

## 📊 GitHub Stats  

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=Sachin2003-WD&show_icons=true&theme=tokyonight&hide_border=true" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=Sachin2003-WD&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sachin2003-WD&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

## 🚀 Highlight Projects  

| Project | Description | Tech Stack |
|----------|--------------|-------------|
| [🧠 **MindMate**](https://github.com/Sachin2003-WD/MindMate) | AI-powered mental wellness companion | GPT, Streamlit, TTS |
| [📄 **GenAI Resume Builder**](https://github.com/Sachin2003-WD/GenAI-Resume-Builder) | Smart resume builder with PDF export | OpenAI, Streamlit |
| [💊 **GPT Medicine Assistant**](https://github.com/Sachin2003-WD/GPT-Medicine-Assistant) | Medicine analyzer from strip or name | OCR, TTS, QR, PDF |

---

## 🏆 Trophies & Snake Game  

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Sachin2003-WD&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=6" />
</p>

<p align="center">
  <img src="https://github.com/Sachin2003-WD/Sachin2003-WD/blob/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</p>

---

## 🌐 Connect with Me  

<p align="center">
  <a href="https://www.linkedin.com/in/sachin-c-k-991005280/"><img src="https://skillicons.dev/icons?i=linkedin" /></a>
  <a href="mailto:cksachin94@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" /></a>
  <a href="https://x.com/SachinCK52651"><img src="https://skillicons.dev/icons?i=twitter" /></a>
  <a href="https://www.facebook.com/Sachin+k"><img src="https://skillicons.dev/icons?i=facebook" /></a>
</p>

---

## ✨ Daily Quote  

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />
</p>
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Snake in a Box — Sachin</title>
<style>
  :root{
    --bg:#0b1020;
    --card:#0f1724;
    --accent1:#7c4dff; /* purple */
    --accent2:#36a3ff; /* blue */
    --muted:#94a3b8;
  }
  *{box-sizing:border-box}
  html,body{height:100%}
  body{
    margin:0;
    font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    background: linear-gradient(180deg,#061021 0%, #071026 100%);
    color:#e6eef8;
    display:flex;
    align-items:center;
    justify-content:center;
    padding:24px;
  }

  .wrap{
    width:min(720px, 96vw);
    display:grid;
    grid-template-columns: 1fr 260px;
    gap:20px;
    align-items:start;
  }

  /* Box (game area) */
  .box{
    background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
    border-radius:12px;
    padding:18px;
    box-shadow: 0 6px 18px rgba(2,6,23,0.6);
    display:flex;
    flex-direction:column;
    gap:12px;
  }
  .card-title{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:8px;
  }
  h1{font-size:18px;margin:0}
  small{color:var(--muted)}

  .game-viewport{
    background:linear-gradient(90deg, rgba(124,77,255,0.06), rgba(54,163,255,0.03));
    border-radius:10px;
    padding:12px;
    display:flex;
    justify-content:center;
    align-items:center;
    border: 1px solid rgba(255,255,255,0.04);
  }

  canvas{
    background: #04102a;
    width:100%;
    height:auto;
    max-width:640px;
    border-radius:6px;
    display:block;
    box-shadow: inset 0 1px 0 rgba(255,255,255,0.02);
  }

  /* Sidebar */
  .panel{
    background: linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.005));
    border-radius:12px;
    padding:16px;
  }

  .stat{
    display:flex;
    justify-content:space-between;
    gap:8px;
    margin:8px 0;
    font-weight:600;
  }

  .controls{
    display:flex;
    gap:8px;
    flex-wrap:wrap;
    margin-top:10px;
  }

  button{
    background: linear-gradient(90deg,var(--accent1),var(--accent2));
    color:white;
    border:0;
    padding:8px 12px;
    border-radius:8px;
    cursor:pointer;
    font-weight:600;
    transition:transform .12s ease,opacity .12s;
  }
  button.secondary{
    background:transparent;
    border:1px solid rgba(255,255,255,0.06);
    color:var(--muted);
    font-weight:600;
  }
  button:active{transform:translateY(1px)}
  .hint{font-size:13px;color:var(--muted);margin-top:8px}

  /* responsive */
  @media (max-width:880px){
    .wrap{grid-template-columns:1fr;align-items:center}
    .panel{order:2;width:100%}
  }
</style>
</head>
<body>
  <div class="wrap">
    <div class="box">
      <div class="card-title">
        <div>
          <h1>Snake in a Box</h1>
          <small>Use arrows / WASD — or swipe on mobile</small>
        </div>
        <div id="scoreDisplay" style="text-align:right">
          <div style="font-weight:700">Score: <span id="score">0</span></div>
          <small id="high">High: 0</small>
        </div>
      </div>

      <div class="game-viewport">
        <!-- canvas will scale to width; internal resolution managed by script -->
        <canvas id="game"></canvas>
      </div>

      <div style="display:flex;gap:8px;justify-content:space-between;align-items:center">
        <div class="hint">Made for README / quick demos — clean, minimal, responsive.</div>
        <div style="display:flex;gap:8px">
          <button id="btnPause">Pause</button>
          <button id="btnRestart" class="secondary">Restart</button>
        </div>
      </div>
    </div>

    <div class="panel">
      <div style="font-size:14px;font-weight:700">Settings</div>

      <div class="stat"><span>Speed</span><span id="speedVal">8</span></div>
      <input id="speed" type="range" min="4" max="18" value="8" style="width:100%">

      <div class="stat"><span>Grid Size</span><span id="gridVal">20</span></div>
      <input id="grid" type="range" min="12" max="32" value="20" style="width:100%">

      <div style="margin-top:12px">
        <div class="stat"><span>Theme</span><span id="themeName">Purple / Blue</span></div>
        <div style="display:flex;gap:8px;margin-top:8px">
          <button id="themeBtn" class="secondary">Toggle Theme</button>
        </div>
      </div>

      <hr style="border:none;border-top:1px solid rgba(255,255,255,0.03);margin:12px 0">

      <div style="font-size:13px;color:var(--muted)">
        Controls:
        <ul>
          <li>Arrow keys / W A S D</li>
          <li>On mobile: swipe inside the game area</li>
          <li>Pause with <strong>P</strong></li>
        </ul>
      </div>
    </div>
  </div>

<script>
/*
  Simple Snake Game (canvas) — Clean & responsive
  Features:
  - Grid-based movement, keyboard + swipe controls
  - Speed & grid size adjustable
  - Pause / Restart, Score & High score (localStorage)
*/

(() => {
  const canvas = document.getElementById('game');
  const ctx = canvas.getContext('2d', { alpha: false });
  const scoreEl = document.getElementById('score');
  const highEl = document.getElementById('high');
  const speedInput = document.getElementById('speed');
  const gridInput = document.getElementById('grid');
  const speedVal = document.getElementById('speedVal');
  const gridVal = document.getElementById('gridVal');
  const btnPause = document.getElementById('btnPause');
  const btnRestart = document.getElementById('btnRestart');
  const themeBtn = document.getElementById('themeBtn');

  let W = 600, H = 600;                 // internal canvas resolution (kept square)
  let grid = parseInt(gridInput.value); // cells per row/col
  let cell = Math.floor(W / grid);
  let speed = parseInt(speedInput.value); // frames per second-ish (game loop tick)
  let delta = 0, lastTime = 0, interval = 1000 / speed;
  let dir = { x: 1, y: 0 }; // start moving right
  let snake = [];
  let food = null;
  let running = true;
  let score = 0;
  let highScore = parseInt(localStorage.getItem('snake_high') || '0');

  highEl.textContent = 'High: ' + highScore;
  scoreEl.textContent = score;
  speedVal.textContent = speed;
  gridVal.textContent = grid;

  // resize canvas to match layout width while keeping internal resolution
  function resizeCanvas(){
    const parent = canvas.parentElement;
    const width = Math.min(parent.clientWidth - 24, 640);
    canvas.style.width = width + 'px';
    canvas.style.height = width + 'px';
    canvas.width = W;
    canvas.height = H;
    cell = Math.floor(W / grid);
  }

  // init/reset
  function reset(){
    grid = parseInt(gridInput.value);
    speed = parseInt(speedInput.value);
    cell = Math.floor(W / grid);
    interval = 1000 / speed;
    dir = { x: 1, y: 0 };
    snake = [{ x: Math.floor(grid/2), y: Math.floor(grid/2) }];
    placeFood();
    score = 0;
    running = true;
    scoreEl.textContent = score;
    speedVal.textContent = speed;
    gridVal.textContent = grid;
    btnPause.textContent = 'Pause';
  }

  function placeFood(){
    // ensure food not on snake
    let tries=0;
    while(true){
      const candidate = { x: Math.floor(Math.random()*grid), y: Math.floor(Math.random()*grid) };
      if(!snake.some(s=>s.x===candidate.x && s.y===candidate.y)) { food = candidate; break; }
      if(++tries>1000) break;
    }
  }

  function draw(){
    // background
    ctx.fillStyle = '#04102a';
    ctx.fillRect(0,0,W,H);

    // grid lines (subtle)
    ctx.strokeStyle = 'rgba(255,255,255,0.02)';
    ctx.lineWidth = 1;
    for(let i=0;i<=grid;i++){
      const pos = i*cell + 0.5;
      ctx.beginPath(); ctx.moveTo(pos,0); ctx.lineTo(pos,H); ctx.stroke();
      ctx.beginPath(); ctx.moveTo(0,pos); ctx.lineTo(W,pos); ctx.stroke();
    }

    // food
    if(food){
      const fx = food.x*cell, fy = food.y*cell;
      const pad = Math.max(2, Math.floor(cell*0.12));
      const radius = Math.max(2, Math.floor(cell*0.36));
      // outer glow
      ctx.fillStyle = 'rgba(54,163,255,0.12)';
      ctx.fillRect(fx+pad-2, fy+pad-2, cell-2*pad+4, cell-2*pad+4);
      ctx.fillStyle = 'rgb(54,163,255)';
      roundRect(ctx, fx+pad, fy+pad, cell-2*pad, cell-2*pad, radius, true, false);
    }

    // snake body
    for(let i=0;i<snake.length;i++){
      const s = snake[i];
      const x = s.x*cell, y = s.y*cell;
      const r = Math.max(3, Math.floor(cell*0.18));
      // head highlight
      if(i===0){
        // gradient for head
        const g = ctx.createLinearGradient(x, y, x+cell, y+cell);
        g.addColorStop(0, '#b99dff');
        g.addColorStop(1, '#70c9ff');
        ctx.fillStyle = g;
        roundRect(ctx, x+2, y+2, cell-4, cell-4, r, true, false);
      } else {
        ctx.fillStyle = '#8eaed5';
        roundRect(ctx, x+2, y+2, cell-4, cell-4, r, true, false);
      }
      // subtle segment border
      ctx.strokeStyle = 'rgba(2,6,23,0.3)';
      ctx.lineWidth = 1;
      roundRect(ctx, x+2, y+2, cell-4, cell-4, r, false, true);
    }
  }

  // Helper: rounded rect
  function roundRect(ctx, x, y, w, h, r, fill, stroke) {
    if (typeof r === 'undefined') r = 5;
    ctx.beginPath();
    ctx.moveTo(x + r, y);
    ctx.arcTo(x + w, y, x + w, y + h, r);
    ctx.arcTo(x + w, y + h, x, y + h, r);
    ctx.arcTo(x, y + h, x, y, r);
    ctx.arcTo(x, y, x + w, y, r);
    ctx.closePath();
    if (fill) ctx.fill();
    if (stroke) ctx.stroke();
  }

  function step(){
    // compute next head
    const head = { x: (snake[0].x + dir.x + grid) % grid, y: (snake[0].y + dir.y + grid) % grid };
    // check collision with self
    if(snake.some((s,i)=>i>0 && s.x===head.x && s.y===head.y)){
      // game over
      running = false;
      btnPause.textContent = 'Game Over';
      if(score>highScore){ highScore = score; localStorage.setItem('snake_high', highScore); highEl.textContent='High: '+highScore; }
      return;
    }
    snake.unshift(head);

    // eat
    if(food && head.x===food.x && head.y===food.y){
      score++;
      scoreEl.textContent = score;
      placeFood();
    } else {
      snake.pop();
    }
  }

  function gameLoop(ts){
    if(!lastTime) lastTime = ts;
    delta += ts - lastTime;
    lastTime = ts;

    if(running && delta > interval){
      // run one game tick
      step();
      delta = 0;
    }
    draw();
    requestAnimationFrame(gameLoop);
  }

  // input handling
  const keyMap = {
    ArrowUp: {x:0,y:-1}, ArrowDown: {x:0,y:1}, ArrowLeft: {x:-1,y:0}, ArrowRight: {x:1,y:0},
    w: {x:0,y:-1}, s:{x:0,y:1}, a:{x:-1,y:0}, d:{x:1,y:0},
    W: {x:0,y:-1}, S:{x:0,y:1}, A:{x:-1,y:0}, D:{x:1,y:0}
  };

  function setDir(newDir){
    // prevent reverse
    if(newDir.x === -dir.x && newDir.y === -dir.y) return;
    dir = newDir;
  }

  window.addEventListener('keydown', e=>{
    if(e.key === 'p' || e.key === 'P'){
      running = !running;
      btnPause.textContent = running ? 'Pause' : 'Resume';
      return;
    }
    const mapped = keyMap[e.key];
    if(mapped) setDir(mapped);
  });

  // touch / swipe detection for mobile
  let touchStart = null;
  canvas.addEventListener('touchstart', e=>{
    const t = e.touches[0];
    touchStart = { x: t.clientX, y: t.clientY };
  }, { passive: true });
  canvas.addEventListener('touchend', e=>{
    if(!touchStart) return;
    const t = e.changedTouches[0];
    const dx = t.clientX - touchStart.x;
    const dy = t.clientY - touchStart.y;
    const absX = Math.abs(dx), absY = Math.abs(dy);
    if(Math.max(absX, absY) < 20){ touchStart = null; return; } // tap
    if(absX > absY){
      setDir({ x: dx>0 ? 1 : -1, y:0 });
    } else {
      setDir({ x:0, y: dy>0 ? 1 : -1 });
    }
    touchStart = null;
  }, { passive: true });

  btnPause.addEventListener('click', ()=>{
    running = !running;
    btnPause.textContent = running ? 'Pause' : 'Resume';
  });
  btnRestart.addEventListener('click', ()=>reset());

  // settings listeners
  speedInput.addEventListener('input', ()=>{
    speed = parseInt(speedInput.value);
    interval = 1000 / speed;
    speedVal.textContent = speed;
  });
  gridInput.addEventListener('input', ()=>{
    grid = parseInt(gridInput.value);
    gridVal.textContent = grid;
    reset();
    resizeCanvas();
  });

  // simple theme toggle (swap accent colors)
  let alt = false;
  themeBtn.addEventListener('click', ()=>{
    alt = !alt;
    document.documentElement.style.setProperty('--accent1', alt ? '#36a3ff' : '#7c4dff');
    document.documentElement.style.setProperty('--accent2', alt ? '#7c4dff' : '#36a3ff');
    document.getElementById('themeName').textContent = alt ? 'Blue / Purple' : 'Purple / Blue';
  });

  // prevent instant reverse when switching direction too fast: buffer next dir
  // (optional improvement) -- for simplicity it's not included here

  // initialize and start
  function init(){
    resizeCanvas();
    window.addEventListener('resize', resizeCanvas);
    reset();
    requestAnimationFrame(gameLoop);
  }
  init();
})();
</script>
</body>
</html>
