<html lang="kk">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Бағдаршам тест ойыны</title>
<style>
  :root{
    --bg:#3785a3;
    --card:#161a2b;
    --muted:#9aa3b2;
    --green:#22c55e;
    --red:#ef4444;
    --yellow:#f59e0b;
    --border:#22263b;
  }
  *{box-sizing:border-box}
  html,body{height:100%}
  body{
    margin:0;
    font-family: system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
    background: radial-gradient(1200px 700px at 70% -10%, #1b1f36 0%, var(--bg) 60%);
    color:#e7eaf3;
    display:flex;
    min-height:100svh;
    align-items:center;
    justify-content:center;
    padding:24px;
    position:relative;
    overflow:hidden;
  }

  /* Жаяу жүргіншілер жолы фон ретінде */
  .crosswalk{
    position:absolute; left:50%; transform:translateX(-50%) skewX(-8deg);
    bottom:-10vh; width:130vw; height:48vh; opacity:.18; pointer-events:none;
    background:
      repeating-linear-gradient(
        90deg,
        rgba(255,255,255,0.85) 0 36px,
        transparent 36px 86px
      );
    filter: blur(2px) saturate(60%);
  }

  .app{
    width:min(1200px, 100%);
    display:grid;
    grid-template-columns: 380px 1fr;
    gap:24px;
    position:relative;
    z-index:1;
  }
  @media (max-width:980px){
    .app{grid-template-columns: 1fr}
  }

  .panel{
    background:linear-gradient(180deg, #1d2140, #14182c);
    border:1px solid var(--border);
    border-radius:18px;
    padding:18px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:12px;
    box-shadow: 0 10px 30px rgba(0,0,0,.35);
  }
  .score{
    font-weight:800;
    font-size:clamp(20px, 2.4vw, 26px);
  }
  .hint{
    color:var(--muted);
    font-size:clamp(14px, 1.6vw, 16px);
    margin-top:6px;
  }

  /* Бағдаршам */
  .stage{
    background:linear-gradient(180deg, #121528, #0c0f1f);
    border:1px solid var(--border);
    border-radius:18px;
    padding:22px;
    display:flex;
    align-items:center;
    justify-content:center;
    box-shadow: 0 20px 40px rgba(0,0,0,.45);
  }
  .traffic{
    width:230px;
    background:#0b0f1e;
    border:2px solid #1f2442;
    border-radius:24px;
    padding:18px;
    position:relative;
  }
  .traffic::after{
    content:"";
    position:absolute;
    left:50%; transform:translateX(-50%);
    bottom:-20px;
    width:28px; height:110px;
    background:#0b0f1e;
    border:2px solid #1f2442;
    border-radius:8px;
  }
  .light{
    width:150px; height:150px;
    margin:12px auto;
    border-radius:50%;
    border:3px solid #222849;
    display:grid;
    place-items:center;
    cursor:pointer;
    user-select:none;
    position:relative;
  }
  .bulb{
    width:88%;
    height:88%;
    border-radius:50%;
    filter:saturate(120%);
    box-shadow: inset 0 0 22px rgba(0,0,0,.5);
    animation: breathe 2.2s ease-in-out infinite;
  }
  .light.red    { box-shadow: 0 0 35px 10px rgba(239,68,68,.45), inset 0 0 22px rgba(0,0,0,.6); }
  .light.yellow { box-shadow: 0 0 35px 10px rgba(245,158,11,.45), inset 0 0 22px rgba(0,0,0,.6); }
  .light.green  { box-shadow: 0 0 35px 10px rgba(34,197,94,.45), inset 0 0 22px rgba(0,0,0,.6); }

  .light.red    .bulb{ background: radial-gradient(60% 60% at 40% 35%, #ff7070, #b91c1c 70%); }
  .light.yellow .bulb{ background: radial-gradient(60% 60% at 40% 35%, #ffd166, #b45309 70%); }
  .light.green  .bulb{ background: radial-gradient(60% 60% at 40% 35%, #6ee7b7, #15803d 70%); }

  @keyframes breathe {
    0%,100%{ filter:brightness(1); transform:scale(1) }
    50%{ filter:brightness(1.08); transform:scale(1.01) }
  }

  /* Сұрақ картасы */
  .card{
    background:linear-gradient(180deg, #161a2b, #101427);
    border:1px solid var(--border);
    border-radius:18px;
    padding:22px;
    box-shadow: 0 16px 36px rgba(0,0,0,.4);
    min-height:360px;
    display:flex;
    flex-direction:column;
    gap:16px;
  }
  .q-header{ display:flex; justify-content:space-between; }
  .q-idx{ padding:8px 12px; border:1px solid #263055; border-radius:999px; background:#0e1330; }
  .question{ font-size:clamp(24px, 3vw, 30px); font-weight:800; }
  .options{ display:grid; gap:12px; }
  .btn{
    display:flex; gap:12px; align-items:center;
    border:1px solid #2a3057; border-radius:14px;
    padding:16px; cursor:pointer;
    font-size:clamp(18px, 2.2vw, 20px);
    background:#0d1230; color:#e8eaf4;
  }
  .btn .tag{ width:34px; height:34px; border-radius:9px; display:grid; place-items:center; }
  .btn.correct{ border-color:#22c55e; background:rgba(34,197,94,.15) }
  .btn.wrong{ border-color:#ef4444; background:rgba(239,68,68,.15) }
  .footer{ margin-top:auto; display:flex; justify-content:space-between; }
  .done{ text-align:center; padding:26px; }
  .big{ font-size:clamp(28px, 3.5vw, 36px); font-weight:900; }
  .again{ margin-top:16px; padding:14px 16px; border-radius:14px; cursor:pointer; background:#0f1538; color:#fff; }
</style>
</head>
<body>
  <div class="crosswalk"></div>
  <main class="app">
    <section class="stage">
      <div class="traffic">
        <button class="light red" id="redBtn"><div class="bulb"></div></button>
        <button class="light yellow" id="yelBtn"><div class="bulb"></div></button>
        <button class="light green" id="grnBtn"><div class="bulb"></div></button>
      </div>
    </section>
    <section>
      <div class="panel">
        <div>
          <div class="score" id="score">Ұпай: 0</div>
          <div class="hint" id="hint">Келесі сұрақ үшін бағдаршамның кез келген көзін басыңыз.</div>
        </div>
        <span id="progress">0 / 10</span>
      </div>
      <div class="card" id="card">
        <div id="welcome">
          <div class="big">Қауіпсіздік тесті</div>
          <p>Бағдаршам көзін басқанда сұрақ шығады. Әр дұрыс жауапқа +2 балл қосылады.</p>
        </div>
      </div>
    </section>
  </main>

<script>
const QUESTIONS = [
  {q:"Жаяу жүргіншілер жолымен қалай жүру керек?",options:{A:"Оң жақ шетімен, көлік бағытымен",B:"Сол жақ жиегімен, көлікке қарсы бағытта",C:"Жол ортасымен",D:"Кез келген жағымен"},correct:"B"},
  {q:"Реттелетін жаяу жүргінші өткелінен қашан өтеміз?",options:{A:"Сары жанғанда",B:"Қызыл жанғанда көлік жоқ болса",C:"Жасыл жанғанда",D:"Кез келген түсте, егер асықсаң"},correct:"C"},
  {q:"Жолдан өтер алдындағы бірінші қадам қандай?",options:{A:"Оңға қарау",B:"Телефонды қалтаға салу",C:"Тоқтап, алдымен солға қарау",D:"Жүгіріп өте шығу"},correct:"C"},
  {q:"«Фликер» (шағылыстырғыш) не үшін керек?",options:{A:"Велосипедтің жылдамдығын арттыру үшін",B:"Қараңғыда көрінуді жақсарту үшін",C:"Телефон қуатын жинау үшін",D:"Дулығаны алмастыру үшін"},correct:"B"},
  {q:"Велосипедпен жаяу аймақта қалай қозғалу керек?",options:{A:"Қалыпты жылдамдықта айдай беру",B:"Қатты жылдамдықпен өтіп кету",C:"Велосипедті жаяу жетектеп өту",D:"Құлаққаппен жүрсе болады"},correct:"C"},
  {q:"Велосипедші үшін қауіпсіз жабдыққа жатпайды:",options:{A:"Дулыға",B:"Алдыңғы/артқы жарық",C:"Шағылыстырғыш элементтер",D:"Биік өкшелі аяқ киім"},correct:"D"},
  {q:"Электросамокат мінгенде нені жасауға болмайды?",options:{A:"Жеке жүру",B:"Жолаушы мінгізу",C:"Веложолақпен жүру",D:"Жаяу жүргіншілерге жол беру"},correct:"B"},
  {q:"Қоғамдық көлікке мінгенде ең дұрыс әрекет:",options:{A:"Есіктің алдына тұрып, итеріліп кіру",B:"Салонда тұтқадан ұстау",C:"Терезеден бас шығару",D:"Есіктер жабылғанда секіріп түсу"},correct:"B"},
  {q:"Жол қиылысында велосипедші бұрыларын қалай білдіреді?",options:{A:"Дауыстап айқайлау",B:"Телефон шамын жағу",C:"Қолымен белгі беру",D:"Құлаққапты шешу"},correct:"C"},
  {q:"«Қауіпті сигналға» қайсысы жатады?",options:{A:"Көпшілік жерде бағыт-бағдар сұрау",B:"«Ешкімге айтпа» деп сыйлық ұсыну",C:"Өтпеден жасыл жанғанда өту",D:"Досыңмен бірге жүру"},correct:"B"}
];

let idx=-1, score=0, answered=true;
const total=QUESTIONS.length;
const card=document.getElementById('card');
const scoreEl=document.getElementById('score');
const hintEl=document.getElementById('hint');
const progressEl=document.getElementById('progress');
const redBtn=document.getElementById('redBtn'), yelBtn=document.getElementById('yelBtn'), grnBtn=document.getElementById('grnBtn');

function updateHUD(){scoreEl.textContent=`Ұпай: ${score}`;progressEl.textContent=`${Math.min(idx+1,total)} / ${total}`;}
function renderQuestion(qObj){
  card.innerHTML='';
  const q=document.createElement('div');q.className='question';q.textContent=qObj.q;card.appendChild(q);
  const opts=document.createElement('div');opts.className='options';card.appendChild(opts);
  Object.entries(qObj.options).forEach(([k,t])=>{
    const btn=document.createElement('button');btn.className='btn';btn.setAttribute('data-key',k);btn.innerHTML=`<span class="tag">${k}</span>${t}`;
    btn.onclick=()=>handleAnswer(btn,qObj.correct,opts);opts.appendChild(btn);
  });
}
function handleAnswer(btn,correctKey,container){
  if(answered)return;
  [...container.children].forEach(b=>b.disabled=true);
  if(btn.getAttribute('data-key')===correctKey){btn.classList.add('correct');score+=2;}else{btn.classList.add('wrong');container.querySelector(`[data-key=${correctKey}]`).classList.add('correct');}
  answered=true;updateHUD();
  if(idx===total-1)setTimeout(showFinal,400);
}
function nextQuestion(){
  if(idx>=total-1&&answered)return;
  if(!answered){hintEl.textContent="Алдымен жауап беріңіз";return;}
  idx++;renderQuestion(QUESTIONS[idx]);answered=false;updateHUD();
}
function showFinal(){card.innerHTML=`<div class="done"><div class="big">Тест аяқталды! 🎉</div><p>Ұпай: ${score} / ${total*2}</p><button class="again" onclick="resetGame()">Қайта бастау</button></div>`;}
function resetGame(){idx=-1;score=0;answered=true;updateHUD();card.innerHTML='<div class="big">Қауіпсіздік тесті</div><p>Бағдаршамды басып бастаңыз</p>';}
[redBtn,yelBtn,grnBtn].forEach(b=>b.onclick=nextQuestion);
updateHUD();
</script>
</body>
</html>
