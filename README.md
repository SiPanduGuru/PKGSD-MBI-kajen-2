<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Family | English Grade 3</title>
<style>
:root{--navy:#173b68;--blue:#4ca6dc;--sky:#e9f7ff;--yellow:#ffd45f;--coral:#ff8d7c;--green:#8bcda5;--cream:#fffaf0;--ink:#26364a;--white:#fff;--shadow:0 12px 30px #23476b18}
*{box-sizing:border-box}body{margin:0;font-family:"Trebuchet MS",Arial,sans-serif;background:linear-gradient(145deg,#e7f6ff,#fff7e8);color:var(--ink)}
header{padding:26px 18px 22px;text-align:center;background:linear-gradient(120deg,#bfeaff,#fff0b9);border-bottom:5px solid white;position:relative;overflow:hidden}
header:before,header:after{content:"☁️";position:absolute;font-size:48px;opacity:.65;top:12px}header:before{left:5%}header:after{right:5%}
h1{margin:0;color:var(--navy);font-size:clamp(2rem,6vw,3.5rem);letter-spacing:1px}header p{margin:8px 0 0;font-size:1.08rem;font-weight:700}
nav{display:flex;gap:8px;justify-content:center;flex-wrap:wrap;padding:12px;background:#ffffffc9;position:sticky;top:0;z-index:5;backdrop-filter:blur(8px)}
nav button,.btn{border:0;border-radius:999px;padding:10px 16px;font-weight:800;background:var(--navy);color:white;cursor:pointer;box-shadow:0 4px 0 #102b4b;transition:.15s}
nav button:hover,.btn:hover{transform:translateY(-2px);filter:brightness(1.08)}button:focus-visible{outline:4px solid var(--yellow);outline-offset:3px}
nav button.active{background:var(--coral);box-shadow:0 4px 0 #c75e53}
main{max-width:1100px;margin:22px auto;padding:0 16px 50px}
section{display:none;animation:fade .25s ease}section.active{display:block}@keyframes fade{from{opacity:.3;transform:translateY(7px)}to{opacity:1;transform:none}}
.panel{background:white;border-radius:24px;padding:clamp(18px,3vw,30px);box-shadow:var(--shadow);margin-bottom:18px;border:2px solid #fff}
h2{color:var(--navy);font-size:clamp(1.5rem,4vw,2.1rem);margin:0 0 10px}h3{color:var(--navy);margin:8px 0}
.lead{font-size:1.08rem;line-height:1.6}.goal{background:#fff6d8;border-left:7px solid var(--yellow);padding:14px 18px;border-radius:14px;line-height:1.55}
.family-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(145px,1fr));gap:14px;margin-top:18px}
.person{background:var(--sky);border:2px solid #d4edfc;border-radius:20px;padding:15px 10px;text-align:center;cursor:pointer;transition:.2s;min-height:190px}
.person:hover{transform:translateY(-5px);box-shadow:var(--shadow);background:#fff6d8}
.avatar{font-size:clamp(3.2rem,8vw,4.7rem);display:block;line-height:1.35;filter:drop-shadow(0 4px 1px #173b6815)}
.word{font-size:1.2rem;color:var(--navy);font-weight:900}.translation{font-size:.9rem;color:#5c6c7d;margin-top:4px}
.small{font-size:.9rem;color:#607286}.row{display:flex;gap:10px;flex-wrap:wrap;align-items:center}.center{text-align:center}
.btn.secondary{background:var(--blue);box-shadow:0 4px 0 #2678aa}.btn.yellow{background:var(--yellow);color:var(--navy);box-shadow:0 4px 0 #d6a82e}.btn.coral{background:var(--coral);box-shadow:0 4px 0 #c75e53}
.flashcard{max-width:460px;margin:18px auto;text-align:center;background:linear-gradient(145deg,#e8f7ff,#fff5d5);border:3px solid white;border-radius:26px;padding:25px;box-shadow:var(--shadow);min-height:270px}
.flashcard .avatar{font-size:6rem}.flashcard .word{font-size:2rem;margin:8px}
.game-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(135px,1fr));gap:10px;margin:16px 0}
.choice{border:2px solid #d7eaf5;border-radius:15px;padding:13px;background:#f5fbff;font-weight:800;color:var(--navy);cursor:pointer;font-size:1rem}
.choice:hover{background:#fff4cc;border-color:var(--yellow)}
.feedback{font-weight:800;min-height:28px;margin:12px 0;color:var(--navy)}
.progress{height:12px;background:#e7edf3;border-radius:20px;overflow:hidden;margin:12px 0}.bar{height:100%;background:linear-gradient(90deg,var(--green),var(--blue));width:0%;transition:.3s}
.match-card{min-height:100px;display:flex;align-items:center;justify-content:center;text-align:center;font-size:1.1rem}
.match-card .avatar{font-size:2.5rem}
input[type=text]{padding:12px;border:2px solid #cfe5f4;border-radius:12px;font-size:1rem;max-width:100%}
footer{text-align:center;padding:20px;color:#5b7185;font-size:.9rem}
@media(max-width:600px){nav{position:static}nav button{padding:9px 12px;font-size:.88rem}.panel{border-radius:18px}.person{min-height:165px}}

/* LANDSCAPE UPGRADE */
body{background:
 radial-gradient(circle at 8% 8%,#fff3bf 0 8%,transparent 8.5%),
 radial-gradient(circle at 95% 22%,#c9f0ff 0 9%,transparent 9.5%),
 linear-gradient(135deg,#e5f6ff 0%,#fff8e8 55%,#f0eaff 100%)}
header{padding:18px 24px 16px;min-height:150px;display:flex;align-items:center;justify-content:center;gap:28px}
header h1{font-size:clamp(2.3rem,4vw,4rem);text-shadow:2px 3px 0 #fff}
header p{font-size:1.15rem}
nav{gap:10px;padding:13px 16px}
nav button{font-size:.98rem;padding:11px 18px}
main{max-width:1450px;margin:20px auto;padding:0 22px 55px}
.panel{padding:clamp(20px,2.5vw,34px);border-radius:28px;box-shadow:0 15px 35px #31577b18}
h2{font-size:clamp(1.7rem,2.4vw,2.5rem)}
.family-grid{grid-template-columns:repeat(6,minmax(0,1fr));gap:16px}
.person{min-height:215px;padding:18px 10px;border-radius:23px;background:linear-gradient(155deg,#f1fbff,#e5f4ff);box-shadow:0 6px 0 #cfe7f6;position:relative;overflow:hidden}
.person:after{content:"✦";position:absolute;right:12px;top:8px;color:#ffc84c;font-size:20px}
.person .avatar{font-size:clamp(3.6rem,5vw,5rem)}
.person .word{font-size:clamp(1.05rem,1.5vw,1.35rem)}
.person .translation{font-size:.95rem}
.person:hover{transform:translateY(-7px) rotate(-1deg);box-shadow:0 12px 20px #23476b20}
#home .family-grid{margin-top:25px}
#home .panel:first-child{background:linear-gradient(120deg,#fff 0%,#f4fbff 58%,#fff8df 100%)}
.goal{font-size:1.05rem;padding:18px 22px}
.flashcard{max-width:700px;min-height:300px;padding:28px;background:linear-gradient(135deg,#dff4ff,#fff1c7);border:4px solid #fff;box-shadow:0 12px 0 #d5eaf6}
.flashcard .avatar{font-size:6.5rem}
.flashcard .word{font-size:2.4rem}
.game-grid{grid-template-columns:repeat(3,minmax(0,1fr));gap:13px}
.choice{padding:16px;border-radius:18px;font-size:1.08rem;box-shadow:0 4px 0 #dcebf4}
.choice:active{transform:translateY(3px);box-shadow:none}
.match-card{min-height:120px}
.progress{height:15px;background:#e7eff6}
.bar{background:linear-gradient(90deg,#77d6a0,#4ca6dc,#a58bea);border-radius:20px}
.btn{font-size:1rem;padding:12px 20px}
button:disabled{opacity:.65;cursor:default}
#memoryBoard{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:14px;max-width:1000px;margin:20px auto}
.memory-card{min-height:145px;border:0;border-radius:22px;background:linear-gradient(145deg,#5ab2e7,#3b83c2);color:#fff;font-size:2.4rem;font-weight:900;box-shadow:0 7px 0 #286b9f;cursor:pointer;transition:.2s}
.memory-card .back{font-size:1.1rem;letter-spacing:2px}
.memory-card.revealed,.memory-card.matched{background:linear-gradient(145deg,#fff2bf,#ffe18b);color:#173b68;box-shadow:0 7px 0 #e4bd55}
.memory-card.matched{background:linear-gradient(145deg,#d8f8e5,#a8e6bd);box-shadow:0 7px 0 #78bf91}
.hero-row{display:grid;grid-template-columns:1.2fr .8fr;gap:22px;align-items:center}
.hero-note{background:#fff4ce;border-radius:24px;padding:22px}
.landscape-tip{display:inline-block;background:#e6f7ec;color:#236343;border-radius:99px;padding:7px 13px;font-weight:800;font-size:.85rem}
@media(min-width:1000px){
 #say .panel:first-child{display:grid;grid-template-columns:.9fr 1.1fr;align-items:center;column-gap:28px}
 #say .panel:first-child h2,#say .panel:first-child>p{grid-column:1/-1}
 #say .flashcard{grid-column:1;grid-row:3/5;width:100%}
 #say .row{grid-column:2;justify-content:center}
 #say .small{grid-column:2;text-align:center}
}
@media(max-width:950px){.family-grid{grid-template-columns:repeat(3,minmax(0,1fr))}}
@media(max-width:650px){
 header{min-height:unset;padding:22px 12px;display:block}
 main{padding:0 12px 35px}
 .family-grid{grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}
 .person{min-height:165px}
 .game-grid{grid-template-columns:repeat(2,minmax(0,1fr))}
 #memoryBoard{grid-template-columns:repeat(3,minmax(0,1fr));gap:9px}
 .memory-card{min-height:105px}
}
@media(orientation:landscape) and (min-width:800px){
 header{min-height:125px;padding:12px 20px}
 main{margin-top:14px}
 section.active{min-height:calc(100vh - 230px)}
}

</style>
</head>
<body>
<header>
  <h1>🌈 MY FAMILY 🏡</h1>
  <p>Let’s learn English together! | Grade 3</p>
</header>
<nav aria-label="Menu pembelajaran">
  <button class="active" data-go="home">🏠 Home</button>
  <button data-go="learn">👨‍👩‍👧‍👦 Learn</button>
  <button data-go="say">🗣️ Listen & Say</button>
  <button data-go="game">🎮 Games</button>
  <button data-go="quiz">⭐ Quiz</button>
  <button data-go="memory">🃏 Memory</button>
</nav>
<main>
<section id="home" class="active">
 <div class="panel">
  <h2>Hello, students! 👋</h2>
  <p class="lead">Today we will learn the names of family members in English. Look at the pictures, listen carefully, repeat the words, and play the games!</p>
  <div class="goal"><strong>🎯 Tujuan Pembelajaran</strong><br>Pada akhir pembelajaran ini, murid diharapkan mampu mengidentifikasi dan melafalkan kosakata anggota keluarga (<b>Father, Mother, Brother, Sister, Grandmother, Grandfather</b>) dengan benar secara lisan.</div>
  <div class="family-grid">
   <div class="person"><span class="avatar">👨🏻</span><div class="word">Father</div><div class="translation">Ayah</div></div>
   <div class="person"><span class="avatar">👩🏻</span><div class="word">Mother</div><div class="translation">Ibu</div></div>
   <div class="person"><span class="avatar">👦🏻</span><div class="word">Brother</div><div class="translation">Saudara laki-laki</div></div>
   <div class="person"><span class="avatar">👧🏻</span><div class="word">Sister</div><div class="translation">Saudara perempuan</div></div>
   <div class="person"><span class="avatar">👴🏻</span><div class="word">Grandfather</div><div class="translation">Kakek</div></div>
   <div class="person"><span class="avatar">👵🏻</span><div class="word">Grandmother</div><div class="translation">Nenek</div></div>
  </div>
  <p class="center"><button class="btn yellow" onclick="go('learn')">Start Learning! ➜</button></p>
 </div>
 <div class="panel"><h2>🧑‍🏫 How to learn</h2><p class="lead">1. <b>Look</b> at the picture. &nbsp; 2. <b>Listen</b> to the word. &nbsp; 3. <b>Repeat</b> the word. &nbsp; 4. <b>Play</b> the games!</p></div>
</section>

<section id="learn">
 <div class="panel">
  <h2>👨‍👩‍👧‍👦 Meet the Family!</h2>
  <p class="lead">Klik kartu untuk mendengarkan cara pengucapannya.</p>
  <div class="family-grid" id="learnGrid"></div>
 </div>
</section>

<section id="say">
 <div class="panel center">
  <h2>🎧 Listen and Say!</h2>
  <p class="lead">Tekan tombol speaker. Dengarkan, lalu tirukan dengan suara jelas.</p>
  <div class="flashcard" id="flash">
   <div class="avatar" id="flashEmoji">👨🏻</div><div class="word" id="flashWord">Father</div>
   <div class="translation" id="flashMeaning">Ayah</div>
   <button class="btn secondary" id="speakCurrent">🔊 Listen</button>
  </div>
  <div class="row" style="justify-content:center">
   <button class="btn" id="prev">← Previous</button><button class="btn yellow" id="next">Next →</button>
  </div>
  <p class="small">Pronunciation helper: <b>FA-ther • MUTH-er • BRUH-ther • SIS-ter</b><br>Grandfather and Grandmother: say “grand” + the family word.</p>
 </div>
 <div class="panel"><h3>👏 Family Chant</h3><p class="lead center">Father, Father, this is my father!<br>Mother, Mother, this is my mother!<br>Brother, Brother, this is my brother!<br>Sister, Sister, this is my sister!<br>Grandfather, Grandfather, this is my grandfather!<br>Grandmother, Grandmother, this is my grandmother!</p><p class="center"><button class="btn coral" onclick="speak('Father, Father. This is my father. Mother, Mother. This is my mother. Brother, Brother. This is my brother. Sister, Sister. This is my sister. Grandfather, Grandfather. This is my grandfather. Grandmother, Grandmother. This is my grandmother.')">🔊 Play chant</button></p></div>
</section>

<section id="game">
 <div class="panel">
  <h2>🎮 Game 1: Who is this?</h2><p class="lead">Pilih nama anggota keluarga yang tepat berdasarkan gambar.</p>
  <div class="flashcard"><div class="avatar" id="gameEmoji">👩🏻</div><div class="small">Who is this?</div></div>
  <div class="game-grid" id="gameChoices"></div><div class="feedback" id="gameFeedback" aria-live="polite"></div>
  <div class="progress"><div class="bar" id="gameBar"></div></div>
  <div class="row"><span id="gameCount">Question 1 of 6</span><button class="btn secondary" id="gameNext">Next question ➜</button><button class="btn yellow" id="gameReset">↻ Restart</button></div>
 </div>
 <div class="panel">
  <h2>🧩 Game 2: Match the Words</h2><p class="lead">Pasangkan gambar dengan kata yang sesuai. Pilih satu gambar dan satu kata.</p>
  <div class="game-grid" id="matchPics"></div><div class="game-grid" id="matchWords"></div>
  <div class="feedback" id="matchFeedback" aria-live="polite">Matched: 0 / 6</div>
  <button class="btn yellow" onclick="resetMatch()">↻ Play again</button>
 </div>
</section>

<section id="quiz">
 <div class="panel">
  <h2>⭐ Quick Quiz</h2><p class="lead">Uji pemahamanmu! Dengarkan pertanyaan atau baca petunjuk, lalu pilih jawaban.</p>
  <div class="flashcard"><div class="avatar" id="quizEmoji">👴🏻</div><div class="word">Who is this?</div><button class="btn secondary" id="quizListen">🔊 Listen to the word</button></div>
  <div class="game-grid" id="quizChoices"></div>
  <div class="feedback" id="quizFeedback" aria-live="polite"></div>
  <div class="progress"><div class="bar" id="quizBar"></div></div>
  <div class="row"><span id="quizCount">Score: 0 / 6</span><button class="btn" id="quizNext">Next ➜</button><button class="btn yellow" id="quizReset">↻ Try again</button></div>
 </div>
 <div class="panel"><h3>🌟 Self Reflection</h3><p>Bagaimana perasaanmu setelah belajar?</p><div class="row"><button class="choice" onclick="reflect('Great! You did it! 🌟')">😊 I can say the words!</button><button class="choice" onclick="reflect('Good effort! Keep practising! 💪')">🙂 I need more practice.</button></div><div class="feedback" id="reflection"></div></div>
</section>

<section id="memory">
 <div class="panel center">
  <span class="landscape-tip">🃏 MEMORY CHALLENGE</span>
  <h2>Find the Family Pairs!</h2>
  <p class="lead">Buka dua kartu. Temukan pasangan gambar dan nama anggota keluarga yang cocok!</p>
  <div class="row" style="justify-content:center">
   <span class="landscape-tip">Moves: <b id="memoryMoves">0</b></span>
   <span class="landscape-tip">Pairs: <b id="memoryPairs">0 / 6</b></span>
  </div>
  <div id="memoryBoard"></div>
  <div class="feedback" id="memoryFeedback" aria-live="polite">You can do it! Find all six pairs.</div>
  <button class="btn yellow" onclick="startMemory()">↻ Shuffle & Play Again</button>
 </div>
 <div class="panel">
  <h3>🗣️ Say it when you find a pair!</h3>
  <p class="lead">Setelah menemukan pasangan, ucapkan kosakatanya bersama-sama: <b>Father, Mother, Brother, Sister, Grandfather, Grandmother.</b></p>
 </div>
</section>

</main>
<footer>🌼 Great job, everyone! Keep learning and keep speaking English! 🌼</footer>
<script>
const people=[
 {word:"Father",meaning:"Ayah",emoji:"👨🏻"},
 {word:"Mother",meaning:"Ibu",emoji:"👩🏻"},
 {word:"Brother",meaning:"Saudara laki-laki",emoji:"👦🏻"},
 {word:"Sister",meaning:"Saudara perempuan",emoji:"👧🏻"},
 {word:"Grandfather",meaning:"Kakek",emoji:"👴🏻"},
 {word:"Grandmother",meaning:"Nenek",emoji:"👵🏻"}
];
function go(id){document.querySelectorAll('section').forEach(s=>s.classList.toggle('active',s.id===id));document.querySelectorAll('nav button').forEach(b=>b.classList.toggle('active',b.dataset.go===id));window.scrollTo({top:0,behavior:'smooth'});}
document.querySelectorAll('nav button').forEach(b=>b.addEventListener('click',()=>go(b.dataset.go)));
function speak(word){if(!('speechSynthesis'in window)){alert('Fitur suara belum didukung browser ini. Guru dapat mengucapkan kata sebagai contoh.');return;}speechSynthesis.cancel();let u=new SpeechSynthesisUtterance(word);u.lang='en-US';u.rate=.78;speechSynthesis.speak(u);}
function personCard(p){return `<button class="person" onclick="speak('${p.word}')"><span class="avatar">${p.emoji}</span><div class="word">${p.word}</div><div class="translation">${p.meaning}</div><div class="small">🔊 Tap to listen</div></button>`}
document.getElementById('learnGrid').innerHTML=people.map(personCard).join('');
let flashIndex=0;
function showFlash(){let p=people[flashIndex];flashEmoji.textContent=p.emoji;flashWord.textContent=p.word;flashMeaning.textContent=p.meaning;}
speakCurrent.onclick=()=>speak(people[flashIndex].word);
prev.onclick=()=>{flashIndex=(flashIndex+5)%6;showFlash()};next.onclick=()=>{flashIndex=(flashIndex+1)%6;showFlash()};
let gameIndex=0,gameOrder=[2,5,1,4,0,3],gameDone=0;
function renderGame(){let p=people[gameOrder[gameIndex]];gameEmoji.textContent=p.emoji;gameCount.textContent=`Question ${gameIndex+1} of 6`;gameFeedback.textContent='';gameChoices.innerHTML=[...people].sort(()=>Math.random()-.5).map(x=>`<button class="choice" onclick="answerGame('${x.word}')">${x.word}</button>`).join('');}
function answerGame(w){let correct=people[gameOrder[gameIndex]].word;if(w===correct){gameFeedback.textContent='✅ Correct! Excellent!';gameDone=Math.max(gameDone,gameIndex+1);gameBar.style.width=(gameDone/6*100)+'%';gameChoices.querySelectorAll('button').forEach(b=>b.disabled=true)}else gameFeedback.textContent='💡 Try again. Look at the picture!';}
gameNext.onclick=()=>{gameIndex=(gameIndex+1)%6;renderGame()};gameReset.onclick=()=>{gameIndex=0;gameDone=0;gameBar.style.width='0%';renderGame()};renderGame();
let selectedPic=null,selectedWord=null,matched=new Set();
function resetMatch(){selectedPic=null;selectedWord=null;matched.clear();matchFeedback.textContent='Matched: 0 / 6';renderMatch()}
function renderMatch(){
 matchPics.innerHTML=people.map((p,i)=>`<button class="choice match-card" id="pic${i}" onclick="pickPic(${i})"><span class="avatar">${p.emoji}</span></button>`).join('');
 matchWords.innerHTML=[...people].map((p)=>p).sort(()=>Math.random()-.5).map(p=>`<button class="choice match-card" id="word${p.word}" onclick="pickWord('${p.word}')">${p.word}</button>`).join('');
}
function pickPic(i){if(matched.has(i))return;selectedPic=i;document.querySelectorAll('#matchPics button').forEach(b=>b.style.borderColor='');document.getElementById('pic'+i).style.borderColor='#ffb92e';checkMatch()}
function pickWord(w){if(matched.has(people.findIndex(p=>p.word===w)))return;selectedWord=w;document.querySelectorAll('#matchWords button').forEach(b=>b.style.borderColor='');document.getElementById('word'+w).style.borderColor='#ffb92e';checkMatch()}
function checkMatch(){if(selectedPic===null||!selectedWord)return;let p=people[selectedPic];if(p.word===selectedWord){matched.add(selectedPic);document.getElementById('pic'+selectedPic).disabled=true;document.getElementById('word'+selectedWord).disabled=true;document.getElementById('pic'+selectedPic).style.background='#dcf7e5';document.getElementById('word'+selectedWord).style.background='#dcf7e5';matchFeedback.textContent=`🎉 Great match! Matched: ${matched.size} / 6`;if(matched.size===6)matchFeedback.textContent='🏆 Perfect! All pairs matched!';}else{matchFeedback.textContent='Not a match yet. Try another pair!'}selectedPic=null;selectedWord=null;}
renderMatch();
let quizIndex=0,quizScore=0,quizAnswered=false,quizOrder=[5,0,3,2,4,1];
function renderQuiz(){let p=people[quizOrder[quizIndex]];quizEmoji.textContent=p.emoji;quizFeedback.textContent='';quizAnswered=false;quizCount.textContent=`Score: ${quizScore} / 6`;quizBar.style.width=(quizIndex/6*100)+'%';quizChoices.innerHTML=[...people].sort(()=>Math.random()-.5).map(x=>`<button class="choice" onclick="answerQuiz('${x.word}')">${x.word}</button>`).join('');}
function answerQuiz(w){if(quizAnswered)return;quizAnswered=true;let p=people[quizOrder[quizIndex]];if(w===p.word){quizScore++;quizFeedback.textContent='✅ Correct answer! Well done!';}else quizFeedback.textContent=`The correct answer is ${p.word}. Keep practising!`;quizCount.textContent=`Score: ${quizScore} / 6`;quizBar.style.width=((quizIndex+1)/6*100)+'%';}
quizListen.onclick=()=>speak(people[quizOrder[quizIndex]].word);quizNext.onclick=()=>{if(!quizAnswered){quizFeedback.textContent='Choose an answer first!';return;}if(quizIndex<5){quizIndex++;renderQuiz()}else{quizFeedback.textContent=`🎉 Quiz finished! Your score: ${quizScore} / 6`;quizNext.disabled=true;}};quizReset.onclick=()=>{quizIndex=0;quizScore=0;quizNext.disabled=false;renderQuiz()};renderQuiz();
function reflect(msg){reflection.textContent=msg;}

// Memory match game: picture + word pairs
let memoryDeck=[],memoryOpen=[],memoryMatched=0,memoryMoveCount=0,memoryLock=false;
function startMemory(){
 memoryDeck=[];
 people.forEach((p,i)=>{memoryDeck.push({id:i,type:'pic',face:p.emoji,word:p.word});memoryDeck.push({id:i,type:'word',face:p.word,word:p.word});});
 memoryDeck.sort(()=>Math.random()-.5);memoryOpen=[];memoryMatched=0;memoryMoveCount=0;memoryLock=false;
 memoryMoves.textContent='0';memoryPairs.textContent='0 / 6';memoryFeedback.textContent='You can do it! Find all six pairs.';
 memoryBoard.innerHTML=memoryDeck.map((c,i)=>`<button class="memory-card" id="mem${i}" onclick="flipMemory(${i})"><span class="back">?</span></button>`).join('');
}
function flipMemory(i){
 if(memoryLock||memoryOpen.includes(i)||memoryDeck[i].done)return;
 const c=memoryDeck[i],el=document.getElementById('mem'+i);
 el.classList.add('revealed');el.innerHTML=c.type==='pic'?`<span>${c.face}</span>`:`<span style="font-size:1.1rem">${c.face}</span>`;
 memoryOpen.push(i);
 if(memoryOpen.length===2){
  memoryMoveCount++;memoryMoves.textContent=memoryMoveCount;
  const [a,b]=memoryOpen,ca=memoryDeck[a],cb=memoryDeck[b];
  if(ca.id===cb.id&&ca.type!==cb.type){
   ca.done=true;cb.done=true;memoryMatched++;memoryPairs.textContent=memoryMatched+' / 6';
   document.getElementById('mem'+a).classList.add('matched');document.getElementById('mem'+b).classList.add('matched');
   memoryFeedback.textContent='🎉 Great! '+ca.word+'! Say it aloud!';
   speak(ca.word);memoryOpen=[];
   if(memoryMatched===6)memoryFeedback.textContent='🏆 Fantastic! You found all family pairs!';
  }else{
   memoryFeedback.textContent='Not a pair. Try again!';
   memoryLock=true;setTimeout(()=>{[a,b].forEach(j=>{let e=document.getElementById('mem'+j);e.classList.remove('revealed');e.innerHTML='<span class="back">?</span>';});memoryOpen=[];memoryLock=false;},850);
  }
 }
}
startMemory();

</script>
</body>
</html>
