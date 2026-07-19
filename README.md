<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>hani ✦</title>
<link href="https://fonts.googleapis.com/css2?family=Space+Mono:ital,wght@0,400;0,700;1,400&family=Nunito:wght@400;600;700;800&family=Dancing+Script:wght@600&display=swap" rel="stylesheet">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: #d4e8d0;
    background-image:
      radial-gradient(circle at 20% 20%, #c8e6c9 0%, transparent 50%),
      radial-gradient(circle at 80% 80%, #b2d8b2 0%, transparent 50%);
    min-height: 100vh;
    font-family: 'Nunito', sans-serif;
    overflow-x: hidden;
    padding: 20px;
  }

  .desktop {
    position: relative;
    width: 100%;
    max-width: 900px;
    min-height: 600px;
    margin: 0 auto;
  }

  .window {
    position: absolute;
    background: rgba(255,255,255,0.92);
    border-radius: 12px;
    border: 1px solid rgba(255,255,255,0.8);
    box-shadow: 0 4px 20px rgba(0,0,0,0.12), 0 1px 4px rgba(0,0,0,0.08);
    overflow: hidden;
  }

  .titlebar {
    background: #ececec;
    padding: 7px 12px;
    display: flex;
    align-items: center;
    gap: 7px;
    border-bottom: 1px solid #ddd;
  }

  .dot {
    width: 12px; height: 12px;
    border-radius: 50%;
    flex-shrink: 0;
  }
  .dot.red { background: #ff6057; }
  .dot.yellow { background: #ffbd2e; }
  .dot.green { background: #28c841; }

  .titlebar-label {
    font-size: 12px;
    color: #666;
    font-family: 'Space Mono', monospace;
    margin-left: 4px;
    flex: 1;
    text-align: center;
  }

  .window-body { padding: 14px; }

  .sticker {
    position: absolute;
    font-size: 22px;
    transform: rotate(-8deg);
    user-select: none;
    filter: drop-shadow(0 2px 4px rgba(0,0,0,0.15));
    z-index: 20;
  }

  .handwriting {
    font-family: 'Dancing Script', cursive;
    color: #5a5a7a;
  }

  .badge {
    display: inline-block;
    padding: 3px 10px;
    border-radius: 20px;
    font-size: 11px;
    font-weight: 700;
    margin: 2px 2px;
  }

  .photo-frame {
    border: 3px solid white;
    border-radius: 4px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.18);
    overflow: hidden;
    display: inline-block;
  }

  .avatar-placeholder {
    background: linear-gradient(135deg, #f9c6d0, #d4b8e0);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 28px;
    color: white;
    font-weight: 800;
  }

  .note-paper {
    background: #fffde7;
    border-left: 3px solid #ffd54f;
    padding: 8px 10px;
    border-radius: 2px;
    font-size: 12px;
    color: #5d4037;
    font-family: 'Space Mono', monospace;
    line-height: 1.6;
  }

  .ios-notif {
    background: rgba(255,255,255,0.96);
    border-radius: 14px;
    padding: 10px 14px;
    border: 1px solid #e0e0e0;
    box-shadow: 0 2px 12px rgba(0,0,0,0.12);
  }

  .tag-cloud { display: flex; flex-wrap: wrap; gap: 4px; margin-top: 6px; }

  .wname {
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    color: #999;
    letter-spacing: 0.5px;
  }
</style>
</head>
<body>

<div class="desktop">

  <!-- BIG NAME top right -->
  <div style="position:absolute; top:0; right:10px; z-index:5; text-align:right; line-height:1;">
    <div style="font-family:'Space Mono',monospace; font-size:52px; font-weight:700; color:rgba(255,255,255,0.6); letter-spacing:-2px; text-shadow: 1px 1px 0 rgba(100,150,100,0.3);">hani</div>
  </div>

  <!-- Main Photo Booth window -->
  <div class="window" style="left:120px; top:10px; width:340px; z-index:10;">
    <div class="titlebar">
      <div class="dot red"></div>
      <div class="dot yellow"></div>
      <div class="dot green"></div>
      <div class="titlebar-label">Photo Booth</div>
    </div>
    <div style="background:#1a1a1a; padding:16px; text-align:center;">
      <div class="photo-frame" style="width:280px; height:210px;">
        <div class="avatar-placeholder" style="width:280px; height:210px; font-size:60px;">H</div>
      </div>
      <div style="margin-top:10px; display:flex; justify-content:center; gap:8px;">
        <div class="photo-frame" style="width:72px; height:54px;">
          <div class="avatar-placeholder" style="width:72px; height:54px; font-size:18px;">✦</div>
        </div>
        <div class="photo-frame" style="width:72px; height:54px;">
          <div class="avatar-placeholder" style="width:72px; height:54px; font-size:18px; background:linear-gradient(135deg,#b8d4e0,#c8b0d8);">:)</div>
        </div>
        <div class="photo-frame" style="width:72px; height:54px;">
          <div class="avatar-placeholder" style="width:72px; height:54px; font-size:18px; background:linear-gradient(135deg,#d0e8b8,#b8d4a0);">&lt;3</div>
        </div>
      </div>
      <div style="margin-top:10px;">
        <div style="width:50px; height:50px; background:#ff3b30; border-radius:50%; margin:0 auto; display:flex; align-items:center; justify-content:center; box-shadow:0 0 0 4px rgba(255,59,48,0.25);">
          <div style="width:20px; height:20px; background:white; border-radius:50%;"></div>
        </div>
      </div>
    </div>
  </div>

  <!-- About me / finder window -->
  <div class="window" style="left:0; top:10px; width:200px; z-index:8;">
    <div class="titlebar">
      <div class="dot red"></div>
      <div class="dot yellow"></div>
      <div class="dot green"></div>
      <div class="titlebar-label">README.md</div>
    </div>
    <div class="window-body">
      <div style="font-size:13px; font-weight:800; color:#333; margin-bottom:4px;">hani</div>
      <div style="font-size:11px; color:#888; font-family:'Space Mono',monospace; margin-bottom:8px;">she/her · creative dev</div>
      <div style="font-size:11px; color:#555; line-height:1.6; margin-bottom:8px;">
        building things that feel as good as they look. art + code + curiosity.
      </div>
      <div style="font-size:10px; color:#aaa; font-family:'Space Mono',monospace; border-top:1px solid #eee; padding-top:6px; margin-top:4px;">
        <div>📍 somewhere creative</div>
        <div style="margin-top:3px;">⏰ always coding</div>
      </div>
    </div>
  </div>

  <!-- Skills window -->
  <div class="window" style="left:0; top:230px; width:200px; z-index:8;">
    <div class="titlebar">
      <div class="dot red"></div>
      <div class="dot yellow"></div>
      <div class="dot green"></div>
      <div class="titlebar-label">skills.txt</div>
    </div>
    <div class="window-body">
      <div class="tag-cloud">
        <span class="badge" style="background:#dde8ff; color:#3356b3;">Python</span>
        <span class="badge" style="background:#fff0cc; color:#b37000;">JS</span>
        <span class="badge" style="background:#d9f0ff; color:#006b99;">React</span>
        <span class="badge" style="background:#ffe0ec; color:#b3004a;">Figma</span>
        <span class="badge" style="background:#e0f5e0; color:#1a7a1a;">Node</span>
        <span class="badge" style="background:#f0d9ff; color:#6a00b3;">CSS</span>
        <span class="badge" style="background:#ffd9cc; color:#b33300;">SQL</span>
        <span class="badge" style="background:#d9fff0; color:#007a50;">p5.js</span>
        <span class="badge" style="background:#fff0d9; color:#b36a00;">Adobe</span>
        <span class="badge" style="background:#dde8ff; color:#3356b3;">Git</span>
      </div>
    </div>
  </div>

  <!-- Notification / reminder -->
  <div class="ios-notif" style="position:absolute; right:10px; top:70px; width:180px; z-index:15;">
    <div style="font-size:10px; font-weight:700; color:#555; margin-bottom:4px;">Reminder</div>
    <div style="font-size:12px; color:#333;">you're gonna be alright.</div>
    <div style="margin-top:8px; display:flex; justify-content:flex-end;">
      <div style="background:#007aff; color:white; font-size:11px; font-weight:700; padding:4px 14px; border-radius:8px; cursor:pointer;">okay ♡</div>
    </div>
  </div>

  <!-- AirDrop style bubble -->
  <div class="ios-notif" style="position:absolute; right:10px; top:190px; width:180px; z-index:15;">
    <div style="display:flex; align-items:center; gap:8px; margin-bottom:6px;">
      <div style="width:30px; height:30px; border-radius:50%; background:linear-gradient(135deg,#34c759,#30b0c7); display:flex; align-items:center; justify-content:center; font-size:14px;">✈</div>
      <div>
        <div style="font-size:11px; font-weight:700; color:#333;">AirDrop</div>
        <div style="font-size:10px; color:#888;">a vibe to share</div>
      </div>
    </div>
    <div style="display:flex; gap:6px; justify-content:flex-end;">
      <div style="background:#efefef; color:#333; font-size:11px; font-weight:700; padding:4px 10px; border-radius:8px;">decline</div>
      <div style="background:#007aff; color:white; font-size:11px; font-weight:700; padding:4px 10px; border-radius:8px;">accept</div>
    </div>
  </div>

  <!-- Projects window -->
  <div class="window" style="left:120px; top:350px; width:340px; z-index:10;">
    <div class="titlebar">
      <div class="dot red"></div>
      <div class="dot yellow"></div>
      <div class="dot green"></div>
      <div class="titlebar-label">projects</div>
    </div>
    <div class="window-body" style="padding:10px 14px;">
      <div style="display:grid; grid-template-columns:1fr 1fr; gap:8px;">
        <div style="background:#f8f0ff; border:1px solid #e0c8ff; border-radius:8px; padding:8px;">
          <div style="font-size:11px; font-weight:800; color:#6a00b3;">◈ portfolio</div>
          <div style="font-size:10px; color:#888; margin-top:2px;">visual experiments</div>
          <div style="font-size:10px; color:#aaa; margin-top:4px;">JS · ★12</div>
        </div>
        <div style="background:#f0f8ff; border:1px solid #c0d8ff; border-radius:8px; padding:8px;">
          <div style="font-size:11px; font-weight:800; color:#0055b3;">◈ generative-art</div>
          <div style="font-size:10px; color:#888; margin-top:2px;">chaotic & beautiful</div>
          <div style="font-size:10px; color:#aaa; margin-top:4px;">Python · ★8</div>
        </div>
        <div style="background:#f0fff4; border:1px solid #b8e8c8; border-radius:8px; padding:8px;">
          <div style="font-size:11px; font-weight:800; color:#006b33;">◈ data-stories</div>
          <div style="font-size:10px; color:#888; margin-top:2px;">CSV in, beauty out</div>
          <div style="font-size:10px; color:#aaa; margin-top:4px;">Python · ★6</div>
        </div>
        <div style="background:#fff8f0; border:1px solid #ffd8b0; border-radius:8px; padding:8px;">
          <div style="font-size:11px; font-weight:800; color:#b35000;">◈ ui-experiments</div>
          <div style="font-size:10px; color:#888; margin-top:2px;">pure front-end joy</div>
          <div style="font-size:10px; color:#aaa; margin-top:4px;">CSS · ★19</div>
        </div>
      </div>
    </div>
  </div>

  <!-- Note paper -->
  <div class="note-paper" style="position:absolute; right:10px; top:320px; width:180px; z-index:12; transform:rotate(2deg);">
    find me:<br>
    ✦ behance<br>
    ✦ linkedin<br>
    ✦ instagram<br>
    <br>
    <span style="color:#aaa; font-size:10px;">— made with intention</span>
  </div>

  <!-- Handwriting label -->
  <div class="handwriting" style="position:absolute; left:130px; top:330px; font-size:22px; color:#8a6a9a; z-index:20; transform:rotate(-3deg);">
    sweety ♡
  </div>

  <!-- Stickers scattered -->
  <div class="sticker" style="left:80px; top:180px; font-size:28px; transform:rotate(10deg);">🎀</div>
  <div class="sticker" style="left:420px; top:40px; font-size:24px; transform:rotate(-5deg);">⭐</div>
  <div class="sticker" style="right:200px; top:310px; font-size:20px; transform:rotate(8deg);">🩷</div>
  <div class="sticker" style="left:65px; top:430px; font-size:20px; transform:rotate(-12deg);">✨</div>
  <div class="sticker" style="left:470px; top:320px; font-size:18px; transform:rotate(6deg);">🌸</div>

  <!-- On / Off toggle pill -->
  <div style="position:absolute; right:10px; top:0; z-index:20;">
    <div style="background:rgba(255,255,255,0.85); border-radius:20px; border:1px solid #ddd; display:flex; overflow:hidden; font-family:'Space Mono',monospace; font-size:12px; font-weight:700;">
      <div style="padding:5px 18px; background:#333; color:white;">On</div>
      <div style="padding:5px 18px; color:#999;">Off</div>
    </div>
  </div>

  <!-- Bottom spacer for absolute layout -->
  <div style="height:560px;"></div>

</div>

<!-- Dock -->
<div style="position:sticky; bottom:16px; left:0; right:0; display:flex; justify-content:center; margin-top:20px;">
  <div style="background:rgba(255,255,255,0.55); border:1px solid rgba(255,255,255,0.8); border-radius:18px; padding:8px 16px; display:flex; gap:10px; backdrop-filter:blur(10px);">
    <div style="width:44px; height:44px; background:#1c1c1e; border-radius:12px; display:flex; align-items:center; justify-content:center; font-size:22px;">🖥</div>
    <div style="width:44px; height:44px; background:linear-gradient(135deg,#007aff,#34c759); border-radius:12px; display:flex; align-items:center; justify-content:center; font-size:22px;">📁</div>
    <div style="width:44px; height:44px; background:linear-gradient(135deg,#ff9500,#ff3b30); border-radius:12px; display:flex; align-items:center; justify-content:center; font-size:22px;">🎨</div>
    <div style="width:44px; height:44px; background:linear-gradient(135deg,#5856d6,#af52de); border-radius:12px; display:flex; align-items:center; justify-content:center; font-size:22px;">✦</div>
    <div style="width:44px; height:44px; background:linear-gradient(135deg,#30b0c7,#34c759); border-radius:12px; display:flex; align-items:center; justify-content:center; font-size:22px;">💻</div>
  </div>
</div>

</body>
</html>
