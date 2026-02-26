# maszynki-barberskie
Dzień dobry,  oferuję profesjonalne czyszczenie i konserwację maszynek barberskich, w tym:  czyszczenie mechanizmu i ostrzy,  smarowanie i regulację,  usuwanie problemów ze słabym cięciem i szarpaniem,  konserwację maszynek po upadku,  naprawę drobnej elektroniki.
<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Czyszczenie i konserwacja maszynek barberskich — Oleh (Wrocław)</title>
  <meta name="description" content="Czyszczenie, konserwacja i drobne naprawy maszynek barberskich we Wrocławiu. Regulacja ostrzy, smarowanie, czyszczenie mechanizmu." />
  <style>
    :root{
      --bg:#0b0f14; --card:#111826; --text:#e6edf3; --muted:#a6b3c2;
      --accent:#4cc9f0; --accent2:#80ffdb; --border:rgba(255,255,255,.08);
      --shadow: 0 18px 60px rgba(0,0,0,.55);
      --radius:18px;
    }
    *{box-sizing:border-box}
    body{
      margin:0; font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      background: radial-gradient(1200px 700px at 20% -10%, rgba(76,201,240,.20), transparent 60%),
                  radial-gradient(900px 600px at 90% 10%, rgba(128,255,219,.12), transparent 55%),
                  var(--bg);
      color:var(--text);
      line-height:1.4;
    }
    a{color:inherit; text-decoration:none}
    .wrap{max-width:980px; margin:0 auto; padding:28px 18px 60px;}
    header{
      display:flex; gap:18px; align-items:center; justify-content:space-between; flex-wrap:wrap;
      padding:18px 0 8px;
    }
    .brand{display:flex; gap:12px; align-items:center;}
    .logo{
      width:44px; height:44px; border-radius:14px;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      box-shadow: 0 10px 30px rgba(76,201,240,.18);
    }
    .brand h1{margin:0; font-size:16px; font-weight:700; letter-spacing:.2px}
    .brand p{margin:2px 0 0; color:var(--muted); font-size:13px}
    nav{display:flex; gap:10px; align-items:center; flex-wrap:wrap}
    .btn{
      display:inline-flex; align-items:center; gap:10px;
      padding:10px 14px; border-radius:999px;
      border:1px solid var(--border);
      background: rgba(255,255,255,.03);
      transition: transform .15s ease, background .15s ease, border-color .15s ease;
      font-weight:600; font-size:14px;
    }
    .btn:hover{transform: translateY(-1px); background: rgba(255,255,255,.06); border-color: rgba(255,255,255,.16)}
    .btn.primary{
      border:none;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      color:#031018;
    }
    .hero{margin-top:18px; display:grid; grid-template-columns: 1.2fr .8fr; gap:16px;}
    @media (max-width: 860px){ .hero{grid-template-columns:1fr;} }
    .card{
      background: linear-gradient(180deg, rgba(255,255,255,.05), rgba(255,255,255,.02));
      border: 1px solid var(--border);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding:18px;
    }
    .hero h2{margin:0 0 10px; font-size:34px; letter-spacing:-.4px}
    .hero .lead{margin:0 0 14px; color:var(--muted); font-size:15.5px}
    .badges{display:flex; flex-wrap:wrap; gap:10px; margin-top:12px}
    .badge{
      padding:8px 12px; border-radius:999px;
      border:1px solid var(--border);
      background: rgba(255,255,255,.03);
      color: var(--text);
      font-size:13px;
    }
    .grid{margin-top:14px; display:grid; grid-template-columns: repeat(3, 1fr); gap:12px;}
    @media (max-width: 860px){ .grid{grid-template-columns:1fr;} }
    .mini{
      padding:14px; border-radius:16px;
      border:1px solid var(--border);
      background: rgba(0,0,0,.18);
    }
    .mini h3{margin:0 0 6px; font-size:16px}
    .mini p{margin:0; color:var(--muted); font-size:13.5px}
    .section{margin-top:18px}
    .section h3{margin:0 0 10px; font-size:18px}
    ul{margin:10px 0 0 18px; color:var(--muted)}
    li{margin:8px 0}
    .contact{display:grid; grid-template-columns:1fr; gap:10px;}
    .contact .row{display:flex; flex-wrap:wrap; gap:10px;}
    .note{color:var(--muted); font-size:12.5px; margin-top:8px}
    footer{margin-top:22px; color:var(--muted); font-size:12.5px; text-align:center}
    .hr{height:1px; background:var(--border); margin:14px 0}
    .copy{cursor:pointer}
    .small{font-size:12.5px; color:var(--muted)}
  </style>
</head>

<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo" aria-hidden="true"></div>
        <div>
          <h1>Oleh — serwis maszynek barberskich (Wrocław)</h1>
          <p>czyszczenie • konserwacja • regulacja • drobna elektronika</p>
        </div>
      </div>

      <nav>
        <a class="btn" href="#uslugi">Usługi</a>
        <a class="btn" href="#jak">Jak to działa</a>
        <a class="btn" href="#cennik">Cennik</a>
        <a class="btn primary" href="#kontakt">Kontakt</a>
      </nav>
    </header>

    <section class="hero">
      <div class="card">
        <h2>Maszynka tnie słabo albo szarpie? Naprawię i zakonserwuję.</h2>
        <p class="lead">
          Profesjonalne czyszczenie, smarowanie i regulacja maszynek barberskich we Wrocławiu.
          Szybko, konkretnie i bez ściemy.
        </p>

        <div class="row" style="display:flex; gap:10px; flex-wrap:wrap;">
          <a class="btn primary" href="tel:+48782618575">Zadzwoń: +48 782 618 575</a>
          <a class="btn" href="mailto:twojemail@domena.pl">Napisz e-mail</a>
          <a class="btn" href="#kontakt">Formularz / dane</a>
        </div>

        <div class="badges">
          <span class="badge">Czyszczenie mechanizmu</span>
          <span class="badge">Regulacja ostrzy</span>
          <span class="badge">Smarowanie</span>
          <span class="badge">Konserwacja po upadku</span>
          <span class="badge">Drobna elektronika</span>
        </div>

        <div class="grid">
          <div class="mini">
            <h3>Dlaczego warto</h3>
            <p>Lepsze cięcie, mniej szarpania i dłuższa żywotność maszynki.</p>
          </div>
          <div class="mini">
            <h3>Szybka realizacja</h3>
            <p>Najczęściej tego samego / następnego dnia (zależnie od kolejki).</p>
          </div>
          <div class="mini">
            <h3>Uczciwa diagnoza</h3>
            <p>Jeśli naprawa się nie opłaca — mówię wprost.</p>
          </div>
        </div>
      </div>

      <aside class="card">
        <h3 id="uslugi">Zakres usług</h3>
        <ul>
          <li>Dokładne czyszczenie po włosach i zabrudzeniach</li>
          <li>Smarowanie i konserwacja elementów ruchomych</li>
          <li>Regulacja i ustawienie ostrzy</li>
          <li>Rozwiązanie problemów ze słabym cięciem / szarpaniem</li>
          <li>Konserwacja po upadku</li>
          <li>Naprawa drobnej elektroniki (jeśli możliwe)</li>
        </ul>

        <div class="hr"></div>

        <h3 id="jak">Jak to działa</h3>
        <ol class="small">
          <li>Kontakt: telefon / e-mail / wiadomość.</li>
          <li>Krótki opis problemu + model maszynki.</li>
          <li>Diagnoza → koszt → realizacja.</li>
        </ol>

        <p class="note">*Jeśli robisz wysyłkowo lub dojazd/odbiór — dopiszemy tu jedną linijkę.</p>
      </aside>
    </section>

    <section class="section card" id="cennik">
      <h3>Cennik (przykład — do edycji)</h3>
      <div class="small">
        <p>• Czyszczenie + smarowanie + regulacja: <b>od 60 zł</b></p>
        <p>• Konserwacja po upadku / dodatkowa regulacja: <b>od 80 zł</b></p>
        <p>• Drobna elektronika: <b>wycena po diagnozie</b></p>
        <p class="note">Zmień kwoty albo usuń cennik, jeśli wolisz wycenę indywidualną.</p>
      </div>
    </section>

    <section class="section card" id="kontakt">
      <h3>Kontakt</h3>
      <div class="contact">
        <div class="row">
          <a class="btn primary" href="tel:+48782618575">+48 782 618 575</a>
          <a class="btn" href="mailto:twojemail@domena.pl">twojemail@domena.pl</a>
          <span class="btn copy" data-copy="Wrocław">Wrocław (kliknij, kopiuj)</span>
        </div>
        <div class="small">
          <p><b>Godziny:</b> pn–pt po 18:00, weekend 9:00–16:00 (edytuj jeśli chcesz)</p>
          <p><b>Obsługa:</b> Wrocław i okolice / wysyłkowo (edytuj)</p>
        </div>
      </div>
      <p class="note">Jeśli chcesz — dodam przycisk WhatsApp/Messenger.</p>
    </section>

    <footer>
      © <span id="year"></span> Oleh — serwis maszynek barberskich
    </footer>
  </div>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();

    document.querySelectorAll("[data-copy]").forEach(el => {
      el.addEventListener("click", async () => {
        try{
          await navigator.clipboard.writeText(el.getAttribute("data-copy"));
          const old = el.textContent;
          el.textContent = "Skopiowano ✅";
          setTimeout(()=> el.textContent = old, 900);
        }catch(e){
          alert("Nie mogę skopiować — skopiuj ręcznie: " + el.getAttribute("data-copy"));
        }
      });
    });
  </script>
</body>
</html>
