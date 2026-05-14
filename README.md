<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FiveM Regelwerk</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      background:#0f172a;
      color:white;
      line-height:1.6;
    }

    header{
      background:linear-gradient(90deg,#2563eb,#1e40af);
      padding:30px;
      text-align:center;
      box-shadow:0 4px 10px rgba(0,0,0,0.4);
    }

    header h1{
      font-size:3rem;
    }

    header p{
      margin-top:10px;
      color:#dbeafe;
    }

    nav{
      background:#111827;
      padding:15px;
      position:sticky;
      top:0;
      z-index:100;
    }

    nav ul{
      display:flex;
      justify-content:center;
      list-style:none;
      gap:25px;
      flex-wrap:wrap;
    }

    nav a{
      color:white;
      text-decoration:none;
      transition:0.3s;
      font-weight:bold;
    }

    nav a:hover{
      color:#60a5fa;
    }

    .container{
      max-width:1200px;
      margin:auto;
      padding:40px 20px;
    }

    .rule-section{
      background:#1e293b;
      margin-bottom:25px;
      padding:25px;
      border-radius:15px;
      box-shadow:0 5px 15px rgba(0,0,0,0.3);
      transition:0.3s;
    }

    .rule-section:hover{
      transform:translateY(-5px);
    }

    .rule-section h2{
      color:#60a5fa;
      margin-bottom:15px;
    }

    .rule-section ul{
      padding-left:20px;
    }

    .rule-section li{
      margin-bottom:10px;
    }

    footer{
      text-align:center;
      padding:20px;
      background:#111827;
      margin-top:40px;
      color:#94a3b8;
    }

    .highlight{
      color:#f87171;
      font-weight:bold;
    }

    @media(max-width:768px){
      header h1{
        font-size:2rem;
      }

      nav ul{
        gap:15px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>FiveM Regelwerk</h1>
    <p>Offizielles Server Regelwerk</p>
  </header>

  <nav>
    <ul>
      <li><a href="#allgemein">Allgemein</a></li>
      <li><a href="#rp">RP Regeln</a></li>
      <li><a href="#crime">Crime Regeln</a></li>
      <li><a href="#safezone">Safezones</a></li>
      <li><a href="#support">Support</a></li>
    </ul>
  </nav>

  <div class="container">

    <section class="rule-section" id="allgemein">
      <h2>📜 Allgemeine Regeln</h2>
      <ul>
        <li>Jeder Spieler muss respektvoll mit anderen umgehen.</li>
        <li>Beleidigungen, Rassismus oder Diskriminierung sind verboten.</li>
        <li>Cheats, Hacks oder Exploits führen zum permanenten Bann.</li>
        <li>Das Ausnutzen von Bugs ist untersagt.</li>
      </ul>
    </section>

    <section class="rule-section" id="rp">
      <h2>🎭 Roleplay Regeln</h2>
      <ul>
        <li>Realistisches Roleplay ist Pflicht.</li>
        <li>FailRP ist verboten.</li>
        <li>RDM und VDM sind streng untersagt.</li>
        <li>PowerRP sowie MetaGaming sind verboten.</li>
      </ul>
    </section>

    <section class="rule-section" id="crime">
      <h2>🔫 Crime Regeln</h2>
      <ul>
        <li>Geiseln müssen realistisch behandelt werden.</li>
        <li>Cop-Baiting ist verboten.</li>
        <li>New-Life-Regel muss eingehalten werden.</li>
        <li>Nach dem Tod dürfen keine Erinnerungen an das RP bestehen.</li>
      </ul>
    </section>

    <section class="rule-section" id="safezone">
      <h2>🛡️ Safezone Regeln</h2>
      <ul>
        <li>In Safezones sind Waffen verboten.</li>
        <li>Kein Töten oder Ausrauben in Safezones.</li>
        <li>Fahrzeuge dürfen nicht absichtlich gerammt werden.</li>
      </ul>
    </section>

    <section class="rule-section" id="support">
      <h2>📞 Support Regeln</h2>
      <ul>
        <li>Supportfälle werden respektvoll behandelt.</li>
        <li>Lügen im Support ist verboten.</li>
        <li>Clips oder Beweise sollten vorhanden sein.</li>
        <li class="highlight">Supporter Entscheidungen sind zu respektieren.</li>
      </ul>
    </section>

  </div>

  <footer>
    © 2026 FiveM Server | Alle Rechte vorbehalten
  </footer>

</body>
</html>
