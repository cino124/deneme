<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#071b3d">
<title>Fenerbahçe Bilmece Arenası</title>
<style>
:root{--navy:#071b3d;--navy2:#102d59;--yellow:#ffd52a;--gold:#eab91c;--ink:#f7f9ff;--muted:#aab8d2;--panel:#10284d;--panel2:#17365f;--green:#42d6a1;--red:#ff7777}
*{box-sizing:border-box}
body{margin:0;min-height:100vh;color:var(--ink);font-family:Inter,Segoe UI,Arial,sans-serif;background:radial-gradient(ellipse at 50% -10%,#224d7c 0,#0b2850 38%,#06152e 80%);padding:28px 16px 40px}
.wrap{width:min(940px,100%);margin:auto}
.topline{display:flex;justify-content:space-between;align-items:center;gap:12px;margin-bottom:18px;color:var(--muted);font-size:12px;letter-spacing:.1em;text-transform:uppercase}
.brand{display:flex;align-items:center;gap:13px}.crest{width:52px;height:61px;flex:none;display:grid;place-items:center;background:linear-gradient(90deg,var(--yellow) 0 44%,#fff 44% 51%,var(--navy2) 51% 100%);clip-path:polygon(5% 0,95% 0,90% 72%,50% 100%,10% 72%);color:#092047;font-weight:1000;font-size:13px;text-shadow:0 1px #fff;position:relative}.crest:after{content:"1907";position:absolute;bottom:12px;font-size:9px;letter-spacing:.5px;color:#fff;text-shadow:0 1px 2px #001}
h1{font-size:clamp(26px,5vw,42px);line-height:1.02;margin:0;color:var(--yellow);letter-spacing:-.045em}.subtitle{margin:7px 0 0;color:#d4def0;font-size:14px}.tag{border:1px solid #45628a;border-radius:999px;padding:8px 12px;color:#dce7f9;font-size:10px;white-space:nowrap;letter-spacing:.05em}
.card{background:linear-gradient(160deg,rgba(19,48,87,.98),rgba(8,28,57,.99));border:1px solid #35547e;box-shadow:0 22px 70px #0007;border-radius:25px;overflow:hidden}
.welcome{padding:clamp(25px,5vw,48px);text-align:center;background:radial-gradient(ellipse at 50% 0%,#264d78 0,transparent 65%),linear-gradient(145deg,#102e56,#081d3b)}
.welcome-mark{width:86px;height:86px;margin:0 auto 18px;border-radius:50%;display:grid;place-items:center;background:linear-gradient(135deg,var(--yellow),#f1b800);color:#0a2145;font-size:39px;box-shadow:0 8px 36px #ffd52a30;border:4px solid #fff3}
.eyebrow{color:#ffe47b;font-weight:900;font-size:11px;letter-spacing:.19em;text-transform:uppercase;margin-bottom:12px}.welcome h2{font-size:clamp(27px,5vw,43px);margin:0;color:#fff;letter-spacing:-.035em}.welcome h2 span{color:var(--yellow)}.welcome p{max-width:590px;margin:13px auto 24px;color:#bdcce2;line-height:1.65;font-size:14px}
.name-box{max-width:390px;margin:0 auto;text-align:left}.name-box label{display:block;color:#e4edfa;font-size:11px;font-weight:900;letter-spacing:.1em;margin:0 0 8px 3px}.name-box input{width:100%;background:#071a35;border:1px solid #526d91;color:white;border-radius:12px;padding:15px 16px;font:inherit;font-size:16px;outline:none}.name-box input:focus{border-color:var(--yellow);box-shadow:0 0 0 3px #ffd52a22}.name-box input::placeholder{color:#8194b2}.name-help{color:#99abc8;font-size:11px;margin:8px 2px 16px}.primary{background:var(--yellow);color:#12264a;min-width:145px}.start-btn{width:100%;padding:16px;font-size:14px;letter-spacing:.04em}.welcome-features{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;max-width:600px;margin:27px auto 0}.feature{background:#ffffff0b;border:1px solid #ffffff18;border-radius:13px;padding:13px 8px}.feature b{display:block;color:var(--yellow);font-size:15px;margin-bottom:5px}.feature small{color:#adbeda;font-size:11px}
.game-content{display:none}.game-content.show{display:block}.hero{padding:21px 28px 15px;background:linear-gradient(110deg,rgba(255,213,42,.12),transparent 48%)}.hero-top{display:flex;justify-content:space-between;align-items:center;gap:14px;flex-wrap:wrap}.hero h2{margin:0;font-size:19px}.hero p{color:var(--muted);margin:6px 0 0;font-size:13px}.hero-tools{display:flex;gap:9px;align-items:center;flex-wrap:wrap}.player-badge{border:1px solid #50698d;border-radius:999px;padding:8px 12px;color:#f6e7a8;font-size:12px;font-weight:800}.stats{display:grid;grid-template-columns:repeat(5,1fr);gap:9px;padding:0 28px 18px}.stat{background:#0a2042;border:1px solid #29466d;border-radius:13px;padding:11px 12px}.stat small{display:block;color:var(--muted);font-size:10px;text-transform:uppercase;letter-spacing:.07em;margin-bottom:6px}.stat strong{font-size:21px;color:var(--yellow);font-variant-numeric:tabular-nums}.stat.timer strong{color:#fff}.stat.timer.warning strong{color:#ff9c83;animation:pulse 1s infinite}@keyframes pulse{50%{opacity:.55}}
.progress-area{padding:0 28px 19px}.progress-label{display:flex;justify-content:space-between;color:var(--muted);font-size:12px;margin-bottom:8px}.track{height:9px;background:#061631;border-radius:99px;overflow:hidden;border:1px solid #29466d}.fill{height:100%;width:0;background:linear-gradient(90deg,var(--gold),var(--yellow));border-radius:99px;transition:width .35s ease}
.play{padding:23px 28px 28px;border-top:1px solid #29466d;background:rgba(4,17,37,.3)}.levelrow{display:flex;justify-content:space-between;align-items:center;gap:10px;margin-bottom:14px}.level{display:inline-flex;align-items:center;gap:7px;border-radius:999px;padding:7px 12px;background:#253e66;color:#ffe58a;font-size:12px;font-weight:800;letter-spacing:.04em}.question-no{color:var(--muted);font-size:12px}.riddle{min-height:130px;border:1px solid #42628e;border-radius:18px;background:linear-gradient(140deg,#183964,#10294e);display:flex;align-items:center;justify-content:center;text-align:center;padding:26px 22px;font-size:clamp(19px,3vw,26px);font-weight:750;line-height:1.42;box-shadow:inset 0 1px #ffffff0b}.options{display:grid;grid-template-columns:1fr 1fr;gap:11px;margin-top:16px}.option{display:flex;gap:12px;align-items:center;text-align:left;background:#10294c;border:1px solid #42628e;color:#f6f8ff;min-height:59px;padding:12px 14px;border-radius:13px;font-size:14px;font-weight:700}.option:hover:not(:disabled){background:#1b3d68;border-color:#8ba7d1}.option .letter{display:grid;place-items:center;width:29px;height:29px;flex:none;border-radius:8px;background:#29476e;color:#ffe27a;font-size:13px}.option.correct{background:#0b3b36;border-color:var(--green);color:#c8ffeb}.option.correct .letter{background:#1d8069;color:white}.option.wrong{background:#3e202c;border-color:var(--red);color:#ffd9df}.option:disabled{cursor:default;opacity:1}
button{font:inherit;border:0;border-radius:11px;padding:12px 15px;font-weight:800;cursor:pointer;transition:transform .15s,filter .15s,background .15s}button:hover:not(:disabled){filter:brightness(1.08);transform:translateY(-1px)}button:active{transform:translateY(0)}button:focus-visible{outline:3px solid #fff;outline-offset:3px}button:disabled{cursor:not-allowed;opacity:.55}.secondary{background:#23466f;color:#f3f6ff;border:1px solid #4a6991}.ghost{background:transparent;border:1px solid #4a6991;color:#c8d5ea}.actions{display:flex;flex-wrap:wrap;gap:9px;margin-top:13px}.actions button{flex:1}.feedback{min-height:58px;margin-top:14px;border-radius:13px;padding:12px 15px;background:#091e3b;border:1px solid #29476f;color:#dce8fa;line-height:1.45;font-size:13px}.feedback.good{border-color:#298b71;color:#baf7df;background:#0b302e}.feedback.bad{border-color:#9d505b;color:#ffd0d0;background:#321d32}.rules{display:flex;justify-content:space-between;gap:9px;flex-wrap:wrap;margin-top:13px;color:var(--muted);font-size:11px}.bottom{display:flex;justify-content:space-between;align-items:center;gap:12px;padding:15px 28px;border-top:1px solid #29466d;color:#aab8d2;font-size:11px}.bottom a{color:#ffe27a;text-decoration:none}.bottom a:hover{text-decoration:underline}
.overlay{display:none;padding:28px;text-align:center;border-top:1px solid #29466d}.overlay.show{display:block}.trophy{font-size:49px;margin:4px 0 10px}.overlay h2{margin:0 0 8px;color:var(--yellow);font-size:27px}.overlay p{color:#d5e0f2;line-height:1.55}.finalscore{font-size:42px;color:var(--yellow);font-weight:900;margin:10px 0}.rank{display:inline-block;padding:8px 14px;border-radius:999px;background:#253f66;color:#ffe58a;font-weight:800;margin-bottom:14px}.leaderboard{padding:21px 28px 23px;border-top:1px solid #29466d;background:#091e3b;text-align:left}.leader-head{display:flex;justify-content:space-between;align-items:center;gap:10px;margin-bottom:12px}.leader-head h3{margin:0;color:var(--yellow);font-size:19px}.local-note{color:var(--muted);font-size:10px}.leader-table{width:100%;border-collapse:collapse;font-size:13px}.leader-table th,.leader-table td{padding:10px 9px;border-bottom:1px solid #29466d;text-align:left}.leader-table th{color:#aab8d2;font-size:10px;text-transform:uppercase;letter-spacing:.06em}.leader-table td:last-child,.leader-table th:last-child{text-align:right;font-variant-numeric:tabular-nums}.leader-table tr:first-child td:first-child{color:var(--yellow);font-weight:900}.empty-rank{text-align:center!important;color:var(--muted);padding:18px!important}.rank-actions{display:flex;justify-content:flex-end;margin-top:10px}.clear-rank{font-size:10px;padding:8px 10px}.sources{margin:15px 5px 0;color:#aab8d2;font-size:11px;line-height:1.75}.sources a{color:#ffe27a}.hidden{display:none!important}
@media(max-width:660px){body{padding:17px 10px 27px}.topline{align-items:flex-start}.tag{display:none}.stats{grid-template-columns:repeat(3,1fr);padding:0 16px 16px;gap:7px}.stat{padding:9px}.stat strong{font-size:19px}.stat small{font-size:9px}.hero{padding:18px 16px 13px}.play{padding:18px 16px 21px}.progress-area{padding:0 16px 16px}.options{grid-template-columns:1fr;gap:8px}.option{min-height:52px}.bottom{padding:13px 16px;align-items:flex-start;flex-direction:column}.leaderboard{padding:19px 15px}.overlay{padding:22px 16px}.welcome{padding:28px 17px}.welcome-features{gap:6px}.feature{padding:11px 5px}.feature b{font-size:13px}.feature small{font-size:10px}.rules{justify-content:flex-start}.hero-tools{width:100%;justify-content:space-between}}
@media(prefers-reduced-motion:reduce){*{transition:none!important;animation:none!important;scroll-behavior:auto!important}}
</style>
</head>
<body>
<div class="wrap">
  <header class="topline">
    <div class="brand"><div class="crest" aria-label="1907 temalı arma">FB</div><div><h1>Bilmece Arenası</h1><p class="subtitle">Fenerbahçe hakkında ne kadar bilgilisin?</p></div></div>
    <div class="tag">SARI-LACİVERT • 1907</div>
  </header>

  <main class="card">
    <section class="welcome" id="welcomeScreen">
      <div class="welcome-mark" aria-hidden="true">★</div>
      <div class="eyebrow">FENERBAHÇE • TARAFTARIN HAFIZASI</div>
      <h2>KANARYA, <span>HOŞ GELDİN!</span></h2>
      <p>Bilmece arenasına girmeye hazır mısın? Adını belirle, 15 soruyu cevapla ve kendi tarayıcındaki taraftar sıralamasında zirveye çık.</p>
      <div class="name-box">
        <label for="playerName">OYUNCU ADINIZ</label>
        <input id="playerName" maxlength="18" minlength="2" placeholder="Adını yaz..." autocomplete="nickname">
        <div class="name-help">2–18 karakter • Gerçek adını yazmak zorunda değilsin; bir rumuz seç.</div>
        <button class="primary start-btn" id="startBtn" type="button">BİLMECEYE BAŞLA →</button>
      </div>
      <div class="welcome-features">
        <div class="feature"><b>15 SORU</b><small>4 şıklı bilgi turu</small></div>
        <div class="feature"><b>15:00</b><small>Geri sayım süresi</small></div>
        <div class="feature"><b>🏆 TOP 10</b><small>Taraftar sıralaması</small></div>
      </div>
    </section>

    <div class="game-content" id="gameContent">
      <section class="hero">
        <div class="hero-top">
          <div><h2>Fenerbahçe bilgin konuşsun!</h2><p>Doğru şıkkı seç, serini koru ve puanını yükselt.</p></div>
          <div class="hero-tools"><span class="player-badge" id="playerBadge">★ Oyuncu</span><button class="ghost" id="soundBtn" type="button" aria-pressed="true">🔊 SES AÇIK</button></div>
        </div>
      </section>
      <section class="stats" aria-label="Oyun istatistikleri">
        <div class="stat"><small>PUAN</small><strong id="score">0</strong></div>
        <div class="stat"><small>TAMAMLANAN</small><strong id="doneCount">0/15</strong></div>
        <div class="stat timer" id="timerStat"><small>SÜRE • 15 DK</small><strong id="timer">15:00</strong></div>
        <div class="stat"><small>DOĞRU SERİSİ</small><strong id="streak">0 🔥</strong></div>
        <div class="stat"><small>REKORUN</small><strong id="best">0</strong></div>
      </section>
      <section class="progress-area"><div class="progress-label"><span>Bulmaca ilerlemesi</span><span id="progressText">0 / 15 tamamlandı</span></div><div class="track"><div class="fill" id="progress"></div></div></section>
      <section class="play" id="gameArea">
        <div class="levelrow"><span class="level" id="level">⭐ KOLAY</span><span class="question-no" id="questionNo">SORU 1 / 15</span></div>
        <div class="riddle" id="riddle" aria-live="polite">Fenerbahçe Spor Kulübü hangi yılda kuruldu?</div>
        <div class="options" id="options" aria-label="Cevap seçenekleri"></div>
        <div class="actions"><button class="secondary" id="hintBtn" type="button">💡 İPUCU AL (−2 PUAN)</button><button class="secondary" id="skipBtn" type="button">SORUYU GEÇ</button></div>
        <div class="feedback" id="feedback" role="status" aria-live="polite">Doğru cevabı seçerek 10 puan kazan. İpucu kullanmak 2 puan götürür.</div>
        <div class="rules"><span>✓ Doğru cevap: +10 puan</span><span>💡 İpucu: −2 puan</span><span>🔥 Her 3 doğru seri: +3 bonus</span></div>
      </section>
      <section class="overlay" id="endScreen">
        <div class="trophy">🏆</div><h2>ARENA TAMAMLANDI!</h2><p id="endMessage">Harika mücadele!</p><div class="finalscore" id="finalScore">0 PUAN</div><div class="rank" id="rank">Taraftar</div><p id="endStats"></p><button class="primary" id="restartBtn" type="button">↻ YENİDEN OYNA</button> <button class="ghost" id="homeBtn" type="button">BAŞLANGICA DÖN</button>
      </section>
      <section class="leaderboard" id="leaderboard">
        <div class="leader-head"><h3>🏆 OYUN SONU PUAN TABLOSU</h3><span class="local-note">Bu tarayıcıdaki kayıtlar</span></div>
        <table class="leader-table"><thead><tr><th>SIRA</th><th>OYUNCU</th><th>PUAN</th></tr></thead><tbody id="leaderRows"><tr><td colspan="3" class="empty-rank">Henüz skor kaydedilmedi. İlk sıraya sen yerleş!</td></tr></tbody></table>
        <div class="rank-actions"><button class="ghost clear-rank" id="clearRanksBtn" type="button">SIRALAMAYI TEMİZLE</button></div>
      </section>
      <div class="bottom"><span>Bu oyun taraftar projesidir; Fenerbahçe Spor Kulübü ile resmî bağlantısı yoktur.</span><a href="#sources">Bilgi kaynakları ↓</a></div>
    </div>
  </main>

  <section class="sources" id="sources">
    <strong style="color:#e7eefb">Tarihî bilgi kaynakları:</strong><br>
    <a href="https://www.fenercell.com/kurumsal" target="_blank" rel="noopener">Fenercell – Kulübümüzün tarihçesi ve amblem bilgileri</a> ·
    <a href="https://media.fenerbahce.org/getmedia/f2279e20-35af-4e5a-a333-49d52711511d/FenerbahceTuzuk.pdf.aspx" target="_blank" rel="noopener">Fenerbahçe Spor Kulübü tüzüğü</a>
  </section>
</div>
<script>
const riddles = [
 {level:'KOLAY',stars:'⭐',q:'Fenerbahçe Spor Kulübü hangi yılda kuruldu?',options:['1903','1907','1910','1923'],answer:'1907',hint:'Kulübün armasında da gördüğün dört rakam.',fact:'Fenerbahçe Spor Kulübü 1907 yılında kuruldu.'},
 {level:'KOLAY',stars:'⭐',q:'Fenerbahçe’nin geleneksel renkleri hangileridir?',options:['Kırmızı – beyaz','Sarı – siyah','Sarı – lacivert','Mavi – beyaz'],answer:'Sarı – lacivert',hint:'Bir renk sarı, diğeri koyu mavidir.',fact:'Fenerbahçe Spor Kulübü tüzüğünde kulübün renkleri sarı-lacivert olarak belirtilir.'},
 {level:'KOLAY',stars:'⭐',q:'Fenerbahçe’nin kuruluş adresi hangi semttedir?',options:['Moda','Beyoğlu','Üsküdar','Şişli'],answer:'Moda',hint:'Kadıköy çevresinde, sahiliyle de bilinen semt.',fact:'Kulüp tarihçesine göre Fenerbahçe, Moda’da Beşbıyık Sokağı 3 numaralı evin alt katında kuruldu.'},
 {level:'KOLAY',stars:'⭐',q:'Fenerbahçe’nin ilk başkanı kimdir?',options:['Ayetullah Bey','Necip Okaner','Nurizade Ziya Songülen','Hikmet Topuz'],answer:'Nurizade Ziya Songülen',hint:'Adı Ziya, soyadı Songülen.',fact:'Fenercell’in kulüp tarihçesinde ilk başkan Nurizade Ziya Songülen olarak belirtilir.'},
 {level:'ORTA',stars:'⭐⭐',q:'Fenerbahçe’nin ilk yıllardaki forma renkleri hangileriydi?',options:['Sarı – beyaz','Sarı – lacivert','Kırmızı – beyaz','Yeşil – beyaz'],answer:'Sarı – beyaz',hint:'Bugünkü renklerden sarı vardı; diğer renk beyazdı.',fact:'Kulüp tarihçesine göre ilk renkler sarı-beyazdı.'},
 {level:'ORTA',stars:'⭐⭐',q:'Kulübün adı ve renkleri hangi yıl bugünkü hâline dönüştü?',options:['1907','1908','1909','1912'],answer:'1909',hint:'Kuruluşundan iki yıl sonra.',fact:'Kulüp tarihçesine göre 1909’da adı Fenerbahçe Spor Kulübü oldu, renkleri sarı-laciverte çevrildi.'},
 {level:'ORTA',stars:'⭐⭐',q:'İlk yönetim kurulunda genel sekreter kimdi?',options:['Ayetullah Bey','Necip Okaner','Ziya Songülen','Hikmet Topuz'],answer:'Ayetullah Bey',hint:'Kuruluş hikâyesinde Ziya ve Necip ile birlikte anılan isim.',fact:'İlk yönetim kurulunda Ayetullah Bey genel sekreterlik görevini üstlendi.'},
 {level:'ORTA',stars:'⭐⭐',q:'İlk yönetim kurulunda genel kaptan ve veznedar kimdi?',options:['Ziya Songülen','Ayetullah Bey','Necip Okaner','Asaf Beşpınar'],answer:'Necip Okaner',hint:'Soyadı Okaner.',fact:'İlk yönetim kurulunda Necip Bey genel kaptan ve veznedardı.'},
 {level:'ORTA',stars:'⭐⭐',q:'Bugünkü Fenerbahçe armasını 1910’da çizen futbolcu kimdi?',options:['Ayetullah Bey','Hikmet (Topuz)','Necip Okaner','Enver Yetiker'],answer:'Hikmet (Topuz)',hint:'Adı Hikmet, Topuz adıyla da anılır.',fact:'Kulüp tarihçesi, bugünkü armayı 1910’da futbolcu Hikmet (Topuz)’un çizdiğini aktarır.'},
 {level:'ORTA',stars:'⭐⭐',q:'Fenerbahçe’nin bugünkü arması ilk kez hangi yıl yaptırıldı?',options:['1907','1909','1910','1929'],answer:'1910',hint:'Armayı çizen Hikmet (Topuz) ile aynı yıl.',fact:'Fenercell tarihçesine göre bugünkü rozet ilk kez 1910’da yaptırıldı.'},
 {level:'ZOR',stars:'⭐⭐⭐',q:'Fenerbahçe’nin ilk ambleminde hangi simge bulunuyordu?',options:['Deniz feneri','Meşe ağacı','Futbol topu','Yıldız'],answer:'Deniz feneri',hint:'Kulübün adına da ilham veren, ışık saçan bir yapı.',fact:'Kulüp tarihçesine göre ilk amblem, Fenerbahçe burnundaki ışık saçan beyaz feneri simgeliyordu.'},
 {level:'ZOR',stars:'⭐⭐⭐',q:'Fenerbahçe tüzüğüne göre armadaki yeşil dal hangi ağaca aittir?',options:['Zeytin','Meşe','Defne','Çınar'],answer:'Meşe',hint:'Palamut veren, güçlü ve uzun ömürlü bir ağaç.',fact:'Kulübün tüzüğü armadaki yeşil dalı meşe dalı olarak tanımlar.'},
 {level:'ZOR',stars:'⭐⭐⭐',q:'Kulüp tarihçesinde ilk kurucular arasında sayılan isimlerden biri hangisidir?',options:['Asaf Beşpınar','Şükrü Saracoğlu','Hikmet Topuz','Elkatipzade Mustafa'],answer:'Asaf Beşpınar',hint:'“Hindli” adıyla da anıldığı belirtilir.',fact:'Kulüp tarihçesinde kurucular arasında Asaf Beşpınar da sayılır.'},
 {level:'ZOR',stars:'⭐⭐⭐',q:'Fenerbahçe’nin resmî GSM markasının adı nedir?',options:['FenerNet','FenerCell','Kanarya Mobil','SarıLacivert Tel'],answer:'FenerCell',hint:'Kulübün adı ile cep telefonu iletişimini çağrıştıran kelime birleşir.',fact:'Fenercell’in kurumsal sayfası markayı Fenerbahçe’nin resmî GSM hattı olarak tanımlar.'},
 {level:'ZOR',stars:'⭐⭐⭐',q:'Fenercell hangi tarihte faaliyete başladı?',options:['23 Şubat 2009','19 Mayıs 2007','3 Temmuz 2011','29 Ekim 2009'],answer:'23 Şubat 2009',hint:'2009 yılının ikinci ayında, ayın 23’ünde.',fact:'Fenercell’in kurumsal sayfasına göre hizmet 23 Şubat 2009’da başladı.'}
];

let order=[],index=0,score=0,correct=0,streak=0,usedHint=false,locked=false,soundOn=true,best=0,savedThisRun=false,playerName='Kanarya',timeLeft=900,timerId=null,completed=0;
const $=id=>document.getElementById(id);
const RANK_KEY='fbBilmeceLeaderboard_v3',BEST_KEY='fbBilmeceBest_v3';
try{best=Number(localStorage.getItem(BEST_KEY)||0)||0}catch(e){}
function shuffle(a){const x=[...a];for(let i=x.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[x[i],x[j]]=[x[j],x[i]]}return x}
function tone(type='good'){
 if(!soundOn)return;
 try{const C=window.AudioContext||window.webkitAudioContext;if(!C)return;const ctx=new C(),notes=type==='good'?[660,880]:type==='bad'?[220,180]:[523,659,784];const t=ctx.currentTime;notes.forEach((f,i)=>{const o=ctx.createOscillator(),g=ctx.createGain();o.type='sine';o.frequency.value=f;g.gain.setValueAtTime(.0001,t+i*.1);g.gain.exponentialRampToValueAtTime(.065,t+i*.1+.02);g.gain.exponentialRampToValueAtTime(.0001,t+i*.1+.16);o.connect(g);g.connect(ctx.destination);o.start(t+i*.1);o.stop(t+i*.1+.18)});setTimeout(()=>ctx.close(),900)}catch(e){}
}
function setFeedback(text,kind=''){const el=$('feedback');el.className='feedback'+(kind?' '+kind:'');el.textContent=text}
function getLeaderboard(){try{const value=JSON.parse(localStorage.getItem(RANK_KEY)||'[]');return Array.isArray(value)?value:[]}catch(e){return []}}
function renderLeaderboard(){const rows=$('leaderRows'),list=getLeaderboard().sort((a,b)=>b.score-a.score||a.time-b.time).slice(0,10);rows.innerHTML='';if(!list.length){const tr=document.createElement('tr'),td=document.createElement('td');td.colSpan=3;td.className='empty-rank';td.textContent='Henüz skor kaydedilmedi. İlk sıraya sen yerleş!';tr.appendChild(td);rows.appendChild(tr);return}list.forEach((entry,i)=>{const tr=document.createElement('tr'),rank=document.createElement('td'),name=document.createElement('td'),points=document.createElement('td');rank.textContent=['🥇','🥈','🥉'][i]||String(i+1);name.textContent=entry.name;points.textContent=entry.score+' puan';tr.append(rank,name,points);rows.appendChild(tr)})}
function saveScore(){if(savedThisRun)return;const list=getLeaderboard();list.push({name:playerName,score,time:Date.now()});list.sort((a,b)=>b.score-a.score||a.time-b.time);try{localStorage.setItem(RANK_KEY,JSON.stringify(list.slice(0,10)));savedThisRun=true;renderLeaderboard()}catch(e){$('endStats').textContent+=' Tarayıcı sıralamasına kaydedilemedi.'}}
function updateStats(){ $('score').textContent=score;$('doneCount').textContent=completed+'/15';$('streak').textContent=streak+' 🔥';$('best').textContent=best;$('progressText').textContent=completed+' / 15 tamamlandı';$('progress').style.width=(completed/15*100)+'%';}
function showTime(){const m=Math.floor(timeLeft/60),s=timeLeft%60;$('timer').textContent=String(m).padStart(2,'0')+':'+String(s).padStart(2,'0');$('timerStat').classList.toggle('warning',timeLeft<=60)}
function stopTimer(){if(timerId){clearInterval(timerId);timerId=null}}
function startTimer(){stopTimer();timeLeft=900;showTime();timerId=setInterval(()=>{timeLeft--;showTime();if(timeLeft<=0){stopTimer();finish(true)}},1000)}
function renderOptions(){const host=$('options');host.innerHTML='';const r=order[index];shuffle(r.options).forEach((choice,i)=>{const b=document.createElement('button');b.type='button';b.className='option';b.dataset.choice=choice;const letter=document.createElement('span');letter.className='letter';letter.textContent=String.fromCharCode(65+i);const text=document.createElement('span');text.textContent=choice;b.append(letter,text);b.addEventListener('click',()=>choose(b,choice));host.appendChild(b)})}
function loadQuestion(){locked=false;usedHint=false;const r=order[index];$('level').textContent=r.stars+' '+r.level;$('questionNo').textContent='SORU '+(index+1)+' / 15';$('riddle').textContent=r.q;$('hintBtn').disabled=false;$('skipBtn').disabled=false;$('hintBtn').textContent='💡 İPUCU AL (−2 PUAN)';renderOptions();setFeedback('Doğru cevap 10 puan kazandırır. Yanlış cevapta bu sorudan puan alamazsın.');updateStats()}
function nextButton(){const old=$('nextQuestionBtn');if(old)old.remove();const b=document.createElement('button');b.id='nextQuestionBtn';b.type='button';b.className='primary';b.style.marginTop='13px';b.style.width='100%';b.textContent=index===order.length-1?'SONUCU GÖR →':'SONRAKİ SORU →';b.addEventListener('click',()=>{b.remove();advance()});$('options').after(b)}
function completeQuestion(){completed++;$('hintBtn').disabled=true;$('skipBtn').disabled=true;updateStats();nextButton()}
function choose(button,choice){if(locked||button.disabled)return;const r=order[index];if(choice===r.answer){locked=true;correct++;streak++;let earned=10;if(streak>0&&streak%3===0)earned+=3;score+=earned;button.classList.add('correct');$('options').querySelectorAll('button').forEach(b=>{b.disabled=true;if(b.dataset.choice===r.answer)b.classList.add('correct')});let extra=streak%3===0?' Üç doğru üst üste! +3 seri bonusu kazandın.':'';setFeedback('✓ Doğru! +'+earned+' puan. '+r.fact+extra,'good');tone('good');completeQuestion()}else{locked=true;streak=0;$('options').querySelectorAll('button').forEach(b=>{b.disabled=true;if(b===button)b.classList.add('wrong');if(b.dataset.choice===r.answer)b.classList.add('correct')});setFeedback('✗ Yanlış cevap! Bu sorudan 0 puan aldın. Doğru cevap: '+r.answer+'. '+r.fact,'bad');tone('bad');completeQuestion()}}
function hint(){if(locked||usedHint)return;usedHint=true;score=Math.max(0,score-2);$('hintBtn').disabled=true;$('hintBtn').textContent='İPUCU KULLANILDI';setFeedback('💡 İpucu: '+order[index].hint);updateStats()}
function skip(){if(locked)return;locked=true;streak=0;const r=order[index];$('options').querySelectorAll('button').forEach(b=>{b.disabled=true;if(b.dataset.choice===r.answer)b.classList.add('correct')});setFeedback('Soruyu geçtin. Doğru cevap: '+r.answer+'. '+r.fact,'bad');tone('bad');completeQuestion()}
function advance(){index++;if(index>=order.length){finish(false);return}loadQuestion()}
function finish(timeExpired=false){stopTimer();$('gameArea').classList.add('hidden');$('endScreen').classList.add('show');$('progress').style.width=(completed/15*100)+'%';const rank=score>=135?'EFSANE KANARYA 🏆':score>=105?'TRİBÜN LİDERİ 💛💙':score>=70?'SADIK TARAFTAR':'YENİ TARAFTAR';const msg=timeExpired?'Süre doldu! Zamanla yarıştın, bir tur daha deneyebilirsin.':score>=135?'Muhteşem! Fenerbahçe tarihine çok hâkimsin.':score>=105?'Çok iyi oynadın. Birkaç ayrıntı dışında harika!':score>=70?'Güzel bir turdu. Zirveye biraz daha yaklaştın.':'Bu sadece başlangıç. Her turda daha fazlasını öğreneceksin.';$('endMessage').textContent=msg;$('finalScore').textContent=score+' PUAN';$('rank').textContent=rank;$('endStats').textContent=completed+' soruyu tamamladın, '+correct+' doğru cevap verdin. Süre: '+$('timer').textContent+'.';if(score>best){best=score;try{localStorage.setItem(BEST_KEY,String(best))}catch(e){}$('best').textContent=best}saveScore();tone('finish');}
function startGame(){const value=$('playerName').value.trim().replace(/\s+/g,' ');if(value.length<2){$('playerName').focus();$('playerName').setCustomValidity('Lütfen en az 2 karakterli bir rumuz yaz.');$('playerName').reportValidity();$('playerName').setCustomValidity('');return}playerName=value.slice(0,18);$('playerBadge').textContent='★ '+playerName;$('welcomeScreen').classList.add('hidden');$('gameContent').classList.add('show');start();}
function start(){order=shuffle(riddles);index=0;score=0;correct=0;streak=0;completed=0;savedThisRun=false;$('gameArea').classList.remove('hidden');$('endScreen').classList.remove('show');const next=$('nextQuestionBtn');if(next)next.remove();loadQuestion();startTimer()}
$('startBtn').addEventListener('click',startGame);$('playerName').addEventListener('keydown',e=>{if(e.key==='Enter')startGame()});$('hintBtn').addEventListener('click',hint);$('skipBtn').addEventListener('click',skip);$('restartBtn').addEventListener('click',start);$('homeBtn').addEventListener('click',()=>{stopTimer();$('gameContent').classList.remove('show');$('welcomeScreen').classList.remove('hidden');$('endScreen').classList.remove('show');$('gameArea').classList.remove('hidden')});$('soundBtn').addEventListener('click',()=>{soundOn=!soundOn;$('soundBtn').textContent=soundOn?'🔊 SES AÇIK':'🔇 SES KAPALI';$('soundBtn').setAttribute('aria-pressed',String(soundOn));if(soundOn)tone('finish')});$('clearRanksBtn').addEventListener('click',()=>{if(confirm('Bu tarayıcıda kayıtlı sıralama silinsin mi?')){try{localStorage.removeItem(RANK_KEY)}catch(e){}renderLeaderboard()}});
$('best').textContent=best;renderLeaderboard();
</script>
</body>
</html>
