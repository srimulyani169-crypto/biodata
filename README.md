# biodata<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sri Mulyani - Biodata</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Playfair+Display:ital,wght@1,500&display=swap" rel="stylesheet">
<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
  body{
    min-height:100vh;
    background:#fff0f5;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:20px;
    overflow:hidden;
    position:relative;
  }
  /* bunga background */
  .flower{
    position:absolute;
    font-size:20px;
    opacity:0.5;
    animation: float 6s infinite ease-in-out;
  }
  @keyframes float {
    0%,100%{transform:translateY(0) rotate(0deg)}
    50%{transform:translateY(-20px) rotate(10deg)}
  }
  .card{
    background:rgba(255,255,255,0.85);
    backdrop-filter: blur(12px);
    width:100%;
    max-width:360px;
    border-radius:32px;
    padding:32px 28px;
    border:1.5px solid #ffc2d1;
    box-shadow: 0 20px 50px rgba(255,105,148,0.18);
    text-align:center;
    position:relative;
    z-index:2;
  }
  .top-decor{
    font-family:'Playfair Display', serif;
    color:#ff8fab;
    font-size:14px;
    letter-spacing:3px;
    margin-bottom:10px;
  }
  .avatar{
    width:100px;height:100px;
    margin:0 auto 15px;
    border-radius:50%;
    background: linear-gradient(135deg, #ffc2d1, #ff8fab);
    padding:3px;
  }
  .avatar-inner{
    width:100%;height:100%;
    background:white;
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:45px;
  }
  h1{
    font-family:'Playfair Display', serif;
    color:#d93a6a;
    font-size:26px;
    font-style:italic;
  }
  .divider{
    width:40px;height:3px;
    background:#ffc2d1;
    margin:8px auto 18px;
    border-radius:10px;
  }
  .info{
    background: white;
    border-radius:18px;
    padding:6px 16px;
    border:1px solid #ffe4ec;
  }
  .row{
    display:flex;
    align-items:center;
    gap:12px;
    padding:13px 0;
    border-bottom:1px dashed #ffc2d1;
    text-align:left;
  }
  .row:last-child{border:none}
  .icon{
    width:32px;height:32px;
    background:#fff0f5;
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:14px;
    flex-shrink:0;
  }
  .label{font-size:10px;color:#ff8fab;letter-spacing:1px;text-transform:uppercase;font-weight:600}
  .value{font-size:14px;color:#5e3540;font-weight:500}
  .tag{
    margin-top:20px;
    display:inline-block;
    background:#ff8fab;
    color:white;
    font-size:11px;
    padding:6px 14px;
    border-radius:50px;
    letter-spacing:1px;
  }
</style>
</head>
<body>

<!-- Bunga-bunga jatuh aesthetic -->
<span class="flower" style="top:10%; left:15%; animation-delay:0s">🌸</span>
<span class="flower" style="top:20%; right:12%; animation-delay:1s">🌷</span>
<span class="flower" style="top:75%; left:10%; animation-delay:2s">💮</span>
<span class="flower" style="top:80%; right:15%; animation-delay:0.5s">🌸</span>
<span class="flower" style="top:5%; right:30%; animation-delay:1.5s">🌼</span>
<span class="flower" style="bottom:15%; left:30%; animation-delay:2.5s">🌺</span>

<div class="card">
  <p class="top-decor">✿ MY BIODATA ✿</p>
  
  <div class="avatar">
    <div class="avatar-inner">🌸</div>
  </div>

  <h1>Sri Mulyani</h1>
  <div class="divider"></div>

  <div class="info">
    <div class="row">
      <div class="icon">🏫</div>
      <div>
        <div class="label">Sekolah</div>
        <div class="value">SMK Banjar Asri</div>
      </div>
    </div>
    <div class="row">
      <div class="icon">📚</div>
      <div>
        <div class="label">Kelas</div>
        <div class="value">X TJKT 1</div>
      </div>
    </div>
    <div class="row">
      <div class="icon">📍</div>
      <div>
        <div class="label">Alamat</div>
        <div class="value">Gamblok</div>
      </div>
    </div>
  </div>

  <span class="tag">🌷 pink blossom aesthetic 🌷</span>
</div>

</body>
</html>
