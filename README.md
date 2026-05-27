<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>초등 영어 단어 정복</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.0/chart.umd.min.js"></script>
<style>
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:'Malgun Gothic',sans-serif;background:#F4F6F9;min-height:100vh;-webkit-tap-highlight-color: transparent;user-select: none;}
input{user-select: auto;}
.app{max-width:700px;margin:0 auto;padding:20px;}
.screen{display:none;}.screen.active{display:block; animation: fadeIn 0.3s ease-out;}
@keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }

.login-wrap{display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:80vh;text-align:center;}
.login-logo{font-size:56px;margin-bottom:10px;}
.login-title{font-size:24px;font-weight:800;color:#2D3436;margin-bottom:6px;}
.login-sub{font-size:14px;color:#636E72;margin-bottom:32px;}
.login-input{width:260px;padding:14px 18px;font-size:18px;text-align:center;border-radius:16px;border:2px solid #DFE6E9;background:#fff;color:#2D3436;outline:none;margin-bottom:12px;font-family:inherit;}
.login-input:focus{border-color:#00B894;}
.login-btn{width:260px;padding:14px;background:#00B894;color:#fff;border:none;border-radius:16px;font-size:16px;font-weight:700;cursor:pointer;font-family:inherit;}
.saved-users{margin-top:24px;width:280px;}
.saved-title{font-size:12px;color:#B2BEC3;margin-bottom:8px;font-weight:600;}
.saved-chip{display:inline-block;padding:6px 14px;background:#fff;border:1.5px solid #DFE6E9;border-radius:99px;font-size:13px;color:#636E72;cursor:pointer;margin:3px;}

.home-header{display:flex;align-items:center;justify-content:space-between;padding:16px 0 14px;}
.home-greeting{font-size:18px;font-weight:800;color:#2D3436;}
.home-greeting span{color:#00B894;}
.home-btns{display:flex;gap:8px;}
.icon-btn{width:36px;height:36px;border-radius:50%;border:1.5px solid #DFE6E9;background:#fff;cursor:pointer;display:flex;align-items:center;justify-content:center;}

.cat-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(130px,1fr));gap:10px;margin-top:4px;}
.cat-card{background:#fff;border:1.5px solid #E8EAED;border-radius:16px;padding:14px 10px;cursor:pointer;text-align:center;position:relative;transition:all 0.15s;}
.cat-card:hover{border-color:#00B894;transform:translateY(-2px);box-shadow:0 4px 12px rgba(0,184,148,0.12);}
.cat-icon{font-size:26px;margin-bottom:5px;}
.cat-name{font-size:12px;font-weight:700;}
.cat-prog{height:4px;background:#DFE6E9;border-radius:99px;margin-top:8px;overflow:hidden;}
.cat-prog-fill{height:100%;background:#00B894;border-radius:99px;}
.cat-badge{position:absolute;top:8px;right:8px;background:#00B894;color:#fff;font-size:10px;padding:2px 6px;border-radius:99px;}

.top-bar{display:flex;align-items:center;gap:10px;margin-bottom:12px;}
.back-btn{width:36px;height:36px;border-radius:50%;border:1.5px solid #DFE6E9;background:#fff;cursor:pointer;}
.top-title{font-size:15px;font-weight:700;flex:1;}
.prog-track{width:100%;height:7px;background:#DFE6E9;border-radius:99px;overflow:hidden;margin-bottom:14px;}
.prog-fill{height:100%;background:linear-gradient(90deg,#00B894,#00CEC9);transition:width 0.35s;}

.word-card{background:#fff;border-radius:20px;padding:28px 22px 24px;margin-bottom:14px;text-align:center;box-shadow:0 2px 12px rgba(0,0,0,0.06);}
.w-eng{font-size:44px;font-weight:800;color:#2D3436;}
.w-kor{font-size:26px;font-weight:700;color:#00B894;margin:14px 0 8px;}
.ex-box{background:#F8F9FA;border-left:4px solid #00B894;border-radius:10px;padding:12px 14px;text-align:left;flex:1;}
.btn-row{display:flex;gap:8px;}
.btn{flex:1;padding:13px;border-radius:12px;font-size:14px;font-weight:700;cursor:pointer;border:none;font-family:inherit;}
.btn-outline{background:#fff;border:1.5px solid #DFE6E9;color:#636E72;}
.btn-green{background:#00B894;color:#fff;}

.quiz-input{width:100%;padding:14px;font-size:18px;text-align:center;border-radius:12px;border:2px solid #DFE6E9;outline:none;}
.feedback{font-size:16px;font-weight:700;text-align:center;min-height:28px;margin:10px 0;}
.fb-ok{color:#00B894;}.fb-ng{color:#E17055;}

.stats-sect{background:#fff;border-radius:16px;padding:16px;margin-bottom:14px;}
.stat-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;}
.stat-box{background:#F8F9FA;border-radius:12px;padding:14px;text-align:center;}
.stat-num{font-size:24px;font-weight:800;}
.chart-wrap{height:190px;}
.hist-table{width:100%;border-collapse:collapse;font-size:13px;}
.hist-table td, .hist-table th{padding:8px;border-bottom:1px solid #F8F9FA;}

@media (max-width: 480px) {
    .app { padding: 12px; }
    .cat-grid { grid-template-columns: repeat(2, 1fr); }
    .w-eng { font-size: 36px; }
    .btn, .login-btn { padding: 16px; }
}
::-webkit-scrollbar { display: none; }
</style>
</head>
<body>
<div class="app">

<div id="sc-login" class="screen active">
  <div class="login-wrap">
    <div class="login-logo">🎯</div>
    <div class="login-title">초등 영어 단어 정복</div>
    <div class="login-sub">이름을 입력하고 시작하세요!</div>
    <input class="login-input" id="name-input" placeholder="이름 입력" maxlength="10" onkeydown="if(event.key==='Enter')loginUser()">
    <button class="login-btn" onclick="loginUser()">시작하기 →</button>
    <div class="saved-users" id="saved-users-wrap" style="display:none">
      <div class="saved-title">이전 학습자</div>
      <div id="saved-chips"></div>
    </div>
  </div>
</div>

<div id="sc-home" class="screen">
  <div class="home-header">
    <div class="home-greeting">안녕, <span id="greeting-name"></span>! 👋</div>
    <div class="home-btns">
      <button class="icon-btn" onclick="showStats()">📊</button>
      <button class="icon-btn" onclick="logout()">👤</button>
    </div>
  </div>
  <div class="cat-grid" id="cat-grid"></div>
</div>

<div id="sc-study" class="screen">
  <div class="top-bar">
    <button class="back-btn" onclick="goHome()">←</button>
    <div class="top-title" id="study-title"></div>
    <div class="top-info" id="study-info"></div>
  </div>
  <div class="prog-track"><div class="prog-fill" id="study-bar"></div></div>
  <div class="word-card">
    <div onclick="speak('w')" style="cursor:pointer">
      <span class="w-eng" id="s-eng-text"></span> 🔊
    </div>
    <div class="w-pho" id="s-pho" style="color:#B2BEC3; font-style:italic; margin:10px 0;"></div>
    <button class="btn btn-outline" onclick="revealStudy()">뜻 보기 👁</button>
    <div id="s-reveal" style="display:none; margin-top:20px;">
      <div class="w-kor" id="s-kor"></div>
      <div class="ex-box">
        <div id="s-ex-e" style="font-weight:bold;"></div>
        <div id="s-ex-k" style="font-size:0.9em; color:#636E72;"></div>
      </div>
    </div>
  </div>
  <div class="btn-row">
    <button class="btn btn-outline" id="btn-next" onclick="nextStudy()">다음 단어 →</button>
    <button class="btn btn-green" id="btn-qs" style="display:none" onclick="startQuiz()">퀴즈 시작 🔥</button>
  </div>
</div>

<div id="sc-quiz" class="screen">
  <div class="top-bar">
    <button class="back-btn" onclick="goHome()">←</button>
    <div class="top-title" id="quiz-title"></div>
  </div>
  <div class="prog-track"><div class="prog-fill" id="quiz-bar"></div></div>
  <div class="word-card">
    <div class="w-eng" id="q-eng" onclick="speakQuiz()" style="cursor:pointer"></div>
    <p style="margin:10px 0; color:#636E72;">이 단어의 뜻은?</p>
    <input class="quiz-input" id="q-input" placeholder="정답 입력" autocomplete="off" onkeydown="if(event.key==='Enter')checkQuiz()">
    <div class="feedback" id="q-fb"></div>
    <button class="btn btn-green" onclick="checkQuiz()">정답 확인</button>
  </div>
</div>

<div id="sc-result" class="screen">
  <div class="result-wrap" style="text-align:center; padding:20px 0;">
    <div id="r-emoji" style="font-size:60px;"></div>
    <h2 id="r-title"></h2>
    <div id="r-score" style="font-size:48px; font-weight:800; margin:20px 0;"></div>
    <div class="wrong-panel" id="r-wrong" style="display:none; text-align:left; background:#fff; padding:15px; border-radius:10px;">
      <h3 style="font-size:14px; color:#B2BEC3;">틀린 단어</h3>
      <div id="r-wrong-list"></div>
    </div>
    <div class="btn-row" style="margin-top:20px;">
      <button class="btn btn-outline" onclick="goHome()">홈으로</button>
      <button class="btn btn-green" onclick="showStats()">기록 보기</button>
    </div>
  </div>
</div>

<div id="sc-stats" class="screen">
  <div class="top-bar">
    <button class="back-btn" onclick="goHome()">←</button>
    <div class="top-title">📊 나의 기록</div>
  </div>
  <div class="stats-sect">
    <div class="stat-grid" id="stat-boxes"></div>
  </div>
  <div class="stats-sect">
    <div class="chart-wrap"><canvas id="score-chart"></canvas></div>
  </div>
  <div class="stats-sect" id="history-wrap"></div>
</div>

</div>

<script>
// 데이터 및 상태 관리
const CATS = [
  {id:"animals",name:"동물",icon:"🐾",words:[
    {e:"Cat",p:"[kæt]",k:"고양이",ee:"The cat is sleeping.",ek:"고양이가 자고 있어요."},
    {e:"Dog",p:"[dɔːɡ]",k:"강아지",ee:"My dog is friendly.",ek:"우리 강아지는 친근해요."},
    {e:"Bird",p:"[bɜːrd]",k:"새",ee:"A bird is singing.",ek:"새가 노래하고 있어요."},
    {e:"Fish",p:"[fɪʃ]",k:"물고기",ee:"Fish swim in water.",ek:"물고기는 물에서 헤엄쳐요."},
    {e:"Tiger",p:"[ˈtaɪɡər]",k:"호랑이",ee:"The tiger is strong.",ek:"호랑이는 강해요."},
    {e:"Lion",p:"[ˈlaɪən]",k:"사자",ee:"Lions live in Africa.",ek:"사자는 아프리카에 살아요."},
    {e:"Elephant",p:"[ˈelɪfənt]",k:"코끼리",ee:"The elephant is big.",ek:"코끼리는 커요."},
    {e:"Monkey",p:"[ˈmʌŋki]",k:"원숭이",ee:"Monkeys climb trees.",ek:"원숭이는 나무에 올라요."},
    {e:"Rabbit",p:"[ˈræbɪt]",k:"토끼",ee:"Rabbits have long ears.",ek:"토끼는 귀가 길어요."},
    {e:"Panda",p:"[ˈpændə]",k:"판다",ee:"Pandas eat bamboo.",ek:"판다는 대나무를 먹어요."}
  ]},
  {id:"food",name:"음식",icon:"🍱",words:[
    {e:"Bread",p:"[bred]",k:"빵",ee:"Bread is soft.",ek:"빵은 부드러워요."},
    {e:"Milk",p:"[mɪlk]",k:"우유",ee:"Drink your milk.",ek:"우유를 마세요."},
    {e:"Apple",p:"[ˈæpl]",k:"사과",ee:"I eat an apple.",ek:"나는 사과를 먹어요."},
    {e:"Pizza",p:"[ˈpiːtsə]",k:"피자",ee:"I love pizza.",ek:"나는 피자를 좋아해요."},
    {e:"Water",p:"[ˈwɔːtər]",k:"물",ee:"Drink water every day.",ek:"매일 물을 마세요."}
  ]}
];

let curUser='', curCat=null, studyWords=[], studyIdx=0;
let quizWords=[], quizIdx=0, quizScore=0, wrongWords=[];
let scoreChart=null;

// 유틸리티 함수
const $ = (id) => document.getElementById(id);
const show = (id) => {
    document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
    $(id).classList.add('active');
};
const shuffle = (a) => [...a].sort(() => Math.random() - 0.5);

// 데이터베이스 로직
const getDB = () => JSON.parse(localStorage.getItem('evDB') || '{}');
const saveRecord = (u, rec) => {
    const db = getDB();
    if(!db[u]) db[u] = {records:[]};
    db[u].records.push(rec);
    localStorage.setItem('evDB', JSON.stringify(db));
};

// TTS
function speakText(t) {
    if(!window.speechSynthesis) return;
    window.speechSynthesis.cancel();
    const u = new SpeechSynthesisUtterance(t);
    u.lang = 'en-US'; u.rate = 0.9;
    window.speechSynthesis.speak(u);
}
function speak(type) {
    const w = studyWords[studyIdx];
    speakText(type === 'w' ? w.e : w.ee);
}
function speakQuiz() { speakText(quizWords[quizIdx].e); }

// 로그인
function loginUser() {
    const n = $('name-input').value.trim();
    if(!n) return;
    curUser = n;
    $('greeting-name').textContent = n;
    buildHome();
    show('sc-home');
}

function logout() { location.reload(); }

// 홈 빌드
function buildHome() {
    const g = $('cat-grid');
    g.innerHTML = '';
    const ud = getDB()[curUser] || {records:[]};
    CATS.forEach(cat => {
        const recs = ud.records.filter(r => r.catId === cat.id);
        const best = recs.length ? Math.max(...recs.map(r => r.score)) : 0;
        const d = document.createElement('div');
        d.className = 'cat-card';
        d.innerHTML = `
            ${best >= 8 ? '<div class="cat-badge">완료</div>' : ''}
            <div class="cat-icon">${cat.icon}</div>
            <div class="cat-name">${cat.name}</div>
            <div class="cat-prog"><div class="cat-prog-fill" style="width:${(best/cat.words.length)*100}%"></div></div>
        `;
        d.onclick = () => startStudy(cat.id);
        g.appendChild(d);
    });
}

function goHome() { buildHome(); show('sc-home'); }

// 학습 로직
function startStudy(id) {
    curCat = CATS.find(c => c.id === id);
    studyWords = shuffle(curCat.words).slice(0, 10);
    studyIdx = 0;
    $('study-title').textContent = curCat.name;
    renderStudy();
    show('sc-study');
}

function renderStudy() {
    const w = studyWords[studyIdx];
    $('s-eng-text').textContent = w.e;
    $('s-pho').textContent = w.p;
    $('s-kor').textContent = w.k;
    $('s-ex-e').textContent = w.ee;
    $('s-ex-k').textContent = w.ek;
    $('s-reveal').style.display = 'none';
    $('study-bar').style.width = `${((studyIdx + 1) / studyWords.length) * 100}%`;
    $('study-info').textContent = `${studyIdx + 1} / ${studyWords.length}`;
    if(studyIdx === studyWords.length - 1) {
        $('btn-next').style.display = 'none';
        $('btn-qs').style.display = 'block';
    } else {
        $('btn-next').style.display = 'block';
        $('btn-qs').style.display = 'none';
    }
}

function revealStudy() { $('s-reveal').style.display = 'block'; speak('w'); }
function nextStudy() { studyIdx++; renderStudy(); }

// 퀴즈 로직
function startQuiz() {
    quizWords = shuffle(studyWords);
    quizIdx = 0; quizScore = 0; wrongWords = [];
    $('quiz-title').textContent = `${curCat.name} 퀴즈`;
    renderQuiz();
    show('sc-quiz');
}

function renderQuiz() {
    const w = quizWords[quizIdx];
    $('q-eng').textContent = w.e;
    $('q-input').value = '';
    $('q-fb').textContent = '';
    $('quiz-bar').style.width = `${((quizIdx + 1) / quizWords.length) * 100}%`;
    setTimeout(() => $('q-input').focus(), 100);
}

function checkQuiz() {
    const ans = $('q-input').value.trim();
    if(!ans) return;
    const w = quizWords[quizIdx];
    if(ans === w.k || w.k.includes(ans)) {
        quizScore++;
        $('q-fb').textContent = '⭕ 정답!';
        $('q-fb').className = 'feedback fb-ok';
    } else {
        wrongWords.push(w);
        $('q-fb').textContent = `❌ 오답 (정답: ${w.k})`;
        $('q-fb').className = '
