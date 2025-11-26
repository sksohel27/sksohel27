<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>SK Sohel — Profile</title>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --accent: #00D9FF;
      --bg: #0b0f14;
      --card: #071018;
      --text: #dbe9ee;
      --muted: #9fb9c4;
      --radius: 18px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#020407 0%, #071025 100%);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial; color:var(--text)}
    .wrap{display:flex;align-items:center;justify-content:center;padding:48px 16px}
    .card{width:100%;max-width:980px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:var(--radius);padding:28px;border:1px solid rgba(255,255,255,0.03);box-shadow:0 14px 40px rgba(0,217,255,0.06)}
    .banner{border-radius:12px;overflow:hidden;display:block;margin:0 auto;width:100%;height:260px;object-fit:cover}
    .center{text-align:center;margin-top:18px}
    h1{font-size:28px;margin:10px 0 6px;font-weight:800}
    h1 span{color:var(--accent)}
    h3{font-size:15px;margin:6px 0 14px;font-weight:600;color:var(--muted)}
    .typing{display:block;margin:14px auto 22px}
    .badges{display:flex;gap:10px;justify-content:center;flex-wrap:wrap;margin-bottom:18px}
    .badge{display:inline-flex;align-items:center;padding:8px 12px;border-radius:999px;background:linear-gradient(90deg, rgba(0,217,255,0.08), rgba(0,217,255,0.02));border:1px solid rgba(0,217,255,0.06);font-weight:600;color:var(--accent)}
    .icons{display:flex;justify-content:center;margin-top:8px}
    .note{color:var(--muted);font-size:13px;text-align:center;margin-top:18px}
    /* Responsive */
    @media (max-width:600px){
      .banner{height:180px}
      h1{font-size:22px}
    }
    /* Small utility */
    a.inline-link{color:var(--accent);text-decoration:none}
  </style>
</head>
<body>
  <div class="wrap">
    <article class="card" role="article" aria-label="SK Sohel profile card">
      <img src="https://raw.githubusercontent.com/sksohel27/sksohel27/main/Picsart_25-11-26_21-40-55-117.jpg" alt="SK Sohel banner" class="banner"/>

      <div class="center">
        <h1>Hi, I'm <span>SK Sohel</span> 👋</h1>
        <h3>Aspiring AI/ML Engineer • Deep Learning • Computer Vision • MLOps</h3>

        <!-- Live typing (Readme-typing-svg) -->
        <div class="typing">
          <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=4000&pause=1000&color=00D9FF&center=true&vCenter=true&width=820&lines=YOLOv8+Multi-Task+Learning+94%25;Federated+Learning+%F0%9F%8C%A8+Flower;Behavioral+Biometrics+Research;Always+learning,+always+building!" alt="typing svg" aria-hidden="true"/>
        </div>

        <!-- Status badges (images from shields.io) -->
        <div class="badges" aria-hidden="false">
          <img class="badge" src="https://img.shields.io/badge/Status-Open%20to%20Work-00D9FF?style=for-the-badge&logo=github" alt="Status Open to Work"/>
          <img class="badge" src="https://img.shields.io/badge/Location-Dankuni%2C%20West%20Bengal-00D9FF?style=for-the-badge" alt="Location"/>
          <img class="badge" src="https://img.shields.io/badge/Pronouns-he%2Fhim-00D9FF?style=for-the-badge" alt="Pronouns"/>
        </div>

        <!-- Optional skill icons (skillicons.dev) -->
        <div class="icons">
          <img src="https://skillicons.dev/icons?i=python,tensorflow,pytorch,opencv,keras,sklearn,pandas,numpy,matplotlib,fastapi,streamlit,docker,aws,git&perline=7&theme=dark" alt="skill icons"/>
        </div>

        <p class="note">If you want this as Markdown for a GitHub README or need tweaks (colors, fonts, icons), tell me which format and I'll adapt it.</p>
      </div>
    </article>
  </div>
</body>
</html>
