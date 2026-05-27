<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>초등 영어 단어 정복</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.0/chart.umd.min.js"></script>
<style>
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:'Malgun Gothic',sans-serif;background:#F4F6F9;min-height:100vh;}
.app{max-width:700px;margin:0 auto;padding:20px;}
.screen{display:none;}.screen.active{display:block;}
.login-wrap{display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:80vh;text-align:center;}
.login-logo{font-size:56px;margin-bottom:10px;}
.login-title{font-size:24px;font-weight:800;color:#2D3436;margin-bottom:6px;}
.login-sub{font-size:14px;color:#636E72;margin-bottom:32px;}
.login-input{width:260px;padding:14px 18px;font-size:18px;text-align:center;border-radius:16px;border:2px solid #DFE6E9;background:#fff;color:#2D3436;outline:none;margin-bottom:12px;font-family:inherit;transition:border-color 0.15s;}
.login-input:focus{border-color:#00B894;}
.login-btn{width:260px;padding:14px;background:#00B894;color:#fff;border:none;border-radius:16px;font-size:16px;font-weight:700;cursor:pointer;font-family:inherit;transition:background 0.15s;}
.login-btn:hover{background:#00A383;}
.saved-users{margin-top:24px;width:280px;}
.saved-title{font-size:12px;color:#B2BEC3;margin-bottom:8px;font-weight:600;}
.saved-chip{display:inline-block;padding:6px 14px;background:#fff;border:1.5px solid #DFE6E9;border-radius:99px;font-size:13px;color:#636E72;cursor:pointer;margin:3px;transition:all 0.15s;}
.saved-chip:hover{border-color:#00B894;color:#00B894;}
.home-header{display:flex;align-items:center;justify-content:space-between;padding:16px 0 14px;}
.home-greeting{font-size:18px;font-weight:800;color:#2D3436;}
.home-greeting span{color:#00B894;}
.home-btns{display:flex;gap:8px;}
.icon-btn{width:36px;height:36px;border-radius:50%;border:1.5px solid #DFE6E9;background:#fff;cursor:pointer;font-size:16px;display:flex;align-items:center;justify-content:center;transition:all 0.15s;}
.icon-btn:hover{border-color:#00B894;background:#E8F8F5;}
.cat-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(130px,1fr));gap:10px;margin-top:4px;}
.cat-card{background:#fff;border:1.5px solid #E8EAED;border-radius:16px;padding:14px 10px;cursor:pointer;text-align:center;transition:all 0.15s;position:relative;}
.cat-card:hover{border-color:#00B894;transform:translateY(-2px);box-shadow:0 4px 12px rgba(0,184,148,0.12);}
.cat-icon{font-size:26px;margin-bottom:5px;}
.cat-name{font-size:12px;font-weight:700;color:#2D3436;}
.cat-count{font-size:11px;color:#B2BEC3;margin-top:2px;}
.cat-prog{height:4px;background:#DFE6E9;border-radius:99px;margin-top:8px;overflow:hidden;}
.cat-prog-fill{height:100%;background:#00B894;border-radius:99px;transition:width 0.4s;}
.cat-badge{position:absolute;top:8px;right:8px;background:#00B894;color:#fff;font-size:10px;font-weight:700;padding:2px 6px;border-radius:99px;}
.top-bar{display:flex;align-items:center;gap:10px;margin-bottom:12px;}
.back-btn{width:36px;height:36px;border-radius:50%;border:1.5px solid #DFE6E9;background:#fff;cursor:pointer;font-size:16px;flex-shrink:0;transition:all 0.15s;}
.back-btn:hover{border-color:#00B894;background:#E8F8F5;}
.top-title{font-size:15px;font-weight:700;color:#2D3436;flex:1;}
.top-info{font-size:13px;color:#B2BEC3;white-space:nowrap;}
.prog-track{width:100%;height:7px;background:#DFE6E9;border-radius:99px;overflow:hidden;margin-bottom:14px;}
.prog-fill{height:100%;border-radius:99px;background:linear-gradient(90deg,#00B894,#00CEC9);transition:width 0.35s;}
.word-card{background:#fff;border-radius:20px;padding:28px 22px 24px;margin-bottom:14px;text-align:center;box-shadow:0 2px 12px rgba(0,0,0,0.06);}
.w-eng-wrap{display:inline-flex;align-items:center;gap:10px;cursor:pointer;padding:6px 12px;border-radius:12px;transition:background 0.15s;}
.w-eng-wrap:hover{background:#F0FDF9;}
.w-eng{font-size:44px;font-weight:800;color:#2D3436;letter-spacing:-1px;line-height:1.1;}
.w-eng-wrap:hover .w-eng{color:#00B894;}
.speak-btn{font-size:22px;opacity:0.35;transition:opacity 0.15s;}
.w-eng-wrap:hover .speak-btn{opacity:1;}
.w-pho{font-size:14px;color:#B2BEC3;font-style:italic;margin:4px 0 14px;}
.reveal-btn{padding:8px 20px;border-radius:99px;border:1.5px solid #DFE6E9;background:#F8F9FA;font-size:13px;color:#636E72;cursor:pointer;transition:all 0.15s;font-family:inherit;}
.reveal-btn:hover{border-color:#00B894;color:#00B894;background:#F0FDF9;}
.w-kor{font-size:26px;font-weight:700;color:#00B894;margin:14px 0 8px;}
.ex-row{display:flex;align-items:stretch;gap:8px;margin-top:10px;}
.ex-box{flex:1;background:#F8F9FA;border-left:4px solid #00B894;border-radius:10px;padding:12px 14px;text-align:left;}
.ex-eng{font-size:14px;font-weight:600;color:#2D3436;}
.ex-kor{font-size:12px;color:#636E72;margin-top:4px;}
.ex-speak-btn{width:40px;background:#E8F8F5;border:none;border-radius:10px;font-size:18px;cursor:pointer;flex-shrink:0;transition:all 0.15s;}
.ex-speak-btn:hover{background:#00B894;color:#fff;}
.btn-row{display:flex;gap:8px;}
.btn{flex:1;padding:13px;border-radius:12px;font-size:14px;font-weight:700;cursor:pointer;border:none;transition:all 0.15s;font-family:inherit;}
.btn-outline{background:#fff;border:1.5px solid #DFE6E9;color:#636E72;}
.btn-outline:hover{border-color:#00B894;color:#00B894;background:#F0FDF9;}
.btn-green{background:#00B894;color:#fff;}
.btn-green:hover{background:#00A383;}
.quiz-word-wrap{display:flex;align-items:center;justify-content:center;gap:10px;padding:22px 0 10px;cursor:pointer;border-radius:14px;transition:background 0.15s;}
.quiz-word-wrap:hover{background:#F0FDF9;}
.quiz-word{font-size:42px;font-weight:800;color:#2D3436;letter-spacing:-1px;}
.quiz-word-wrap:hover .quiz-word{color:#00B894;}
.quiz-speak{font-size:22px;opacity:0.35;transition:opacity 0.15s;}
.quiz-word-wrap:hover .quiz-speak{opacity:1;}
.quiz-prompt{font-size:14px;color:#636E72;text-align:center;margin-bottom:12px;}
.quiz-input{width:100%;padding:14px;font-size:18px;text-align:center;border-radius:12px;border:2px solid #DFE6E9;background:#fff;color:#2D3436;outline:none;transition:border-color 0.15s;font-family:inherit;}
.quiz-input:focus{border-color:#00B894;}
.feedback{font-size:16px;font-weight:700;text-align:center;min-height:28px;margin:10px 0 6px;transition:opacity 0.2s;}
.fb-ok{color:#00B894;}.fb-ng{color:#E17055;}
.result-wrap{padding:8px 0;}
.result-top{text-align:center;margin-bottom:16px;}
.result-meta{font-size:13px;color:#636E72;margin-bottom:3px;}
.result-date{font-size:12px;color:#B2BEC3;margin-bottom:14px;}
.result-emoji{font-size:50px;margin-bottom:8px;}
.result-title{font-size:20px;font-weight:800;color:#2D3436;margin-bottom:4px;}
.result-score{font-size:50px;font-weight:800;margin:10px 0 6px;}
.score-pass{color:#00B894;}.score-fail{color:#E17055;}
.result-msg{font-size:14px;color:#636E72;margin-bottom:16px;}
.wrong-panel{background:#fff;border-radius:16px;padding:14px;margin:12px 0;box-shadow:0 2px 8px rgba(0,0,0,0.05);}
.wrong-panel h3{font-size:11px;font-weight:700;color:#B2BEC3;margin-bottom:10px;text-transform:uppercase;letter-spacing:0.06em;}
.wrong-item{display:flex;justify-content:space-between;padding:7px 0;border-bottom:1px solid #F4F6F9;font-size:13px;}
.wrong-item:last-child{border-bottom:none;}
.wi-eng{font-weight:700;color:#2D3436;}.wi-kor{color:#00B894;font-weight:600;}
.stats-header{display:flex;align-items:center;gap:10px;margin-bottom:16px;}
.stats-sect{background:#fff;border-radius:16px;padding:16px;margin-bottom:14px;box-shadow:0 2px 8px rgba(0,0,0,0.04);}
.stats-sect-title{font-size:12px;font-weight:700;color:#B2BEC3;margin-bottom:14px;text-transform:uppercase;letter-spacing:0.06em;}
.stat-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;}
.stat-box{background:#F8F9FA;border-radius:12px;padding:14px;text-align:center;}
.stat-num{font-size:24px;font-weight:800;color:#2D3436;}
.stat-num.green{color:#00B894;}
.stat-lbl{font-size:11px;color:#B2BEC3;margin-top:3px;}
.chart-wrap{height:190px;position:relative;}
.cat-filter{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:14px;}
.f-chip{padding:5px 12px;border-radius:99px;border:1.5px solid #DFE6E9;background:#fff;font-size:12px;color:#636E72;cursor:pointer;font-family:inherit;transition:all 0.15s;}
.f-chip:hover{border-color:#00B894;color:#00B894;}
.f-chip.active{border-color:#00B894;background:#E8F8F5;color:#00B894;font-weight:700;}
.hist-table{width:100%;border-collapse:collapse;font-size:13px;}
.hist-table th{font-size:11px;color:#B2BEC3;font-weight:600;text-align:left;padding:6px 8px;border-bottom:1px solid #EEF0F3;}
.hist-table td{padding:8px;border-bottom:1px solid #F8F9FA;color:#2D3436;}
.hist-table tr:last-child td{border-bottom:none;}
.badge{padding:2px 9px;border-radius:99px;font-size:11px;font-weight:700;}
.badge-pass{background:#E8F8F5;color:#00B894;}
.badge-fail{background:#FFF0ED;color:#E17055;}
.no-data{text-align:center;color:#B2BEC3;font-size:14px;padding:28px;}
/* --- 모바일 및 태블릿 최적화 추가 --- */

/* 1. 모바일에서 텍스트 선택 및 하이라이트 방지 (앱 느낌 강조) */
body {
    -webkit-tap-highlight-color: transparent;
    user-select: none;
}
input {
    user-select: auto; /* 입력창은 선택 가능하게 */
}

/* 2. 작은 화면 (모바일) 대응 미디어 쿼리 */
@media (max-width: 480px) {
    .app {
        padding: 12px; /* 여백 축소 */
    }

    .login-logo {
        font-size: 48px;
    }

    .login-title {
        font-size: 20px;
    }

    /* 카테고리 그리드를 2열로 고정하여 가독성 향상 */
    .cat-grid {
        grid-template-columns: repeat(2, 1fr);
        gap: 8px;
    }

    .cat-card {
        padding: 20px 10px;
    }

    /* 단어 카드 글자 크기 조정 */
    .w-eng {
        font-size: 36px;
    }

    .w-kor {
        font-size: 22px;
    }

    /* 버튼 크기 키우기 (터치 편의성) */
    .btn, .login-btn {
        padding: 16px;
        font-size: 16px;
    }

    /* 퀴즈 입력창 최적화 */
    .quiz-word {
        font-size: 32px;
    }
}

/* 3. 노치 디자인 대응 (아이폰 등 최신 기기) */
@supports (padding: env(safe-area-inset-top)) {
    .app {
        padding-top: env(safe-area-inset-top);
        padding-bottom: env(safe-area-inset-bottom);
    }
}

/* 4. 애니메이션 효과 추가 (학습 경험 개선) */
.screen.active {
    animation: fadeIn 0.3s ease-out;
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
}

/* 5. 스크롤바 숨기기 (깔끔한 UI) */
::-webkit-scrollbar {
    display: none;
}
</style>
</head>
<body>
<div class="app">

<!-- LOGIN -->
<div id="sc-login" class="screen active">
  <div class="login-wrap">
    <div class="login-logo">🎯</div>
    <div class="login-title">초등 영어 단어 정복</div>
    <div class="login-sub">이름을 입력하고 시작하세요!</div>
    <input class="login-input" id="name-input" placeholder="이름 입력" maxlength="10"
      onkeydown="if(event.key==='Enter')loginUser()">
    <button class="login-btn" onclick="loginUser()">시작하기 →</button>
    <div class="saved-users" id="saved-users-wrap" style="display:none">
      <div class="saved-title">이전 학습자</div>
      <div id="saved-chips"></div>
    </div>
  </div>
</div>

<!-- HOME -->
<div id="sc-home" class="screen">
  <div class="home-header">
    <div class="home-greeting">안녕, <span id="greeting-name"></span>! 👋</div>
    <div class="home-btns">
      <button class="icon-btn" title="학습 기록" onclick="showStats()">📊</button>
      <button class="icon-btn" title="로그아웃" onclick="logout()">👤</button>
    </div>
  </div>
  <div class="cat-grid" id="cat-grid"></div>
</div>

<!-- STUDY -->
<div id="sc-study" class="screen">
  <div class="top-bar">
    <button class="back-btn" onclick="goHome()">←</button>
    <div class="top-title" id="study-title"></div>
    <div class="top-info" id="study-info"></div>
  </div>
  <div class="prog-track"><div class="prog-fill" id="study-bar"></div></div>
  <div class="word-card">
    <div>
      <div class="w-eng-wrap" onclick="speak('w')">
        <div class="w-eng" id="s-eng-text"></div>
        <div class="speak-btn">🔊</div>
      </div>
    </div>
    <div class="w-pho" id="s-pho"></div>
    <button class="reveal-btn" onclick="revealStudy()">뜻 보기 👁</button>
    <div id="s-reveal" style="display:none">
      <div class="w-kor" id="s-kor"></div>
      <div class="ex-row">
        <div class="ex-box">
          <div class="ex-eng" id="s-ex-e"></div>
          <div class="ex-kor" id="s-ex-k"></div>
        </div>
        <button class="ex-speak-btn" onclick="speak('ex')" title="예문 듣기">🔊</button>
      </div>
    </div>
  </div>
  <div class="btn-row">
    <button class="btn btn-outline" id="btn-next" onclick="nextStudy()">다음 단어 →</button>
    <button class="btn btn-green" id="btn-qs" style="display:none" onclick="startQuiz()">퀴즈 시작 🔥</button>
  </div>
</div>

<!-- QUIZ -->
<div id="sc-quiz" class="screen">
  <div class="top-bar">
    <button class="back-btn" onclick="goHome()">←</button>
    <div class="top-title" id="quiz-title"></div>
    <div class="top-info" id="quiz-info"></div>
  </div>
  <div class="prog-track"><div class="prog-fill" id="quiz-bar"></div></div>
  <div class="word-card">
    <div class="quiz-word-wrap" onclick="speakQuiz()">
      <div class="quiz-word" id="q-eng"></div>
      <div class="quiz-speak">🔊</div>
    </div>
    <p class="quiz-prompt">이 단어의 한글 뜻은?</p>
    <input class="quiz-input" id="q-input" placeholder="한글 뜻을 입력하세요"
      autocomplete="off" onkeydown="if(event.key==='Enter')checkQuiz()">
    <div class="feedback" id="q-fb"></div>
    <div class="btn-row" style="margin-top:6px">
      <button class="btn btn-green" onclick="checkQuiz()">정답 확인</button>
    </div>
  </div>
</div>

<!-- RESULT -->
<div id="sc-result" class="screen">
  <div class="result-wrap">
    <div class="result-top">
      <div class="result-meta" id="r-name"></div>
      <div class="result-date" id="r-date"></div>
      <div class="result-emoji" id="r-emoji"></div>
      <div class="result-title" id="r-title"></div>
      <div class="result-score" id="r-score"></div>
      <div class="result-msg" id="r-msg"></div>
    </div>
    <div class="wrong-panel" id="r-wrong" style="display:none">
      <h3>틀린 단어</h3>
      <div id="r-wrong-list"></div>
    </div>
    <div class="btn-row">
      <button class="btn btn-outline" onclick="retryStudy()">다시 공부</button>
      <button class="btn btn-green" onclick="showStats()">📊 기록 보기</button>
      <button class="btn btn-outline" onclick="goHome()">다른 범주</button>
    </div>
  </div>
</div>

<!-- STATS -->
<div id="sc-stats" class="screen">
  <div class="stats-header">
    <button class="back-btn" onclick="goHome()">←</button>
    <div class="top-title">📊 <span id="stats-name"></span>의 학습 기록</div>
  </div>
  <div class="stats-sect">
    <div class="stats-sect-title">요약</div>
    <div class="stat-grid" id="stat-boxes"></div>
  </div>
  <div class="stats-sect">
    <div class="stats-sect-title">범주 필터</div>
    <div class="cat-filter" id="cat-filter"></div>
    <div class="stats-sect-title">점수 변화</div>
    <div class="chart-wrap"><canvas id="score-chart"></canvas></div>
  </div>
  <div class="stats-sect">
    <div class="stats-sect-title">최근 기록 (최대 30개)</div>
    <div id="history-wrap"></div>
  </div>
</div>

</div><!-- .app -->
<script>
const CATS = [
  {id:"animals",name:"동물",icon:"🐾",words:[
    {e:"Cat",p:"[kæt]",k:"고양이",ee:"The cat is sleeping.",ek:"고양이가 자고 있어요."},
    {e:"Dog",p:"[dɔːɡ]",k:"강아지",ee:"My dog is friendly.",ek:"우리 강아지는 친근해요."},
    {e:"Bird",p:"[bɜːrd]",k:"새",ee:"A bird is singing.",ek:"새가 노래하고 있어요."},
    {e:"Fish",p:"[fɪʃ]",k:"물고기",ee:"Fish swim in water.",ek:"물고기는 물에서 헤엄쳐요."},
    {e:"Horse",p:"[hɔːrs]",k:"말",ee:"The horse runs fast.",ek:"말이 빠르게 달려요."},
    {e:"Cow",p:"[kaʊ]",k:"소",ee:"The cow eats grass.",ek:"소가 풀을 먹어요."},
    {e:"Pig",p:"[pɪɡ]",k:"돼지",ee:"The pig is pink.",ek:"돼지는 분홍색이에요."},
    {e:"Sheep",p:"[ʃiːp]",k:"양",ee:"Sheep have wool.",ek:"양에게는 털이 있어요."},
    {e:"Rabbit",p:"[ˈræbɪt]",k:"토끼",ee:"Rabbits have long ears.",ek:"토끼는 귀가 길어요."},
    {e:"Tiger",p:"[ˈtaɪɡər]",k:"호랑이",ee:"The tiger is strong.",ek:"호랑이는 강해요."},
    {e:"Lion",p:"[ˈlaɪən]",k:"사자",ee:"Lions live in Africa.",ek:"사자는 아프리카에 살아요."},
    {e:"Elephant",p:"[ˈelɪfənt]",k:"코끼리",ee:"The elephant is big.",ek:"코끼리는 커요."},
    {e:"Monkey",p:"[ˈmʌŋki]",k:"원숭이",ee:"Monkeys climb trees.",ek:"원숭이는 나무에 올라요."},
    {e:"Snake",p:"[sneɪk]",k:"뱀",ee:"The snake is long.",ek:"뱀은 길어요."},
    {e:"Frog",p:"[frɔːɡ]",k:"개구리",ee:"Frogs jump high.",ek:"개구리는 높이 뛰어요."},
    {e:"Duck",p:"[dʌk]",k:"오리",ee:"Ducks swim in ponds.",ek:"오리는 연못에서 수영해요."},
    {e:"Butterfly",p:"[ˈbʌtərflaɪ]",k:"나비",ee:"Butterflies are colorful.",ek:"나비는 알록달록해요."},
    {e:"Bee",p:"[biː]",k:"벌",ee:"Bees make honey.",ek:"벌은 꿀을 만들어요."},
    {e:"Spider",p:"[ˈspaɪdər]",k:"거미",ee:"Spiders make webs.",ek:"거미는 거미줄을 쳐요."},
    {e:"Turtle",p:"[ˈtɜːrtl]",k:"거북이",ee:"Turtles are slow.",ek:"거북이는 느려요."},
    {e:"Bear",p:"[ber]",k:"곰",ee:"The bear is very big.",ek:"그 곰은 매우 커요."},
    {e:"Fox",p:"[fɑːks]",k:"여우",ee:"The fox is clever.",ek:"여우는 영리해요."},
    {e:"Wolf",p:"[wʊlf]",k:"늑대",ee:"Wolves howl at the moon.",ek:"늑대는 달을 향해 울부짖어요."},
    {e:"Deer",p:"[dɪr]",k:"사슴",ee:"Deer run in the forest.",ek:"사슴은 숲에서 달려요."},
    {e:"Giraffe",p:"[dʒɪˈræf]",k:"기린",ee:"Giraffes have long necks.",ek:"기린은 목이 길어요."},
    {e:"Zebra",p:"[ˈziːbrə]",k:"얼룩말",ee:"Zebras have stripes.",ek:"얼룩말은 줄무늬가 있어요."},
    {e:"Panda",p:"[ˈpændə]",k:"판다",ee:"Pandas eat bamboo.",ek:"판다는 대나무를 먹어요."},
    {e:"Penguin",p:"[ˈpeŋɡwɪn]",k:"펭귄",ee:"Penguins live in the cold.",ek:"펭귄은 추운 곳에 살아요."},
    {e:"Crocodile",p:"[ˈkrɑːkədaɪl]",k:"악어",ee:"Crocodiles live near rivers.",ek:"악어는 강 근처에 살아요."},
    {e:"Parrot",p:"[ˈpærət]",k:"앵무새",ee:"Parrots can talk.",ek:"앵무새는 말을 할 수 있어요."},
    {e:"Hamster",p:"[ˈhæmstər]",k:"햄스터",ee:"Hamsters are tiny.",ek:"햄스터는 아주 작아요."},
    {e:"Dolphin",p:"[ˈdɑːlfɪn]",k:"돌고래",ee:"Dolphins are smart.",ek:"돌고래는 영리해요."},
    {e:"Whale",p:"[weɪl]",k:"고래",ee:"Whales are huge.",ek:"고래는 거대해요."},
    {e:"Shark",p:"[ʃɑːrk]",k:"상어",ee:"Sharks swim fast.",ek:"상어는 빠르게 수영해요."},
    {e:"Octopus",p:"[ˈɑːktəpəs]",k:"문어",ee:"An octopus has eight arms.",ek:"문어는 팔이 여덟 개예요."},
    {e:"Ant",p:"[ænt]",k:"개미",ee:"Ants work together.",ek:"개미는 함께 일해요."},
    {e:"Ladybug",p:"[ˈleɪdibʌɡ]",k:"무당벌레",ee:"Ladybugs are red and black.",ek:"무당벌레는 빨간색과 검은색이에요."},
    {e:"Grasshopper",p:"[ˈɡræshɑːpər]",k:"메뚜기",ee:"Grasshoppers jump far.",ek:"메뚜기는 멀리 뛰어요."},
    {e:"Owl",p:"[aʊl]",k:"올빼미",ee:"Owls see well at night.",ek:"올빼미는 밤에 잘 봐요."},
    {e:"Eagle",p:"[ˈiːɡl]",k:"독수리",ee:"Eagles fly very high.",ek:"독수리는 매우 높이 날아요."},
    {e:"Peacock",p:"[ˈpiːkɑːk]",k:"공작새",ee:"Peacocks have beautiful feathers.",ek:"공작새는 깃털이 아름다워요."},
    {e:"Squirrel",p:"[ˈskwɜːrəl]",k:"다람쥐",ee:"Squirrels collect nuts.",ek:"다람쥐는 견과류를 모아요."},
    {e:"Hedgehog",p:"[ˈhedʒhɑːɡ]",k:"고슴도치",ee:"Hedgehogs have sharp spines.",ek:"고슴도치는 날카로운 가시가 있어요."},
    {e:"Flamingo",p:"[fləˈmɪŋɡoʊ]",k:"플라밍고",ee:"Flamingos are pink.",ek:"플라밍고는 분홍색이에요."},
    {e:"Cheetah",p:"[ˈtʃiːtə]",k:"치타",ee:"Cheetahs are the fastest.",ek:"치타는 가장 빨라요."},
    {e:"Gorilla",p:"[ɡəˈrɪlə]",k:"고릴라",ee:"Gorillas are very strong.",ek:"고릴라는 매우 강해요."},
    {e:"Camel",p:"[ˈkæml]",k:"낙타",ee:"Camels live in deserts.",ek:"낙타는 사막에 살아요."},
    {e:"Kangaroo",p:"[ˌkæŋɡəˈruː]",k:"캥거루",ee:"Kangaroos jump and hop.",ek:"캥거루는 깡충깡충 뛰어요."},
    {e:"Koala",p:"[koʊˈɑːlə]",k:"코알라",ee:"Koalas sleep a lot.",ek:"코알라는 잠을 많이 자요."},
    {e:"Raccoon",p:"[ræˈkuːn]",k:"너구리",ee:"Raccoons are curious.",ek:"너구리는 호기심이 많아요."}
  ]},
  {id:"food",name:"음식",icon:"🍱",words:[
    {e:"Bread",p:"[bred]",k:"빵",ee:"Bread is soft.",ek:"빵은 부드러워요."},
    {e:"Milk",p:"[mɪlk]",k:"우유",ee:"Drink your milk.",ek:"우유를 마세요."},
    {e:"Egg",p:"[eɡ]",k:"달걀",ee:"Eggs are healthy.",ek:"달걀은 건강에 좋아요."},
    {e:"Rice",p:"[raɪs]",k:"밥",ee:"I eat rice every day.",ek:"나는 매일 밥을 먹어요."},
    {e:"Noodle",p:"[ˈnuːdl]",k:"국수",ee:"I like noodles.",ek:"나는 국수를 좋아해요."},
    {e:"Cake",p:"[keɪk]",k:"케이크",ee:"The cake is sweet.",ek:"케이크는 달아요."},
    {e:"Cookie",p:"[ˈkʊki]",k:"쿠키",ee:"Cookies are delicious.",ek:"쿠키는 맛있어요."},
    {e:"Juice",p:"[dʒuːs]",k:"주스",ee:"Orange juice is fresh.",ek:"오렌지 주스는 신선해요."},
    {e:"Water",p:"[ˈwɔːtər]",k:"물",ee:"Drink water every day.",ek:"매일 물을 마세요."},
    {e:"Cheese",p:"[tʃiːz]",k:"치즈",ee:"Cheese is yummy.",ek:"치즈는 맛있어요."},
    {e:"Pizza",p:"[ˈpiːtsə]",k:"피자",ee:"I love pizza.",ek:"나는 피자를 좋아해요."},
    {e:"Soup",p:"[suːp]",k:"수프",ee:"Soup is warm.",ek:"수프는 따뜻해요."},
    {e:"Salad",p:"[ˈsæləd]",k:"샐러드",ee:"Salad is healthy.",ek:"샐러드는 건강에 좋아요."},
    {e:"Candy",p:"[ˈkændi]",k:"사탕",ee:"Candy is sweet.",ek:"사탕은 달아요."},
    {e:"Hamburger",p:"[ˈhæmbɜːrɡər]",k:"햄버거",ee:"I want a hamburger.",ek:"나는 햄버거를 먹고 싶어요."},
    {e:"Sandwich",p:"[ˈsænwɪtʃ]",k:"샌드위치",ee:"She made a sandwich.",ek:"그녀가 샌드위치를 만들었어요."},
    {e:"Spaghetti",p:"[spəˈɡeti]",k:"스파게티",ee:"Spaghetti is delicious.",ek:"스파게티는 맛있어요."},
    {e:"Sushi",p:"[ˈsuːʃi]",k:"초밥",ee:"Sushi comes from Japan.",ek:"초밥은 일본에서 왔어요."},
    {e:"Taco",p:"[ˈtækoʊ]",k:"타코",ee:"Tacos are spicy.",ek:"타코는 매워요."},
    {e:"Ice cream",p:"[ˈaɪs kriːm]",k:"아이스크림",ee:"Ice cream is cold.",ek:"아이스크림은 차가워요."},
    {e:"Chocolate",p:"[ˈtʃɑːklət]",k:"초콜릿",ee:"Chocolate is sweet.",ek:"초콜릿은 달아요."},
    {e:"Popcorn",p:"[ˈpɑːpkɔːrn]",k:"팝콘",ee:"I eat popcorn at the movies.",ek:"영화관에서 팝콘을 먹어요."},
    {e:"Donut",p:"[ˈdoʊnʌt]",k:"도넛",ee:"Donuts have holes.",ek:"도넛에는 구멍이 있어요."},
    {e:"Pancake",p:"[ˈpænkeɪk]",k:"팬케이크",ee:"Pancakes are fluffy.",ek:"팬케이크는 폭신해요."},
    {e:"Waffle",p:"[ˈwɑːfl]",k:"와플",ee:"Waffles are crispy.",ek:"와플은 바삭바삭해요."},
    {e:"Butter",p:"[ˈbʌtər]",k:"버터",ee:"Put butter on the bread.",ek:"빵에 버터를 발라요."},
    {e:"Jam",p:"[dʒæm]",k:"잼",ee:"I like strawberry jam.",ek:"나는 딸기잼을 좋아해요."},
    {e:"Honey",p:"[ˈhʌni]",k:"꿀",ee:"Honey is very sweet.",ek:"꿀은 매우 달아요."},
    {e:"Yogurt",p:"[ˈjoʊɡərt]",k:"요거트",ee:"Yogurt is good for you.",ek:"요거트는 몸에 좋아요."},
    {e:"Cereal",p:"[ˈsɪriəl]",k:"시리얼",ee:"I eat cereal for breakfast.",ek:"아침에 시리얼을 먹어요."},
    {e:"Meat",p:"[miːt]",k:"고기",ee:"We grill meat outside.",ek:"밖에서 고기를 구워요."},
    {e:"Chicken",p:"[ˈtʃɪkɪn]",k:"닭고기",ee:"Fried chicken is popular.",ek:"치킨은 인기가 많아요."},
    {e:"Fish cake",p:"[fɪʃ keɪk]",k:"어묵",ee:"Fish cakes are chewy.",ek:"어묵은 쫄깃해요."},
    {e:"Tofu",p:"[ˈtoʊfuː]",k:"두부",ee:"Tofu is soft.",ek:"두부는 부드러워요."},
    {e:"Dumpling",p:"[ˈdʌmplɪŋ]",k:"만두",ee:"Dumplings are delicious.",ek:"만두는 맛있어요."},
    {e:"Curry",p:"[ˈkɜːri]",k:"카레",ee:"Curry is spicy.",ek:"카레는 매워요."},
    {e:"Stew",p:"[stjuː]",k:"찌개",ee:"Stew is warm and filling.",ek:"찌개는 따뜻하고 든든해요."},
    {e:"Porridge",p:"[ˈpɔːrɪdʒ]",k:"죽",ee:"Porridge is easy to eat.",ek:"죽은 먹기 편해요."},
    {e:"Kimbap",p:"[ˈkɪmbæp]",k:"김밥",ee:"Kimbap is a Korean roll.",ek:"김밥은 한국 음식이에요."},
    {e:"Ramen",p:"[ˈrɑːmən]",k:"라면",ee:"Ramen is my favorite.",ek:"라면은 내가 제일 좋아하는 음식이에요."},
    {e:"Tea",p:"[tiː]",k:"차",ee:"Hot tea warms you up.",ek:"따뜻한 차가 몸을 녹여요."},
    {e:"Coffee",p:"[ˈkɑːfi]",k:"커피",ee:"Adults drink coffee.",ek:"어른들은 커피를 마셔요."},
    {e:"Lemonade",p:"[ˌlemənˈeɪd]",k:"레모네이드",ee:"Lemonade is refreshing.",ek:"레모네이드는 시원해요."},
    {e:"Smoothie",p:"[ˈsmuːði]",k:"스무디",ee:"Smoothies are healthy.",ek:"스무디는 건강에 좋아요."},
    {e:"Chips",p:"[tʃɪps]",k:"과자",ee:"Chips are salty.",ek:"과자는 짜요."},
    {e:"Gum",p:"[ɡʌm]",k:"껌",ee:"I chew gum.",ek:"나는 껌을 씹어요."},
    {e:"Pudding",p:"[ˈpʊdɪŋ]",k:"푸딩",ee:"Pudding is creamy.",ek:"푸딩은 크리미해요."},
    {e:"Jelly",p:"[ˈdʒeli]",k:"젤리",ee:"Jelly is wobbly.",ek:"젤리는 흔들흔들해요."},
    {e:"Pretzel",p:"[ˈpretsəl]",k:"프레첼",ee:"Pretzels are salty.",ek:"프레첼은 짭짤해요."},
    {e:"Brownie",p:"[ˈbraʊni]",k:"브라우니",ee:"Brownies are chewy.",ek:"브라우니는 쫄깃해요."}
  ]},
  {id:"vegetables",name:"야채",icon:"🥦",words:[
    {e:"Carrot",p:"[ˈkærət]",k:"당근",ee:"Carrots are orange.",ek:"당근은 주황색이에요."},
    {e:"Potato",p:"[pəˈteɪtoʊ]",k:"감자",ee:"I like potato chips.",ek:"나는 감자칩을 좋아해요."},
    {e:"Tomato",p:"[təˈmeɪtoʊ]",k:"토마토",ee:"Tomatoes are red.",ek:"토마토는 빨간색이에요."},
    {e:"Onion",p:"[ˈʌnjən]",k:"양파",ee:"Onions make me cry.",ek:"양파는 눈물이 나게 해요."},
    {e:"Cabbage",p:"[ˈkæbɪdʒ]",k:"양배추",ee:"Cabbage is green.",ek:"양배추는 초록색이에요."},
    {e:"Broccoli",p:"[ˈbrɑːkəli]",k:"브로콜리",ee:"Broccoli is healthy.",ek:"브로콜리는 건강에 좋아요."},
    {e:"Spinach",p:"[ˈspɪnɪtʃ]",k:"시금치",ee:"Spinach makes you strong.",ek:"시금치는 힘을 줘요."},
    {e:"Cucumber",p:"[ˈkjuːkʌmbər]",k:"오이",ee:"Cucumbers are cool.",ek:"오이는 시원해요."},
    {e:"Pepper",p:"[ˈpepər]",k:"피망",ee:"Peppers are colorful.",ek:"피망은 알록달록해요."},
    {e:"Mushroom",p:"[ˈmʌʃruːm]",k:"버섯",ee:"Mushrooms grow in forests.",ek:"버섯은 숲에서 자라요."},
    {e:"Corn",p:"[kɔːrn]",k:"옥수수",ee:"Corn is yellow.",ek:"옥수수는 노란색이에요."},
    {e:"Peas",p:"[piːz]",k:"완두콩",ee:"Peas are small and green.",ek:"완두콩은 작고 초록색이에요."},
    {e:"Garlic",p:"[ˈɡɑːrlɪk]",k:"마늘",ee:"Garlic smells strong.",ek:"마늘은 냄새가 강해요."},
    {e:"Ginger",p:"[ˈdʒɪndʒər]",k:"생강",ee:"Ginger is spicy.",ek:"생강은 매워요."},
    {e:"Celery",p:"[ˈseləri]",k:"셀러리",ee:"Celery is crunchy.",ek:"셀러리는 아삭해요."},
    {e:"Lettuce",p:"[ˈletɪs]",k:"상추",ee:"Lettuce goes in salad.",ek:"상추는 샐러드에 들어가요."},
    {e:"Eggplant",p:"[ˈeɡplænt]",k:"가지",ee:"Eggplant is purple.",ek:"가지는 보라색이에요."},
    {e:"Zucchini",p:"[zuːˈkiːni]",k:"애호박",ee:"Zucchini is green.",ek:"애호박은 초록색이에요."},
    {e:"Pumpkin",p:"[ˈpʌmpkɪn]",k:"호박",ee:"Pumpkins are orange.",ek:"호박은 주황색이에요."},
    {e:"Sweet potato",p:"[swiːt pəˈteɪtoʊ]",k:"고구마",ee:"Sweet potatoes are sweet.",ek:"고구마는 달아요."},
    {e:"Radish",p:"[ˈrædɪʃ]",k:"무",ee:"Radishes are crispy.",ek:"무는 아삭해요."},
    {e:"Bean",p:"[biːn]",k:"콩",ee:"Beans are full of protein.",ek:"콩에는 단백질이 많아요."},
    {e:"Leek",p:"[liːk]",k:"대파",ee:"Leeks go in soup.",ek:"대파는 국에 들어가요."},
    {e:"Asparagus",p:"[əˈspærəɡəs]",k:"아스파라거스",ee:"Asparagus is long and green.",ek:"아스파라거스는 길고 초록색이에요."},
    {e:"Cauliflower",p:"[ˈkɑːliflaʊər]",k:"콜리플라워",ee:"Cauliflower is white.",ek:"콜리플라워는 하얀색이에요."},
    {e:"Artichoke",p:"[ˈɑːrtɪtʃoʊk]",k:"아티초크",ee:"Artichokes look unusual.",ek:"아티초크는 독특하게 생겼어요."},
    {e:"Turnip",p:"[ˈtɜːrnɪp]",k:"순무",ee:"Turnips grow underground.",ek:"순무는 땅속에서 자라요."},
    {e:"Kale",p:"[keɪl]",k:"케일",ee:"Kale is a superfood.",ek:"케일은 슈퍼푸드예요."},
    {e:"Chili",p:"[ˈtʃɪli]",k:"고추",ee:"Chili is very hot.",ek:"고추는 매우 매워요."},
    {e:"Beet",p:"[biːt]",k:"비트",ee:"Beets are dark red.",ek:"비트는 진한 빨간색이에요."},
    {e:"Bok choy",p:"[bɑːk tʃɔɪ]",k:"청경채",ee:"Bok choy is used in stir-fry.",ek:"청경채는 볶음에 사용해요."},
    {e:"Parsley",p:"[ˈpɑːrsli]",k:"파슬리",ee:"Parsley is a herb.",ek:"파슬리는 허브예요."},
    {e:"Rosemary",p:"[ˈroʊzmeri]",k:"로즈마리",ee:"Rosemary smells nice.",ek:"로즈마리는 향기가 좋아요."},
    {e:"Basil",p:"[ˈbeɪzl]",k:"바질",ee:"Basil is used in pizza.",ek:"바질은 피자에 사용해요."},
    {e:"Mint",p:"[mɪnt]",k:"민트",ee:"Mint is fresh.",ek:"민트는 상쾌해요."},
    {e:"Sprout",p:"[spraʊt]",k:"새싹",ee:"Sprouts are tiny plants.",ek:"새싹은 아주 작은 식물이에요."},
    {e:"Bamboo shoot",p:"[bæmˈbuː ʃuːt]",k:"죽순",ee:"Bamboo shoots are thin.",ek:"죽순은 가늘어요."},
    {e:"Seaweed",p:"[ˈsiːwiːd]",k:"해조류",ee:"Seaweed grows in the sea.",ek:"해조류는 바다에서 자라요."},
    {e:"Lotus root",p:"[ˈloʊtəs ruːt]",k:"연근",ee:"Lotus root has holes.",ek:"연근에는 구멍이 있어요."},
    {e:"Perilla",p:"[pəˈrɪlə]",k:"깻잎",ee:"Perilla is used in Korean food.",ek:"깻잎은 한국 음식에 사용해요."},
    {e:"Crown daisy",p:"[kraʊn ˈdeɪzi]",k:"쑥갓",ee:"Crown daisy is fragrant.",ek:"쑥갓은 향기로워요."},
    {e:"Water cress",p:"[ˈwɔːtər kres]",k:"물냉이",ee:"Watercress grows near water.",ek:"물냉이는 물 근처에서 자라요."},
    {e:"Green onion",p:"[ɡriːn ˈʌnjən]",k:"쪽파",ee:"Green onions are thin.",ek:"쪽파는 가늘어요."},
    {e:"Pea shoot",p:"[piː ʃuːt]",k:"완두순",ee:"Pea shoots are tender.",ek:"완두순은 부드러워요."},
    {e:"Daikon",p:"[ˈdaɪkɑːn]",k:"단무지",ee:"Daikon is white and crunchy.",ek:"단무지는 하얗고 아삭해요."},
    {e:"Yam",p:"[jæm]",k:"얌",ee:"Yams are starchy.",ek:"얌은 녹말이 많아요."},
    {e:"Taro",p:"[ˈtɛroʊ]",k:"토란",ee:"Taro is used in soups.",ek:"토란은 국에 넣어요."},
    {e:"Fennel",p:"[ˈfenl]",k:"회향",ee:"Fennel has a sweet smell.",ek:"회향은 달콤한 향이 나요."},
    {e:"Okra",p:"[ˈoʊkrə]",k:"오크라",ee:"Okra is sticky inside.",ek:"오크라는 안쪽이 끈적해요."},
    {e:"Lentil",p:"[ˈlentl]",k:"렌틸콩",ee:"Lentils are full of iron.",ek:"렌틸콩에는 철분이 많아요."}
  ]},
  {id:"fruits",name:"과일",icon:"🍓",words:[
    {e:"Apple",p:"[ˈæpl]",k:"사과",ee:"I eat an apple.",ek:"나는 사과를 먹어요."},
    {e:"Banana",p:"[bəˈnænə]",k:"바나나",ee:"Bananas are yellow.",ek:"바나나는 노란색이에요."},
    {e:"Orange",p:"[ˈɔːrɪndʒ]",k:"오렌지",ee:"Oranges are juicy.",ek:"오렌지는 즙이 많아요."},
    {e:"Strawberry",p:"[ˈstrɔːberi]",k:"딸기",ee:"Strawberries are red.",ek:"딸기는 빨간색이에요."},
    {e:"Grape",p:"[ɡreɪp]",k:"포도",ee:"Grapes grow in bunches.",ek:"포도는 송이로 자라요."},
    {e:"Watermelon",p:"[ˈwɔːtərmelən]",k:"수박",ee:"Watermelon is sweet.",ek:"수박은 달아요."},
    {e:"Peach",p:"[piːtʃ]",k:"복숭아",ee:"Peaches are soft.",ek:"복숭아는 부드러워요."},
    {e:"Pear",p:"[per]",k:"배",ee:"Pears are juicy.",ek:"배는 즙이 많아요."},
    {e:"Mango",p:"[ˈmæŋɡoʊ]",k:"망고",ee:"Mangoes are tropical.",ek:"망고는 열대 과일이에요."},
    {e:"Pineapple",p:"[ˈpaɪnæpl]",k:"파인애플",ee:"Pineapples are spiky.",ek:"파인애플은 가시가 있어요."},
    {e:"Cherry",p:"[ˈtʃeri]",k:"체리",ee:"Cherries are small and red.",ek:"체리는 작고 빨간색이에요."},
    {e:"Lemon",p:"[ˈlemən]",k:"레몬",ee:"Lemons are sour.",ek:"레몬은 셔요."},
    {e:"Lime",p:"[laɪm]",k:"라임",ee:"Limes are green.",ek:"라임은 초록색이에요."},
    {e:"Kiwi",p:"[ˈkiːwi]",k:"키위",ee:"Kiwis are fuzzy outside.",ek:"키위는 겉이 fuzzy해요."},
    {e:"Melon",p:"[ˈmelən]",k:"멜론",ee:"Melons smell sweet.",ek:"멜론은 향기가 달아요."},
    {e:"Blueberry",p:"[ˈbluːberi]",k:"블루베리",ee:"Blueberries are tiny.",ek:"블루베리는 작아요."},
    {e:"Raspberry",p:"[ˈræzberi]",k:"산딸기",ee:"Raspberries are tart.",ek:"산딸기는 새콤해요."},
    {e:"Plum",p:"[plʌm]",k:"자두",ee:"Plums are purple.",ek:"자두는 보라색이에요."},
    {e:"Apricot",p:"[ˈeɪprɪkɑːt]",k:"살구",ee:"Apricots are orange.",ek:"살구는 주황색이에요."},
    {e:"Coconut",p:"[ˈkoʊkənʌt]",k:"코코넛",ee:"Coconuts have white inside.",ek:"코코넛 안은 하얀색이에요."},
    {e:"Papaya",p:"[pəˈpaɪə]",k:"파파야",ee:"Papayas are tropical.",ek:"파파야는 열대 과일이에요."},
    {e:"Guava",p:"[ˈɡwɑːvə]",k:"구아바",ee:"Guavas smell great.",ek:"구아바는 향기가 좋아요."},
    {e:"Passion fruit",p:"[ˈpæʃn fruːt]",k:"패션프루트",ee:"Passion fruit is exotic.",ek:"패션프루트는 이국적이에요."},
    {e:"Lychee",p:"[ˈliːtʃiː]",k:"리치",ee:"Lychees are sweet.",ek:"리치는 달아요."},
    {e:"Dragon fruit",p:"[ˈdræɡən fruːt]",k:"드래곤프루트",ee:"Dragon fruit is colorful.",ek:"드래곤프루트는 색이 화려해요."},
    {e:"Fig",p:"[fɪɡ]",k:"무화과",ee:"Figs are sweet and soft.",ek:"무화과는 달고 부드러워요."},
    {e:"Persimmon",p:"[pərˈsɪmən]",k:"감",ee:"Persimmons are orange.",ek:"감은 주황색이에요."},
    {e:"Pomegranate",p:"[ˈpɑːmɪɡrænɪt]",k:"석류",ee:"Pomegranates have red seeds.",ek:"석류에는 빨간 씨앗이 있어요."},
    {e:"Tangerine",p:"[ˌtændʒəˈriːn]",k:"귤",ee:"Tangerines are small oranges.",ek:"귤은 작은 오렌지예요."},
    {e:"Grapefruit",p:"[ˈɡreɪpfruːt]",k:"자몽",ee:"Grapefruits are bitter.",ek:"자몽은 써요."},
    {e:"Avocado",p:"[ˌævəˈkɑːdoʊ]",k:"아보카도",ee:"Avocados are creamy.",ek:"아보카도는 크리미해요."},
    {e:"Mulberry",p:"[ˈmʌlberi]",k:"오디",ee:"Mulberries are dark purple.",ek:"오디는 짙은 보라색이에요."},
    {e:"Jackfruit",p:"[ˈdʒækfruːt]",k:"잭프루트",ee:"Jackfruit is very large.",ek:"잭프루트는 매우 커요."},
    {e:"Durian",p:"[ˈdʊriən]",k:"두리안",ee:"Durian smells strong.",ek:"두리안은 냄새가 강해요."},
    {e:"Starfruit",p:"[ˈstɑːrfruːt]",k:"스타프루트",ee:"Starfruit looks like a star.",ek:"스타프루트는 별 모양이에요."},
    {e:"Cantaloupe",p:"[ˈkæntəloʊp]",k:"캔탈루프",ee:"Cantaloupes are sweet.",ek:"캔탈루프는 달아요."},
    {e:"Honeydew",p:"[ˈhʌnidʒuː]",k:"허니듀",ee:"Honeydew is pale green.",ek:"허니듀는 연한 초록색이에요."},
    {e:"Nectarine",p:"[ˈnektəriːn]",k:"천도복숭아",ee:"Nectarines are smooth.",ek:"천도복숭아는 매끈해요."},
    {e:"Quince",p:"[kwɪns]",k:"모과",ee:"Quince smells great.",ek:"모과는 향기가 좋아요."},
    {e:"Blackberry",p:"[ˈblækberi]",k:"블랙베리",ee:"Blackberries are dark.",ek:"블랙베리는 색이 어두워요."},
    {e:"Mandarin",p:"[ˈmændərɪn]",k:"만다린",ee:"Mandarins are easy to peel.",ek:"만다린은 껍질을 벗기기 쉬어요."},
    {e:"Clementine",p:"[ˈkleməntiːn]",k:"클레멘타인",ee:"Clementines are tiny.",ek:"클레멘타인은 작아요."},
    {e:"Ugli fruit",p:"[ˈʌɡli fruːt]",k:"어글리 프루트",ee:"Ugli fruit tastes sweet.",ek:"어글리 프루트는 달아요."},
    {e:"Rambutan",p:"[ræmˈbuːtən]",k:"람부탄",ee:"Rambutans are hairy.",ek:"람부탄은 겉이 털이 나 있어요."},
    {e:"Longan",p:"[ˈlɔːŋɡən]",k:"용안",ee:"Longans look like grapes.",ek:"용안은 포도처럼 생겼어요."},
    {e:"Tamarind",p:"[ˈtæmərɪnd]",k:"타마린드",ee:"Tamarind is sour.",ek:"타마린드는 셔요."},
    {e:"Soursop",p:"[ˈsaʊrsɑːp]",k:"사워솝",ee:"Soursop is tropical.",ek:"사워솝은 열대 과일이에요."},
    {e:"Sapodilla",p:"[ˌsæpəˈdɪlə]",k:"사포딜라",ee:"Sapodilla is sweet.",ek:"사포딜라는 달아요."},
    {e:"Feijoa",p:"[feɪˈʒoʊə]",k:"페이조아",ee:"Feijoa is from South America.",ek:"페이조아는 남미에서 왔어요."},
    {e:"Breadfruit",p:"[ˈbredfruːt]",k:"빵나무열매",ee:"Breadfruit is starchy.",ek:"빵나무열매는 녹말이 많아요."}
  ]},
  {id:"taste",name:"맛 표현",icon:"😋",words:[
    {e:"Sweet",p:"[swiːt]",k:"달콤한",ee:"Honey is sweet.",ek:"꿀은 달콤해요."},
    {e:"Sour",p:"[saʊər]",k:"신",ee:"Lemons are sour.",ek:"레몬은 셔요."},
    {e:"Salty",p:"[ˈsɔːlti]",k:"짠",ee:"The soup is too salty.",ek:"수프가 너무 짜요."},
    {e:"Spicy",p:"[ˈspaɪsi]",k:"매운",ee:"This food is spicy.",ek:"이 음식은 매워요."},
    {e:"Bitter",p:"[ˈbɪtər]",k:"쓴",ee:"Coffee is bitter.",ek:"커피는 써요."},
    {e:"Savory",p:"[ˈseɪvəri]",k:"감칠맛 나는",ee:"This dish is savory.",ek:"이 요리는 감칠맛이 나요."},
    {e:"Bland",p:"[blænd]",k:"싱거운",ee:"The porridge is bland.",ek:"죽이 싱거워요."},
    {e:"Tangy",p:"[ˈtæŋɡi]",k:"새콤한",ee:"This yogurt is tangy.",ek:"이 요거트는 새콤해요."},
    {e:"Smoky",p:"[ˈsmoʊki]",k:"훈제 맛 나는",ee:"The meat is smoky.",ek:"고기에서 훈제 향이 나요."},
    {e:"Rich",p:"[rɪtʃ]",k:"진한",ee:"This soup is rich.",ek:"이 수프는 진해요."},
    {e:"Fresh",p:"[freʃ]",k:"신선한",ee:"The salad is fresh.",ek:"샐러드가 신선해요."},
    {e:"Stale",p:"[steɪl]",k:"상한",ee:"The bread is stale.",ek:"빵이 상했어요."},
    {e:"Crispy",p:"[ˈkrɪspi]",k:"바삭한",ee:"Chips are crispy.",ek:"과자가 바삭해요."},
    {e:"Chewy",p:"[ˈtʃuːi]",k:"쫄깃한",ee:"Gummy bears are chewy.",ek:"젤리 곰돌이는 쫄깃해요."},
    {e:"Crunchy",p:"[ˈkrʌntʃi]",k:"아삭한",ee:"Carrots are crunchy.",ek:"당근은 아삭해요."},
    {e:"Soft",p:"[sɔːft]",k:"부드러운",ee:"The cake is soft.",ek:"케이크가 부드러워요."},
    {e:"Creamy",p:"[ˈkriːmi]",k:"크림 같은",ee:"This ice cream is creamy.",ek:"이 아이스크림은 크리미해요."},
    {e:"Fluffy",p:"[ˈflʌfi]",k:"폭신한",ee:"Pancakes are fluffy.",ek:"팬케이크는 폭신해요."},
    {e:"Tender",p:"[ˈtendər]",k:"연한",ee:"The meat is tender.",ek:"고기가 연해요."},
    {e:"Tough",p:"[tʌf]",k:"질긴",ee:"This beef is tough.",ek:"이 쇠고기는 질겨요."},
    {e:"Juicy",p:"[ˈdʒuːsi]",k:"즙이 많은",ee:"Oranges are juicy.",ek:"오렌지는 즙이 많아요."},
    {e:"Dry",p:"[draɪ]",k:"퍽퍽한",ee:"The chicken is dry.",ek:"닭고기가 퍽퍽해요."},
    {e:"Greasy",p:"[ˈɡriːsi]",k:"기름진",ee:"Fast food is greasy.",ek:"패스트푸드는 기름져요."},
    {e:"Light",p:"[laɪt]",k:"담백한",ee:"The salad is light.",ek:"샐러드는 담백해요."},
    {e:"Heavy",p:"[ˈhevi]",k:"묵직한",ee:"This pasta is heavy.",ek:"이 파스타는 묵직해요."},
    {e:"Fishy",p:"[ˈfɪʃi]",k:"비린내 나는",ee:"Raw fish smells fishy.",ek:"날 생선은 비린내가 나요."},
    {e:"Nutty",p:"[ˈnʌti]",k:"고소한",ee:"This butter smells nutty.",ek:"이 버터에서 고소한 향이 나요."},
    {e:"Flavorful",p:"[ˈfleɪvərfl]",k:"풍미 있는",ee:"This stew is very flavorful.",ek:"이 찌개는 풍미가 있어요."},
    {e:"Mild",p:"[maɪld]",k:"순한",ee:"This sauce is mild.",ek:"이 소스는 순해요."},
    {e:"Pungent",p:"[ˈpʌndʒənt]",k:"자극적인",ee:"Kimchi is pungent.",ek:"김치는 자극적이에요."},
    {e:"Delicious",p:"[dɪˈlɪʃəs]",k:"맛있는",ee:"This is delicious!",ek:"이것은 맛있어요!"},
    {e:"Yummy",p:"[ˈjʌmi]",k:"야미한",ee:"The cookie is yummy.",ek:"쿠키가 야미해요."},
    {e:"Gross",p:"[ɡroʊs]",k:"역겨운",ee:"That smells gross.",ek:"저것은 냄새가 역겨워요."},
    {e:"Tasty",p:"[ˈteɪsti]",k:"맛좋은",ee:"The pizza is tasty.",ek:"피자가 맛좋아요."},
    {e:"Appetizing",p:"[ˈæpɪtaɪzɪŋ]",k:"식욕을 돋우는",ee:"That looks appetizing.",ek:"저것은 식욕을 돋워요."},
    {e:"Bland",p:"[blænd]",k:"무미건조한",ee:"Plain tofu is bland.",ek:"맹물 두부는 무미건조해요."},
    {e:"Refreshing",p:"[rɪˈfreʃɪŋ]",k:"상쾌한",ee:"Lemonade is refreshing.",ek:"레모네이드는 상쾌해요."},
    {e:"Warming",p:"[ˈwɔːrmɪŋ]",k:"따뜻한",ee:"This soup is warming.",ek:"이 수프는 따뜻해요."},
    {e:"Cooling",p:"[ˈkuːlɪŋ]",k:"시원한",ee:"Mint is cooling.",ek:"민트는 시원해요."},
    {e:"Aromatic",p:"[ˌærəˈmætɪk]",k:"향긋한",ee:"The garlic is aromatic.",ek:"마늘이 향긋해요."},
    {e:"Bland",p:"[blænd]",k:"맛없는",ee:"The meal was bland.",ek:"그 식사는 맛이 없었어요."},
    {e:"Overpowering",p:"[ˌoʊvərˈpaʊərɪŋ]",k:"냄새가 강한",ee:"The perfume is overpowering.",ek:"그 향수는 냄새가 강해요."},
    {e:"Subtle",p:"[ˈsʌtl]",k:"은은한",ee:"The flavor is subtle.",ek:"맛이 은은해요."},
    {e:"Addictive",p:"[əˈdɪktɪv]",k:"중독성 있는",ee:"This snack is addictive.",ek:"이 과자는 중독성이 있어요."},
    {e:"Mouthwatering",p:"[ˈmaʊθwɔːtərɪŋ]",k:"군침 도는",ee:"The smell is mouthwatering.",ek:"냄새가 군침을 돌게 해요."},
    {e:"Scrumptious",p:"[ˈskrʌmpʃəs]",k:"아주 맛있는",ee:"The cake is scrumptious.",ek:"케이크가 아주 맛있어요."},
    {e:"Zesty",p:"[ˈzesti]",k:"상큼한",ee:"This salad is zesty.",ek:"이 샐러드는 상큼해요."},
    {e:"Hearty",p:"[ˈhɑːrti]",k:"든든한",ee:"A hearty meal fills you.",ek:"든든한 식사는 포만감을 줘요."},
    {e:"Gooey",p:"[ˈɡuːi]",k:"끈적한",ee:"Melted cheese is gooey.",ek:"녹은 치즈는 끈적해요."},
    {e:"Minty",p:"[ˈmɪnti]",k:"민트 향의",ee:"This gum is minty.",ek:"이 껌은 민트 향이에요."}
  ]},
  {id:"school",name:"학교",icon:"🏫",words:[
    {e:"Book",p:"[bʊk]",k:"책",ee:"I read a book.",ek:"나는 책을 읽어요."},
    {e:"Pencil",p:"[ˈpensl]",k:"연필",ee:"I write with a pencil.",ek:"연필로 써요."},
    {e:"Eraser",p:"[ɪˈreɪsər]",k:"지우개",ee:"Use an eraser to fix mistakes.",ek:"실수는 지우개로 고쳐요."},
    {e:"Ruler",p:"[ˈruːlər]",k:"자",ee:"Use a ruler to draw a line.",ek:"선을 그을 때 자를 써요."},
    {e:"Scissors",p:"[ˈsɪzərz]",k:"가위",ee:"Cut with scissors.",ek:"가위로 잘라요."},
    {e:"Desk",p:"[desk]",k:"책상",ee:"Sit at your desk.",ek:"책상에 앉으세요."},
    {e:"Chair",p:"[tʃer]",k:"의자",ee:"Pull out your chair.",ek:"의자를 빼세요."},
    {e:"Board",p:"[bɔːrd]",k:"칠판",ee:"Write on the board.",ek:"칠판에 쓰세요."},
    {e:"Teacher",p:"[ˈtiːtʃər]",k:"선생님",ee:"My teacher is kind.",ek:"우리 선생님은 친절해요."},
    {e:"Student",p:"[ˈstuːdnt]",k:"학생",ee:"Students study hard.",ek:"학생들은 열심히 공부해요."},
    {e:"Class",p:"[klæs]",k:"수업",ee:"Class starts at 9.",ek:"수업은 9시에 시작해요."},
    {e:"Homework",p:"[ˈhoʊmwɜːrk]",k:"숙제",ee:"I do my homework.",ek:"나는 숙제를 해요."},
    {e:"Test",p:"[test]",k:"시험",ee:"We have a test today.",ek:"오늘 시험이 있어요."},
    {e:"Notebook",p:"[ˈnoʊtbʊk]",k:"공책",ee:"Write in your notebook.",ek:"공책에 써요."},
    {e:"Bag",p:"[bæɡ]",k:"가방",ee:"Pack your bag.",ek:"가방을 싸세요."},
    {e:"Library",p:"[ˈlaɪbreri]",k:"도서관",ee:"Borrow books at the library.",ek:"도서관에서 책을 빌려요."},
    {e:"Playground",p:"[ˈpleɪɡraʊnd]",k:"운동장",ee:"We play on the playground.",ek:"운동장에서 놀아요."},
    {e:"Uniform",p:"[ˈjuːnɪfɔːrm]",k:"교복",ee:"I wear a uniform.",ek:"나는 교복을 입어요."},
    {e:"Lesson",p:"[ˈlesn]",k:"수업",ee:"Today's lesson is math.",ek:"오늘 수업은 수학이에요."},
    {e:"Answer",p:"[ˈænsər]",k:"답",ee:"Raise your hand to answer.",ek:"답할 때 손을 드세요."},
    {e:"Question",p:"[ˈkwestʃən]",k:"질문",ee:"Ask a question.",ek:"질문을 하세요."},
    {e:"Pen",p:"[pen]",k:"펜",ee:"Use a pen to sign.",ek:"서명할 때 펜을 써요."},
    {e:"Marker",p:"[ˈmɑːrkər]",k:"마커",ee:"Draw with a marker.",ek:"마커로 그려요."},
    {e:"Crayon",p:"[ˈkreɪɑːn]",k:"크레용",ee:"Color with crayons.",ek:"크레용으로 색칠해요."},
    {e:"Paint",p:"[peɪnt]",k:"물감",ee:"We use paint in art class.",ek:"미술 시간에 물감을 써요."},
    {e:"Glue",p:"[ɡluː]",k:"풀",ee:"Stick with glue.",ek:"풀로 붙여요."},
    {e:"Tape",p:"[teɪp]",k:"테이프",ee:"Use tape to fix it.",ek:"테이프로 붙여요."},
    {e:"Compass",p:"[ˈkʌmpəs]",k:"컴퍼스",ee:"Draw a circle with a compass.",ek:"컴퍼스로 원을 그려요."},
    {e:"Calculator",p:"[ˈkælkjuleɪtər]",k:"계산기",ee:"Use a calculator for math.",ek:"수학에 계산기를 써요."},
    {e:"Globe",p:"[ɡloʊb]",k:"지구본",ee:"A globe shows the Earth.",ek:"지구본은 지구를 보여줘요."},
    {e:"Map",p:"[mæp]",k:"지도",ee:"Find places on a map.",ek:"지도에서 장소를 찾아요."},
    {e:"Report",p:"[rɪˈpɔːrt]",k:"보고서",ee:"Write a report.",ek:"보고서를 써요."},
    {e:"Project",p:"[ˈprɑːdʒekt]",k:"프로젝트",ee:"We do a group project.",ek:"우리는 그룹 프로젝트를 해요."},
    {e:"Grade",p:"[ɡreɪd]",k:"학년/점수",ee:"I got a good grade.",ek:"나는 좋은 점수를 받았어요."},
    {e:"Schedule",p:"[ˈskedʒuːl]",k:"시간표",ee:"Check your schedule.",ek:"시간표를 확인하세요."},
    {e:"Break",p:"[breɪk]",k:"쉬는 시간",ee:"It is break time.",ek:"쉬는 시간이에요."},
    {e:"Lunch",p:"[lʌntʃ]",k:"점심",ee:"We eat lunch at noon.",ek:"우리는 정오에 점심을 먹어요."},
    {e:"Club",p:"[klʌb]",k:"동아리",ee:"I joined a science club.",ek:"나는 과학 동아리에 가입했어요."},
    {e:"Principal",p:"[ˈprɪnsɪpl]",k:"교장선생님",ee:"The principal gave a speech.",ek:"교장선생님이 연설을 했어요."},
    {e:"Classroom",p:"[ˈklæsruːm]",k:"교실",ee:"We study in the classroom.",ek:"우리는 교실에서 공부해요."},
    {e:"Hallway",p:"[ˈhɔːlweɪ]",k:"복도",ee:"Walk slowly in the hallway.",ek:"복도에서 천천히 걸어요."},
    {e:"Gym",p:"[dʒɪm]",k:"체육관",ee:"We exercise in the gym.",ek:"우리는 체육관에서 운동해요."},
    {e:"Cafeteria",p:"[ˌkæfəˈtɪriə]",k:"식당",ee:"We eat at the cafeteria.",ek:"우리는 식당에서 먹어요."},
    {e:"Locker",p:"[ˈlɑːkər]",k:"사물함",ee:"Keep things in your locker.",ek:"사물함에 물건을 보관해요."},
    {e:"Flag",p:"[flæɡ]",k:"국기",ee:"We salute the flag.",ek:"우리는 국기에 경례해요."},
    {e:"Bell",p:"[bel]",k:"종",ee:"The bell rings at 9.",ek:"9시에 종이 울려요."},
    {e:"Textbook",p:"[ˈtekstbʊk]",k:"교과서",ee:"Open your textbook.",ek:"교과서를 펴세요."},
    {e:"Dictionary",p:"[ˈdɪkʃəneri]",k:"사전",ee:"Look it up in the dictionary.",ek:"사전에서 찾아보세요."},
    {e:"Science",p:"[ˈsaɪəns]",k:"과학",ee:"I love science class.",ek:"나는 과학 수업을 좋아해요."},
    {e:"Math",p:"[mæθ]",k:"수학",ee:"Math is fun.",ek:"수학은 재미있어요."}
  ]},
  {id:"body",name:"신체",icon:"🧍",words:[
    {e:"Head",p:"[hed]",k:"머리",ee:"My head hurts.",ek:"머리가 아파요."},
    {e:"Face",p:"[feɪs]",k:"얼굴",ee:"Wash your face.",ek:"얼굴을 씻으세요."},
    {e:"Eye",p:"[aɪ]",k:"눈",ee:"Close your eyes.",ek:"눈을 감으세요."},
    {e:"Ear",p:"[ɪr]",k:"귀",ee:"I can hear with my ears.",ek:"귀로 들을 수 있어요."},
    {e:"Nose",p:"[noʊz]",k:"코",ee:"My nose is cold.",ek:"코가 차가워요."},
    {e:"Mouth",p:"[maʊθ]",k:"입",ee:"Open your mouth.",ek:"입을 벌리세요."},
    {e:"Tooth",p:"[tuːθ]",k:"이",ee:"Brush your teeth.",ek:"이를 닦으세요."},
    {e:"Hand",p:"[hænd]",k:"손",ee:"Wash your hands.",ek:"손을 씻으세요."},
    {e:"Finger",p:"[ˈfɪŋɡər]",k:"손가락",ee:"I have five fingers.",ek:"손가락이 다섯 개예요."},
    {e:"Arm",p:"[ɑːrm]",k:"팔",ee:"Stretch your arms.",ek:"팔을 뻗으세요."},
    {e:"Leg",p:"[leɡ]",k:"다리",ee:"My legs are tired.",ek:"다리가 피곤해요."},
    {e:"Foot",p:"[fʊt]",k:"발",ee:"My feet are small.",ek:"발이 작아요."},
    {e:"Knee",p:"[niː]",k:"무릎",ee:"I hurt my knee.",ek:"무릎을 다쳤어요."},
    {e:"Shoulder",p:"[ˈʃoʊldər]",k:"어깨",ee:"My shoulders are wide.",ek:"어깨가 넓어요."},
    {e:"Back",p:"[bæk]",k:"등",ee:"My back is sore.",ek:"등이 아파요."},
    {e:"Stomach",p:"[ˈstʌmək]",k:"배",ee:"My stomach is full.",ek:"배가 불러요."},
    {e:"Chest",p:"[tʃest]",k:"가슴",ee:"My heart is in my chest.",ek:"심장은 가슴에 있어요."},
    {e:"Neck",p:"[nek]",k:"목",ee:"I have a stiff neck.",ek:"목이 뻣뻣해요."},
    {e:"Hair",p:"[her]",k:"머리카락",ee:"She has long hair.",ek:"그녀는 머리카락이 길어요."},
    {e:"Skin",p:"[skɪn]",k:"피부",ee:"Take care of your skin.",ek:"피부를 관리하세요."},
    {e:"Lip",p:"[lɪp]",k:"입술",ee:"Her lips are red.",ek:"그녀의 입술은 빨간색이에요."},
    {e:"Tongue",p:"[tʌŋ]",k:"혀",ee:"Taste with your tongue.",ek:"혀로 맛을 봐요."},
    {e:"Cheek",p:"[tʃiːk]",k:"뺨",ee:"Her cheeks are pink.",ek:"그녀의 뺨은 분홍색이에요."},
    {e:"Chin",p:"[tʃɪn]",k:"턱",ee:"Hold your chin up.",ek:"턱을 들어요."},
    {e:"Forehead",p:"[ˈfɔːrhed]",k:"이마",ee:"Touch your forehead.",ek:"이마를 만져요."},
    {e:"Eyebrow",p:"[ˈaɪbraʊ]",k:"눈썹",ee:"Raise your eyebrows.",ek:"눈썹을 올려요."},
    {e:"Eyelash",p:"[ˈaɪlæʃ]",k:"속눈썹",ee:"She has long eyelashes.",ek:"그녀는 속눈썹이 길어요."},
    {e:"Wrist",p:"[rɪst]",k:"손목",ee:"My wrist is weak.",ek:"손목이 약해요."},
    {e:"Elbow",p:"[ˈelboʊ]",k:"팔꿈치",ee:"Bend your elbow.",ek:"팔꿈치를 구부려요."},
    {e:"Thumb",p:"[θʌm]",k:"엄지손가락",ee:"Give a thumbs up!",ek:"엄지 척!"},
    {e:"Palm",p:"[pɑːm]",k:"손바닥",ee:"Put it in your palm.",ek:"손바닥에 올려요."},
    {e:"Nail",p:"[neɪl]",k:"손톱",ee:"Cut your nails.",ek:"손톱을 잘라요."},
    {e:"Ankle",p:"[ˈæŋkl]",k:"발목",ee:"I twisted my ankle.",ek:"발목을 삐었어요."},
    {e:"Toe",p:"[toʊ]",k:"발가락",ee:"Wiggle your toes.",ek:"발가락을 움직여요."},
    {e:"Heel",p:"[hiːl]",k:"발뒤꿈치",ee:"My heel hurts.",ek:"발뒤꿈치가 아파요."},
    {e:"Hip",p:"[hɪp]",k:"엉덩이",ee:"Shake your hips.",ek:"엉덩이를 흔들어요."},
    {e:"Thigh",p:"[θaɪ]",k:"허벅지",ee:"My thighs are sore.",ek:"허벅지가 아파요."},
    {e:"Calf",p:"[kæf]",k:"종아리",ee:"My calf muscle aches.",ek:"종아리 근육이 아파요."},
    {e:"Spine",p:"[spaɪn]",k:"척추",ee:"Keep your spine straight.",ek:"척추를 곧게 펴요."},
    {e:"Rib",p:"[rɪb]",k:"갈비뼈",ee:"Ribs protect your heart.",ek:"갈비뼈는 심장을 보호해요."},
    {e:"Lung",p:"[lʌŋ]",k:"폐",ee:"Breathe with your lungs.",ek:"폐로 숨을 쉬어요."},
    {e:"Heart",p:"[hɑːrt]",k:"심장",ee:"My heart beats fast.",ek:"심장이 빠르게 뛰어요."},
    {e:"Brain",p:"[breɪn]",k:"뇌",ee:"Your brain is smart.",ek:"뇌는 똑똑해요."},
    {e:"Blood",p:"[blʌd]",k:"피",ee:"Blood flows in our body.",ek:"피가 몸 안에서 흘러요."},
    {e:"Bone",p:"[boʊn]",k:"뼈",ee:"Bones are strong.",ek:"뼈는 강해요."},
    {e:"Muscle",p:"[ˈmʌsl]",k:"근육",ee:"Build your muscles.",ek:"근육을 키워요."},
    {e:"Tongue",p:"[tʌŋ]",k:"혀",ee:"Stick out your tongue.",ek:"혀를 내밀어요."},
    {e:"Throat",p:"[θroʊt]",k:"목구멍",ee:"My throat is sore.",ek:"목구멍이 아파요."},
    {e:"Jaw",p:"[dʒɔː]",k:"턱뼈",ee:"My jaw hurts.",ek:"턱뼈가 아파요."},
    {e:"Temple",p:"[ˈtempl]",k:"관자놀이",ee:"Press your temples.",ek:"관자놀이를 눌러요."}
  ]},
  {id:"nature",name:"자연/날씨",icon:"🌿",words:[
    {e:"Sun",p:"[sʌn]",k:"태양",ee:"The sun is bright.",ek:"태양이 밝아요."},
    {e:"Moon",p:"[muːn]",k:"달",ee:"The moon shines at night.",ek:"달이 밤에 빛나요."},
    {e:"Star",p:"[stɑːr]",k:"별",ee:"Stars are beautiful.",ek:"별은 아름다워요."},
    {e:"Cloud",p:"[klaʊd]",k:"구름",ee:"Dark clouds bring rain.",ek:"어두운 구름은 비를 가져와요."},
    {e:"Rain",p:"[reɪn]",k:"비",ee:"It will rain today.",ek:"오늘 비가 올 거예요."},
    {e:"Snow",p:"[snoʊ]",k:"눈",ee:"Snow is cold and white.",ek:"눈은 차갑고 하얘요."},
    {e:"Wind",p:"[wɪnd]",k:"바람",ee:"The wind is strong.",ek:"바람이 강해요."},
    {e:"Tree",p:"[triː]",k:"나무",ee:"Trees give us air.",ek:"나무는 공기를 줘요."},
    {e:"Flower",p:"[ˈflaʊər]",k:"꽃",ee:"Flowers smell nice.",ek:"꽃은 냄새가 좋아요."},
    {e:"Grass",p:"[ɡræs]",k:"풀",ee:"Grass is green.",ek:"풀은 초록색이에요."},
    {e:"Mountain",p:"[ˈmaʊntən]",k:"산",ee:"The mountain is tall.",ek:"산이 높아요."},
    {e:"River",p:"[ˈrɪvər]",k:"강",ee:"The river flows fast.",ek:"강이 빠르게 흘러요."},
    {e:"Lake",p:"[leɪk]",k:"호수",ee:"The lake is calm.",ek:"호수는 고요해요."},
    {e:"Sea",p:"[siː]",k:"바다",ee:"The sea is big.",ek:"바다는 넓어요."},
    {e:"Sand",p:"[sænd]",k:"모래",ee:"Sand is on the beach.",ek:"해변에 모래가 있어요."},
    {e:"Rock",p:"[rɑːk]",k:"바위",ee:"Rocks are hard.",ek:"바위는 단단해요."},
    {e:"Leaf",p:"[liːf]",k:"잎",ee:"Leaves fall in autumn.",ek:"가을에 잎이 떨어져요."},
    {e:"Seed",p:"[siːd]",k:"씨앗",ee:"Plant the seed in soil.",ek:"씨앗을 흙에 심으세요."},
    {e:"Sky",p:"[skaɪ]",k:"하늘",ee:"The sky is blue.",ek:"하늘은 파란색이에요."},
    {e:"Season",p:"[ˈsiːzn]",k:"계절",ee:"There are four seasons.",ek:"계절은 네 가지예요."},
    {e:"Spring",p:"[sprɪŋ]",k:"봄",ee:"Spring is warm.",ek:"봄은 따뜻해요."},
    {e:"Summer",p:"[ˈsʌmər]",k:"여름",ee:"Summer is hot.",ek:"여름은 더워요."},
    {e:"Autumn",p:"[ˈɔːtəm]",k:"가을",ee:"Autumn leaves are red.",ek:"가을 잎은 빨간색이에요."},
    {e:"Winter",p:"[ˈwɪntər]",k:"겨울",ee:"Winter is very cold.",ek:"겨울은 매우 추워요."},
    {e:"Storm",p:"[stɔːrm]",k:"폭풍",ee:"A storm is coming.",ek:"폭풍이 오고 있어요."},
    {e:"Thunder",p:"[ˈθʌndər]",k:"천둥",ee:"Thunder is loud.",ek:"천둥은 시끄러워요."},
    {e:"Lightning",p:"[ˈlaɪtnɪŋ]",k:"번개",ee:"Lightning flashes fast.",ek:"번개는 빠르게 번쩍여요."},
    {e:"Rainbow",p:"[ˈreɪnboʊ]",k:"무지개",ee:"A rainbow has seven colors.",ek:"무지개는 일곱 가지 색이에요."},
    {e:"Fog",p:"[fɑːɡ]",k:"안개",ee:"Fog makes it hard to see.",ek:"안개는 보기 어렵게 해요."},
    {e:"Hail",p:"[heɪl]",k:"우박",ee:"Hail is frozen rain.",ek:"우박은 얼어붙은 비예요."},
    {e:"Frost",p:"[frɔːst]",k:"서리",ee:"Frost covers the ground.",ek:"서리가 땅을 덮어요."},
    {e:"Dew",p:"[djuː]",k:"이슬",ee:"Dew forms in the morning.",ek:"이슬은 아침에 맺혀요."},
    {e:"Humidity",p:"[hjuːˈmɪdɪti]",k:"습도",ee:"High humidity is sticky.",ek:"습도가 높으면 끈적해요."},
    {e:"Temperature",p:"[ˈtemprətʃər]",k:"온도",ee:"Check the temperature.",ek:"온도를 확인해요."},
    {e:"Desert",p:"[ˈdezərt]",k:"사막",ee:"Deserts are hot and dry.",ek:"사막은 덥고 건조해요."},
    {e:"Forest",p:"[ˈfɔːrɪst]",k:"숲",ee:"Animals live in the forest.",ek:"동물들이 숲에 살아요."},
    {e:"Jungle",p:"[ˈdʒʌŋɡl]",k:"정글",ee:"Jungles are dense.",ek:"정글은 울창해요."},
    {e:"Cave",p:"[keɪv]",k:"동굴",ee:"Bats live in caves.",ek:"박쥐는 동굴에 살아요."},
    {e:"Volcano",p:"[vɑːlˈkeɪnoʊ]",k:"화산",ee:"Volcanoes erupt lava.",ek:"화산은 용암을 분출해요."},
    {e:"Earthquake",p:"[ˈɜːrθkweɪk]",k:"지진",ee:"Earthquakes shake the ground.",ek:"지진은 땅을 흔들어요."},
    {e:"Waterfall",p:"[ˈwɔːtərfɔːl]",k:"폭포",ee:"The waterfall is loud.",ek:"폭포는 시끄러워요."},
    {e:"Glacier",p:"[ˈɡleɪʃər]",k:"빙하",ee:"Glaciers are made of ice.",ek:"빙하는 얼음으로 이루어져 있어요."},
    {e:"Tide",p:"[taɪd]",k:"조수",ee:"The tide comes in and out.",ek:"조수가 밀려왔다 나가요."},
    {e:"Wave",p:"[weɪv]",k:"파도",ee:"Big waves crash on the shore.",ek:"큰 파도가 해안에 부딪혀요."},
    {e:"Island",p:"[ˈaɪlənd]",k:"섬",ee:"An island is land in the sea.",ek:"섬은 바다 안의 땅이에요."},
    {e:"Valley",p:"[ˈvæli]",k:"계곡",ee:"Rivers flow through valleys.",ek:"강이 계곡을 흘러요."},
    {e:"Prairie",p:"[ˈpreri]",k:"초원",ee:"Animals graze on prairies.",ek:"동물들이 초원에서 풀을 먹어요."},
    {e:"Swamp",p:"[swɑːmp]",k:"늪",ee:"Swamps are wet and muddy.",ek:"늪은 축축하고 진흙이에요."},
    {e:"Soil",p:"[sɔɪl]",k:"흙",ee:"Plants grow in soil.",ek:"식물은 흙에서 자라요."},
    {e:"Air",p:"[er]",k:"공기",ee:"We breathe air.",ek:"우리는 공기를 마셔요."}
  ]},
  {id:"people",name:"사람/가족",icon:"👨‍👩‍👧",words:[
    {e:"Mother",p:"[ˈmʌðər]",k:"어머니",ee:"My mother cooks well.",ek:"어머니는 요리를 잘 해요."},
    {e:"Father",p:"[ˈfɑːðər]",k:"아버지",ee:"My father works hard.",ek:"아버지는 열심히 일해요."},
    {e:"Brother",p:"[ˈbrʌðər]",k:"남자 형제",ee:"My brother is older.",ek:"오빠(형)는 나보다 나이가 많아요."},
    {e:"Sister",p:"[ˈsɪstər]",k:"여자 형제",ee:"My sister is younger.",ek:"여동생은 나보다 어려요."},
    {e:"Baby",p:"[ˈbeɪbi]",k:"아기",ee:"The baby is cute.",ek:"아기가 귀여워요."},
    {e:"Child",p:"[tʃaɪld]",k:"어린이",ee:"The child is playing.",ek:"어린이가 놀고 있어요."},
    {e:"Boy",p:"[bɔɪ]",k:"남자아이",ee:"The boy is running.",ek:"남자아이가 달리고 있어요."},
    {e:"Girl",p:"[ɡɜːrl]",k:"여자아이",ee:"The girl is singing.",ek:"여자아이가 노래하고 있어요."},
    {e:"Man",p:"[mæn]",k:"남자",ee:"The man is tall.",ek:"그 남자는 키가 커요."},
    {e:"Woman",p:"[ˈwʊmən]",k:"여자",ee:"The woman is kind.",ek:"그 여자는 친절해요."},
    {e:"Friend",p:"[frend]",k:"친구",ee:"She is my best friend.",ek:"그녀는 나의 가장 친한 친구예요."},
    {e:"Grandma",p:"[ˈɡrænmɑː]",k:"할머니",ee:"Grandma tells stories.",ek:"할머니는 이야기를 해줘요."},
    {e:"Grandpa",p:"[ˈɡrænpɑː]",k:"할아버지",ee:"Grandpa goes fishing.",ek:"할아버지는 낚시를 가요."},
    {e:"Neighbor",p:"[ˈneɪbər]",k:"이웃",ee:"My neighbor is friendly.",ek:"이웃이 친근해요."},
    {e:"Doctor",p:"[ˈdɑːktər]",k:"의사",ee:"The doctor helps us.",ek:"의사는 우리를 도와줘요."},
    {e:"Police",p:"[pəˈliːs]",k:"경찰",ee:"Police keep us safe.",ek:"경찰이 우리를 안전하게 해줘요."},
    {e:"Farmer",p:"[ˈfɑːrmər]",k:"농부",ee:"Farmers grow food.",ek:"농부는 음식을 재배해요."},
    {e:"Cook",p:"[kʊk]",k:"요리사",ee:"The cook makes lunch.",ek:"요리사가 점심을 만들어요."},
    {e:"Uncle",p:"[ˈʌŋkl]",k:"삼촌",ee:"My uncle is funny.",ek:"삼촌이 재미있어요."},
    {e:"Aunt",p:"[ænt]",k:"이모/고모",ee:"My aunt bakes cakes.",ek:"이모는 케이크를 구워요."},
    {e:"Cousin",p:"[ˈkʌzn]",k:"사촌",ee:"My cousin lives far away.",ek:"사촌은 멀리 살아요."},
    {e:"Teenager",p:"[ˈtiːneɪdʒər]",k:"십대",ee:"Teenagers like music.",ek:"십대들은 음악을 좋아해요."},
    {e:"Adult",p:"[əˈdʌlt]",k:"어른",ee:"Adults go to work.",ek:"어른들은 일하러 가요."},
    {e:"Elder",p:"[ˈeldər]",k:"어르신",ee:"Respect your elders.",ek:"어르신을 공경하세요."},
    {e:"Classmate",p:"[ˈklæsmeɪt]",k:"반 친구",ee:"He is my classmate.",ek:"그는 내 반 친구예요."},
    {e:"Stranger",p:"[ˈstreɪndʒər]",k:"낯선 사람",ee:"Don't talk to strangers.",ek:"낯선 사람에게 말 걸지 마세요."},
    {e:"Volunteer",p:"[ˌvɑːlənˈtɪr]",k:"봉사자",ee:"Volunteers help the community.",ek:"봉사자는 지역사회를 도와요."},
    {e:"Athlete",p:"[ˈæθliːt]",k:"운동선수",ee:"Athletes train every day.",ek:"운동선수는 매일 훈련해요."},
    {e:"Artist",p:"[ˈɑːrtɪst]",k:"예술가",ee:"Artists create beautiful things.",ek:"예술가는 아름다운 것을 만들어요."},
    {e:"Scientist",p:"[ˈsaɪəntɪst]",k:"과학자",ee:"Scientists study the world.",ek:"과학자는 세상을 연구해요."},
    {e:"Engineer",p:"[ˌendʒɪˈnɪr]",k:"엔지니어",ee:"Engineers build things.",ek:"엔지니어는 것들을 만들어요."},
    {e:"Nurse",p:"[nɜːrs]",k:"간호사",ee:"Nurses care for patients.",ek:"간호사는 환자를 돌봐요."},
    {e:"Pilot",p:"[ˈpaɪlət]",k:"조종사",ee:"Pilots fly planes.",ek:"조종사는 비행기를 조종해요."},
    {e:"Firefighter",p:"[ˈfaɪərfaɪtər]",k:"소방관",ee:"Firefighters save lives.",ek:"소방관은 목숨을 구해요."},
    {e:"Chef",p:"[ʃef]",k:"주방장",ee:"The chef cooks well.",ek:"주방장은 요리를 잘 해요."},
    {e:"Driver",p:"[ˈdraɪvər]",k:"운전사",ee:"The driver stops the bus.",ek:"운전사가 버스를 멈춰요."},
    {e:"Singer",p:"[ˈsɪŋər]",k:"가수",ee:"The singer has a nice voice.",ek:"가수는 목소리가 좋아요."},
    {e:"Actor",p:"[ˈæktər]",k:"배우",ee:"Actors perform on stage.",ek:"배우는 무대에서 공연해요."},
    {e:"Writer",p:"[ˈraɪtər]",k:"작가",ee:"Writers create stories.",ek:"작가는 이야기를 만들어요."},
    {e:"Dentist",p:"[ˈdentɪst]",k:"치과의사",ee:"The dentist checks my teeth.",ek:"치과의사가 이를 검사해요."},
    {e:"Librarian",p:"[laɪˈbreriən]",k:"사서",ee:"The librarian helps find books.",ek:"사서는 책을 찾는 것을 도와요."},
    {e:"Soldier",p:"[ˈsoʊldʒər]",k:"군인",ee:"Soldiers protect our country.",ek:"군인은 나라를 보호해요."},
    {e:"Judge",p:"[dʒʌdʒ]",k:"판사",ee:"The judge makes decisions.",ek:"판사는 결정을 내려요."},
    {e:"Sailor",p:"[ˈseɪlər]",k:"선원",ee:"Sailors travel by sea.",ek:"선원은 바다로 여행해요."},
    {e:"Astronaut",p:"[ˈæstrənɔːt]",k:"우주비행사",ee:"Astronauts go to space.",ek:"우주비행사는 우주로 가요."},
    {e:"Mayor",p:"[meɪər]",k:"시장",ee:"The mayor runs the city.",ek:"시장이 도시를 운영해요."},
    {e:"Prince",p:"[prɪns]",k:"왕자",ee:"The prince lives in a castle.",ek:"왕자는 성에 살아요."},
    {e:"Princess",p:"[ˈprɪnses]",k:"공주",ee:"The princess is kind.",ek:"공주는 친절해요."},
    {e:"King",p:"[kɪŋ]",k:"왕",ee:"The king rules the land.",ek:"왕이 나라를 다스려요."},
    {e:"Queen",p:"[kwiːn]",k:"여왕",ee:"The queen is wise.",ek:"여왕은 현명해요."}
  ]},
  {id:"verbs",name:"일상동사",icon:"🏃",words:[
    {e:"Run",p:"[rʌn]",k:"달리다",ee:"I run every morning.",ek:"나는 매일 아침 달려요."},
    {e:"Walk",p:"[wɔːk]",k:"걷다",ee:"Walk to school.",ek:"학교까지 걸어가세요."},
    {e:"Jump",p:"[dʒʌmp]",k:"뛰다",ee:"Jump over the rope.",ek:"줄을 뛰어넘어요."},
    {e:"Sit",p:"[sɪt]",k:"앉다",ee:"Sit down, please.",ek:"앉으세요."},
    {e:"Stand",p:"[stænd]",k:"서다",ee:"Stand up straight.",ek:"똑바로 서세요."},
    {e:"Eat",p:"[iːt]",k:"먹다",ee:"Eat your vegetables.",ek:"채소를 드세요."},
    {e:"Drink",p:"[drɪŋk]",k:"마시다",ee:"Drink water often.",ek:"물을 자주 마세요."},
    {e:"Sleep",p:"[sliːp]",k:"자다",ee:"Sleep early tonight.",ek:"오늘 밤 일찍 자세요."},
    {e:"Wake",p:"[weɪk]",k:"일어나다",ee:"Wake up at seven.",ek:"일곱 시에 일어나세요."},
    {e:"Play",p:"[pleɪ]",k:"놀다",ee:"Let's play outside.",ek:"밖에서 놀아요."},
    {e:"Study",p:"[ˈstʌdi]",k:"공부하다",ee:"Study every day.",ek:"매일 공부해요."},
    {e:"Read",p:"[riːd]",k:"읽다",ee:"Read a book tonight.",ek:"오늘 밤 책을 읽어요."},
    {e:"Write",p:"[raɪt]",k:"쓰다",ee:"Write your name.",ek:"이름을 쓰세요."},
    {e:"Draw",p:"[drɔː]",k:"그리다",ee:"Draw a picture.",ek:"그림을 그려요."},
    {e:"Sing",p:"[sɪŋ]",k:"노래하다",ee:"Sing a song.",ek:"노래를 불러요."},
    {e:"Dance",p:"[dæns]",k:"춤추다",ee:"She loves to dance.",ek:"그녀는 춤추는 것을 좋아해요."},
    {e:"Cook",p:"[kʊk]",k:"요리하다",ee:"Cook dinner tonight.",ek:"오늘 밤 저녁을 요리해요."},
    {e:"Clean",p:"[kliːn]",k:"청소하다",ee:"Clean your room.",ek:"방을 청소하세요."},
    {e:"Help",p:"[help]",k:"돕다",ee:"Please help me.",ek:"나를 도와주세요."},
    {e:"Listen",p:"[ˈlɪsn]",k:"듣다",ee:"Listen carefully.",ek:"주의 깊게 들으세요."},
    {e:"Speak",p:"[spiːk]",k:"말하다",ee:"Speak slowly.",ek:"천천히 말하세요."},
    {e:"Smile",p:"[smaɪl]",k:"웃다",ee:"Smile at everyone.",ek:"모두에게 미소를 지어요."},
    {e:"Cry",p:"[kraɪ]",k:"울다",ee:"Don't cry.",ek:"울지 마세요."},
    {e:"Laugh",p:"[læf]",k:"웃다(크게)",ee:"They laugh together.",ek:"그들은 함께 웃어요."},
    {e:"Think",p:"[θɪŋk]",k:"생각하다",ee:"Think before you speak.",ek:"말하기 전에 생각해요."},
    {e:"Know",p:"[noʊ]",k:"알다",ee:"I know the answer.",ek:"나는 답을 알아요."},
    {e:"Learn",p:"[lɜːrn]",k:"배우다",ee:"We learn every day.",ek:"우리는 매일 배워요."},
    {e:"Teach",p:"[tiːtʃ]",k:"가르치다",ee:"She teaches English.",ek:"그녀는 영어를 가르쳐요."},
    {e:"Give",p:"[ɡɪv]",k:"주다",ee:"Give it to me.",ek:"나에게 주세요."},
    {e:"Take",p:"[teɪk]",k:"가져가다",ee:"Take an umbrella.",ek:"우산을 가져가세요."},
    {e:"Make",p:"[meɪk]",k:"만들다",ee:"Make a card.",ek:"카드를 만들어요."},
    {e:"Buy",p:"[baɪ]",k:"사다",ee:"Buy some apples.",ek:"사과를 사세요."},
    {e:"Sell",p:"[sel]",k:"팔다",ee:"She sells flowers.",ek:"그녀는 꽃을 팔아요."},
    {e:"Open",p:"[ˈoʊpən]",k:"열다",ee:"Open the window.",ek:"창문을 여세요."},
    {e:"Close",p:"[kloʊz]",k:"닫다",ee:"Close the door.",ek:"문을 닫으세요."},
    {e:"Push",p:"[pʊʃ]",k:"밀다",ee:"Push the cart.",ek:"카트를 밀어요."},
    {e:"Pull",p:"[pʊl]",k:"당기다",ee:"Pull the door.",ek:"문을 당겨요."},
    {e:"Throw",p:"[θroʊ]",k:"던지다",ee:"Throw the ball.",ek:"공을 던져요."},
    {e:"Catch",p:"[kætʃ]",k:"잡다",ee:"Catch the ball.",ek:"공을 잡아요."},
    {e:"Kick",p:"[kɪk]",k:"차다",ee:"Kick the ball.",ek:"공을 차요."},
    {e:"Hit",p:"[hɪt]",k:"치다",ee:"Hit the drum.",ek:"드럼을 쳐요."},
    {e:"Swim",p:"[swɪm]",k:"수영하다",ee:"I swim in summer.",ek:"나는 여름에 수영해요."},
    {e:"Ride",p:"[raɪd]",k:"타다",ee:"Ride a bicycle.",ek:"자전거를 타요."},
    {e:"Fly",p:"[flaɪ]",k:"날다",ee:"Birds fly in the sky.",ek:"새가 하늘을 날아요."},
    {e:"Build",p:"[bɪld]",k:"짓다",ee:"Build a sandcastle.",ek:"모래성을 지어요."},
    {e:"Fix",p:"[fɪks]",k:"고치다",ee:"Fix the broken toy.",ek:"부러진 장난감을 고쳐요."},
    {e:"Plant",p:"[plænt]",k:"심다",ee:"Plant a tree.",ek:"나무를 심어요."},
    {e:"Grow",p:"[ɡroʊ]",k:"자라다",ee:"Plants grow with water.",ek:"식물은 물로 자라요."},
    {e:"Share",p:"[ʃer]",k:"나누다",ee:"Share your lunch.",ek:"점심을 나눠요."},
    {e:"Wait",p:"[weɪt]",k:"기다리다",ee:"Wait for me.",ek:"나를 기다려요."}
  ]},
  {id:"adjectives",name:"형용사",icon:"✨",words:[
    {e:"Big",p:"[bɪɡ]",k:"큰",ee:"This is a big box.",ek:"이것은 큰 상자예요."},
    {e:"Small",p:"[smɔːl]",k:"작은",ee:"That is a small ant.",ek:"저것은 작은 개미예요."},
    {e:"Hot",p:"[hɑːt]",k:"뜨거운",ee:"The soup is hot.",ek:"수프가 뜨거워요."},
    {e:"Cold",p:"[koʊld]",k:"차가운",ee:"Ice cream is cold.",ek:"아이스크림은 차가워요."},
    {e:"Fast",p:"[fæst]",k:"빠른",ee:"A cheetah is fast.",ek:"치타는 빨라요."},
    {e:"Slow",p:"[sloʊ]",k:"느린",ee:"A snail is slow.",ek:"달팽이는 느려요."},
    {e:"Happy",p:"[ˈhæpi]",k:"행복한",ee:"I am very happy.",ek:"나는 매우 행복해요."},
    {e:"Sad",p:"[sæd]",k:"슬픈",ee:"She looks sad.",ek:"그녀는 슬퍼 보여요."},
    {e:"Good",p:"[ɡʊd]",k:"좋은",ee:"You did a good job.",ek:"잘 했어요."},
    {e:"Bad",p:"[bæd]",k:"나쁜",ee:"Bad habits are harmful.",ek:"나쁜 습관은 해로워요."},
    {e:"Long",p:"[lɔːŋ]",k:"긴",ee:"The rope is long.",ek:"줄이 길어요."},
    {e:"Short",p:"[ʃɔːrt]",k:"짧은",ee:"His hair is short.",ek:"그의 머리카락은 짧아요."},
    {e:"Tall",p:"[tɔːl]",k:"키가 큰",ee:"She is very tall.",ek:"그녀는 키가 아주 커요."},
    {e:"Beautiful",p:"[ˈbjuːtɪfl]",k:"아름다운",ee:"That is beautiful.",ek:"저것은 아름다워요."},
    {e:"Ugly",p:"[ˈʌɡli]",k:"못생긴",ee:"Looks don't matter most.",ek:"외모가 전부는 아니에요."},
    {e:"Soft",p:"[sɔːft]",k:"부드러운",ee:"The pillow is soft.",ek:"베개가 부드러워요."},
    {e:"Hard",p:"[hɑːrd]",k:"딱딱한",ee:"Rocks are hard.",ek:"바위는 딱딱해요."},
    {e:"Sweet",p:"[swiːt]",k:"달콤한",ee:"Honey is sweet.",ek:"꿀은 달콤해요."},
    {e:"Sour",p:"[saʊər]",k:"신",ee:"Lemons are sour.",ek:"레몬은 셔요."},
    {e:"Tired",p:"[ˈtaɪərd]",k:"피곤한",ee:"I am so tired.",ek:"나는 매우 피곤해요."},
    {e:"Brave",p:"[breɪv]",k:"용감한",ee:"She is very brave.",ek:"그녀는 매우 용감해요."},
    {e:"Shy",p:"[ʃaɪ]",k:"수줍은",ee:"He is shy.",ek:"그는 수줍어요."},
    {e:"Funny",p:"[ˈfʌni]",k:"재미있는",ee:"He is very funny.",ek:"그는 매우 재미있어요."},
    {e:"Boring",p:"[ˈbɔːrɪŋ]",k:"지루한",ee:"The movie is boring.",ek:"그 영화는 지루해요."},
    {e:"Exciting",p:"[ɪkˈsaɪtɪŋ]",k:"신나는",ee:"The game is exciting.",ek:"그 게임은 신나요."},
    {e:"Scary",p:"[ˈskeri]",k:"무서운",ee:"The dark is scary.",ek:"어두운 것은 무서워요."},
    {e:"Angry",p:"[ˈæŋɡri]",k:"화난",ee:"Don't be angry.",ek:"화내지 마세요."},
    {e:"Surprised",p:"[sərˈpraɪzd]",k:"놀란",ee:"I was surprised.",ek:"나는 놀랐어요."},
    {e:"Hungry",p:"[ˈhʌŋɡri]",k:"배고픈",ee:"I am hungry.",ek:"나는 배고파요."},
    {e:"Full",p:"[fʊl]",k:"배부른",ee:"I am full.",ek:"나는 배불러요."},
    {e:"Clean",p:"[kliːn]",k:"깨끗한",ee:"Keep the room clean.",ek:"방을 깨끗하게 하세요."},
    {e:"Dirty",p:"[ˈdɜːrti]",k:"더러운",ee:"The shoes are dirty.",ek:"신발이 더러워요."},
    {e:"Dark",p:"[dɑːrk]",k:"어두운",ee:"The room is dark.",ek:"방이 어두워요."},
    {e:"Bright",p:"[braɪt]",k:"밝은",ee:"The room is bright.",ek:"방이 밝아요."},
    {e:"Loud",p:"[laʊd]",k:"시끄러운",ee:"The music is loud.",ek:"음악이 시끄러워요."},
    {e:"Quiet",p:"[ˈkwaɪət]",k:"조용한",ee:"Be quiet, please.",ek:"조용히 해주세요."},
    {e:"Heavy",p:"[ˈhevi]",k:"무거운",ee:"The bag is heavy.",ek:"가방이 무거워요."},
    {e:"Light",p:"[laɪt]",k:"가벼운",ee:"The feather is light.",ek:"깃털은 가벼워요."},
    {e:"New",p:"[njuː]",k:"새로운",ee:"I have new shoes.",ek:"나는 새 신발이 있어요."},
    {e:"Old",p:"[oʊld]",k:"낡은",ee:"The book is old.",ek:"그 책은 낡았어요."},
    {e:"Warm",p:"[wɔːrm]",k:"따뜻한",ee:"The sun is warm.",ek:"태양이 따뜻해요."},
    {e:"Cool",p:"[kuːl]",k:"시원한",ee:"The breeze is cool.",ek:"바람이 시원해요."},
    {e:"Wet",p:"[wet]",k:"젖은",ee:"My socks are wet.",ek:"양말이 젖었어요."},
    {e:"Dry",p:"[draɪ]",k:"마른",ee:"The towel is dry.",ek:"수건이 말랐어요."},
    {e:"Healthy",p:"[ˈhelθi]",k:"건강한",ee:"Eat healthy food.",ek:"건강한 음식을 먹어요."},
    {e:"Sick",p:"[sɪk]",k:"아픈",ee:"I feel sick today.",ek:"오늘 몸이 아파요."},
    {e:"Lucky",p:"[ˈlʌki]",k:"운이 좋은",ee:"I feel lucky today.",ek:"오늘 운이 좋아요."},
    {e:"Careful",p:"[ˈkerfəl]",k:"조심스러운",ee:"Be careful!",ek:"조심하세요!"},
    {e:"Kind",p:"[kaɪnd]",k:"친절한",ee:"Be kind to others.",ek:"다른 사람들에게 친절하세요."},
    {e:"Smart",p:"[smɑːrt]",k:"똑똑한",ee:"She is very smart.",ek:"그녀는 매우 똑똑해요."}
  ]},
  {id:"sports",name:"스포츠",icon:"⚽",words:[
    {e:"Soccer",p:"[ˈsɑːkər]",k:"축구",ee:"Soccer is popular worldwide.",ek:"축구는 전 세계에서 인기 있어요."},
    {e:"Basketball",p:"[ˈbæskɪtbɔːl]",k:"농구",ee:"We shoot baskets.",ek:"우리는 슛을 해요."},
    {e:"Baseball",p:"[ˈbeɪsbɔːl]",k:"야구",ee:"Hit the ball with a bat.",ek:"배트로 공을 쳐요."},
    {e:"Tennis",p:"[ˈtenɪs]",k:"테니스",ee:"Tennis uses a racket.",ek:"테니스는 라켓을 사용해요."},
    {e:"Swimming",p:"[ˈswɪmɪŋ]",k:"수영",ee:"Swimming is good exercise.",ek:"수영은 좋은 운동이에요."},
    {e:"Running",p:"[ˈrʌnɪŋ]",k:"달리기",ee:"Running keeps you healthy.",ek:"달리기는 건강을 유지해줘요."},
    {e:"Cycling",p:"[ˈsaɪklɪŋ]",k:"자전거 타기",ee:"Cycling is fun.",ek:"자전거 타기는 재미있어요."},
    {e:"Volleyball",p:"[ˈvɑːlibɔːl]",k:"배구",ee:"Volleyball needs teamwork.",ek:"배구는 팀워크가 필요해요."},
    {e:"Badminton",p:"[ˈbædmɪntən]",k:"배드민턴",ee:"I play badminton after school.",ek:"나는 방과 후 배드민턴을 쳐요."},
    {e:"Table tennis",p:"[ˈteɪbl ˈtenɪs]",k:"탁구",ee:"Table tennis is fast.",ek:"탁구는 빠른 운동이에요."},
    {e:"Gymnastics",p:"[dʒɪmˈnæstɪks]",k:"체조",ee:"Gymnastics needs balance.",ek:"체조는 균형이 필요해요."},
    {e:"Taekwondo",p:"[ˌtaɪkwɒnˈdoʊ]",k:"태권도",ee:"Taekwondo is a Korean sport.",ek:"태권도는 한국 스포츠예요."},
    {e:"Judo",p:"[ˈdʒuːdoʊ]",k:"유도",ee:"Judo teaches discipline.",ek:"유도는 규율을 가르쳐요."},
    {e:"Archery",p:"[ˈɑːrtʃəri]",k:"양궁",ee:"Korea is great at archery.",ek:"한국은 양궁을 잘 해요."},
    {e:"Golf",p:"[ɡɑːlf]",k:"골프",ee:"Golf needs patience.",ek:"골프는 인내심이 필요해요."},
    {e:"Hockey",p:"[ˈhɑːki]",k:"하키",ee:"Hockey is played on ice.",ek:"하키는 얼음 위에서 해요."},
    {e:"Skiing",p:"[ˈskiːɪŋ]",k:"스키",ee:"Skiing is a winter sport.",ek:"스키는 겨울 스포츠예요."},
    {e:"Skating",p:"[ˈskeɪtɪŋ]",k:"스케이팅",ee:"Ice skating is beautiful.",ek:"아이스 스케이팅은 아름다워요."},
    {e:"Boxing",p:"[ˈbɑːksɪŋ]",k:"권투",ee:"Boxing builds strength.",ek:"권투는 힘을 키워줘요."},
    {e:"Wrestling",p:"[ˈreslɪŋ]",k:"씨름/레슬링",ee:"Wrestling is intense.",ek:"레슬링은 강렬해요."},
    {e:"Surfing",p:"[ˈsɜːrfɪŋ]",k:"서핑",ee:"Surfing needs balance.",ek:"서핑은 균형이 필요해요."},
    {e:"Diving",p:"[ˈdaɪvɪŋ]",k:"다이빙",ee:"Diving into water is fun.",ek:"물속으로 뛰어드는 것은 재미있어요."},
    {e:"Rowing",p:"[ˈroʊɪŋ]",k:"조정",ee:"Rowing uses arms and legs.",ek:"조정은 팔과 다리를 써요."},
    {e:"Fencing",p:"[ˈfensɪŋ]",k:"펜싱",ee:"Fencing uses a sword.",ek:"펜싱은 검을 사용해요."},
    {e:"Shooting",p:"[ˈʃuːtɪŋ]",k:"사격",ee:"Shooting needs focus.",ek:"사격은 집중력이 필요해요."},
    {e:"Weightlifting",p:"[ˈweɪtlɪftɪŋ]",k:"역도",ee:"Weightlifting builds muscles.",ek:"역도는 근육을 키워요."},
    {e:"Marathon",p:"[ˈmærəθɑːn]",k:"마라톤",ee:"A marathon is 42km.",ek:"마라톤은 42킬로미터예요."},
    {e:"Triathlon",p:"[traɪˈæθlɑːn]",k:"트라이애슬론",ee:"Triathlon has three sports.",ek:"트라이애슬론은 세 가지 스포츠예요."},
    {e:"Rugby",p:"[ˈrʌɡbi]",k:"럭비",ee:"Rugby is rough.",ek:"럭비는 거친 운동이에요."},
    {e:"Cricket",p:"[ˈkrɪkɪt]",k:"크리켓",ee:"Cricket is popular in India.",ek:"크리켓은 인도에서 인기 있어요."},
    {e:"Field hockey",p:"[fiːld ˈhɑːki]",k:"필드하키",ee:"Field hockey uses a stick.",ek:"필드하키는 막대를 써요."},
    {e:"Handball",p:"[ˈhændbɔːl]",k:"핸드볼",ee:"Handball is team sport.",ek:"핸드볼은 팀 스포츠예요."},
    {e:"Lacrosse",p:"[ləˈkrɑːs]",k:"라크로스",ee:"Lacrosse uses a net stick.",ek:"라크로스는 그물 막대를 써요."},
    {e:"Yoga",p:"[ˈjoʊɡə]",k:"요가",ee:"Yoga stretches your body.",ek:"요가는 몸을 늘여요."},
    {e:"Pilates",p:"[pɪˈlɑːtɪz]",k:"필라테스",ee:"Pilates strengthens the core.",ek:"필라테스는 코어를 강화해요."},
    {e:"Aerobics",p:"[eˈroʊbɪks]",k:"에어로빅",ee:"Aerobics raises your heartbeat.",ek:"에어로빅은 심박수를 높여요."},
    {e:"Climbing",p:"[ˈklaɪmɪŋ]",k:"등산",ee:"Rock climbing is challenging.",ek:"암벽 등반은 도전적이에요."},
    {e:"Skateboarding",p:"[ˈskeɪtbɔːrdɪŋ]",k:"스케이트보드",ee:"Skateboarding is cool.",ek:"스케이트보드는 멋있어요."},
    {e:"Snowboarding",p:"[ˈsnoʊbɔːrdɪŋ]",k:"스노보드",ee:"Snowboarding is exciting.",ek:"스노보드는 신나요."},
    {e:"Equestrian",p:"[ɪˈkwestriən]",k:"승마",ee:"Equestrian means horse riding.",ek:"승마는 말 타기예요."},
    {e:"Polo",p:"[ˈpoʊloʊ]",k:"폴로",ee:"Polo is played on horses.",ek:"폴로는 말 위에서 해요."},
    {e:"Bowling",p:"[ˈboʊlɪŋ]",k:"볼링",ee:"Bowling knocks down pins.",ek:"볼링은 핀을 쓰러뜨려요."},
    {e:"Billiards",p:"[ˈbɪljərdz]",k:"당구",ee:"Billiards uses cue sticks.",ek:"당구는 큐대를 써요."},
    {e:"Darts",p:"[dɑːrts]",k:"다트",ee:"Throw darts at the board.",ek:"판에 다트를 던져요."},
    {e:"Chess",p:"[tʃes]",k:"체스",ee:"Chess is a mind sport.",ek:"체스는 두뇌 스포츠예요."},
    {e:"Badminton",p:"[ˈbædmɪntən]",k:"배드민턴",ee:"I love badminton.",ek:"나는 배드민턴을 좋아해요."},
    {e:"Biathlon",p:"[baɪˈæθlɑːn]",k:"바이애슬론",ee:"Biathlon is skiing and shooting.",ek:"바이애슬론은 스키와 사격이에요."},
    {e:"Pentathlon",p:"[penˈtæθlɑːn]",k:"펜타슬론",ee:"Pentathlon has five events.",ek:"펜타슬론은 다섯 종목이에요."},
    {e:"Decathlon",p:"[dɪˈkæθlɑːn]",k:"10종 경기",ee:"Decathlon has ten events.",ek:"10종 경기는 열 종목이에요."},
    {e:"Hurdling",p:"[ˈhɜːrdlɪŋ]",k:"허들",ee:"Hurdling means jumping barriers.",ek:"허들은 장애물을 뛰어넘어요."}
  ]},
  {id:"music",name:"음악",icon:"🎵",words:[
    {e:"Song",p:"[sɔːŋ]",k:"노래",ee:"I like this song.",ek:"나는 이 노래가 좋아요."},
    {e:"Music",p:"[ˈmjuːzɪk]",k:"음악",ee:"Music makes me happy.",ek:"음악은 나를 행복하게 해요."},
    {e:"Melody",p:"[ˈmelədi]",k:"멜로디",ee:"The melody is beautiful.",ek:"멜로디가 아름다워요."},
    {e:"Rhythm",p:"[ˈrɪðəm]",k:"리듬",ee:"Clap to the rhythm.",ek:"리듬에 맞춰 박수를 쳐요."},
    {e:"Beat",p:"[biːt]",k:"박자",ee:"Feel the beat.",ek:"박자를 느껴요."},
    {e:"Piano",p:"[piˈænoʊ]",k:"피아노",ee:"She plays the piano.",ek:"그녀는 피아노를 쳐요."},
    {e:"Guitar",p:"[ɡɪˈtɑːr]",k:"기타",ee:"He plays guitar.",ek:"그는 기타를 쳐요."},
    {e:"Violin",p:"[ˌvaɪəˈlɪn]",k:"바이올린",ee:"Violins make a sweet sound.",ek:"바이올린은 달콤한 소리를 내요."},
    {e:"Drum",p:"[drʌm]",k:"드럼",ee:"Beat the drum.",ek:"드럼을 쳐요."},
    {e:"Flute",p:"[fluːt]",k:"플루트",ee:"The flute sounds airy.",ek:"플루트는 경쾌한 소리예요."},
    {e:"Trumpet",p:"[ˈtrʌmpɪt]",k:"트럼펫",ee:"Trumpets are loud.",ek:"트럼펫은 소리가 커요."},
    {e:"Saxophone",p:"[ˈsæksəfoʊn]",k:"색소폰",ee:"Saxophone sounds smooth.",ek:"색소폰은 부드럽게 들려요."},
    {e:"Cello",p:"[ˈtʃeloʊ]",k:"첼로",ee:"The cello sounds deep.",ek:"첼로는 깊은 소리예요."},
    {e:"Harp",p:"[hɑːrp]",k:"하프",ee:"The harp is elegant.",ek:"하프는 우아해요."},
    {e:"Clarinet",p:"[ˌklærəˈnet]",k:"클라리넷",ee:"Clarinets are woodwind.",ek:"클라리넷은 목관악기예요."},
    {e:"Xylophone",p:"[ˈzaɪləfoʊn]",k:"실로폰",ee:"Hit the xylophone keys.",ek:"실로폰 건반을 쳐요."},
    {e:"Accordion",p:"[əˈkɔːrdiən]",k:"아코디언",ee:"Squeeze the accordion.",ek:"아코디언을 눌러요."},
    {e:"Tuba",p:"[ˈtuːbə]",k:"튜바",ee:"Tuba makes low sounds.",ek:"튜바는 낮은 소리를 내요."},
    {e:"Oboe",p:"[ˈoʊboʊ]",k:"오보에",ee:"Oboe has a nasal sound.",ek:"오보에는 콧소리 같아요."},
    {e:"Bassoon",p:"[bəˈsuːn]",k:"바순",ee:"Bassoon has low notes.",ek:"바순은 낮은 음을 내요."},
    {e:"Singer",p:"[ˈsɪŋər]",k:"가수",ee:"The singer is famous.",ek:"그 가수는 유명해요."},
    {e:"Conductor",p:"[kənˈdʌktər]",k:"지휘자",ee:"The conductor leads the orchestra.",ek:"지휘자가 오케스트라를 이끌어요."},
    {e:"Orchestra",p:"[ˈɔːrkɪstrə]",k:"오케스트라",ee:"The orchestra plays beautifully.",ek:"오케스트라가 아름답게 연주해요."},
    {e:"Band",p:"[bænd]",k:"밴드",ee:"The band plays loud music.",ek:"밴드가 시끄러운 음악을 연주해요."},
    {e:"Choir",p:"[ˈkwaɪər]",k:"합창단",ee:"The choir sings together.",ek:"합창단이 함께 노래해요."},
    {e:"Concert",p:"[ˈkɑːnsərt]",k:"콘서트",ee:"We go to a concert.",ek:"우리는 콘서트에 가요."},
    {e:"Stage",p:"[steɪdʒ]",k:"무대",ee:"Singers stand on the stage.",ek:"가수들이 무대 위에 서요."},
    {e:"Microphone",p:"[ˈmaɪkrəfoʊn]",k:"마이크",ee:"Speak into the microphone.",ek:"마이크에 대고 말해요."},
    {e:"Headphones",p:"[ˈhedfənoʊnz]",k:"헤드폰",ee:"I wear headphones.",ek:"나는 헤드폰을 써요."},
    {e:"Speaker",p:"[ˈspiːkər]",k:"스피커",ee:"The speaker is loud.",ek:"스피커 소리가 커요."},
    {e:"Note",p:"[noʊt]",k:"음표",ee:"Read the music notes.",ek:"음표를 읽어요."},
    {e:"Chord",p:"[kɔːrd]",k:"화음",ee:"Play a chord.",ek:"화음을 연주해요."},
    {e:"Scale",p:"[skeɪl]",k:"음계",ee:"Practice the scale.",ek:"음계를 연습해요."},
    {e:"Tempo",p:"[ˈtempoʊ]",k:"템포",ee:"The tempo is fast.",ek:"템포가 빨라요."},
    {e:"Lyrics",p:"[ˈlɪrɪks]",k:"가사",ee:"Learn the lyrics.",ek:"가사를 외워요."},
    {e:"Pop",p:"[pɑːp]",k:"팝",ee:"Pop music is popular.",ek:"팝 음악은 인기 있어요."},
    {e:"Classical",p:"[ˈklæsɪkl]",k:"클래식",ee:"Classical music is calm.",ek:"클래식 음악은 차분해요."},
    {e:"Jazz",p:"[dʒæz]",k:"재즈",ee:"Jazz music is fun.",ek:"재즈 음악은 재미있어요."},
    {e:"Rock",p:"[rɑːk]",k:"록",ee:"Rock music is loud.",ek:"록 음악은 시끄러워요."},
    {e:"Hip-hop",p:"[ˈhɪphɑːp]",k:"힙합",ee:"Hip-hop uses rap.",ek:"힙합은 랩을 써요."},
    {e:"Ballad",p:"[ˈbæləd]",k:"발라드",ee:"Ballads are slow songs.",ek:"발라드는 느린 노래예요."},
    {e:"Album",p:"[ˈælbəm]",k:"앨범",ee:"I bought a new album.",ek:"나는 새 앨범을 샀어요."},
    {e:"Playlist",p:"[ˈpleɪlɪst]",k:"플레이리스트",ee:"Make a playlist.",ek:"플레이리스트를 만들어요."},
    {e:"Audition",p:"[ɔːˈdɪʃn]",k:"오디션",ee:"She passed the audition.",ek:"그녀가 오디션에 합격했어요."},
    {e:"Rehearsal",p:"[rɪˈhɜːrsəl]",k:"리허설",ee:"We have rehearsal today.",ek:"오늘 리허설이 있어요."},
    {e:"Performance",p:"[pərˈfɔːrməns]",k:"공연",ee:"The performance was amazing.",ek:"공연이 멋졌어요."},
    {e:"Applause",p:"[əˈplɔːz]",k:"박수",ee:"Give a round of applause.",ek:"박수를 쳐요."},
    {e:"Encore",p:"[ˈɑːŋkɔːr]",k:"앙코르",ee:"The crowd shouts encore.",ek:"관중들이 앙코르를 외쳐요."},
    {e:"Harmony",p:"[ˈhɑːrməni]",k:"화성",ee:"The harmony sounds lovely.",ek:"화성이 아름답게 들려요."},
    {e:"Acoustic",p:"[əˈkuːstɪk]",k:"어쿠스틱",ee:"I like acoustic guitar.",ek:"나는 어쿠스틱 기타를 좋아해요."}
  ]},
  {id:"colors",name:"색깔",icon:"🎨",words:[
    {e:"Red",p:"[red]",k:"빨간색",ee:"Roses are red.",ek:"장미는 빨간색이에요."},
    {e:"Blue",p:"[bluː]",k:"파란색",ee:"The sky is blue.",ek:"하늘은 파란색이에요."},
    {e:"Yellow",p:"[ˈjeloʊ]",k:"노란색",ee:"Bananas are yellow.",ek:"바나나는 노란색이에요."},
    {e:"Green",p:"[ɡriːn]",k:"초록색",ee:"Grass is green.",ek:"풀은 초록색이에요."},
    {e:"Orange",p:"[ˈɔːrɪndʒ]",k:"주황색",ee:"Carrots are orange.",ek:"당근은 주황색이에요."},
    {e:"Purple",p:"[ˈpɜːrpl]",k:"보라색",ee:"Grapes are purple.",ek:"포도는 보라색이에요."},
    {e:"Pink",p:"[pɪŋk]",k:"분홍색",ee:"Flamingos are pink.",ek:"플라밍고는 분홍색이에요."},
    {e:"Black",p:"[blæk]",k:"검은색",ee:"The night is black.",ek:"밤은 검은색이에요."},
    {e:"White",p:"[waɪt]",k:"하얀색",ee:"Snow is white.",ek:"눈은 하얀색이에요."},
    {e:"Brown",p:"[braʊn]",k:"갈색",ee:"Chocolate is brown.",ek:"초콜릿은 갈색이에요."},
    {e:"Gray",p:"[ɡreɪ]",k:"회색",ee:"Clouds can be gray.",ek:"구름은 회색이 될 수 있어요."},
    {e:"Beige",p:"[beɪʒ]",k:"베이지색",ee:"The wall is beige.",ek:"벽이 베이지색이에요."},
    {e:"Gold",p:"[ɡoʊld]",k:"금색",ee:"Gold is shiny.",ek:"금색은 빛나요."},
    {e:"Silver",p:"[ˈsɪlvər]",k:"은색",ee:"Silver is metallic.",ek:"은색은 금속 같아요."},
    {e:"Navy",p:"[ˈneɪvi]",k:"남색",ee:"I like navy blue.",ek:"나는 남색을 좋아해요."},
    {e:"Turquoise",p:"[ˈtɜːrkwɔɪz]",k:"청록색",ee:"The sea looks turquoise.",ek:"바다가 청록색으로 보여요."},
    {e:"Violet",p:"[ˈvaɪələt]",k:"보라",ee:"Violets are violet.",ek:"제비꽃은 보라색이에요."},
    {e:"Indigo",p:"[ˈɪndɪɡoʊ]",k:"남보라색",ee:"Indigo is in the rainbow.",ek:"남보라색은 무지개에 있어요."},
    {e:"Magenta",p:"[məˈdʒentə]",k:"자홍색",ee:"Magenta is bright pink.",ek:"자홍색은 밝은 분홍색이에요."},
    {e:"Cyan",p:"[ˈsaɪæn]",k:"청록",ee:"Cyan is blue-green.",ek:"청록은 파란-초록색이에요."},
    {e:"Scarlet",p:"[ˈskɑːrlɪt]",k:"주홍색",ee:"Scarlet is a bright red.",ek:"주홍색은 밝은 빨간색이에요."},
    {e:"Crimson",p:"[ˈkrɪmzn]",k:"진홍색",ee:"Crimson is deep red.",ek:"진홍색은 짙은 빨간색이에요."},
    {e:"Maroon",p:"[məˈruːn]",k:"밤색",ee:"Maroon is dark red.",ek:"밤색은 어두운 빨간색이에요."},
    {e:"Olive",p:"[ˈɑːlɪv]",k:"올리브색",ee:"Olive is dark yellow-green.",ek:"올리브는 어두운 황록색이에요."},
    {e:"Lime",p:"[laɪm]",k:"라임색",ee:"Lime is bright green.",ek:"라임색은 밝은 초록색이에요."},
    {e:"Teal",p:"[tiːl]",k:"청록색",ee:"Teal is blue-green.",ek:"청록색은 파란-초록색이에요."},
    {e:"Coral",p:"[ˈkɔːrəl]",k:"산호색",ee:"Coral is pinkish orange.",ek:"산호색은 분홍빛 주황이에요."},
    {e:"Peach",p:"[piːtʃ]",k:"복숭아색",ee:"Peach is light orange.",ek:"복숭아색은 연한 주황색이에요."},
    {e:"Lavender",p:"[ˈlævəndər]",k:"라벤더색",ee:"Lavender is light purple.",ek:"라벤더색은 연한 보라색이에요."},
    {e:"Mint",p:"[mɪnt]",k:"민트색",ee:"Mint is light green.",ek:"민트색은 연한 초록색이에요."},
    {e:"Ivory",p:"[ˈaɪvəri]",k:"아이보리색",ee:"Ivory is creamy white.",ek:"아이보리색은 크림색 흰색이에요."},
    {e:"Tan",p:"[tæn]",k:"황갈색",ee:"Tan is light brown.",ek:"황갈색은 연한 갈색이에요."},
    {e:"Khaki",p:"[ˈkɑːki]",k:"카키색",ee:"Khaki is earthy brown.",ek:"카키색은 흙빛 갈색이에요."},
    {e:"Copper",p:"[ˈkɑːpər]",k:"구리색",ee:"Copper is reddish brown.",ek:"구리색은 붉은빛 갈색이에요."},
    {e:"Bronze",p:"[brɑːnz]",k:"청동색",ee:"Bronze is dark gold.",ek:"청동색은 어두운 금색이에요."},
    {e:"Charcoal",p:"[ˈtʃɑːrkoʊl]",k:"숯색",ee:"Charcoal is dark gray.",ek:"숯색은 어두운 회색이에요."},
    {e:"Cream",p:"[kriːm]",k:"크림색",ee:"Cream is off-white.",ek:"크림색은 약간 흰색이에요."},
    {e:"Transparent",p:"[trænsˈpærənt]",k:"투명한",ee:"Glass is transparent.",ek:"유리는 투명해요."},
    {e:"Pastel",p:"[ˈpæstl]",k:"파스텔",ee:"Pastel colors are soft.",ek:"파스텔 색은 부드러워요."},
    {e:"Neon",p:"[ˈniːɑːn]",k:"네온색",ee:"Neon colors are bright.",ek:"네온색은 밝아요."},
    {e:"Dark",p:"[dɑːrk]",k:"어두운",ee:"Dark colors look serious.",ek:"어두운 색은 진지해 보여요."},
    {e:"Light",p:"[laɪt]",k:"밝은",ee:"Light colors look happy.",ek:"밝은 색은 행복해 보여요."},
    {e:"Colorful",p:"[ˈkʌlərfl]",k:"색깔이 다양한",ee:"The painting is colorful.",ek:"그 그림은 색이 다양해요."},
    {e:"Bright",p:"[braɪt]",k:"선명한",ee:"The red is bright.",ek:"빨간색이 선명해요."},
    {e:"Dull",p:"[dʌl]",k:"칙칙한",ee:"The color looks dull.",ek:"색이 칙칙해 보여요."},
    {e:"Faded",p:"[ˈfeɪdɪd]",k:"바랜",ee:"The shirt is faded.",ek:"셔츠가 바랬어요."},
    {e:"Glossy",p:"[ˈɡlɑːsi]",k:"광택 있는",ee:"The paint is glossy.",ek:"페인트가 광택이 있어요."},
    {e:"Matte",p:"[mæt]",k:"무광의",ee:"The finish is matte.",ek:"마감이 무광이에요."},
    {e:"Striped",p:"[straɪpt]",k:"줄무늬의",ee:"The shirt is striped.",ek:"셔츠가 줄무늬예요."},
    {e:"Spotted",p:"[ˈspɑːtɪd]",k:"점무늬의",ee:"The dog is spotted.",ek:"강아지가 점무늬예요."}
  ]},
  {id:"jobs",name:"직업",icon:"👷",words:[
    {e:"Teacher",p:"[ˈtiːtʃər]",k:"선생님",ee:"My teacher is kind.",ek:"우리 선생님은 친절해요."},
    {e:"Doctor",p:"[ˈdɑːktər]",k:"의사",ee:"The doctor helps us.",ek:"의사는 우리를 도와줘요."},
    {e:"Nurse",p:"[nɜːrs]",k:"간호사",ee:"Nurses care for patients.",ek:"간호사는 환자를 돌봐요."},
    {e:"Police",p:"[pəˈliːs]",k:"경찰",ee:"Police keep us safe.",ek:"경찰이 우리를 안전하게 해줘요."},
    {e:"Firefighter",p:"[ˈfaɪərfaɪtər]",k:"소방관",ee:"Firefighters save lives.",ek:"소방관은 목숨을 구해요."},
    {e:"Farmer",p:"[ˈfɑːrmər]",k:"농부",ee:"Farmers grow food.",ek:"농부는 음식을 재배해요."},
    {e:"Chef",p:"[ʃef]",k:"주방장",ee:"The chef cooks well.",ek:"주방장은 요리를 잘 해요."},
    {e:"Pilot",p:"[ˈpaɪlət]",k:"조종사",ee:"Pilots fly planes.",ek:"조종사는 비행기를 조종해요."},
    {e:"Engineer",p:"[ˌendʒɪˈnɪr]",k:"엔지니어",ee:"Engineers build things.",ek:"엔지니어는 것들을 만들어요."},
    {e:"Scientist",p:"[ˈsaɪəntɪst]",k:"과학자",ee:"Scientists study the world.",ek:"과학자는 세상을 연구해요."},
    {e:"Artist",p:"[ˈɑːrtɪst]",k:"예술가",ee:"Artists create beautiful things.",ek:"예술가는 아름다운 것을 만들어요."},
    {e:"Singer",p:"[ˈsɪŋər]",k:"가수",ee:"The singer is famous.",ek:"그 가수는 유명해요."},
    {e:"Actor",p:"[ˈæktər]",k:"배우",ee:"Actors perform on stage.",ek:"배우는 무대에서 공연해요."},
    {e:"Writer",p:"[ˈraɪtər]",k:"작가",ee:"Writers create stories.",ek:"작가는 이야기를 만들어요."},
    {e:"Dentist",p:"[ˈdentɪst]",k:"치과의사",ee:"The dentist checks my teeth.",ek:"치과의사가 이를 검사해요."},
    {e:"Lawyer",p:"[ˈlɔːjər]",k:"변호사",ee:"Lawyers defend people.",ek:"변호사는 사람들을 변호해요."},
    {e:"Accountant",p:"[əˈkaʊntənt]",k:"회계사",ee:"Accountants count money.",ek:"회계사는 돈을 계산해요."},
    {e:"Architect",p:"[ˈɑːrkɪtekt]",k:"건축가",ee:"Architects design buildings.",ek:"건축가는 건물을 설계해요."},
    {e:"Mechanic",p:"[mɪˈkænɪk]",k:"정비사",ee:"Mechanics fix cars.",ek:"정비사는 차를 고쳐요."},
    {e:"Electrician",p:"[ɪˌlekˈtrɪʃn]",k:"전기공",ee:"Electricians fix wiring.",ek:"전기공은 전선을 고쳐요."},
    {e:"Plumber",p:"[ˈplʌmər]",k:"배관공",ee:"Plumbers fix pipes.",ek:"배관공은 파이프를 고쳐요."},
    {e:"Carpenter",p:"[ˈkɑːrpəntər]",k:"목수",ee:"Carpenters work with wood.",ek:"목수는 나무를 다뤄요."},
    {e:"Gardener",p:"[ˈɡɑːrdnər]",k:"정원사",ee:"Gardeners grow plants.",ek:"정원사는 식물을 키워요."},
    {e:"Postman",p:"[ˈpoʊstmən]",k:"우편배달부",ee:"The postman brings letters.",ek:"우편배달부가 편지를 가져와요."},
    {e:"Baker",p:"[ˈbeɪkər]",k:"제빵사",ee:"Bakers make bread.",ek:"제빵사는 빵을 만들어요."},
    {e:"Butcher",p:"[ˈbʊtʃər]",k:"정육점 주인",ee:"Butchers sell meat.",ek:"정육점 주인은 고기를 팔아요."},
    {e:"Librarian",p:"[laɪˈbreriən]",k:"사서",ee:"The librarian helps find books.",ek:"사서는 책을 찾는 것을 도와요."},
    {e:"Photographer",p:"[fəˈtɑːɡrəfər]",k:"사진작가",ee:"Photographers take photos.",ek:"사진작가는 사진을 찍어요."},
    {e:"Journalist",p:"[ˈdʒɜːrnəlɪst]",k:"기자",ee:"Journalists report the news.",ek:"기자는 뉴스를 보도해요."},
    {e:"Hairdresser",p:"[ˈherdresər]",k:"미용사",ee:"Hairdressers cut hair.",ek:"미용사는 머리를 잘라요."},
    {e:"Optician",p:"[ɑːpˈtɪʃn]",k:"안경사",ee:"Opticians check eyesight.",ek:"안경사는 시력을 검사해요."},
    {e:"Veterinarian",p:"[ˌvetərɪˈneriən]",k:"수의사",ee:"Vets treat animals.",ek:"수의사는 동물을 치료해요."},
    {e:"Pharmacist",p:"[ˈfɑːrməsɪst]",k:"약사",ee:"Pharmacists give medicine.",ek:"약사는 약을 줘요."},
    {e:"Astronaut",p:"[ˈæstrənɔːt]",k:"우주비행사",ee:"Astronauts go to space.",ek:"우주비행사는 우주로 가요."},
    {e:"Soldier",p:"[ˈsoʊldʒər]",k:"군인",ee:"Soldiers protect our country.",ek:"군인은 나라를 보호해요."},
    {e:"Judge",p:"[dʒʌdʒ]",k:"판사",ee:"The judge makes decisions.",ek:"판사는 결정을 내려요."},
    {e:"Sailor",p:"[ˈseɪlər]",k:"선원",ee:"Sailors travel by sea.",ek:"선원은 바다로 여행해요."},
    {e:"Driver",p:"[ˈdraɪvər]",k:"운전사",ee:"The driver stops the bus.",ek:"운전사가 버스를 멈춰요."},
    {e:"Cleaner",p:"[ˈkliːnər]",k:"청소부",ee:"Cleaners keep things tidy.",ek:"청소부는 깨끗하게 해요."},
    {e:"Waiter",p:"[ˈweɪtər]",k:"웨이터",ee:"The waiter takes our order.",ek:"웨이터가 주문을 받아요."},
    {e:"Cashier",p:"[kæˈʃɪr]",k:"계산원",ee:"The cashier takes payment.",ek:"계산원이 결제를 받아요."},
    {e:"Manager",p:"[ˈmænɪdʒər]",k:"매니저",ee:"The manager leads the team.",ek:"매니저가 팀을 이끌어요."},
    {e:"Secretary",p:"[ˈsekrəteri]",k:"비서",ee:"A secretary manages schedules.",ek:"비서는 일정을 관리해요."},
    {e:"Designer",p:"[dɪˈzaɪnər]",k:"디자이너",ee:"Designers create visuals.",ek:"디자이너는 시각물을 만들어요."},
    {e:"Programmer",p:"[ˈproʊɡræmər]",k:"프로그래머",ee:"Programmers write code.",ek:"프로그래머는 코드를 작성해요."},
    {e:"Coach",p:"[koʊtʃ]",k:"코치",ee:"The coach trains athletes.",ek:"코치는 선수들을 훈련해요."},
    {e:"Referee",p:"[ˌrefəˈriː]",k:"심판",ee:"The referee makes calls.",ek:"심판이 판정을 내려요."},
    {e:"Translator",p:"[trænsˈleɪtər]",k:"번역가",ee:"Translators translate languages.",ek:"번역가는 언어를 번역해요."},
    {e:"Musician",p:"[mjuˈzɪʃn]",k:"음악가",ee:"Musicians play instruments.",ek:"음악가는 악기를 연주해요."},
    {e:"Dancer",p:"[ˈdænsər]",k:"무용수",ee:"Dancers move gracefully.",ek:"무용수는 우아하게 움직여요."},
    {e:"Model",p:"[ˈmɑːdl]",k:"모델",ee:"Models walk the runway.",ek:"모델은 런웨이를 걸어요."}
  ]}
];

let curUser='', curCat=null, studyWords=[], studyIdx=0;
let quizWords=[], quizIdx=0, quizScore=0, wrongWords=[];
let scoreChart=null, activeCatFilter='all';

// ── Storage ──────────────────────────────────────────────
function getDB(){try{return JSON.parse(localStorage.getItem('evDB')||'{}');}catch{return {};}}
function saveDB(db){localStorage.setItem('evDB',JSON.stringify(db));}
function getUsers(){return Object.keys(getDB());}
function getUserData(u){const db=getDB();return db[u]||{records:[]};}
function saveRecord(u,rec){
  const db=getDB();
  if(!db[u])db[u]={records:[]};
  db[u].records.push(rec);
  saveDB(db);
}

// ── Helpers ───────────────────────────────────────────────
function $(id){return document.getElementById(id);}
function show(id){document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));$(id).classList.add('active');}
function shuffle(a){const b=[...a];for(let i=b.length-1;i>0;i--){const j=0|Math.random()*(i+1);[b[i],b[j]]=[b[j],b[i]];}return b;}
function fmtDate(ts){const d=new Date(ts);return `${d.getFullYear()}.${pad(d.getMonth()+1)}.${pad(d.getDate())}`;}
function fmtDT(ts){const d=new Date(ts);return `${fmtDate(ts)} ${pad(d.getHours())}:${pad(d.getMinutes())}`;}
function pad(n){return String(n).padStart(2,'0');}

// ── TTS ───────────────────────────────────────────────────
function speakText(t){
  if(!window.speechSynthesis)return;
  const u=new SpeechSynthesisUtterance(t);
  u.lang='en-US'; u.rate=0.85;
  window.speechSynthesis.cancel();
  window.speechSynthesis.speak(u);
}
function speak(type){
  const w=studyWords[studyIdx];
  speakText(type==='w'?w.e:w.ee);
}
function speakQuiz(){speakText(quizWords[quizIdx].e);}

// ── Login ─────────────────────────────────────────────────
function initLogin(){
  const users=getUsers();
  if(users.length){
    $('saved-users-wrap').style.display='block';
    $('saved-chips').innerHTML=users.map(u=>
      `<span class="saved-chip" onclick="selectUser('${u}')">${u}</span>`
    ).join('');
  }
}
function selectUser(n){$('name-input').value=n;loginUser();}
function loginUser(){
  const n=$('name-input').value.trim();
  if(!n){$('name-input').style.borderColor='#E17055';return;}
  curUser=n;
  $('greeting-name').textContent=n;
  $('stats-name').textContent=n;
  buildHome(); show('sc-home');
}
function logout(){curUser='';$('name-input').value='';initLogin();show('sc-login');}

// ── Home ──────────────────────────────────────────────────
function buildHome(){
  const g=$('cat-grid'); g.innerHTML='';
  const ud=getUserData(curUser);
  CATS.forEach(cat=>{
    const recs=ud.records.filter(r=>r.catId===cat.id);
    const best=recs.length?Math.max(...recs.map(r=>r.score)):0;
    const pct=best/20*100;
    const d=document.createElement('div');
    d.className='cat-card';
    d.innerHTML=`
      ${best>=15?`<div class="cat-badge">✓ ${best}/20</div>`:''}
      <div class="cat-icon">${cat.icon}</div>
      <div class="cat-name">${cat.name}</div>
      <div class="cat-count">단어 ${cat.words.length}개${recs.length?` · ${recs.length}회`:''}</div>
      <div class="cat-prog"><div class="cat-prog-fill" style="width:${pct}%"></div></div>`;
    d.onclick=()=>startCat(cat.id);
    g.appendChild(d);
  });
}
function goHome(){buildHome();show('sc-home');}

// ── Study ─────────────────────────────────────────────────
function startCat(id){
  curCat=CATS.find(c=>c.id===id);
  studyWords=shuffle([...curCat.words]).slice(0,20); // 랜덤 20개 선택
  studyIdx=0;
  $('study-title').textContent=`${curCat.icon} ${curCat.name}`;
  $('btn-qs').style.display='none';
  $('btn-next').style.display='block';
  show('sc-study'); renderStudy();
}
function renderStudy(){
  const w=studyWords[studyIdx];
  $('s-eng-text').textContent=w.e;
  $('s-pho').textContent=w.p;
  $('s-kor').textContent=w.k;
  $('s-ex-e').textContent=w.ee;
  $('s-ex-k').textContent=w.ek;
  $('s-reveal').style.display='none';
  $('study-bar').style.width=((studyIdx+1)/20*100)+'%';
  $('study-info').textContent=`${studyIdx+1} / 20`;
}
function revealStudy(){$('s-reveal').style.display='block'; speak('w');}
function nextStudy(){
  if(studyIdx<19){studyIdx++;renderStudy();}
  else{$('btn-next').style.display='none';$('btn-qs').style.display='block';}
}

// ── Quiz ──────────────────────────────────────────────────
function startQuiz(){
  quizWords=shuffle([...studyWords]); // 학습한 20개 랜덤 순서
  quizIdx=0; quizScore=0; wrongWords=[];
  $('quiz-title').textContent=`${curCat.icon} ${curCat.name} 퀴즈`;
  show('sc-quiz'); renderQuiz();
}
function renderQuiz(){
  const w=quizWords[quizIdx];
  $('q-eng').textContent=w.e;
  $('q-input').value=''; $('q-fb').textContent=''; $('q-fb').className='feedback';
  $('quiz-info').textContent=`${quizIdx+1} / 20`;
  $('quiz-bar').style.width=((quizIdx+1)/20*100)+'%';
  setTimeout(()=>$('q-input').focus(),60);
}
function checkQuiz(){
  const ans=$('q-input').value.trim(); if(!ans)return;
  const w=quizWords[quizIdx]; const c=w.k;
  const ok=ans===c||c.split('/').some(p=>p.trim()===ans)||c.includes(ans);
  if(ok){quizScore++;$('q-fb').textContent='⭕ 정답!';$('q-fb').className='feedback fb-ok';}
  else{wrongWords.push(w);$('q-fb').textContent=`❌ 오답 — 정답: ${c}`;$('q-fb').className='feedback fb-ng';}
  $('q-input').disabled=true;
  setTimeout(()=>{
    $('q-input').disabled=false;
    if(quizIdx<19){quizIdx++;renderQuiz();}else showResult();
  },1300);
}

// ── Result ────────────────────────────────────────────────
function showResult(){
  const now=Date.now();
  const pass=quizScore>=15;
  saveRecord(curUser,{catId:curCat.id,catName:curCat.name,catIcon:curCat.icon,
    score:quizScore,total:20,pass,date:now});
  show('sc-result');
  $('r-name').textContent=`👤 ${curUser}`;
  $('r-date').textContent=`📅 ${fmtDT(now)}  ·  ${curCat.icon} ${curCat.name}`;
  $('r-emoji').textContent=pass?'🎉':'😢';
  $('r-title').textContent=pass?'통과!':'다시 도전해요!';
  $('r-score').textContent=`${quizScore} / 20`;
  $('r-score').className='result-score '+(pass?'score-pass':'score-fail');
  $('r-msg').textContent=pass
    ?`${curCat.name} 범주 완료! 정말 잘했어요!`
    :'15개 이상 맞아야 통과예요. 조금 더 공부하고 재도전!';
  if(wrongWords.length){
    $('r-wrong').style.display='block';
    $('r-wrong-list').innerHTML=wrongWords.map(w=>
      `<div class="wrong-item"><span class="wi-eng">${w.e}</span><span class="wi-kor">${w.k}</span></div>`
    ).join('');
  }else{$('r-wrong').style.display='none';}
}
function retryStudy(){startCat(curCat.id);}

// ── Stats ─────────────────────────────────────────────────
function showStats(){show('sc-stats');renderStats();}

function renderStats(){
  const recs=getUserData(curUser).records||[];
  // Summary cards
  const total=recs.length;
  const passed=recs.filter(r=>r.pass).length;
  const avg=total?Math.round(recs.reduce((s,r)=>s+r.score,0)/total):0;
  $('stat-boxes').innerHTML=`
    <div class="stat-box"><div class="stat-num">${total}</div><div class="stat-lbl">총 퀴즈</div></div>
    <div class="stat-box"><div class="stat-num green">${passed}</div><div class="stat-lbl">통과 횟수</div></div>
    <div class="stat-box"><div class="stat-num">${avg}<span style="font-size:16px">/20</span></div><div class="stat-lbl">평균 점수</div></div>`;

  // Category filter chips
  const catIds=[...new Set(recs.map(r=>r.catId))];
  $('cat-filter').innerHTML=
    `<button class="f-chip ${activeCatFilter==='all'?'active':''}" onclick="setCatFilter('all')">전체</button>`
    +catIds.map(id=>{
      const c=CATS.find(x=>x.id===id);
      return c?`<button class="f-chip ${activeCatFilter===id?'active':''}" onclick="setCatFilter('${id}')">${c.icon} ${c.name}</button>`:'';
    }).join('');

  // Filtered records
  const filtered=activeCatFilter==='all'?recs:recs.filter(r=>r.catId===activeCatFilter);
  const last20=filtered.slice(-20);

  // Chart
  if(scoreChart){scoreChart.destroy();scoreChart=null;}
  if(last20.length){
    const ctx=$('score-chart').getContext('2d');
    scoreChart=new Chart(ctx,{
      type:'line',
      data:{
        labels:last20.map(r=>`${fmtDate(r.date)} ${r.catIcon}`),
        datasets:[
          {label:'점수',data:last20.map(r=>r.score),
           borderColor:'#00B894',backgroundColor:'rgba(0,184,148,0.07)',
           borderWidth:2.5,tension:0.35,fill:true,
           pointBackgroundColor:last20.map(r=>r.pass?'#00B894':'#E17055'),
           pointBorderColor:'#fff',pointBorderWidth:2,pointRadius:6},
          {label:'통과선',data:last20.map(()=>15),
           borderColor:'#FDCB6E',borderDash:[5,5],borderWidth:1.5,
           pointRadius:0,fill:false}
        ]
      },
      options:{
        responsive:true,maintainAspectRatio:false,
        plugins:{
          legend:{display:false},
          tooltip:{callbacks:{
            label:ctx=>`${ctx.parsed.y}/20점`,
            afterLabel:ctx=>last20[ctx.dataIndex].pass?'✅ 통과':'❌ 미통과'
          }}
        },
        scales:{
          y:{min:0,max:20,ticks:{stepSize:5},grid:{color:'#F0F2F5'}},
          x:{ticks:{maxRotation:40,font:{size:10}},grid:{display:false}}
        }
      }
    });
  }

  // History table
  const hw=$('history-wrap');
  if(!filtered.length){hw.innerHTML='<div class="no-data">아직 학습 기록이 없어요 📚</div>';return;}
  const rows=[...filtered].reverse().slice(0,30);
  hw.innerHTML=`<table class="hist-table">
    <thead><tr><th>날짜 / 시간</th><th>범주</th><th>점수</th><th>결과</th></tr></thead>
    <tbody>${rows.map(r=>`<tr>
      <td style="font-size:12px;color:#636E72">${fmtDT(r.date)}</td>
      <td>${r.catIcon} ${r.catName}</td>
      <td style="font-weight:700;color:${r.pass?'#00B894':'#E17055'}">${r.score}/20</td>
      <td><span class="badge ${r.pass?'badge-pass':'badge-fail'}">${r.pass?'통과':'재도전'}</span></td>
    </tr>`).join('')}</tbody>
  </table>`;
}
function setCatFilter(id){activeCatFilter=id;renderStats();}

// ── Init ──────────────────────────────────────────────────
initLogin();
</script>
</body>
</html>
