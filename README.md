<html lang="he" dir="rtl"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>אנגלית בפאן</title>
<link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;600;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#eef4ff;--card:#fff;--ink:#17214a;--mut:#5a6486;--line:#d5def5;--y:#ffb800;--c:#ff6b5b;--g:#16a174;--b:#3d5afe;--okbg:#d9f6ea;--nobg:#ffe1dd;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0f1530;--card:#1a2250;--ink:#f1f4ff;--mut:#aab4dd;--line:#2f3a73;--okbg:#14473a;--nobg:#5a2a2f;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#0f1530;--card:#1a2250;--ink:#f1f4ff;--mut:#aab4dd;--line:#2f3a73;--okbg:#14473a;--nobg:#5a2a2f;color-scheme:dark}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:Rubik,Arial,sans-serif;font-size:18px}
#app{max-width:520px;margin:0 auto;padding:16px}
h1{font-size:2.4rem;font-weight:800;margin:24px 0 4px;text-align:center}
.sub{text-align:center;color:var(--mut);margin:0 0 20px}
.ages{display:grid;grid-template-columns:1fr 1fr;gap:14px}
.age{background:var(--card);border:3px solid var(--k);border-radius:22px;padding:16px 8px;color:var(--ink);font:inherit;cursor:pointer;display:flex;flex-direction:column;align-items:center;gap:4px}
.age b{font-size:3.2rem;line-height:1;color:var(--k);font-weight:800}
.age span{font-size:.9rem;color:var(--mut)}
.top{display:flex;justify-content:space-between;align-items:center;color:var(--mut);font-size:.95rem}
.x{background:none;border:0;font-size:1.3rem;color:var(--mut);cursor:pointer}
.pb{height:10px;background:var(--line);border-radius:9px;overflow:hidden;margin:6px 0 16px}
.pb i{display:block;height:100%;background:var(--b);border-radius:9px;transition:width .3s}
.card{background:var(--card);border-radius:24px;padding:20px;text-align:center;border:2px solid var(--line)}
.emo{font-size:4rem;line-height:1.1}
.en{font-size:2.6rem;font-weight:800;color:var(--b);unicode-bidi:isolate}
.he{font-size:1.9rem;font-weight:600;margin:6px 0}
.tip{background:var(--bg);border-radius:14px;padding:10px 12px;margin:12px 0;font-size:1rem}
.ex,.ex2{font-size:1.15rem;unicode-bidi:isolate}
.ex2{font-size:1.5rem;font-weight:600}
.ex u{text-decoration-color:var(--y);text-decoration-thickness:3px}
.exh,.pr{color:var(--mut);font-size:.95rem;margin-top:4px}
.pr{margin:0 0 8px;font-weight:600}
button{font-family:inherit}
.say{background:none;border:2px solid var(--line);color:var(--ink);border-radius:20px;padding:4px 14px;font-size:.95rem;cursor:pointer}
.nav{display:flex;gap:10px;margin-top:16px}
.pri,.sec{flex:1;border-radius:16px;padding:14px;font-size:1.1rem;font-weight:600;cursor:pointer;border:0}
.pri{background:var(--b);color:#fff}
.sec{background:var(--card);color:var(--ink);border:2px solid var(--line)}
.sec:disabled{opacity:.4}
.opts{display:grid;gap:10px;margin-top:14px}
.opt{background:var(--card);color:var(--ink);border:2px solid var(--line);border-radius:16px;padding:14px;font-size:1.25rem;font-weight:600;cursor:pointer;unicode-bidi:isolate}
.opt.ok{background:var(--okbg);border-color:var(--g)}
.opt.no{background:var(--nobg);border-color:var(--c)}
.fb{margin:14px 0 10px;font-size:1.05rem;text-align:center}
.stars{font-size:3rem;margin:8px 0}
:focus-visible{outline:3px solid var(--y);outline-offset:2px}
.hero{text-align:center;padding-top:12px}
.owl{font-size:4.5rem;animation:hop 2.4s ease-in-out infinite}
.logo{font-size:3.4rem;line-height:1.05;margin:4px 0 6px;display:flex;flex-direction:column;align-items:center}
.logo span{background:var(--y);color:#17214a;padding:0 18px;border-radius:18px;transform:rotate(-3deg);font-size:3rem;margin-top:6px}
.menu{display:grid;gap:16px;margin-top:20px;position:relative;z-index:1}
.mode{display:grid;grid-template-columns:auto 1fr;column-gap:14px;align-items:center;text-align:right;background:var(--card);color:var(--ink);border:3px solid var(--k);border-radius:26px;padding:18px;cursor:pointer;box-shadow:0 6px 0 var(--k);transition:transform .1s,box-shadow .1s;font:inherit}
.mode i{grid-row:span 2;font-size:3rem;font-style:normal}
.mode b{font-size:1.5rem}.mode small{color:var(--mut)}
.mode:active{transform:translateY(5px);box-shadow:0 1px 0 var(--k)}
.m1{--k:var(--b)}.m2{--k:var(--c)}
.floaties em{position:fixed;bottom:-40px;font-style:normal;font-size:2rem;opacity:.5;animation:rise 9s linear infinite;pointer-events:none}
textarea{width:100%;margin-top:8px;border:2px solid var(--line);border-radius:14px;padding:12px;font:inherit;background:var(--bg);color:var(--ink);resize:none}
.pop{position:fixed;font-size:1.6rem;pointer-events:none;animation:pop .9s ease-out forwards;z-index:9}
@keyframes hop{50%{transform:translateY(-10px) rotate(-6deg)}}
@keyframes rise{to{transform:translateY(-110vh) rotate(30deg)}}
@keyframes pop{to{transform:translate(var(--dx),var(--dy));opacity:0}}
@media (prefers-reduced-motion:reduce){.owl,.floaties em,.pop{animation:none}.floaties,.pop{display:none}}
:root{--paper:#f1ebff}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--paper:#262052}}
:root[data-theme="dark"]{--paper:#262052}
.age{transform:rotate(var(--r,0deg));box-shadow:0 6px 0 var(--k);transition:transform .15s;gap:2px}
.age:hover{transform:rotate(0) scale(1.04)}
.age i{font-style:normal;font-size:2.2rem}
.age s{text-decoration:none;color:var(--k);letter-spacing:2px;margin-top:4px}
.m3{--k:var(--g)}.m4{--k:#8a5cf6}.m5{--k:var(--y)}
.kc{border:3px solid var(--b);transform:rotate(-1.5deg);box-shadow:0 8px 0 var(--b)}
.nb{background:repeating-linear-gradient(var(--card) 0 31px,var(--line) 31px 32px);border-right:5px solid var(--c);text-align:right}
.sp{border:3px solid var(--g)}
.slots{display:flex;gap:6px;justify-content:center;flex-wrap:wrap;direction:ltr;margin:14px 0}
.slot{width:36px;height:46px;border-bottom:4px solid var(--g);font:800 1.8rem/46px Rubik,sans-serif;font-style:normal;text-align:center;color:var(--b)}
.slots.okk .slot{color:var(--g)}.slots.nok .slot{color:var(--c)}
.tiles{display:flex;gap:8px;justify-content:center;flex-wrap:wrap;direction:ltr;margin:0 0 14px}
.tl{width:48px;height:52px;border-radius:12px;border:2px solid var(--line);background:var(--card);color:var(--ink);font:800 1.5rem Rubik,sans-serif;box-shadow:0 4px 0 var(--line);cursor:pointer}
.tl:disabled{opacity:.25}
.ro{border-width:4px;margin-top:30px;padding:40px 20px}
.paper{background:var(--paper);border-radius:24px;padding:20px;border:2px solid var(--line)}
.stt{margin:0 0 10px;font-family:Georgia,serif;text-align:left}
.story{font-family:Georgia,'Times New Roman',serif;font-size:1.25rem;line-height:1.7;direction:ltr;text-align:left}
mark.w{background:color-mix(in srgb,var(--y) 55%,transparent);color:inherit;border-radius:6px;padding:0 3px;cursor:pointer}
#gl{margin:12px 0;background:var(--card);border:2px dashed var(--line);border-radius:14px;padding:10px;text-align:center;min-height:44px}
.btnrow{display:flex;gap:8px;margin-top:12px}
.chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin:8px 0 14px}
.chip{border:2px solid var(--line);background:var(--card);color:var(--ink);border-radius:20px;padding:8px 14px;font:inherit;font-size:1rem;cursor:pointer}
.chip.on{background:var(--b);color:#fff;border-color:var(--b)}
.vl{display:flex;flex-wrap:wrap;gap:8px}
.vl span{background:var(--card);border:1px solid var(--line);border-radius:12px;padding:4px 10px;font-size:.95rem}
.ld .emo{animation:hop 1s infinite}
@media (prefers-reduced-motion:reduce){.ld .emo{animation:none}}
:root{color-scheme:light dark}
:root[data-theme="light"]{color-scheme:light}
:root[data-theme="dark"]{color-scheme:dark}
body{background:var(--bg);transition:background .4s}
body:has(.logo){--bg:light-dark(#ffd84d,#1d1b4d);--ac:#3d5afe}
body:has(.ages){--bg:light-dark(#bfe3ff,#14305c);--ac:#3d5afe}
body:has(.tip){--bg:light-dark(#c9f3e1,#12392f);--ac:#0f8a63}
body:has(.kc){--bg:light-dark(#cfdcff,#1a2a66);--ac:#3d5afe}
body:has(.card.nb){--bg:light-dark(#ffe9a0,#4a3d12);--ac:#c2410c}
body:has(.sp){--bg:light-dark(#c9f3e1,#12392f);--ac:#0f8a63}
body:has(.ro){--bg:light-dark(#ffd4cf,#4d1f28);--ac:#d9382a}
body:has(textarea){--bg:light-dark(#ffd4cf,#4d1f28);--ac:#d9382a}
body:has(.m4){--bg:light-dark(#e3d6ff,#2c2160);--ac:#7c3aed}
body:has(.chips){--bg:light-dark(#ffd9ec,#4a1f3d);--ac:#c026a3}
body:has(.story){--bg:light-dark(#d9c8ff,#231a55);--ac:#7c3aed}
body:has(.stars){--bg:light-dark(#ffe0a3,#4d3d10);--ac:#b45309}
body:has(.ld){--bg:light-dark(#d9c8ff,#231a55)}
.logo span{background:#e8472f;color:#fff}
.sub,.pr,.exh{color:color-mix(in srgb,var(--ink) 75%,transparent)}
.pri{background:var(--ac,var(--b))}
.pb i{background:var(--ac,var(--b))}
.pb{background:color-mix(in srgb,var(--ink) 15%,transparent)}
.card{background:color-mix(in srgb,var(--ac,var(--b)) 12%,var(--card))}
.card.nb{background:repeating-linear-gradient(color-mix(in srgb,var(--ac,var(--b)) 8%,var(--card)) 0 31px,var(--line) 31px 32px)}
.tip{background:color-mix(in srgb,var(--ac,var(--b)) 16%,var(--card))}
.mode{background:color-mix(in srgb,var(--k) 26%,var(--card))}
.age{background:color-mix(in srgb,var(--k) 28%,var(--card))}
.opt:nth-child(1){--o:var(--b)}.opt:nth-child(2){--o:var(--c)}.opt:nth-child(3){--o:var(--g)}.opt:nth-child(4){--o:var(--y)}
.opt{background:color-mix(in srgb,var(--o,var(--b)) 20%,var(--card));border-color:var(--o,var(--line));box-shadow:0 4px 0 var(--o,var(--line))}
.opts .opt.ok{background:var(--okbg);border-color:var(--g)}
.opts .opt.no{background:var(--nobg);border-color:var(--c)}
.chip,.sec,#gl,.vl span{background:color-mix(in srgb,var(--ac,var(--b)) 10%,var(--card))}
.chip.on{background:var(--ac,var(--b));border-color:var(--ac,var(--b))}
.paper{background:color-mix(in srgb,var(--ac,var(--b)) 10%,var(--paper))}
#app{position:relative;z-index:1}
body::before{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(circle at 15% 18%,#ffffff55 0 5%,transparent 5.5%),radial-gradient(circle at 85% 28%,#ffffff44 0 8%,transparent 8.5%),radial-gradient(circle at 60% 85%,#ffffff44 0 6%,transparent 6.5%);animation:drift 12s ease-in-out infinite alternate}
#app>*:not(.floaties){animation:rin .45s cubic-bezier(.2,.9,.3,1.2) backwards}
#app>*:nth-child(2){animation-delay:.07s}#app>*:nth-child(3){animation-delay:.14s}#app>*:nth-child(4){animation-delay:.21s}
.mode{animation:rin .5s cubic-bezier(.2,.9,.3,1.2) backwards}.mode:nth-child(2){animation-delay:.12s}.mode:nth-child(3){animation-delay:.24s}
.age{animation:agein .55s cubic-bezier(.2,1.4,.4,1) backwards}.age:nth-child(2){animation-delay:.08s}.age:nth-child(3){animation-delay:.16s}.age:nth-child(4){animation-delay:.24s}
.mode:hover{filter:brightness(1.04);translate:0 -3px}
.opt{transition:translate .12s,box-shadow .12s}.opt:hover:not(:disabled){translate:0 -2px}
.opt:active,.tl:active{translate:0 3px;box-shadow:0 1px 0 var(--o,var(--line))}
.opt.ok{animation:pulse .5s}
.opt.no,.slots.nok{animation:shake .4s}
.slots.okk{animation:pulse .5s}
.slot:not(:empty){animation:letter .2s}
.pb i{background-image:linear-gradient(90deg,transparent,#ffffff66,transparent);background-size:200% 100%;animation:shim 1.6s linear infinite}
mark.w{animation:glow 2.6s ease-in-out infinite}
.stars{animation:starpop .9s cubic-bezier(.2,1.6,.4,1) .15s backwards}
.pop.fall{animation:fall 1.8s ease-in both}
.toast{position:fixed;top:calc(env(safe-area-inset-top,0px) + 64px);left:50%;transform:translateX(-50%);background:var(--ac,var(--b));color:#fff;padding:10px 22px;border-radius:30px;font-weight:800;z-index:20;animation:toast 1.5s both}
.mute{position:fixed;left:10px;bottom:calc(env(safe-area-inset-bottom,0px) + 10px);z-index:15;border:2px solid var(--line);background:var(--card);border-radius:50%;width:42px;height:42px;font-size:1.2rem;cursor:pointer}
@keyframes rin{from{opacity:0;transform:translateY(24px) scale(.96)}}
@keyframes agein{from{opacity:0;transform:scale(.5) rotate(var(--r,0deg))}}
@keyframes pulse{40%{transform:scale(1.06)}}
@keyframes shake{20%{transform:translateX(-8px)}40%{transform:translateX(8px)}60%{transform:translateX(-5px)}80%{transform:translateX(5px)}}
@keyframes letter{from{transform:scale(1.6);opacity:.3}}
@keyframes shim{to{background-position:-200% 0}}
@keyframes glow{50%{box-shadow:0 0 0 4px color-mix(in srgb,var(--y) 40%,transparent)}}
@keyframes starpop{from{transform:scale(0) rotate(-40deg);opacity:0}}
@keyframes fall{from{transform:translate(0,0)}to{transform:translate(var(--dx),110vh) rotate(360deg)}}
@keyframes toast{0%{transform:translate(-50%,-20px) scale(.6);opacity:0}15%{transform:translate(-50%,0) scale(1.1);opacity:1}25%{transform:translate(-50%,0) scale(1)}85%{opacity:1}100%{opacity:0}}
@keyframes drift{to{transform:translate(18px,-14px) scale(1.04)}}
@media (prefers-reduced-motion:reduce){*,*::before,*::after{animation:none!important;transition:none!important}.pop,.floaties,.toast{display:none}}
.ages .age:last-child:nth-child(odd){grid-column:span 2}
.gear{left:60px}
.ov{position:fixed;inset:0;z-index:30;background:var(--bg);overflow:auto;padding:env(safe-area-inset-top,0px) 0 env(safe-area-inset-bottom,0px);animation:rin .3s backwards}
.ovi{max-width:520px;margin:0 auto;padding:16px}
.hw{cursor:pointer;border-radius:5px;padding:0 1px}
.hw:hover{background:color-mix(in srgb,var(--y) 40%,transparent)}
.hw.sel{background:var(--y);color:#17214a}
.hw.vk{text-decoration:underline dotted}
.hb{display:flex;gap:10px;align-items:center;justify-content:space-between;margin:10px 0;padding:10px 14px;border-radius:14px;background:color-mix(in srgb,var(--y) 30%,var(--card))}
.hb[hidden]{display:none}
.hb .pri{flex:0 0 auto;padding:8px 14px;font-size:1rem}
.gc{display:inline-block;background:var(--card);border:1px solid var(--line);border-radius:12px;padding:3px 10px;margin:3px}
.say.hon{background:var(--y);color:#17214a;border-color:var(--y)}
.cd{height:6px;background:color-mix(in srgb,var(--ink) 15%,transparent);border-radius:6px;overflow:hidden;margin-top:10px}
.cd i{display:block;height:100%;background:var(--ac,var(--b));animation:cdn linear forwards}
.skip{margin-top:8px;width:100%;padding:8px;border-radius:12px;font-size:.95rem;flex:none}
@keyframes cdn{from{width:100%}to{width:0}}
[data-calm] *,[data-calm] *::before,[data-calm] *::after{animation:none!important;transition:none!important}
[data-calm] .pop,[data-calm] .floaties,[data-calm] .toast{display:none}
.cd i{animation:cdn linear forwards!important}
.m6{--k:#0ea5e9}
body:has(.pz){--bg:light-dark(#c9f0ff,#103044);--ac:#0e7490}
.pz{position:relative;width:min(300px,80vw);aspect-ratio:1;margin:8px auto 14px;border-radius:24px;overflow:hidden;background:var(--card);border:3px solid var(--ac,var(--b));display:grid;place-items:center}
.pic{font-size:min(11rem,48vw);line-height:1}
.cov{position:absolute;inset:0;display:grid;grid-template:repeat(3,1fr)/repeat(3,1fr)}
.cv{background:var(--cc);border:2px solid #ffffff88;display:grid;place-items:center;font:800 1.8rem Rubik,sans-serif;font-style:normal;color:#fff;transition:transform .5s,opacity .5s}
.cv.rv{opacity:0;transform:scale(.3) rotate(40deg);pointer-events:none}
</style></head><body><div id="app"></div>
<script>
const D={
9:[["cat","חתול","🐱","חתול אומר מיאו – ״קט״ כמו חתול קטן","The ___ says meow.","החתול אומר מיאו."],
["dog","כלב","🐶","דוֹג – ״דוגמן״ כלב יפה","The ___ likes to run.","הכלב אוהב לרוץ."],
["apple","תפוח","🍎","אֶפל – הלוגו של חברת אפל הוא תפוח","I eat a red ___.","אני אוכל תפוח אדום."],
["book","ספר","📚","בּוּק – פותחים ספר בבוקר","I read a ___.","אני קורא ספר."],
["house","בית","🏠","האוּס – ״הוא אוסף״ אותך הביתה","I live in a ___.","אני גר בבית."],
["water","מים","💧","וּוֹטֶר – נשמע כמו מים שנשפכים","I drink ___.","אני שותה מים."],
["red","אדום","🔴","רֶד – ״ורד״ אדום","The rose is ___.","הוורד אדום."],
["happy","שמח","😊","הֶפִּי – האפי-אנד, סוף שמח","I am ___ today.","אני שמח היום."]],
10:[["school","בית ספר","🏫","סְקוּל – ״סקרנים״ הולכים לבית ספר","I go to ___ every day.","אני הולך לבית ספר כל יום."],
["friend","חבר","🧑‍🤝‍🧑","פְרֶנְד – ״פרנדס״, הסדרה על חברים","She is my best ___.","היא החברה הכי טובה שלי."],
["teacher","מורה","👩‍🏫","טִיצ׳ר – ״טי״ (תה) ו״צ׳ר״, המורה שותה תה","The ___ writes on the board.","המורה כותבת על הלוח."],
["breakfast","ארוחת בוקר","🥞","בְּרֶקְפַסְט – ״שוברים צום״ בבוקר","I eat ___ at seven.","אני אוכל ארוחת בוקר בשבע."],
["window","חלון","🪟","וִינְדוֹ – ווינדוז, מערכת של חלונות","Please open the ___.","בבקשה פתחו את החלון."],
["rain","גשם","🌧️","רֵיין – ״רן״ רץ בגשם","I like the ___ in winter.","אני אוהב את הגשם בחורף."],
["big","גדול","🐘","בִּיג – ״ביג״ מק, המבורגר גדול","An elephant is very ___.","פיל הוא מאוד גדול."],
["play","לשחק","⚽","פְּלֵיי – ״פלייסטיישן״ לשחק","We ___ football after school.","אנחנו משחקים כדורגל אחרי בית הספר."]],
11:[["library","ספרייה","📖","לַיְבְּרֶרִי – ״ליברלי״ ספרים בחינם","I borrow books from the ___.","אני שואל ספרים מהספרייה."],
["weather","מזג אוויר","⛅","וֶדֶר – ״וֶדֶר״ נשמע כמו ״ווטר״ מהשמיים","The ___ is sunny today.","מזג האוויר שמשי היום."],
["brother","אח","👦","בְּרָדֶר – ״ברו״, אחי","My ___ is older than me.","האח שלי מבוגר ממני."],
["morning","בוקר","🌅","מוֹרְנִינְג – ״מורן״ קמה בבוקר","I wake up early in the ___.","אני מתעורר מוקדם בבוקר."],
["travel","לנסוע","✈️","טְרָבֶל – ״טראבל״, בדרך לטיול","We ___ to Eilat every summer.","אנחנו נוסעים לאילת כל קיץ."],
["healthy","בריא","🥗","הֶלְתִי – ״הל״ בהל-ת׳, בריא","Fruit is ___ food.","פירות הם אוכל בריא."],
["beautiful","יפה","🌸","בְּיוּטִיפוּל – ״ביוטי״ = יופי","What a ___ flower!","איזה פרח יפה!"],
["remember","לזכור","🧠","רִימֶמְבֶּר – ״ריי-מֶמְבֶּר״, מחזירים לזיכרון","Please ___ your homework.","בבקשה זכרו את שיעורי הבית."]],
12:[["adventure","הרפתקה","🧭","אַדְוֶנְצ׳ר – ״אדוונטורה״, הרפתקה","The trip was a big ___.","הטיול היה הרפתקה גדולה."],
["important","חשוב","❗","אִימְפּוֹרְטֶנְט – ״אימפורט״ מביאים דברים חשובים","Sleep is ___ for health.","שינה חשובה לבריאות."],
["language","שפה","🗣️","לֶנְגְוִידְג׳ – ״לשון״ ו״לנגווידג׳״ שפה","English is a useful ___.","אנגלית היא שפה שימושית."],
["popular","פופולרי","⭐","פּוֹפְּיוּלֶר – ״פופ״ אהוב על כולם","This game is very ___.","המשחק הזה מאוד פופולרי."],
["borrow","לשאול","🤝","בּוֹרוֹ – ״בורו״ = לשאול לזמן קצר","Can I ___ your pencil?","אפשר לשאול את העיפרון שלך?"],
["enjoy","ליהנות","🎉","אִינְג׳וֹי – ״אין גוֹי״? אין ״ג׳וי״ בלעדיו, כיף!","I ___ reading comic books.","אני נהנה לקרוא קומיקס."],
["difficult","קשה","🧗","דִיפִיקֶלְט – ״דיפיקולטי״, קושי","The exam was very ___.","המבחן היה מאוד קשה."],
["neighbor","שכן","🏘️","נֵיבֶּר – ״ניבר״ ליד הבית שלי","Our ___ has a friendly dog.","לשכן שלנו יש כלב ידידותי."]]};
const N={9:"מילים ראשונות",10:"בית ספר וחברים",11:"יומיום וטיולים",12:"אתגר באנגלית"};
const K={9:"#ffb800",10:"#ff6b5b",11:"#16a174",12:"#3d5afe"};
const P=[["מה פירוש המילה?","השלימו את המשפט","איך אומרים באנגלית?"],["מה פירוש המילה?","השלימו את המשפט","איך אומרים באנגלית?"],["What does it mean? (מה פירוש?)","Complete the sentence","How do you say it in English?"],["What does this word mean?","Complete the sentence","Choose the English word"]];
const $=document.getElementById('app');
Object.assign(K,{8:'#ff8fab',13:'#8a5cf6',14:'#0ea5e9'});
D[8]=[["sun","שמש","☀️","סאן – ״סאנדיי״, יום שמש","The ___ is hot.","השמש חמה."],
["fish","דג","🐟","פיש – ״פישפש״ דג קטן","A ___ lives in water.","דג חי במים."],
["milk","חלב","🥛","מילק – ״מילקי״, שוקו חלב","I drink ___ every morning.","אני שותה חלב כל בוקר."],
["blue","כחול","🔵","בלו – ים כחול","The sky is ___.","השמיים כחולים."],
["bird","ציפור","🐦","בֶּרד – ציפור שנופלת כמו ברד","A ___ can fly.","ציפור יכולה לעוף."],
["hand","יד","✋","הנד – ״הנדי״, שימושי עם יד","I wash my ___.","אני שוטף את היד."],
["tree","עץ","🌳","טרי – ״טרי״ וירוק, עץ","The ___ is tall.","העץ גבוה."],
["sleep","לישון","😴","סליפ – ״סליפרס״, נעלי בית לשינה","I ___ at night.","אני ישן בלילה."]];
D[13]=[["challenge","אתגר","⛰️","צ׳אלנג׳ – ״צ׳אלנג׳ר״, מי שמתמודד","Climbing the mountain was a big ___.",""],
["environment","סביבה","🌍","אנווירונמנט – ״אנווירו״, איכות הסביבה","We must protect the ___.",""],
["influence","השפעה","🌟","אינפלואנס – ״משפיענים״ ברשת","Friends can ___ your choices.",""],
["decision","החלטה","🤔","דיסיז׳ן – ״דיסק״, בוחרים איזה","It was a hard ___ to make.",""],
["experience","חוויה","🎒","אקספיריאנס – ״אקסטרה״ חוויות","Travel is a great ___.",""],
["opinion","דעה","💬","אופיניון – ״אופי״ ו״דעה״","In my ___, this book is great.",""],
["achieve","להשיג","🏅","אצ׳יב – ״אצ׳״ מגיעים למטרה","She worked hard to ___ her goal.",""],
["responsible","אחראי","🛡️","ריספונסיבל – ״ספונסר״ שאחראי","He is ___ for the class pet.",""]];
D[14]=[["although","למרות ש","🌧️","אולדו – ״אל״ תדאג, למרות הכול","___ it was raining, we played outside.",""],
["knowledge","ידע","🧠","נולג׳ – ״נו, לך״ ללמוד, ידע","Reading gives us ___.",""],
["opportunity","הזדמנות","🚪","אופורטיוניטי – ״פורט״ שנפתח","This is a great ___ to learn.",""],
["curious","סקרן","🔍","קיוריאס – ״קוריוז״, סקרנות","She is ___ about space.",""],
["improve","לשפר","📈","אימפרוב – ״אימפרוביזציה״, משתפרים","I want to ___ my English.",""],
["communicate","לתקשר","📡","קומיוניקייט – ״קומוניקציה״","We ___ by phone and email.",""],
["community","קהילה","🏘️","קומיוניטי – ״קומונה״, קהילה","Our ___ has a big park.",""],
["succeed","להצליח","🏆","סאקסיד – ״סקסס״, הצלחה","If you try, you can ___.",""]];
const AGES=[8,9,10,11,12,13,14];
let ST={age:0,mute:false,calm:false};
try{Object.assign(ST,JSON.parse(localStorage.getItem('enfun')||'{}'))}catch(e){}
const save=()=>{try{localStorage.setItem('enfun',JSON.stringify(ST))}catch(e){}};
const calm=()=>document.documentElement.toggleAttribute('data-calm',!!ST.calm);
const tier=a=>a<=9?0:a==10?1:a==11?2:3;
const HELP=a=>a>=8&&a<=11;
let age,words,i,qs,qi,score,cur,streak=0,RL=8,SP,SD,sq,si,ss,sopts,ta=10,tp='',CE='🎮',AT,AF,PA=0,PK=0,HM=0,HS=new Set(),HC={};
const sh=a=>[...a].sort(()=>Math.random()-.5);
const esc=x=>String(x??'').replace(/[&<>"]/g,m=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[m]));
const clr=(x,q)=>String(x||'').replace(q?/["'<>`\\]/g:/["<>`\\]/g,'');
const $i=id=>document.getElementById(id);
function say(t){try{const u=new SpeechSynthesisUtterance(t);u.lang='en-US';u.rate=.85;speechSynthesis.cancel();speechSynthesis.speak(u)}catch(e){}}
const bar=(n,t,l)=>`<div class="top"><button class="x" onclick="home()" aria-label="יציאה">✕</button><span>${l}</span><span dir="ltr">${n}/${t}</span></div><div class="pb"><i style="width:${n/t*100}%"></i></div>`;
const back=(l,f='home()')=>`<div class="top"><button class="x" onclick="${f}" aria-label="חזרה">→</button><span>${l}</span><span></span></div>`;
const parse=raw=>[...new Set(raw.split(/[\n,;]+/).map(s=>s.replace(/[^A-Za-z -]/g,'').trim().toLowerCase()).filter(Boolean))].slice(0,16);
async function S(){try{return await claude.use('sample')}catch(e){return null}}
const TH={8:['🐣','מתחילים לגמרי','צבעים, חיות ודברים סביבנו'],9:['🌱','מילים ראשונות','חיות, אוכל וצבעים'],10:['🚀','בית ספר וחברים','יומיום ומשפטים'],11:['🧭','יומיום וטיולים','מילים שמגלים בדרך'],12:['🏆','אתגר באנגלית','הוראות באנגלית בלבד'],13:['🌍','עולם המילים','רעיונות, דעות והחלטות'],14:['🎓','רמת מומחים','מילים לקראת תיכון']};
const RI=[{e:'🃏',n:'קלפי משמעות',d:'בוחרים מה פירוש המילה',c:'--b'},{e:'✏️',n:'מחברת המשפטים',d:'משלימים את המילה החסרה',c:'--y'},{e:'🔤',n:'בונים מילה',d:'מסדרים את האותיות לפי הסדר',c:'--g'}];
/* overlays + auto-advance */
function ov(h){cl(1);const d=document.createElement('div');d.id='ov';d.className='ov';d.innerHTML=`<div class="ovi"><div class="top"><button class="x" onclick="cl()" aria-label="סגירה">✕</button><span></span><span></span></div>${h}<div class="nav"><button class="pri" onclick="cl()">סגירה</button></div></div>`;document.body.appendChild(d)}
function cl(q){const d=$i('ov');if(d)d.remove();if(!q&&PK){PK=0;if(PA&&AF)go(AF,3500)}}
function go(f,ms){clearTimeout(AT);AF=f;document.querySelectorAll('.cd,.skip').forEach(x=>x.remove());$i('fb').insertAdjacentHTML('beforeend',`<div class="cd"><i style="animation-duration:${ms}ms"></i></div><button class="sec skip" onclick="skip()">דלגו ⏭</button>`);AT=setTimeout(f,ms)}
function skip(){clearTimeout(AT);if(AF)AF()}
/* settings */
function sets(){ov(`<h2 style="text-align:center">⚙️ הגדרות</h2><p class="pr">גיל קבוע: לא תצטרכו לבחור גיל בכל פעם</p><div class="chips">${[0,...AGES].map(a=>`<button class="chip ${ST.age==a?'on':''}" data-g="S" onclick="setAge(this,${a})">${a||'לבחור בכל פעם'}</button>`).join('')}</div><p class="pr">צלילים</p><div class="chips"><button class="chip on" id="smu" onclick="tgl('mute')">${ST.mute?'🔇 מושתק':'🔊 פועלים'}</button></div><p class="pr">תנועה ואפקטים</p><div class="chips"><button class="chip on" id="sca" onclick="tgl('calm')">${ST.calm?'😌 מצב רגוע (בלי אנימציות)':'✨ אפקטים מלאים'}</button></div>`)}
function setAge(b,a){ST.age=a;save();document.querySelectorAll('[data-g="S"]').forEach(x=>x.classList.remove('on'));b.classList.add('on')}
function tgl(k){ST[k]=!ST[k];save();calm();$i('smu').textContent=ST.mute?'🔇 מושתק':'🔊 פועלים';$i('sca').textContent=ST.calm?'😌 מצב רגוע (בלי אנימציות)':'✨ אפקטים מלאים';mb.textContent=ST.mute?'🔇':'🔊'}
/* menus */
function home(){clearTimeout(AT);cl(1);$.innerHTML=`<div class="hero"><div class="owl">🦉</div><h1 class="logo">אנגלית<span>בפאן!</span></h1><p class="sub">לומדים, משחקים, מנצחים</p></div><div class="menu">${[['m1','play()','🎮','לתרגל אנגלית','מילים וחידונים לפי גיל'],['m2','mine()','✍️','המילים שלי','כותבים עד 16 מילים ומתרגלים אותן'],['m3','tales()','📖','מגדל הסיפורים','קוראים סיפורים ועונים על שאלות'],['m6','wg()','🖼️','חושפים את התמונה','מרכיבים מילים מאותיות ומגלים מה מתחבא']].map(m=>`<button class="mode ${m[0]}" onclick="${m[1]}"><i>${m[2]}</i><b>${m[3]}</b><small>${m[4]}</small></button>`).join('')}</div><p class="sub" style="margin-top:18px">${ST.age?`🎂 גיל ${ST.age} · משנים בהגדרות ⚙️`:'💡 אפשר לקבוע גיל קבוע בהגדרות ⚙️'}</p><div class="floaties" aria-hidden="true">${['🍎','⭐','🎈','📚','🚀','🐶','🎵'].map((e,k)=>`<em style="left:${6+k*14}%;animation-delay:${k*-1.3}s">${e}</em>`).join('')}</div>`}
function burst(b){const r=b.getBoundingClientRect();for(let k=0;k<12;k++){const e=document.createElement('span');e.className='pop';e.textContent=['🎉','⭐','✨','🎈'][k%4];e.style.left=r.left+r.width/2+'px';e.style.top=r.top+'px';e.style.setProperty('--dx',(Math.random()*240-120)+'px');e.style.setProperty('--dy',(-40-Math.random()*120)+'px');document.body.appendChild(e);setTimeout(()=>e.remove(),900)}}
function play(){ST.age?start(ST.age):ages()}
function ages(){clearTimeout(AT);age=0;$.innerHTML=`${back('לתרגל אנגלית')}<h1>מי משחק היום?</h1><p class="sub">כל גיל מקבל עולם מילים משלו</p><div class="ages">${AGES.map((a,k)=>`<button class="age" style="--k:${K[a]};--r:${k%2?2:-2}deg" onclick="start(${a})"><i>${TH[a][0]}</i><b>${a}</b><span>${TH[a][1]}</span><span>${TH[a][2]}</span><s>${'★'.repeat(a-7)+'☆'.repeat(14-a)}</s></button>`).join('')}</div>`}
function start(a){age=a;CE=TH[a][0];words=D[a];i=0;learn()}
function learn(){const w=words[i],last=i==words.length-1;$.innerHTML=`${bar(i+1,words.length,CE+' לומדים מילים חדשות')}<div class="card" style="border-color:${K[age]||K[10]}"><div class="emo">${w[2]}</div><div class="en" dir="ltr">${w[0]}</div><button class="say" onclick="say('${w[0]}')">🔊 שמעו</button><div class="he">${w[1]}</div><div class="tip">💡 ${w[3]}</div><div class="ex" dir="ltr">${w[4].replace('___','<u>'+w[0]+'</u>')}</div>${age<12?`<div class="exh">${w[5]}</div>`:''}</div><div class="nav"><button class="sec" onclick="i--;learn()" ${i?'':'disabled'}>הקודם</button><button class="pri" onclick="${last?'quiz()':'i++;learn()'}">${last?'מתחילים חידון!':'הבא'}</button></div>`;say(w[0])}
/* quiz */
function quiz(){const n=Math.min(words.length,8);RL=n;qs=[];[0,1,2].forEach(r=>sh(words).slice(0,n).forEach(w=>qs.push({r,w})));qi=0;score=0;streak=0;intro()}
function intro(){const r=qs[qi].r,x=RI[r];$.innerHTML=`<div class="card ro" style="border-color:var(${x.c})"><div class="emo">${x.e}</div><h1 style="margin:6px 0">סיבוב ${r+1}: ${x.n}</h1><p class="sub">${x.d}</p></div><div class="nav"><button class="pri" onclick="ask()">קדימה!</button></div>`}
function nxt(){qi++;if(qi>=qs.length)return end();qi%RL==0?intro():ask()}
function ask(){const{r,w}=qs[qi],t=tier(age),hd=bar(qi+1,qs.length,RI[r].e+' סיבוב '+(r+1)+(streak>1?' 🔥 '+streak:''));
if(r==2){const L=w[0].replace(/[^a-z]/gi,'');SP={L,g:[],u:[],w,tl:sh(L.split('')),done:0};$.innerHTML=`${hd}<div class="card sp"><div class="pr">${t<3?'איך מאייתים באנגלית?':'Spell it in English'}</div>${t<3?`<div class="emo">${w[2]}</div>`:''}<div class="he">${w[1]}</div><div class="slots" id="sl"></div><div class="tiles" id="tl"></div><button class="say" onclick="un()">⌫ מחיקה</button></div><div id="fb"></div>`;return rsp()}
let q,pool;
if(r==0){q=`<div class="en" dir="ltr">${w[0]}</div>`;cur=w[1];pool=words.map(x=>x[1])}
else{q=`<div class="ex2" dir="ltr">${w[4].replace('___','<u>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</u>')}</div>${t<3?`<div class="exh">${w[5]}</div>`:''}`;cur=w[0];pool=words.map(x=>x[0])}
const o=sh([cur,...sh(pool.filter(x=>x!=cur)).slice(0,3)]);
$.innerHTML=`${hd}<div class="card ${r?'nb':'kc'}"><div class="pr">${P[t][r]}</div>${r==0&&t<3?`<div class="emo">${w[2]}</div>`:''}${q}</div><div class="opts">${o.map(x=>`<button class="opt" data-v="${x}" dir="${r==0?'rtl':'ltr'}" onclick="pick(this)">${x}</button>`).join('')}</div><div id="fb"></div>`}
function fin(ok,w,el){if(ok){score++;streak++;burst(el);sfx(1);if(streak==3||streak==5||streak==8)toast('🔥 רצף של '+streak+'!');say(w[0])}else{streak=0;sfx(3)}$i('fb').innerHTML=`<div class="fb">${ok?'🎉 נכון, כל הכבוד!':`לא נורא! <b dir="ltr">${w[0]}</b> = ${w[1]}<br>💡 ${w[3]}`}</div>`;go(nxt,ok?3000:5000)}
function pick(b){const ok=b.dataset.v==cur;document.querySelectorAll('.opt').forEach(x=>{x.disabled=true;if(x.dataset.v==cur)x.classList.add('ok')});if(!ok)b.classList.add('no');fin(ok,qs[qi].w,b)}
function rsp(){$i('sl').innerHTML=SP.L.split('').map((_,k)=>`<i class="slot">${SP.g[k]||''}</i>`).join('');$i('tl').innerHTML=SP.tl.map((c,k)=>`<button class="tl" ${SP.u.includes(k)?'disabled':''} onclick="tap(${k})">${c}</button>`).join('')}
function tap(k){if(SP.done)return;SP.g.push(SP.tl[k]);SP.u.push(k);rsp();if(SP.g.length==SP.L.length){SP.done=1;const ok=SP.g.join('').toLowerCase()==SP.L.toLowerCase(),sl=$i('sl');sl.classList.add(ok?'okk':'nok');fin(ok,SP.w,sl)}}
function un(){if(SP.done||!SP.g.length)return;SP.g.pop();SP.u.pop();rsp()}
function end(){setTimeout(rain,250);const p=score/qs.length,s=p>=.85?3:p>=.6?2:1;$.innerHTML=`<div class="card" style="margin-top:24px"><div class="stars">${'⭐'.repeat(s)}</div><h1 style="margin:0">${s==3?'מדהים!':s==2?'יפה מאוד!':'התחלה טובה!'}</h1><p class="he">${score} מתוך ${qs.length} תשובות נכונות</p><p class="sub">${s==3?'אתם שולטים במילים האלה.':'עוד סיבוב ואתם שם.'}</p></div><div class="nav" style="flex-direction:column"><button class="pri" onclick="quiz()">חידון חדש</button><button class="sec" onclick="i=0;learn()">ללמוד את המילים שוב</button><button class="sec" onclick="home()">לתפריט הראשי</button></div>`}
/* my words */
function mine(msg){clearTimeout(AT);$.innerHTML=`${back('המילים שלי')}<div class="card" style="border-color:var(--c)"><div class="emo">✍️</div><p class="pr">כתבו 4 עד 16 מילים באנגלית, מילה בכל שורה או עם פסיקים. אתרגם ונתרגל אותן.</p><textarea id="mw" dir="ltr" rows="6" placeholder="elephant&#10;pizza&#10;brave&#10;rocket"></textarea>${msg?`<div class="fb">${msg}</div>`:''}</div><div class="nav"><button class="pri" id="go" onclick="trans()">תרגמו לי ✨</button></div>`}
async function trans(){const ws=parse($i('mw').value),a=ST.age||10;if(ws.length<4)return mine('צריך לפחות 4 מילים באנגלית (אפשר עד 16).');const b=$i('go');b.disabled=true;b.textContent='מתרגם... ⏳';try{const s=await S();if(!s)return mine('התרגום לא זמין כרגע. נסו שוב מאוחר יותר.');let r=await s.json(`For each English word below, return a JSON array (same order) of objects {"en":the word,"he":short Hebrew translation (most common meaning for kids),"emoji":one emoji,"tip":Hebrew memory trick, max 10 words (how it sounds in Hebrew letters plus a fun association),"s":a simple English sentence for a child aged ${a} where the word is replaced by ___ ,"sh":Hebrew translation of that sentence}. Return only JSON. Words: ${ws.join(', ')}`);if(!Array.isArray(r))r=r.words||[];words=r.filter(o=>o&&o.en&&o.he).map(o=>[clr(o.en,1),clr(o.he,1),o.emoji||'⭐',clr(o.tip),String(o.s||'').includes('___')?clr(o.s):'I like the word ___.',clr(o.sh)]);if(words.length<4)return mine('לא הצלחתי לתרגם מספיק מילים. נסו מילים אחרות.');age=a;CE='✍️';i=0;learn()}catch(e){mine('משהו השתבש, נסו שוב.')}}
/* stories */
function tales(){clearTimeout(AT);$.innerHTML=`${back('מגדל הסיפורים')}<div class="hero"><div class="owl">🏰</div><h1>מגדל הסיפורים</h1><p class="sub">קוראים, לומדים מילים ועונים על שאלות</p></div><div class="menu">${[['m4','tcfg(0)','🎲','סיפור הפתעה','סיפור קצר לפי גיל ונושא, עם שאלות'],['m5','tcfg(1)','🧩','סיפור בהזמנה','בוחרים 4 עד 16 מילים והסיפור משלב אותן']].map(m=>`<button class="mode ${m[0]}" onclick="${m[1]}"><i>${m[2]}</i><b>${m[3]}</b><small>${m[4]}</small></button>`).join('')}</div>`}
function tcfg(m){ta=ST.age||10;tp='';$.innerHTML=`${back(m?'סיפור בהזמנה':'סיפור הפתעה','tales()')}<div class="card paper" style="text-align:center"><div class="emo">${m?'🧩':'🎲'}</div>${m?`<p class="pr">כתבו 4 עד 16 מילים באנגלית ואכתוב סיפור שמשלב אותן.</p><textarea id="mw" dir="ltr" rows="4" placeholder="dragon&#10;brave&#10;castle"></textarea>`:''}<p class="pr">${ST.age?`🎂 גיל ${ST.age} (משנים בהגדרות ⚙️)`:'גיל הקורא'}</p>${ST.age?'':`<div class="chips">${AGES.map(a=>`<button class="chip ${a==10?'on':''}" data-g="A" onclick="chip(this,'A',${a})">${a}</button>`).join('')}</div>`}<p class="pr">נושא</p><div class="chips">${['🎲 הפתעה','🚀 חלל','🐾 חיות','🕵️ מסתורין','⚽ ספורט','🏰 הרפתקה','🌊 ים','🤖 רובוטים','🎨 יצירה','🌦️ מזג-אוויר'].map((c,k)=>`<button class="chip ${k?'':'on'}" data-g="P" onclick="chip(this,'P','${k?c.split(' ')[1]:''}')">${c}</button>`).join('')}</div><div class="fb" id="err"></div></div><div class="nav"><button class="pri" onclick="gen(${m})">כתבו לי סיפור ✨</button></div>`}
function chip(b,g,v){document.querySelectorAll('[data-g="'+g+'"]').forEach(x=>x.classList.remove('on'));b.classList.add('on');if(g=='A')ta=v;else tp=v}
const pk=a=>a[Math.floor(Math.random()*a.length)];
const TOP=['outer space','wild animals','a mystery','sports','friendship','inventions','the ocean','weather','music','time travel','a school trip','a lost treasure','robots','a magic garden','a rescue mission'];
const SETS=['a tiny island','a busy train station','a quiet library','a school science fair','a rainy camping trip','an old market','a space station','a farm at sunrise','a football match','a snowy mountain','a beach cleanup day','a robot workshop','a zoo at night','a lighthouse','a desert road','a museum'];
const NM=['Noa','Daniel','Yael','Omar','Lina','Ravi','Mia','Tomer','Sara','Leo','Dana','Amir','Nina','Ben','Hana','Eli','Zoe','Adam'];
const MOODS=['funny','mysterious','heartwarming','exciting','a little silly','surprising','calm and cozy'];
async function gen(m){const err=$i('err');let ws=[];if(m){ws=parse($i('mw').value);if(ws.length<4){err.textContent='צריך לפחות 4 מילים באנגלית (עד 16).';return}}
const s=await S();if(!s){err.textContent='הכתיבה לא זמינה כרגע. נסו שוב מאוחר יותר.';return}
const a=ta,t=tier(a),len={8:50,9:60,10:90,11:110,12:140,13:170,14:200}[a],ql=t<2?'Hebrew':t==2?'English followed by a short Hebrew hint in parentheses':'English only';
$.innerHTML=`<div class="card ld" style="margin-top:40px"><div class="emo">📖</div><h2>כותבים לך סיפור...</h2><p class="sub">זה לוקח כמה שניות</p></div>`;
try{const r=await s.json(`Write a fun reading text for a Hebrew-speaking child aged ${a} learning English (vocabulary and sentence length suitable for that age). Topic: ${tp||pk(TOP)}. Setting: ${pk(SETS)}. Main character: ${pk(NM)}. Mood: ${pk(MOODS)}. Be original: never use pizza, dragons or the name Max. Return only JSON: {"title":English title,"story":English story of about ${len} words${m?`, naturally using ALL of these words: ${ws.join(', ')}`:''},"vocab":[{"en":word exactly as it appears in the story,"he":Hebrew meaning}] ${m?'for every given word':'for 6 harder words'},"qs":[5 multiple-choice comprehension questions {"q":question written in ${ql},"o":[4 short options in English, the correct one FIRST],"w":one short Hebrew sentence explaining the answer}]}${m?'. At least 2 questions must ask what a given word means or which word fits.':''}`,{cache:false});
if(!r||typeof r.story!='string'||!Array.isArray(r.qs))throw 0;
SD={t:clr(r.title),s:r.story.replace(/[<>`]/g,''),v:(r.vocab||[]).filter(x=>x&&x.en&&x.he).map(x=>({en:clr(x.en),he:clr(x.he)})),q:r.qs.filter(x=>x&&x.q&&Array.isArray(x.o)&&x.o.length>=2).slice(0,5).map(x=>({q:String(x.q),o:x.o.slice(0,4).map(String),w:String(x.w||'')}))};
if(SD.q.length<3)throw 0;age=a;HM=0;HS.clear();HC={};read()}catch(e){tcfg(m);$i('err').textContent='משהו השתבש, נסו שוב.'}}
function sHTML(){const idx=p=>{const l=p.toLowerCase();return SD.v.findIndex(v=>{const e=v.en.toLowerCase();return l==e||(e.length>3&&l.startsWith(e))})};
return SD.s.split(/([A-Za-z]+)/).map((p,j)=>{if(j%2){const k=idx(p),l=p.toLowerCase();if(HM)return`<span class="hw${HS.has(l)?' sel':''}${k<0?'':' vk'}" data-w="${l}" onclick="hw(this)">${p}</span>`;return k<0?p:`<mark class="w" onclick="gl(${k})">${p}</mark>`}return esc(p).replace(/\n/g,'<br>')}).join('')}
const hcnt=()=>HS.size?'נבחרו '+HS.size+' מילים':'בחרו מילים מהטקסט';
const gtxt=()=>HM?'לחצו על מילים שקשה לכם ואז על "גלו את הפירוש"':'לחצו על מילה מסומנת כדי לראות מה פירושה 👆';
function storyBox(){return`<div class="paper"><h2 class="stt" dir="ltr">${esc(SD.t)}</h2><div class="story" id="st">${sHTML()}</div><div class="btnrow"><button class="say" onclick="say(SD.s)">🔊 הקראה</button>${HELP(age)?`<button class="say ${HM?'hon':''}" id="hbt" onclick="hlp()">🆘 עזרה</button>`:''}</div></div>${HELP(age)?`<div id="hb" class="hb" ${HM?'':'hidden'}><span id="hc">${hcnt()}</span><button class="pri" onclick="htr()">גלו את הפירוש</button></div>`:''}<div id="gl">${gtxt()}</div>`}
function read(){clearTimeout(AT);$.innerHTML=`${back('מגדל הסיפורים','tales()')}${storyBox()}<div class="vl">${SD.v.map(v=>`<span dir="ltr">${esc(v.en)} = ${esc(v.he)}</span>`).join('')}</div><div class="nav"><button class="pri" onclick="qgo()">לשאלות ✏️</button></div>`}
function gl(k){const v=SD.v[k];$i('gl').innerHTML=`<b dir="ltr">${esc(v.en)}</b> = ${esc(v.he)}`;say(v.en)}
function hlp(){HM=!HM;HS.clear();$i('st').innerHTML=sHTML();$i('hb').hidden=!HM;$i('hbt').classList.toggle('hon',!!HM);$i('hc').textContent=hcnt();$i('gl').textContent=gtxt()}
function hw(el){const w=el.dataset.w;HS.has(w)?HS.delete(w):HS.add(w);el.classList.toggle('sel');$i('hc').textContent=hcnt()}
async function htr(){if(!HS.size)return;const g=$i('gl'),ws=[...HS],need=ws.filter(w=>!HC[w]);if(need.length){g.textContent='מתרגם... ⏳';const s=await S();if(!s){g.textContent='התרגום לא זמין כרגע.';return}try{const r=await s.json(`Translate these English words to Hebrew, as used in this story. Return only a JSON object mapping each word to a short Hebrew meaning. Story: ${SD.s}\nWords: ${need.join(', ')}`),m={};Object.keys(r).forEach(k=>m[k.toLowerCase()]=r[k]);need.forEach(w=>{HC[w]=clr(m[w],1)||'?'})}catch(e){g.textContent='משהו השתבש, נסו שוב.';return}}
g.innerHTML=ws.map(w=>`<span class="gc" dir="ltr">${esc(w)} = <b>${esc(HC[w])}</b></span>`).join('');HS.clear();$i('st').innerHTML=sHTML();$i('hc').textContent=hcnt()}
function peek(){PK=1;clearTimeout(AT);document.querySelectorAll('.cd,.skip').forEach(x=>x.remove());ov(storyBox())}
function qgo(){si=0;ss=0;streak=0;sq=SD.q;sask()}
function sask(){PA=0;const q=sq[si];sopts=sh(q.o.map((x,k)=>({x,c:!k})));$.innerHTML=`${bar(si+1,sq.length,'📖 שאלות על הסיפור'+(streak>1?' 🔥 '+streak:''))}<div class="card nb"><div class="ex2" ${/[א-ת]/.test(q.q)?'':'dir="ltr"'}>${esc(q.q)}</div></div><div class="btnrow" style="margin-top:10px"><button class="say" onclick="peek()">📖 חזרה לטקסט</button></div><div class="opts">${sopts.map((o,k)=>`<button class="opt" dir="ltr" onclick="sa(this,${k})">${esc(o.x)}</button>`).join('')}</div><div id="fb"></div>`}
function sa(b,k){const ok=sopts[k].c,q=sq[si];PA=1;document.querySelectorAll('.opt').forEach((x,j)=>{x.disabled=true;if(sopts[j].c)x.classList.add('ok')});if(ok){ss++;streak++;burst(b);sfx(1);if(streak==3||streak==5)toast('🔥 רצף של '+streak+'!')}else{streak=0;sfx(3);b.classList.add('no')}$i('fb').innerHTML=`<div class="fb">${ok?'🎉 נכון!':'לא נורא!'} ${esc(q.w)}</div>`;go(()=>{si++;si<sq.length?sask():send()},ok?3500:5000)}
function send(){setTimeout(rain,250);const p=ss/sq.length,s=p>=.85?3:p>=.6?2:1;$.innerHTML=`<div class="card" style="margin-top:24px"><div class="stars">${'⭐'.repeat(s)}</div><h1 style="margin:0">${s==3?'קוראים מצוינים!':s==2?'קריאה יפה!':'התחלה טובה!'}</h1><p class="he">${ss} מתוך ${sq.length} תשובות נכונות</p></div><div class="nav" style="flex-direction:column"><button class="pri" onclick="read()">לקרוא שוב</button><button class="sec" onclick="tales()">סיפור חדש</button><button class="sec" onclick="home()">לתפריט הראשי</button></div>`}
/* effects */
let AC;
function sfx(k){if(ST.mute)return;try{AC=AC||new(window.AudioContext||window.webkitAudioContext)();const sq=k==1?[[523,0],[659,.09],[784,.18]]:k==2?[[523,0],[659,.1],[784,.2],[1047,.3]]:k==3?[[330,0],[262,.12]]:[[880,0]];sq.forEach(([f,d])=>{const o=AC.createOscillator(),g=AC.createGain(),t=AC.currentTime+d;o.type=k==3?'sawtooth':'triangle';o.frequency.value=f;g.gain.setValueAtTime(.001,t);g.gain.exponentialRampToValueAtTime(k==0?.04:k==3?.08:.15,t+.02);g.gain.exponentialRampToValueAtTime(.001,t+(k==0?.06:.2));o.connect(g);g.connect(AC.destination);o.start(t);o.stop(t+.25)})}catch(e){}}
function rain(){sfx(2);for(let k=0;k<36;k++){const e=document.createElement('span');e.className='pop fall';e.textContent=['🎉','⭐','✨','🎈','🎊'][k%5];e.style.left=Math.random()*100+'vw';e.style.top='-30px';e.style.animationDelay=Math.random()*.8+'s';e.style.setProperty('--dx',(Math.random()*80-40)+'px');document.body.appendChild(e);setTimeout(()=>e.remove(),2800)}}
function toast(t){const e=document.createElement('div');e.className='toast';e.textContent=t;document.body.appendChild(e);setTimeout(()=>e.remove(),1500)}
document.addEventListener('click',e=>{if(e.target.closest('button')&&!e.target.closest('.opt,.mute'))sfx(0)});
const mb=document.createElement('button');mb.className='mute';mb.textContent=ST.mute?'🔇':'🔊';mb.setAttribute('aria-label','צלילים');mb.onclick=()=>{ST.mute=!ST.mute;save();mb.textContent=ST.mute?'🔇':'🔊'};document.body.appendChild(mb);
const gb=document.createElement('button');gb.className='mute gear';gb.textContent='⚙️';gb.setAttribute('aria-label','הגדרות');gb.onclick=sets;document.body.appendChild(gb);
const PZ=[{p:'🐘',n:'elephant',h:'פיל',c:'חיה',w:'ant pen hen pan tap net ten eat tea the then plan lane lean heap hat pat nap pet let tan ape lap hate heat late neat pale plant planet leap tape tale lent ate apt peel heel teen pane pant path plate petal elephant'},
{p:'🍍',n:'pineapple',h:'אננס',c:'פרי',w:'pin pen pan nap pie pal pea ape lap nip pip pine pain pale leap plan lane lean line nail pail apple pipe peel pile plain panel lip lie eel nape plane'},
{p:'🦒',n:'giraffe',h:'ג׳ירפה',c:'חיה',w:'far rag rig fire fare rage gear grief fig fir ear era age are air fair fear rife giraffe'},
{p:'☂️',n:'umbrella',h:'מטרייה',c:'חפץ',w:'bell bull rub rule mule ball real blue bar bear ram bum mall lamb blur blare label elm male mare ear era are lure blame mural realm umbrella lab'},
{p:'✈️',n:'airplane',h:'מטוס',c:'חפץ',w:'plane pain rain lane pair nail pail air ran pan pen lap ear era line lain pine peal real near lair ripe plan learn pearl panel plain pale leap nap nip pin pea pal pie lip lie ape are paler airplane'},
{p:'🦋',n:'butterfly',h:'פרפר',c:'חיה',w:'but bet rub tub fur rut true flute fly try bury blue buy butter flutter bye lure rule tube blur turf belt left felt ruby yet fuel butterfly'},
{p:'🍓',n:'strawberry',h:'תות שדה',c:'פרי',w:'straw star rat bat bar bear bet tray stay west wet war was saw sat set art arts ray rays yes year tear beat rest rare stray water barter berry tarry wary strawberry'},
{p:'🐬',n:'dolphin',h:'דולפין',c:'חיה',w:'hold hop pin nip oil lip hip dip pod nod don pond lid old hid hind lion loin ion lop plod din nil oh dolphin'},
{p:'🌈',n:'rainbow',h:'קשת',c:'טבע',w:'bar barn bow row rob born bin ran rain brain win wan war raw now own brow brawn boar bran bra rib nab boa ban robin brown won worn iron rainbow'},
{p:'🌻',n:'sunflower',h:'חמנייה',c:'טבע',w:'sun fun run low flow flower slow own now sew few new sue use rule role wolf fuse lens fuel flour lose rose nose snow sown worn wore sure user lure owl fowl sunflower'},
{p:'🍉',n:'watermelon',h:'אבטיח',c:'פרי',w:'water melon meal more tear team tame mean lean male name learn later alert motel tone note loan alone metal tale wane tower lower mower meat mate moral melt ant eat ate net ten tea wet owl tree watermelon'}];
/* reveal-the-picture game */
let G,LASTP=-1;
function wg(){clearTimeout(AT);let k;do{k=Math.floor(Math.random()*PZ.length)}while(k==LASTP);LASTP=k;const p=PZ[k];G={p,V:new Set(p.w.split(' ')),f:[],c:[],t:sh(p.n.split('')),hid:sh([0,1,2,3,4,5,6,7,8]),done:0};
$.innerHTML=`${back('חושפים את התמונה')}<div class="pz"><div class="pic">${p.p}</div><div class="cov">${[0,1,2,3,4,5,6,7,8].map(j=>`<i class="cv" style="--cc:hsl(${j*40+10},70%,50%)">?</i>`).join('')}</div></div><p class="sub">רמז: ${p.c}. מרכיבים מילים באנגלית מהאותיות, וכל מילה חושפת חלק מהתמונה</p><div class="slots" id="wsl" style="min-height:48px"></div><div class="tiles" id="wtl"></div><div class="btnrow"><button class="say" onclick="wun()">⌫ מחיקה</button><button class="say" onclick="wmix()">🔀 ערבוב</button><button class="say" onclick="whint()">💡 רמז</button></div><div class="nav"><button class="pri" onclick="wchk()">בדקו מילה ✔️</button></div><div class="fb" id="wmsg">הרכיבו מילה של 3 אותיות ומעלה</div><div class="vl" id="wf"></div><div class="nav"><button class="sec" onclick="wguess()">🤔 ידעתי מה זה!</button></div>`;wr()}
function wr(){$i('wsl').innerHTML=G.c.map(k=>`<i class="slot">${G.t[k]}</i>`).join('');$i('wtl').innerHTML=G.t.map((c,k)=>`<button class="tl" ${G.c.includes(k)?'disabled':''} onclick="wt(${k})">${c}</button>`).join('')}
function wt(k){if(!G.done){G.c.push(k);wr()}}
function wun(){G.c.pop();wr()}
function wmix(){G.c=[];G.t=sh(G.t);wr()}
function wm(t){$i('wmsg').innerHTML=t}
function wchk(){if(G.done)return;const w=G.c.map(k=>G.t[k]).join('').toLowerCase(),sl=$i('wsl');if(w.length<3)return wm('צריך לפחות 3 אותיות');if(G.f.includes(w))return wm('כבר מצאתם את <b dir="ltr">'+w+'</b>!');
if(G.V.has(w)){G.f.push(w);let rv=0;for(let j=0;j<(w.length>=5?2:1)&&G.hid.length;j++){document.querySelectorAll('.cv')[G.hid.shift()].classList.add('rv');rv++}sfx(1);burst(sl);say(w);wm('🎉 <b dir="ltr">'+w+'</b>! נחשף '+(rv>1?'עוד חלק גדול':'עוד חלק')+' מהתמונה');G.c=[];wr();$i('wf').innerHTML=G.f.map(x=>`<span dir="ltr">${x}</span>`).join('');if(!G.hid.length)wwin(0)}
else{sfx(3);sl.classList.add('nok');setTimeout(()=>sl.classList.remove('nok'),450);wm('המילה <b dir="ltr">'+esc(w)+'</b> לא ברשימה שלנו. נסו אחרת!')}}
function whint(){const r=[...G.V].filter(x=>x.length>=3&&!G.f.includes(x)),w=r[Math.floor(Math.random()*r.length)];if(w)wm('💡 יש מילה של '+w.length+' אותיות שמתחילה ב-<b dir="ltr">'+w[0].toUpperCase()+'</b>')}
function wguess(){const o=sh([G.p.n,...sh(PZ.map(x=>x.n).filter(x=>x!=G.p.n)).slice(0,3)]);ov(`<h2 style="text-align:center">מה מתחבא בתמונה? 🤔</h2><div class="opts">${o.map(x=>`<button class="opt" dir="ltr" onclick="wans('${x}')">${x}</button>`).join('')}</div>`)}
function wans(x){if(x==G.p.n){cl(1);wwin(1)}else{sfx(3);toast('לא זה, נסו שוב 🙈')}}
function wwin(g){if(G.done)return;G.done=1;const rv=9-G.hid.length,s=g?(rv<=4?3:rv<=7?2:1):2;document.querySelectorAll('.cv').forEach(c=>c.classList.add('rv'));setTimeout(()=>{rain();say(G.p.n);$.innerHTML=`<div class="card" style="margin-top:20px"><div class="stars">${'⭐'.repeat(s)}</div><div class="emo" style="font-size:6rem">${G.p.p}</div><div class="en" dir="ltr">${G.p.n}</div><div class="he">${G.p.h}</div><p class="sub">מצאתם ${G.f.length} מילים${g?' וניחשתם לבד!':' וחשפתם את כל התמונה!'}</p></div><div class="nav" style="flex-direction:column"><button class="pri" onclick="wg()">תמונה חדשה</button><button class="sec" onclick="home()">לתפריט הראשי</button></div>`},1100)}
calm();home();
</script></body></html>
