<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Profil — Bunga Ramadhani</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&family=Pacifico&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#ffd6e8;
      --pink-1:#ffb3d1;
      --pink-2:#ff7fbf;
      --card:#ffffff;
      --muted:#6b6b6b;
      --accent:#ff6aa3;
      --glass: rgba(255,255,255,0.6);
    }

    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background: radial-gradient(circle at 10% 10%, #ffe8f3 0%, var(--bg) 30%, #fff 100%);}

    /* cute floating hearts background */
    .bg-hearts{position:fixed;inset:0;pointer-events:none;overflow:hidden}
    .heart{position:absolute;width:30px;height:30px;transform:translate(-50%,-50%) rotate(-25deg);opacity:0.9}
    .heart::before,.heart::after{content:"";position:absolute;width:100%;height:100%;background:var(--pink-2);border-radius:50%;}
    .heart::before{left:25%;top:0}
    .heart::after{left:0;top:25%}

    /* generate variety by nth-child */
    .heart:nth-child(1){left:10%;top:20%;animation:floater 8s linear infinite;opacity:0.8}
    .heart:nth-child(2){left:85%;top:15%;width:22px;height:22px;animation:floater 10s linear -2s infinite;opacity:0.7}
    .heart:nth-child(3){left:60%;top:70%;width:40px;height:40px;animation:floater 12s linear -4s infinite}
    .heart:nth-child(4){left:30%;top:40%;width:18px;height:18px;animation:floater 9s linear -1s infinite}
    .heart:nth-child(5){left:75%;top:55%;width:26px;height:26px;animation:floater 11s linear -3s infinite}

    @keyframes floater{
      0%{transform:translate(-50%,-50%) translateY(0) scale(1) rotate(-25deg);opacity:0.95}
      50%{transform:translate(-50%,-50%) translateY(-40px) scale(1.05) rotate(-5deg);opacity:0.75}
      100%{transform:translate(-50%,-50%) translateY(0) scale(1) rotate(-25deg);opacity:0.95}
    }

    /* container */
    .wrap{min-height:100vh;display:grid;place-items:center;padding:48px}
    .card{width:100%;max-width:980px;background:linear-gradient(180deg,var(--glass), rgba(255,255,255,0.9));border-radius:18px;box-shadow:0 10px 30px rgba(255,105,180,0.15);backdrop-filter: blur(6px);display:grid;grid-template-columns:360px 1fr;gap:28px;padding:28px}

    /* profile column */
    .profile{display:flex;flex-direction:column;align-items:center;gap:18px;padding:18px}
    .avatar{width:170px;height:170px;border-radius:22px;overflow:hidden;display:grid;place-items:center;background:linear-gradient(135deg,var(--pink-1),var(--pink-2));box-shadow:0 8px 20px rgba(255,106,160,0.18);transform:rotate(-4deg);transition:transform .4s}
    .avatar:hover{transform:rotate(0deg) scale(1.03)}
    .avatar svg{width:70%;height:70%}
    h1{name:--;font-size:1.6rem;margin:0}
    .role{font-weight:600;color:var(--muted);font-size:0.95rem}

    .badges{display:flex;gap:8px;flex-wrap:wrap;justify-content:center}
    .badge{background:linear-gradient(90deg,#fff,rgba(255,255,255,0.85));padding:8px 12px;border-radius:999px;font-weight:600;font-size:0.85rem;box-shadow:0 4px 10px rgba(255,105,180,0.06)}

    .contact{width:100%;display:flex;gap:8px;justify-content:center}
    .btn{padding:10px 14px;border-radius:12px;border:0;background:var(--accent);color:white;font-weight:700;cursor:pointer;box-shadow:0 6px 18px rgba(255,106,160,0.18);transition:transform .18s}
    .btn:active{transform:translateY(2px)}

    /* main content */
    .main{padding:6px 12px}
    .card-section{background:transparent;padding:14px;border-radius:12px;margin-bottom:12px}
    .about{font-size:0.98rem;color:#333;line-height:1.5}

    .skills{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px}
    .skill{padding:8px 10px;border-radius:8px;background:linear-gradient(90deg,rgba(255,255,255,0.9),rgba(255,255,255,0.8));font-weight:600;box-shadow:0 6px 12px rgba(0,0,0,0.03)}

    .timeline{display:grid;gap:10px;margin-top:12px}
    .timeline-item{display:flex;gap:12px;align-items:flex-start}
    .dot{width:10px;height:10px;border-radius:50%;background:var(--pink-2);margin-top:6px}

    /* social icons row */
    .social{display:flex;gap:10px;align-items:center}
    .social a{display:inline-flex;padding:10px;border-radius:999px;background:rgba(255,255,255,0.9);box-shadow:0 6px 14px rgba(0,0,0,0.04);text-decoration:none}

    /* floating card accent */
    .accent-blob{position:absolute;right:30px;top:12px;filter:blur(28px);width:160px;height:160px;background:linear-gradient(45deg,var(--pink-2),#ffd1ea);border-radius:50%;opacity:0.25}

    /* responsive */
    @media (max-width:880px){
      .card{grid-template-columns:1fr;}
      .avatar{width:140px;height:140px}
    }
  </style>
</head>
<body>
  <div class="bg-hearts" aria-hidden="true">
    <div class="heart"></div>
    <div class="heart"></div>
    <div class="heart"></div>
    <div class="heart"></div>
    <div class="heart"></div>
  </div>

  <div class="wrap">
    <div class="card">
      <div class="profile">
        <div class="avatar" title="Foto">
          <!-- cute SVG avatar placeholder -->
          <svg viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="avatar">
            <defs>
              <linearGradient id="g" x1="0" x2="1">
                <stop offset="0" stop-color="#fff" stop-opacity="0.35" />
                <stop offset="1" stop-color="#ffd1ea" stop-opacity="0.6" />
              </linearGradient>
            </defs>
            <rect x="0" y="0" width="120" height="120" rx="16" fill="url(#g)" />
            <g transform="translate(20,20)">
              <circle cx="40" cy="28" r="18" fill="#fff" />
              <circle cx="38" cy="30" r="16" fill="#ff9ccf" opacity="0.9" />
              <ellipse cx="40" cy="58" rx="28" ry="18" fill="#fff" opacity="0.9" />
            </g>
          </svg>
        </div>
        <div style="text-align:center">
          <h1>Bunga Ramadhani</h1>
          <div class="role">Kelas 10 RPL 1</div>
        </div>
        </div>

        <div class="contact">
          <button class="btn" onclick="location.href='#contact'">WEB</button>
          <button class="btn" style="background:transparent;color:var(--accent);box-shadow:none;border:2px solid rgba(255,106,160,0.12)" onclick="downloadResume()">PROFILE</button>
        </div>

        <div style="width:100%;text-align:center;margin-top:6px">
          <div class="social">
          </div>
        </div>
      </div>

      <div class="main">
        <div class="card-section about">
          <strong>TENTANG SAYA</strong>
          <p>Saya adalah siswi SMKN 7 Batam, kelas 10 rpl 1. Umur saya 16 tahun,saya adalah anak pertama dari 3 bersaudara. Di umur saya yang sudah 16 tahun, saya sudah mendapatkan beberapa pengalaman, salah satunya saya pernah melakukan perdagangan barang/jasa.</p>
        </div>

        <div class="card-section">
          <h3>KEAHLIAN</h3>
          <div class="skills">
            <div class="skill">Memasak</div>
            <div class="skill">Editing</div>
            <div class="skill">Bermain Gim</div>
            <div class="skill">Ahli Strategi</div>
          </div>
        </div>

        <div class="card-section">
          <h3>RIWAYAT SEKOLAH</h3>
          <div class="timeline">
            <div class="timeline-item"><div class="dot"></div><div><strong>SD NEGERI 06 : 2016 — 2022</strong><div class="muted">Taman Raya</div></div></div>
            <div class="timeline-item"><div class="dot"></div><div><strong>SMP NEGERI 42 : 2022 — 2025</strong><div class="muted">Bida Asri 2</div></div></div>
          </div>
        </div>

        <div class="card-section" id="contact">
          <h3>Kontak</h3>
          <p class="muted">Email : bunga290809@gmail.com</p>
          <p class="muted">Nomor : 0857-9462-1670</p>
          <p class="muted">Instagram : @nra.kze</p>
            </div>
          </form>
        </div>

      </div>

      <div class="accent-blob" aria-hidden="true"></div>
    </div>
  </div>

  <script>
    function downloadResume(){
      // simple demo: create a text resume and trigger download
      const resume = `Bunga Ramadhani\nFrontend Developer & Illustrator\nEmail: email@example.com\n\nRingkasan:\n- Membangun UI interaktif dengan HTML/CSS/JS\n- Ilustrasi sederhana untuk aset digital`;
      const blob = new Blob([resume], {type: 'text/plain'});
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url; a.download = 'Bunga_Ramadhani_CV.txt'; document.body.appendChild(a); a.click(); a.remove();
      URL.revokeObjectURL(url);
    }
  </script>
</body>
</html>
