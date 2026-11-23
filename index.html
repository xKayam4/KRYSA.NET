<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>KRYSA.NET — Закрытая база данных</title>
<style>
:root{
  --bg:#080d0d;--panel:#101a19;--panel2:#142220;--line:#29413a;
  --green:#9cffb0;--green2:#48d879;--muted:#91a79c;--red:#ff5c66;
  --gold:#e7c96a;--text:#e6f0e9;--shadow:0 18px 60px #0009;
}
*{box-sizing:border-box}
body{margin:0;background:
 radial-gradient(ellipse at 15% 0%,#173329 0,transparent 38%),
 radial-gradient(ellipse at 100% 20%,#301b20 0,transparent 32%),var(--bg);
 color:var(--text);font:15px/1.6 "Courier New",monospace;min-height:100vh}
body:before{content:"";position:fixed;inset:0;pointer-events:none;opacity:.12;
 background:repeating-linear-gradient(0deg,transparent 0 3px,#b4ffc0 4px,transparent 5px)}
button,input{font:inherit}
button{cursor:pointer}
a{color:var(--green)}
.wrap{max-width:1080px;margin:auto;padding:26px 18px 60px}
.top{display:flex;justify-content:space-between;align-items:center;gap:14px;border-bottom:1px solid var(--line);padding:12px 0 20px}
.brand{font-size:clamp(24px,5vw,38px);font-weight:bold;letter-spacing:3px;color:var(--green);text-shadow:0 0 18px #48d87966}
.brand small{display:block;font-size:10px;letter-spacing:2px;color:var(--muted);font-weight:normal}
.status{font-size:11px;color:var(--red);border:1px solid #77363b;padding:7px 10px;letter-spacing:1px}
.hero{padding:48px 0 28px;max-width:760px}
.eyebrow{color:var(--gold);font-size:11px;letter-spacing:3px}
h1{font-size:clamp(30px,6vw,56px);line-height:1.05;margin:12px 0;color:#f0f7ef}
h2{font-size:23px;margin:0 0 12px;color:var(--green)}
h3{font-size:17px;color:var(--gold);margin:0 0 8px}
p{margin:8px 0 14px}
.muted{color:var(--muted)}
.grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px}
@media(max-width:650px){.grid{grid-template-columns:1fr}.top{align-items:flex-start}.status{max-width:130px;text-align:center}}
.card{background:linear-gradient(145deg,#14221fdd,#0d1514f2);border:1px solid var(--line);padding:20px;border-radius:10px;box-shadow:var(--shadow)}
.card + .card{margin-top:14px}
.nav{display:flex;flex-wrap:wrap;gap:8px;margin:22px 0}
.nav button,.btn{background:#172823;border:1px solid #426b56;color:var(--green);padding:10px 14px;border-radius:5px}
.nav button:hover,.btn:hover{background:#234033}
.nav button:disabled{opacity:.35;cursor:not-allowed}
.btn.primary{background:#17452d;border-color:var(--green2);color:#eaffef}
.btn.danger{border-color:#86424a;color:#ff9ca2;background:#30191d}
input{width:100%;background:#070d0c;border:1px solid #426052;border-radius:5px;padding:12px;color:var(--text);outline:none}
input:focus{border-color:var(--green)}
.formrow{display:flex;gap:8px;margin-top:12px}
.formrow input{flex:1;min-width:0}
@media(max-width:500px){.formrow{flex-direction:column}}
.lock{display:inline-block;color:var(--red);font-size:10px;border:1px solid #77363b;padding:3px 7px}
.open{color:var(--green);border-color:#39754e}
.doc{border-left:3px solid var(--gold);background:#0a1210;padding:14px 16px;margin:14px 0;white-space:pre-line}
.file{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:13px 0;border-bottom:1px dashed #29413a}
.file:last-child{border:0}
.file strong{display:block}
.file small{color:var(--muted)}
.tag{font-size:10px;color:var(--gold);letter-spacing:1px}
.hidden{display:none!important}
.notice{padding:12px 14px;border:1px solid #755f2b;background:#211d10;color:#f2dda0;border-radius:5px;margin:14px 0}
.success{padding:12px 14px;border:1px solid #34764b;background:#102419;color:#a9ffc0;border-radius:5px;margin:14px 0}
.error{color:#ff8e96;font-size:12px;margin-top:8px;min-height:18px}
.bigcode{font-size:clamp(22px,5vw,34px);letter-spacing:6px;color:var(--green);text-align:center;padding:16px}
.footer{margin-top:40px;border-top:1px solid var(--line);padding-top:16px;color:#71877b;font-size:11px;display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
.count{color:var(--gold)}
.badge{display:inline-block;background:#1e3028;color:var(--green);padding:3px 8px;border-radius:3px;font-size:11px}
hr{border:0;border-top:1px solid var(--line);margin:18px 0}
ul{padding-left:22px}
li{margin:5px 0}
</style>
</head>
<body>
<div class="wrap">
  <header class="top">
    <div class="brand">KRYSA.NET<small>ЦЕНТРАЛЬНАЯ СИСТЕМА КРЫСИНОГО ГОРОДА</small></div>
    <div class="status">● ДОСТУП ОГРАНИЧЕН</div>
  </header>

  <main>
    <section id="home">
      <div class="hero">
        <div class="eyebrow">АРХИВНОЕ ДЕЛО №001 / 31.12</div>
        <h1>ПОСЛЕДНЯЯ НОЧЬ<br>КРЫСИНОГО ГОРОДА</h1>
        <p class="muted">Закрытая база данных городского управления. Несанкционированный доступ преследуется законом. Особенно если вы хомяк.</p>
        <div class="notice"><strong>ЭКСТРЕННОЕ УВЕДОМЛЕНИЕ</strong><br>Новогодний таймер остановлен на отметке 23:00. Золотая Крыса пропала. Глава города Крысослав Первый не выходит на связь.</div>
        <p>Для продолжения расследования откройте доступ к архиву жителей. Пароль указан в последнем сообщении городского диспетчера:</p>
        <div class="doc">«Город отмечает своё основание в последний день года. Четыре цифры. Без точек».</div>
        <button class="btn primary" onclick="showSection('archive')">ПЕРЕЙТИ К АРХИВУ →</button>
      </div>
      <div class="grid">
        <div class="card"><span class="tag">СОСТОЯНИЕ СИСТЕМЫ</span><h3>Таймер</h3><div class="bigcode">23:00</div><p class="muted">Обратный отсчёт приостановлен.</p></div>
        <div class="card"><span class="tag">ОБЪЕКТ ПОИСКА</span><h3>Золотая Крыса</h3><p>Декоративный ключ запуска. Последний раз замечена в центральном зале.</p><span class="badge">СТАТУС: ПРОПАЛА</span></div>
      </div>
    </section>

    <section id="app" class="hidden">
      <div class="nav">
        <button onclick="showSection('home')">⌂ Главная</button>
        <button id="nav-archive" onclick="showSection('archive')">01 Архив</button>
        <button id="nav-docs" disabled onclick="showSection('docs')">02 Документы 🔒</button>
        <button id="nav-lab" disabled onclick="showSection('lab')">03 Лаборатория 🔒</button>
        <button id="nav-secret" disabled onclick="showSection('secret')">04 Закрытый отдел 🔒</button>
        <button id="nav-final" disabled onclick="showSection('final')">05 Дело №001 🔒</button>
      </div>

      <section id="archive" class="section card">
        <span class="tag">РАЗДЕЛ 01 / АРХИВ ЖИТЕЛЕЙ</span>
        <h2>Личные дела подозреваемых</h2>
        <p class="muted">Четыре жителя, у каждого — свои секреты. Изучите досье.</p>
        <div class="grid">
          <div class="card"><h3>Крысослав Первый</h3><p>Глава города. Любит торжественные речи, дорогие плащи и чтобы ему аплодировали. Последний раз замечен около таймера.</p><span class="badge">НЕ ВЫХОДИТ НА СВЯЗЬ</span></div>
          <div class="card"><h3>Доктор Писк</h3><p>Главный инженер. Разработчик таймера. Утверждает, что механизм был полностью исправен.</p><span class="badge">ЛАБОРАТОРИЯ</span></div>
          <div class="card"><h3>Мистер Сыр</h3><p>Владелец казино. Последним видел главу города. Обладает подозрительно большим количеством сыра.</p><span class="badge">КАЗИНО</span></div>
          <div class="card"><h3>Дед Крыс</h3><p>Старейший житель. Путает дни недели, события и иногда собственное имя. Зато многое видел.</p><span class="badge">СТАРОЖИЛ</span></div>
        </div>
        <hr>
        <h3>Вход в секретные документы</h3>
        <p>Введите дату основания города: последний день года, четыре цифры.</p>
        <div class="formrow"><input id="pass1" placeholder="Введите пароль" autocomplete="off"><button class="btn primary" onclick="unlock('3112','pass1','err1','docs','nav-docs')">ОТКРЫТЬ</button></div><div id="err1" class="error"></div>
      </section>

      <section id="docs" class="section card hidden">
        <span class="tag">РАЗДЕЛ 02 / СЕКРЕТНЫЕ ДОКУМЕНТЫ</span>
        <h2>Архив происшествия</h2>
        <div class="doc"><h3>ДОКУМЕНТ А — ОТЧЁТ ОХРАНЫ</h3>22:40 — Крысослав вошёл в помещение таймера.
22:44 — Свет в помещении погас.
22:47 — Из помещения никто не выходил.
22:51 — Система зарегистрировала открытие технического люка.
22:55 — Камера отключена вручную.</div>
        <div class="doc"><h3>ДОКУМЕНТ Б — ПЕРЕПИСКА</h3><strong>Доктор Писк:</strong> Таймер в порядке. Я проверял его утром.<br><strong>Неизвестный:</strong> А если он не запустится?<br><strong>Доктор Писк:</strong> Тогда кто-то должен вернуть питание.<br><strong>Неизвестный:</strong> Отлично. Значит, план работает.</div>
        <div class="doc"><h3>ДОКУМЕНТ В — ЗАПИСКА</h3><div class="bigcode">16 - 15 - 5 - 3 - 1 - 12</div><p>Подсказка: А = 1, Б = 2 и так далее. Русский алфавит без Ё.</p></div>
        <div class="notice">Задание: расшифруйте слово. Оно укажет, где искать следующий файл.</div>
        <div class="formrow"><input id="pass2" placeholder="Куда искать?"><button class="btn primary" onclick="unlock('подвал','pass2','err2','lab','nav-lab')">ПОДТВЕРДИТЬ</button></div><div id="err2" class="error"></div>
        <p class="muted">Если застряли: начните с чисел и русского алфавита. Ответ — место в здании.</p>
      </section>

      <section id="lab" class="section card hidden">
        <span class="tag">РАЗДЕЛ 03 / ЛАБОРАТОРИЯ</span>
        <h2>Технический журнал</h2>
        <div class="doc"><h3>ОТЧЁТ №77</h3>Новогодний таймер не повреждён.<br>Электрическое питание отключено вручную.<br>Золотая Крыса является декоративным ключом запуска, а не частью механизма.<br>При возвращении ключа и питания система заработает.</div>
        <div class="doc"><h3>ПОКАЗАНИЯ СОТРУДНИКА</h3>«Я видел человека в красном плаще около сцены. Он нёс что-то большое. Лица я не разглядел. Но походка была очень знакомой».</div>
        <div class="doc"><h3>ЗАГАДКА</h3>Там выступают, поздравляют и читают речи.<br>Все смотрят туда, когда наступает полночь.<br>Именно там скрывается то, что ищут.</div>
        <div class="formrow"><input id="pass3" placeholder="Введите место"><button class="btn primary" onclick="unlock('подиум','pass3','err3','secret','nav-secret')">ОТКРЫТЬ СЛЕДУЮЩИЙ РАЗДЕЛ</button></div><div id="err3" class="error"></div>
      </section>

      <section id="secret" class="section card hidden">
        <span class="tag">РАЗДЕЛ 04 / СОВЕРШЕННО СЕКРЕТНО</span>
        <h2>Закрытый отдел</h2>
        <div class="doc"><h3>ФАЙЛ №1 — ЧЕК ИЗ КОСТЮМЕРНОЙ</h3><strong>КРЫСИНЫЙ КОСТЮМЕР / ЧЕК №00431</strong><br>Красный плащ — 1 шт.<br>Огромная голова крысы — 1 шт.<br>Маска с усами — 1 шт.<br>Накладной живот — 1 шт.<br>Доставка: главная площадь.<hr>Покупатель: <strong>К. Первый</strong><br>Время: 22:30</div>
        <div class="doc"><h3>ФАЙЛ №2 — ЧЕРНОВИК РЕЧИ</h3>«Дорогие жители! В этом году мы снова собрались... Нет, слишком скучно.<br><br>Дорогие крысы! Я не могу больше стоять перед вами и говорить одно и то же! Почему каждый год я должен выступать?! И почему в этом году я должен быть одет в костюм гигантской крысы?!<br><br>Я ухожу. Я спрячусь там, где никто не будет меня искать. Под сценой.<br><br>Крысослав».</div>
        <div class="doc"><h3>ФАЙЛ №3 — ФОТОГРАФИЯ С КАМЕРЫ</h3><p>На снимке — новогодний подиум. Из-под сцены виден край красной ткани. На заднем плане — табличка «КОНКУРС КОСТЮМОВ. УЧАСТИЕ ГЛАВЫ ГОРОДА ОБЯЗАТЕЛЬНО».</p><p class="muted">Примечание оператора: «Клянусь, ткань шевелилась».</p></div>
        <div class="notice">Улики указывают на главу города. Но для подтверждения найдите финальное личное дело.</div>
        <p>Пароль указан в названии главного праздника, который город пытается спасти. Одно слово.</p>
        <div class="formrow"><input id="pass4" placeholder="Введите пароль"><button class="btn primary" onclick="unlock('новогодний','pass4','err4','final','nav-final')">РАЗБЛОКИРОВАТЬ ДЕЛО</button></div><div id="err4" class="error"></div>
      </section>

      <section id="final" class="section card hidden">
        <span class="tag">РАЗДЕЛ 05 / ЛИЧНОЕ ДЕЛО №001</span>
        <h2>Последняя запись Крысослава</h2>
        <div class="notice">ВНИМАНИЕ: ФАЙЛ ПРЕДНАЗНАЧЕН ДЛЯ ФИНАЛА ИГРЫ. ВЕДУЩИЙ, НЕ ОТКРЫВАЙТЕ ЕГО ДО ОТВЕТОВ КОМАНД.</div>
        <div class="doc"><h3>ЗАПИСЬ ИЗ ЛИЧНОГО ДНЕВНИКА</h3>Если вы читаете это, значит, мои планы провалились.<br><br>Я всего лишь хотел спокойно провести Новый год.<br><br>Но совет города заставил меня выступать, надевать костюм и участвовать в конкурсе «Мисс Крысиный город».<br><br>Я не выдержал.<br><br>Поэтому я отключил таймер, забрал Золотую Крысу и спрятался под подиумом.<br><br>Я не думал, что вы воспримете это настолько серьёзно.<br><br>И да, пожалуйста, не говорите никому, что я плакал в костюме.</div>
        <div class="success"><strong>ДЕЛО РАСКРЫТО.</strong><br>Виновник — Крысослав Первый. Мотив — страх перед новогодней речью и конкурсом костюмов. Золотая Крыса спрятана под подиумом.</div>
        <h3>СИСТЕМНОЕ СООБЩЕНИЕ</h3>
        <div class="bigcode">С НОВЫМ ГОДОМ!</div>
        <p class="muted">Таймер восстановлен. Город спасён. Крысославу назначено обязательное участие в конкурсе костюмов следующего года.</p>
        <button class="btn danger" onclick="showSection('home')">ЗАВЕРШИТЬ СЕАНС</button>
      </section>
    </section>
  </main>

  <footer class="footer"><span>KRYSA.NET // MUNICIPAL DATABASE</span><span>Сеанс защищён. Не кормить сервер сыром.</span></footer>
</div>
<script>
const unlocked = new Set(['archive']);
function showSection(id){
  if(id==='home'){document.getElementById('home').classList.remove('hidden');document.getElementById('app').classList.add('hidden');return;}
  document.getElementById('home').classList.add('hidden');
  document.getElementById('app').classList.remove('hidden');
  document.querySelectorAll('.section').forEach(s=>s.classList.add('hidden'));
  const target=document.getElementById(id);
  if(target) target.classList.remove('hidden');
  window.scrollTo({top:0,behavior:'smooth'});
}
function unlock(expected,inputId,errorId,nextId,navId){
  const input=document.getElementById(inputId);
  const error=document.getElementById(errorId);
  const value=input.value.trim().toLocaleLowerCase('ru').replaceAll('ё','е').replace(/\s+/g,'');
  const answer=expected.toLocaleLowerCase('ru').replaceAll('ё','е').replace(/\s+/g,'');
  if(value===answer){
    error.textContent='';
    unlocked.add(nextId);
    const nav=document.getElementById(navId);
    if(nav){nav.disabled=false;nav.textContent=nav.textContent.replace(' 🔒','');}
    showSection(nextId);
  }else{
    error.textContent='ОШИБКА ДОСТУПА. Проверьте пароль и попробуйте ещё раз.';
    input.focus();
  }
}
document.addEventListener('keydown',e=>{
  if(e.key==='Enter'){
    const active=document.activeElement;
    if(active && active.tagName==='INPUT'){
      const btn=active.parentElement.querySelector('button');
      if(btn) btn.click();
    }
  }
});
</script>
</body>
</html>
