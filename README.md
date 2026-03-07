
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chúc Mừng Ngày 8/3 💐</title>
<meta name="author" content="HaiHuy — độc quyền, không sao chép">
<meta name="signature" content="HH-83-2026-✦">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Nunito:wght@300;400;500&family=Dancing+Script:wght@400;700&display=swap" rel="stylesheet">
<style>
*, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

body {
  min-height: 100vh;
  background: #0d0a14;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: 'Nunito', sans-serif;
  overflow: hidden;
  position: relative;
}

.bg {
  position: fixed;
  inset: 0;
  background:
    radial-gradient(ellipse 70% 50% at 50% 0%, #2d1040 0%, transparent 60%),
    radial-gradient(ellipse 50% 40% at 0% 100%, #1a0a2e 0%, transparent 50%),
    radial-gradient(ellipse 60% 50% at 100% 80%, #200d35 0%, transparent 55%),
    #0d0a14;
  z-index: 0;
}

.orb {
  position: fixed;
  border-radius: 50%;
  filter: blur(80px);
  pointer-events: none;
  z-index: 1;
}
.orb1 {
  width: 400px; height: 400px;
  background: radial-gradient(circle, rgba(220,80,120,0.18) 0%, transparent 70%);
  top: -100px; left: -100px;
  animation: orbFloat 8s ease-in-out infinite;
}
.orb2 {
  width: 350px; height: 350px;
  background: radial-gradient(circle, rgba(150,60,200,0.14) 0%, transparent 70%);
  bottom: -80px; right: -80px;
  animation: orbFloat 10s ease-in-out infinite reverse;
}
.orb3 {
  width: 250px; height: 250px;
  background: radial-gradient(circle, rgba(255,150,180,0.1) 0%, transparent 70%);
  top: 50%; left: 50%;
  transform: translate(-50%, -50%);
  animation: orbFloat 12s ease-in-out infinite 2s;
}
@keyframes orbFloat {
  0%, 100% { transform: translate(0, 0); }
  33% { transform: translate(30px, -20px); }
  66% { transform: translate(-20px, 25px); }
}

#stars {
  position: fixed;
  inset: 0;
  z-index: 1;
}

.content {
  position: relative;
  z-index: 10;
  text-align: center;
  padding: 40px 24px;
  max-width: 520px;
  width: 100%;
  animation: fadeUp 1.2s cubic-bezier(0.16, 1, 0.3, 1) both;
}

@keyframes fadeUp {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}

.eyebrow {
  font-size: 0.68rem;
  letter-spacing: 0.35em;
  text-transform: uppercase;
  color: rgba(255,160,190,0.6);
  margin-bottom: 40px;
  animation: fadeUp 1s 0.2s both;
}

.rose-icon {
  font-size: 2.8rem;
  display: block;
  margin-bottom: 24px;
  animation: roseFloat 3s ease-in-out infinite;
  filter: drop-shadow(0 0 20px rgba(255,100,140,0.5));
}
@keyframes roseFloat {
  0%, 100% { transform: translateY(0) rotate(-3deg); }
  50% { transform: translateY(-10px) rotate(3deg); }
}

.date-wrap {
  margin-bottom: 8px;
  animation: fadeUp 1s 0.3s both;
}

.date {
  font-family: 'Dancing Script', cursive;
  font-size: clamp(5rem, 18vw, 8.5rem);
  font-weight: 700;
  line-height: 0.9;
  color: transparent;
  background: linear-gradient(160deg, #ff9ab8 0%, #e8476a 40%, #c0305a 70%, #ff7fab 100%);
  -webkit-background-clip: text;
  background-clip: text;
  letter-spacing: 2px;
  filter: drop-shadow(0 0 40px rgba(232,71,106,0.4));
}

.line-deco {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 16px;
  margin: 28px auto;
  animation: fadeUp 1s 0.5s both;
}
.line-deco::before, .line-deco::after {
  content: '';
  width: 80px;
  height: 1px;
  background: linear-gradient(to right, transparent, rgba(255,150,180,0.4));
}
.line-deco::after {
  background: linear-gradient(to left, transparent, rgba(255,150,180,0.4));
}
.line-deco span {
  color: rgba(255,160,190,0.7);
  font-size: 1rem;
  letter-spacing: 6px;
}

.message {
  font-size: 1.05rem;
  line-height: 2;
  color: rgba(255,230,240,0.75);
  font-weight: 300;
  margin-bottom: 48px;
  animation: fadeUp 1s 0.6s both;
}

.message em {
  font-style: normal;
  color: #ffb3cc;
  font-weight: 400;
}

.footer-line {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 12px;
  animation: fadeUp 1s 0.8s both;
}

.dot {
  width: 4px; height: 4px;
  border-radius: 50%;
  background: rgba(255,150,180,0.4);
}

.footer-text {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: 0.95rem;
  color: rgba(255,160,190,0.45);
  letter-spacing: 0.08em;
}

/* Splash screen */
#splash {
  position: fixed;
  inset: 0;
  z-index: 999;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  background:
    radial-gradient(ellipse 70% 50% at 50% 0%, #2d1040 0%, transparent 60%),
    radial-gradient(ellipse 50% 40% at 0% 100%, #1a0a2e 0%, transparent 50%),
    #0d0a14;
  transition: opacity 1.2s ease;
}
#splash.hide {
  opacity: 0;
  pointer-events: none;
  transition: opacity 1.6s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Petal burst canvas */
#petalCanvas {
  position: fixed;
  inset: 0;
  z-index: 998;
  pointer-events: none;
  opacity: 0;
  transition: opacity 0.3s ease;
}
#petalCanvas.active { opacity: 1; }

.flower-wrap {
  position: relative;
  width: 260px;
  height: 260px;
  margin-bottom: 44px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.flower-wrap svg {
  width: 100%;
  height: 100%;
  overflow: visible;
  display: block;
}

.rose-group {
  transform-origin: 130px 130px;
  animation: roseBreath 4s ease-in-out infinite;
}
@keyframes roseBreath {
  0%, 100% { transform: scale(1) rotate(0deg); }
  50% { transform: scale(1.05) rotate(3deg); }
}

.flower-wrap.blooming .rose-group {
  animation: bloomExpand 1.4s cubic-bezier(0.22, 1, 0.36, 1) forwards;
}
@keyframes bloomExpand {
  0%   { transform: scale(1)   rotate(0deg);  opacity: 1; }
  30%  { transform: scale(1.4) rotate(8deg);  opacity: 1; }
  65%  { transform: scale(4.5) rotate(22deg); opacity: 0.7; }
  100% { transform: scale(28)  rotate(38deg); opacity: 0; }
}

.flower-glow {
  position: absolute;
  inset: -40px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(220,60,100,0.3) 0%, transparent 65%);
  animation: glowPulse 3s ease-in-out infinite;
  pointer-events: none;
}
@keyframes glowPulse {
  0%, 100% { transform: scale(1); opacity: 0.6; }
  50% { transform: scale(1.2); opacity: 1; }
}

.splash-btn {
  font-family: 'Nunito', sans-serif;
  font-size: 0.75rem;
  letter-spacing: 0.3em;
  text-transform: uppercase;
  color: rgba(255,160,190,0.6);
  border: 1px solid rgba(255,150,180,0.3);
  padding: 12px 28px;
  border-radius: 100px;
  background: transparent;
  cursor: pointer;
  animation: splashPulse 2s ease-in-out infinite;
  transition: opacity 0.4s;
}
.splash-btn.hide { opacity: 0; pointer-events: none; }
@keyframes splashPulse {
  0%, 100% { opacity: 0.6; transform: scale(1); }
  50% { opacity: 1; transform: scale(1.04); }
}
#musicBtn {
  position: fixed;
  bottom: 24px;
  right: 24px;
  z-index: 100;
  width: 44px;
  height: 44px;
  border-radius: 50%;
  border: 1px solid rgba(255,150,180,0.3);
  background: rgba(255,255,255,0.05);
  backdrop-filter: blur(10px);
  color: rgba(255,160,190,0.7);
  font-size: 1.1rem;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: all 0.3s ease;
}
#musicBtn:hover {
  border-color: rgba(255,150,180,0.6);
  background: rgba(255,150,180,0.1);
  color: #ffb3cc;
}
#musicBtn.playing {
  border-color: rgba(255,150,180,0.6);
  box-shadow: 0 0 16px rgba(232,71,106,0.3);
  animation: pulse 2s ease-in-out infinite;
}
@keyframes pulse {
  0%, 100% { box-shadow: 0 0 12px rgba(232,71,106,0.3); }
  50% { box-shadow: 0 0 24px rgba(232,71,106,0.5); }
}

.apology {
  margin-top: 20px;
  font-size: 0.78rem;
  line-height: 1.8;
  color: rgba(255, 180, 200, 0.3);
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  letter-spacing: 0.04em;
  animation: fadeUp 1s 1s both;
  transition: color 0.4s ease;
}
.apology:hover {
  color: rgba(255, 180, 200, 0.65);
}

.watermark {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%) rotate(-25deg);
  font-family: 'Dancing Script', cursive;
  font-size: clamp(4rem, 14vw, 7rem);
  font-weight: 700;
  color: rgba(255, 150, 180, 0.14);
  pointer-events: none;
  z-index: 2;
  white-space: nowrap;
  letter-spacing: 8px;
  user-select: none;
}

.shoot {
  position: fixed;
  width: 2px;
  height: 2px;
  background: white;
  border-radius: 50%;
  z-index: 5;
  pointer-events: none;
}
.shoot::after {
  content: '';
  position: absolute;
  top: 50%;
  right: 0;
  transform: translateY(-50%);
  width: 80px;
  height: 1px;
  background: linear-gradient(to left, rgba(255,255,255,0.8), transparent);
}
</style>
</head>
<body>

<div class="bg"></div>
<div class="orb orb1"></div>
<div class="orb orb2"></div>
<div class="orb orb3"></div>
<canvas id="stars"></canvas>

<canvas id="petalCanvas"></canvas>

<div id="splash">
  <div class="flower-wrap" id="flowerWrap">
    <div class="flower-glow"></div>
    <canvas id="roseCanvas" width="260" height="260"></canvas>
  </div>
  <button class="splash-btn" id="splashBtn">✦ Nhấn để vào ✦</button>
</div>

<button id="musicBtn" title="Bật/tắt nhạc">🔊</button>

<div class="watermark">HaiHuy</div>

<div class="content">
  <div class="eyebrow">✦ Ngày Quốc Tế Phụ Nữ ✦</div>
  <span class="rose-icon">🌹</span>
  <div class="date-wrap">
    <div class="date">8/3</div>
  </div>
  <div class="line-deco"><span>✦ ✦ ✦</span></div>
  <p class="message">
    Không cần phải hoàn hảo, chỉ cần mỗi ngày đều tiến lên một bước nhỏ.<br>
    Chúc <em>cô</em> và các <em>bạn nữ</em> luôn vững vàng trước mọi thử thách,<br>
    học thêm thật nhiều điều hay, làm được nhiều điều ý nghĩa,<br>
    và luôn tin tưởng vào sức mạnh tuyệt vời của chính mình. 🌸
  </p>
  <div class="footer-line">
    <div class="dot"></div>
    <div class="footer-text">Lời chúc từ <em style="font-style:normal; color: #ffb3cc;">HaiHuy</em></div>
    <div class="dot"></div>
  </div>

  <p class="apology">
    Nếu lời chúc còn vụng về hay chưa đủ hay —<br>
    mong cô và các bạn bỏ qua cho nhé 🌷
  </p>
</div>

<script>
const canvas = document.getElementById('stars');
const ctx = canvas.getContext('2d');
canvas.width = window.innerWidth;
canvas.height = window.innerHeight;

const stars = Array.from({length: 200}, () => ({
  x: Math.random() * canvas.width,
  y: Math.random() * canvas.height,
  r: Math.random() * 1.4 + 0.2,
  speed: Math.random() * 0.008 + 0.003,
  phase: Math.random() * Math.PI * 2
}));

function drawStars(t) {
  ctx.clearRect(0, 0, canvas.width, canvas.height);
  stars.forEach(s => {
    const alpha = 0.3 + 0.5 * Math.sin(t * s.speed * 60 + s.phase);
    ctx.beginPath();
    ctx.arc(s.x, s.y, s.r, 0, Math.PI * 2);
    ctx.fillStyle = `rgba(255,220,235,${alpha})`;
    ctx.fill();
  });
}

let last = 0;
function loop(t) {
  drawStars((t - last) / 1000 + last / 1000);
  last = t;
  requestAnimationFrame(loop);
}
requestAnimationFrame(loop);

window.addEventListener('resize', () => {
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
});

function shootingStar() {
  const el = document.createElement('div');
  el.className = 'shoot';
  const startX = Math.random() * window.innerWidth * 0.6 + window.innerWidth * 0.1;
  const startY = Math.random() * window.innerHeight * 0.4;
  el.style.left = startX + 'px';
  el.style.top = startY + 'px';
  document.body.appendChild(el);
  const dist = 200 + Math.random() * 150;
  el.animate([
    { transform: 'translate(0,0)', opacity: 1 },
    { transform: `translate(${dist * 0.87}px, ${dist * 0.5}px)`, opacity: 0 }
  ], { duration: 700 + Math.random() * 400, easing: 'ease-out', fill: 'forwards' })
  .onfinish = () => el.remove();
}

setInterval(shootingStar, 3000);
setTimeout(shootingStar, 1000);

// ── Ambient music via Web Audio API ──
let audioCtx = null, playing = false, nodes = [];

function createMusic() {
  audioCtx = new (window.AudioContext || window.webkitAudioContext)();
  const master = audioCtx.createGain();
  master.gain.setValueAtTime(0, audioCtx.currentTime);
  master.gain.linearRampToValueAtTime(0.5, audioCtx.currentTime + 2.5);
  master.connect(audioCtx.destination);

  // Reverb
  const reverb = audioCtx.createConvolver();
  const rl = audioCtx.sampleRate * 4;
  const rb = audioCtx.createBuffer(2, rl, audioCtx.sampleRate);
  for (let c = 0; c < 2; c++) {
    const d = rb.getChannelData(c);
    for (let i = 0; i < rl; i++) d[i] = (Math.random()*2-1) * Math.pow(1 - i/rl, 1.6);
  }
  reverb.buffer = rb;
  const revGain = audioCtx.createGain(); revGain.gain.value = 0.38;
  reverb.connect(revGain); revGain.connect(master);
  const dry = audioCtx.createGain(); dry.gain.value = 0.62; dry.connect(master);

  // ── PIANO NOTE ──
  // Piano: sine + triangle blend, sharp attack, natural exponential decay
  function piano(freq, t, dur, vol = 0.18) {
    // Fundamental
    const o1 = audioCtx.createOscillator();
    const o2 = audioCtx.createOscillator();
    const o3 = audioCtx.createOscillator();
    const env = audioCtx.createGain();

    o1.type = 'sine';     o1.frequency.value = freq;
    o2.type = 'triangle'; o2.frequency.value = freq * 2;
    o3.type = 'sine';     o3.frequency.value = freq * 3;

    const g2 = audioCtx.createGain(); g2.gain.value = 0.25;
    const g3 = audioCtx.createGain(); g3.gain.value = 0.08;

    o1.connect(env); 
    o2.connect(g2); g2.connect(env);
    o3.connect(g3); g3.connect(env);

    // Piano envelope: instant attack, long natural decay
    env.gain.setValueAtTime(0, t);
    env.gain.linearRampToValueAtTime(vol, t + 0.01);
    env.gain.exponentialRampToValueAtTime(vol * 0.6, t + 0.12);
    env.gain.exponentialRampToValueAtTime(vol * 0.15, t + dur * 0.7);
    env.gain.exponentialRampToValueAtTime(0.0001, t + dur + 0.3);

    env.connect(dry); env.connect(reverb);
    [o1,o2,o3].forEach(o => { o.start(t); o.stop(t + dur + 0.5); nodes.push(o); });
  }

  // ── SAXOPHONE NOTE ──
  // Sax: sawtooth → bandpass filter chain → breathiness via noise
  function sax(freq, t, dur, vol = 0.14) {
    const osc = audioCtx.createOscillator();
    osc.type = 'sawtooth';
    osc.frequency.value = freq;

    // Vibrato
    const vib = audioCtx.createOscillator();
    const vibG = audioCtx.createGain();
    vib.frequency.value = 5.8;
    vibG.gain.value = freq * 0.012;
    vib.connect(vibG); vibG.connect(osc.frequency);

    // Warm bandpass — key to sax tone
    const bp = audioCtx.createBiquadFilter();
    bp.type = 'bandpass';
    bp.frequency.value = freq * 1.8;
    bp.Q.value = 1.2;

    // Second resonance
    const bp2 = audioCtx.createBiquadFilter();
    bp2.type = 'bandpass';
    bp2.frequency.value = freq * 3.2;
    bp2.Q.value = 2.0;
    const bp2G = audioCtx.createGain(); bp2G.gain.value = 0.3;

    // Breathiness (noise layer)
    const noise = audioCtx.createOscillator();
    noise.type = 'sawtooth';
    noise.frequency.value = freq * 0.997; // slight detune for breathiness
    const noiseG = audioCtx.createGain(); noiseG.gain.value = 0.06;
    const noiseLP = audioCtx.createBiquadFilter();
    noiseLP.type = 'lowpass'; noiseLP.frequency.value = freq * 2.5;

    const env = audioCtx.createGain();
    // Sax envelope: soft attack, long sustain, smooth release
    env.gain.setValueAtTime(0, t);
    env.gain.linearRampToValueAtTime(vol, t + 0.18);
    env.gain.setValueAtTime(vol * 0.88, t + dur * 0.5);
    env.gain.linearRampToValueAtTime(0, t + dur + 0.28);

    osc.connect(bp); bp.connect(env);
    osc.connect(bp2); bp2.connect(bp2G); bp2G.connect(env);
    noise.connect(noiseLP); noiseLP.connect(noiseG); noiseG.connect(env);
    env.connect(dry); env.connect(reverb);

    [osc, vib, noise].forEach(o => { o.start(t); o.stop(t + dur + 0.5); nodes.push(o); });
  }

  const C3=130.81, D3=146.83, E3=164.81, F3=174.61, G3=196, A3=220, B3=246.94;
  const C4=261.63, D4=293.66, E4=329.63, F4=349.23, G4=392, A4=440, B4=493.88;
  const C5=523.25, D5=587.33, E5=659.25, F5=698.46, G5=783.99;

  const beat = 0.58;

  function playPhrase(o) {
    // ── Piano: left hand chords (soft, background) ──
    const pianoChords = [
      { t: o+ 0*beat, n: [C3,G3,C4,E4],    d: 8 },
      { t: o+ 8*beat, n: [A3,E3,A3,C4],    d: 4 },
      { t: o+12*beat, n: [F3,C3,F3,A3],    d: 4 },
      { t: o+16*beat, n: [G3,D3,G3,B3],    d: 4 },
      { t: o+20*beat, n: [C3,G3,C4,E4],    d: 4 },
      { t: o+24*beat, n: [F3,C3,F3,A3],    d: 4 },
      { t: o+28*beat, n: [G3,D3,G3,B3],    d: 4 },
      { t: o+32*beat, n: [C3,G3,C4,E4],    d: 8 },
    ];
    pianoChords.forEach(c => c.n.forEach(f => piano(f, c.t, c.d * beat * 0.9, 0.13)));

    // ── Piano: right hand melody fill (gentle, between sax phrases) ──
    const pianoMelody = [
      [E4, 1], [G4, 1], [C5, 2], [B4, 1], [A4, 1],
      [G4, 2], [E4, 2],
    ];
    let pt = o + 2 * beat;
    pianoMelody.forEach(([f, d]) => {
      piano(f, pt, d * beat * 0.82, 0.16);
      pt += d * beat;
    });

    // ── Saxophone: lead melody — slow, expressive, romantic ──
    const saxMelody = [
      [E5, 3], [D5, 1], [C5, 2], [B4, 2],
      [A4, 3], [G4, 1], [A4, 2], [C5, 2],
      [E5, 2], [F5, 1], [E5, 1], [D5, 3], [C5, 1],
      [B4, 2], [A4, 2], [G4, 4],
      [C5, 3], [D5, 1], [E5, 2], [G5, 2],
      [F5, 2], [E5, 2], [D5, 4],
      [A4, 2], [C5, 2], [E5, 2], [D5, 2],
      [C5, 6],
    ];
    let st = o;
    saxMelody.forEach(([f, d]) => {
      sax(f, st, d * beat * 0.92, 0.17);
      st += d * beat;
    });

    return o + 40 * beat;
  }

  let next = playPhrase(audioCtx.currentTime + 0.6);
  const loop = setInterval(() => {
    next = playPhrase(next - 0.2);
  }, 40 * beat * 1000 - 200);

  nodes.push({ stop: () => {
    clearInterval(loop);
    master.gain.linearRampToValueAtTime(0, audioCtx.currentTime + 2.5);
  }});
}

// ── Draw realistic rose on canvas ──
(function drawRose() {
  const rc = document.getElementById('roseCanvas');
  const rx = rc.getContext('2d');
  const cx = 130, cy = 130;

  // Draw one rose petal: round top, wide base, naturally cupped
  // ox,oy = origin (base), pointing upward, rotated by `angle`
  function drawRosePetal(ctx, ox, oy, width, height, angle, fillColor, shadowColor, alpha) {
    ctx.save();
    ctx.globalAlpha = alpha;
    ctx.translate(ox, oy);
    ctx.rotate(angle);

    // Petal shape: flat base, rounded sides, gently rounded top
    ctx.beginPath();
    ctx.moveTo(0, 0);
    // left side curve out then round top
    ctx.bezierCurveTo(-width * 0.9, -height * 0.2, -width * 0.85, -height * 0.75, 0, -height);
    // right side symmetric
    ctx.bezierCurveTo( width * 0.85, -height * 0.75,  width * 0.9, -height * 0.2, 0, 0);
    ctx.closePath();

    // Gradient from tip (light) to base (dark)
    const grad = ctx.createLinearGradient(0, -height, 0, 0);
    grad.addColorStop(0,   fillColor[0]);
    grad.addColorStop(0.5, fillColor[1]);
    grad.addColorStop(1,   fillColor[2]);
    ctx.fillStyle = grad;
    ctx.shadowColor = shadowColor;
    ctx.shadowBlur = 10;
    ctx.fill();

    // Soft vein line down center
    ctx.beginPath();
    ctx.moveTo(0, -height * 0.1);
    ctx.quadraticCurveTo(width * 0.05, -height * 0.55, 0, -height * 0.92);
    ctx.strokeStyle = 'rgba(255,255,255,0.07)';
    ctx.lineWidth = 1.2;
    ctx.stroke();

    // Edge highlight (rim light)
    ctx.beginPath();
    ctx.moveTo(0, 0);
    ctx.bezierCurveTo(-width * 0.9, -height * 0.2, -width * 0.85, -height * 0.75, 0, -height);
    ctx.strokeStyle = 'rgba(255,200,215,0.20)';
    ctx.lineWidth = 1;
    ctx.stroke();

    ctx.restore();
  }

  // Petal color sets [tip, mid, base]
  const outerColor  = ['#ffb8c8', '#d44060', '#6a0e20'];
  const midColor    = ['#f0a0b5', '#c03055', '#580c1c'];
  const innerColor  = ['#e08898', '#b02848', '#480a18'];
  const coreColor   = ['#d07080', '#982040', '#3a0810'];
  const budColor    = ['#c06070', '#801830', '#2e0608'];

  // Layer 0 — outermost 5 big petals, spread wide
  for (let i = 0; i < 5; i++) {
    const a = (i / 5) * Math.PI * 2 - Math.PI / 2;
    const dist = 42;
    const ox = cx + Math.cos(a) * dist;
    const oy = cy + Math.sin(a) * dist;
    drawRosePetal(rx, ox, oy, 30, 74, a - Math.PI / 2, outerColor, 'rgba(80,0,20,0.4)', 0.85);
  }

  // Layer 1 — 5 petals offset, slightly smaller
  for (let i = 0; i < 5; i++) {
    const a = (i / 5) * Math.PI * 2 - Math.PI / 2 + Math.PI / 5;
    const dist = 30;
    const ox = cx + Math.cos(a) * dist;
    const oy = cy + Math.sin(a) * dist;
    drawRosePetal(rx, ox, oy, 24, 60, a - Math.PI / 2, midColor, 'rgba(70,0,15,0.4)', 0.90);
  }

  // Layer 2 — inner 5 petals, cupping inward
  for (let i = 0; i < 5; i++) {
    const a = (i / 5) * Math.PI * 2 - Math.PI / 2;
    const dist = 19;
    const ox = cx + Math.cos(a) * dist;
    const oy = cy + Math.sin(a) * dist;
    drawRosePetal(rx, ox, oy, 18, 46, a - Math.PI / 2, innerColor, 'rgba(60,0,12,0.4)', 0.94);
  }

  // Layer 3 — tight inner 5 petals
  for (let i = 0; i < 5; i++) {
    const a = (i / 5) * Math.PI * 2 + Math.PI / 5;
    const dist = 11;
    const ox = cx + Math.cos(a) * dist;
    const oy = cy + Math.sin(a) * dist;
    drawRosePetal(rx, ox, oy, 12, 30, a - Math.PI / 2, coreColor, 'rgba(50,0,10,0.5)', 0.96);
  }

  // Layer 4 — innermost bud 4 petals, nearly closed
  for (let i = 0; i < 4; i++) {
    const a = (i / 4) * Math.PI * 2 + Math.PI / 8;
    const dist = 5;
    const ox = cx + Math.cos(a) * dist;
    const oy = cy + Math.sin(a) * dist;
    drawRosePetal(rx, ox, oy, 7, 17, a - Math.PI / 2, budColor, 'rgba(40,0,8,0.6)', 0.97);
  }

  // Center dark bud
  const cg = rx.createRadialGradient(cx, cy, 0, cx, cy, 8);
  cg.addColorStop(0, '#200408');
  cg.addColorStop(1, '#0d0204');
  rx.beginPath();
  rx.arc(cx, cy, 7, 0, Math.PI * 2);
  rx.fillStyle = cg;
  rx.shadowBlur = 0;
  rx.fill();

})();

// Breathing animation for rose canvas
const roseCanvas = document.getElementById('roseCanvas');
let breathT = 0;
function breathe() {
  breathT += 0.018;
  const s = 1 + Math.sin(breathT) * 0.04;
  const r = Math.sin(breathT * 0.7) * 2;
  roseCanvas.style.transform = `scale(${s}) rotate(${r}deg)`;
  roseCanvas.style.transformOrigin = 'center';
  if (!roseCanvas.classList.contains('blooming-done')) {
    requestAnimationFrame(breathe);
  }
}
breathe();
const pc = document.getElementById('petalCanvas');
const pcx = pc.getContext('2d');
pc.width = window.innerWidth; pc.height = window.innerHeight;

function spawnPetals(cx, cy) {
  pc.classList.add('active');
  const petals = Array.from({length: 80}, (_, i) => {
    const angle = (Math.random() * Math.PI * 2);
    const speed = 2.5 + Math.random() * 6;
    const size  = 14 + Math.random() * 28;
    const rot   = Math.random() * Math.PI * 2;
    const rotSpeed = (Math.random() - 0.5) * 0.18;
    const colors = ['#e8476a','#ff7fab','#ffaac4','#c0305a','#ff9ab8','#ffd0df','#8a1030'];
    return {
      x: cx, y: cy,
      vx: Math.cos(angle) * speed,
      vy: Math.sin(angle) * speed - 3,
      size, rot, rotSpeed,
      color: colors[Math.floor(Math.random() * colors.length)],
      alpha: 1,
      gravity: 0.12 + Math.random() * 0.08,
      drag: 0.97
    };
  });

  let frame = 0;
  function draw() {
    pcx.clearRect(0, 0, pc.width, pc.height);
    let alive = false;
    petals.forEach(p => {
      if (p.alpha <= 0) return;
      alive = true;
      p.vx *= p.drag; p.vy *= p.drag;
      p.vy += p.gravity;
      p.x += p.vx; p.y += p.vy;
      p.rot += p.rotSpeed;
      p.alpha -= 0.012;

      pcx.save();
      pcx.globalAlpha = Math.max(0, p.alpha);
      pcx.translate(p.x, p.y);
      pcx.rotate(p.rot);
      // Draw petal shape
      pcx.beginPath();
      pcx.ellipse(0, 0, p.size * 0.4, p.size, 0, 0, Math.PI * 2);
      pcx.fillStyle = p.color;
      pcx.shadowColor = p.color;
      pcx.shadowBlur = 8;
      pcx.fill();
      pcx.restore();
    });
    frame++;
    if (alive && frame < 260) requestAnimationFrame(draw);
    else { pc.classList.remove('active'); }
  }
  requestAnimationFrame(draw);
}

// Splash screen → bloom → start music
const splash = document.getElementById('splash');
const flowerWrap = document.getElementById('flowerWrap');
const splashBtn = document.getElementById('splashBtn');

function triggerBloom() {
  splashBtn.classList.add('hide');
  startMusic();

  const rect = flowerWrap.getBoundingClientRect();
  const cx2 = rect.left + rect.width / 2;
  const cy2 = rect.top  + rect.height / 2;

  // Animate the rose canvas scaling up with JS for smoothness
  roseCanvas.classList.add('blooming-done');
  let prog = 0;
  const dur = 1400;
  const start = performance.now();

  function bloomAnim(now) {
    prog = Math.min((now - start) / dur, 1);
    // Ease: cubic-bezier-like
    const e = prog < 0.5
      ? 4 * prog * prog * prog
      : 1 - Math.pow(-2 * prog + 2, 3) / 2;

    const scale = 1 + e * 32;
    const rot   = e * 40;
    const alpha = prog < 0.5 ? 1 : 1 - ((prog - 0.5) * 2);

    roseCanvas.style.transform = `scale(${scale}) rotate(${rot}deg)`;
    roseCanvas.style.transformOrigin = 'center';
    roseCanvas.style.opacity = alpha;
    flowerWrap.style.opacity = alpha;

    if (prog < 0.3) setTimeout(() => spawnPetals(cx2, cy2), 0);

    if (prog < 1) {
      requestAnimationFrame(bloomAnim);
    } else {
      splash.classList.add('hide');
      setTimeout(() => splash.remove(), 1700);
    }
  }
  requestAnimationFrame(bloomAnim);
}

splashBtn.addEventListener('click', e => { e.stopPropagation(); triggerBloom(); });
splash.addEventListener('click', triggerBloom);

function startMusic() {
  if (playing) return;
  createMusic();
  playing = true;
  const btn = document.getElementById('musicBtn');
  btn.textContent = '🔊';
  btn.classList.add('playing');
}

document.getElementById('musicBtn').addEventListener('click', () => {
  const btn = document.getElementById('musicBtn');
  if (!playing) {
    startMusic();
  } else {
    nodes.forEach(n => { try { n.stop(); } catch(e){} });
    nodes = [];
    if (audioCtx) { audioCtx.close(); audioCtx = null; }
    playing = false;
    btn.textContent = '🎵';
    btn.classList.remove('playing');
  }
});
</script>
</body>
</html>
