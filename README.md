<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>for mon chéri 💖 from fio</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap');

    :root{
      --pink-1:#ffe6f0;
      --pink-2:#ffd8ec;
      --pink-3:#f6d0f5;
      --accent:#d4779e;
      --muted:#6a5c55;
      --card-bg:rgba(255,255,255,0.75);
    }

    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:'Poppins',sans-serif;
      background:radial-gradient(circle at top left,var(--pink-1) 0%,var(--pink-2) 45%,var(--pink-3) 100%);
      color:#333;
      display:flex;
      flex-direction:column;
      align-items:center;
      padding:28px 16px 80px;
      min-height:100vh;
      overflow-x:hidden;
      position:relative;
    }

    .sparkle{
      position:absolute;
      width:4px;height:4px;
      background:rgba(255,255,255,0.9);
      border-radius:50%;
      opacity:0;
      animation:twinkle 4s linear infinite;
      pointer-events:none;
    }
    @keyframes twinkle{
      0%{opacity:0;transform:translateY(0)scale(0.9)}
      40%{opacity:0.9}
      100%{opacity:0;transform:translateY(-8px)scale(1.1)}
    }

    header{text-align:center;margin-bottom:42px;}
    header h1{
      margin:0;
      font-size:2.4rem;
      color:var(--accent);
      letter-spacing:0.6px;
    }
    header p{margin:8px 0 0;color:var(--muted);font-size:1rem;}

    .section{
      width:100%;
      max-width:820px;
      background:var(--card-bg);
      backdrop-filter:blur(10px);
      border-radius:16px;
      padding:22px;
      margin-bottom:26px;
      box-shadow:0 6px 20px rgba(0,0,0,0.08);
      opacity:0;
      transform:translateY(10px);
      animation:appear 0.9s ease forwards;
    }
    @keyframes appear{to{opacity:1;transform:translateY(0)}}

    .section h2{
      margin:0 0 12px 0;
      color:#b75c8f;
      font-size:1.25rem;
      text-align:center;
    }
    .section p{
      margin:0 0 14px 0;
      line-height:1.75;
      color:#4a3f45;
      font-size:1.03rem;
      text-align:justify;
      white-space:pre-line;
    }

    .gallery{
      display:grid;
      grid-template-columns:repeat(2,1fr);
      gap:18px;
      align-items:start;
    }
    .gallery img{
      width:100%;
      height:320px;
      object-fit:cover;
      border-radius:12px;
      box-shadow:0 6px 18px rgba(0,0,0,0.12);
    }
    @media(max-width:760px){
      .gallery{grid-template-columns:1fr;}
      .gallery img{height:220px;}
    }

    .videos{
      display:flex;
      flex-direction:column;
      gap:18px;
      margin-top:18px;
    }
    .videos iframe{
      width:100%;
      height:360px;
      border-radius:12px;
      border:0;
      box-shadow:0 6px 20px rgba(0,0,0,0.12);
    }
    @media(max-width:760px){.videos iframe{height:240px;}}

    .button{
      display:inline-block;
      background:var(--accent);
      color:white;
      padding:10px 20px;
      border-radius:10px;
      border:none;
      cursor:pointer;
      font-weight:600;
      margin-top:10px;
      box-shadow:0 6px 14px rgba(196,86,136,0.12);
    }
    .button[disabled]{opacity:0.7;cursor:default;transform:scale(1);}

    .note{font-size:0.95rem;color:#7a5b70;margin-top:8px;text-align:center;}

    .heart{
      position:fixed;
      bottom:-20px;
      font-size:16px;
      pointer-events:none;
      animation:floatUp 6s linear infinite;
      opacity:0.9;
    }
    @keyframes floatUp{
      0%{transform:translateY(0)scale(1);opacity:1;}
      100%{transform:translateY(-110vh)scale(1.4);opacity:0;}
    }

    .love-footer{
      margin-top:18px;
      text-align:center;
      color:#c86b96;
      font-weight:600;
      font-size:1.05rem;
    }
  </style>
</head>
<body>

<script>
  for(let i=0;i<30;i++){
    const s=document.createElement('div');
    s.className='sparkle';
    s.style.left=Math.random()*100+'%';
    s.style.top=Math.random()*100+'%';
    s.style.animationDelay=(Math.random()*4)+'s';
    document.body.appendChild(s);
  }
</script>

<header>
  <h1>for mon chéri 💖 from fio</h1>
  <p>i love u to the moon and back 🌙</p>
</header>

<div class="section" style="animation-delay:0.2s">
  <h2>thiz is especially for u (｡•̀ᴗ-)✧</h2>
  <p>aa, dede cuma pengen bilang sesuatu ... (isi teksmu sama seperti sebelumnya di sini ya, ga aku ubah 💌)</p>
</div>

<div class="section" style="animation-delay:0.4s">
  <h2>Galeri Kenangan</h2>

  <div class="gallery">
    <img src="1760808574089.jpg" alt="Foto 1">
    <img src="1760808637823.jpg" alt="Foto 2">
  </div>

  <p style="text-align:center;font-style:italic;color:#665b57;margin-top:14px;">Setiap foto punya cerita, dan dede pengen kita selalu inget momen indah ini.</p>

  <div class="videos">
    <iframe src="https://www.youtube.com/embed/51zi3QANUWE?autoplay=1&mute=1&loop=1&playlist=51zi3QANUWE" allow="autoplay; encrypted-media; picture-in-picture" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/7zKIvM-M-yU?autoplay=1&mute=1&loop=1&playlist=7zKIvM-M-yU" allow="autoplay; encrypted-media; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>

<div class="section" style="animation-delay:0.6s">
  <h2>message to my universe</h2>
  <p>hai sayang, i want to tell you something : aa orang yang hebat bangett ... dede bobo yaaa 🤍</p>
</div>

<div class="section" style="animation-delay:0.8s;text-align:center;">
  <h2>Lagu Kita</h2>
  <p><strong>A Thousand Years</strong> — Christina Perri 🎶</p>

  <button class="button" id="playMusic">Putar Lagu</button>
  <div class="note" id="note">(kalau autoplay diblokir, klik tombol atau layar)</div>

  <p class="love-footer">I love u to the moon and back, sayang. 🌙💖</p>
</div>

<audio id="bgMusic" loop>
  <source src="Christina Perri - A Thousand Years Official Music Video.mp3" type="audio/mpeg">
</audio>

<script>
  const btn=document.getElementById('playMusic');
  const music=document.getElementById('bgMusic');
  const note=document.getElementById('note');

  function fadeInMusicOnce(){
    music.volume=0;
    music.play().then(()=>{
      let v=0;
      const t=setInterval(()=>{
        v+=0.02;music.volume=Math.min(v,1);
        if(v>=1)clearInterval(t);
      },200);
      btn.textContent='🎵 Sedang Berjalan...';
      btn.disabled=true;
      note.textContent='(lagu sudah diputar 🎶)';
    }).catch(()=>{
      note.textContent='(browser memblokir autoplay — klik lagi)';
    });
  }
  btn.addEventListener('click',fadeInMusicOnce);
  document.body.addEventListener('click',function once(){
    if(!music.paused)return;
    fadeInMusicOnce();
    document.body.removeEventListener('click',once);
  },{once:true});

  function createHeart(){
    const h=document.createElement('div');
    h.className='heart';
    h.textContent='💖';
    h.style.left=Math.random()*90+'vw';
    h.style.fontSize=(10+Math.random()*20)+'px';
    h.style.animationDuration=(4+Math.random()*4)+'s';
    document.body.appendChild(h);
    setTimeout(()=>h.remove(),8000);
  }
  setInterval(createHeart,700);
</script>

</body>
</html>
