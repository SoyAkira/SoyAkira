<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
    }

    body{
        background:#0d1117;
        font-family:'Inter',sans-serif;
        color:#c9d1d9;
        display:flex;
        justify-content:center;
        align-items:center;
        min-height:100vh;
        padding:20px;
    }

    .card{
        width:520px;
        background:#0d1117;
        border:1px solid #30363d;
        border-radius:14px;
        padding:22px;
        box-shadow:0 0 0 1px rgba(255,255,255,0.02);
    }

    .top{
        display:flex;
        justify-content:space-between;
        gap:20px;
    }

    .profile{
        flex:1;
    }

    .username{
        color:#58a6ff;
        font-size:34px;
        font-weight:700;
        margin-bottom:8px;
    }

    .line{
        display:flex;
        align-items:center;
        gap:10px;
        margin-bottom:8px;
        font-size:15px;
        color:#8b949e;
    }

    .stats{
        margin-top:18px;
        display:grid;
        grid-template-columns:1fr;
        gap:10px;
    }

    .stat{
        display:flex;
        align-items:center;
        gap:10px;
        color:#c9d1d9;
        font-size:15px;
    }

    .stat a{
        color:#58a6ff;
        text-decoration:none;
    }

    .stat a:hover{
        text-decoration:underline;
    }

    .right{
        width:220px;
    }

    .contrib{
        display:flex;
        gap:4px;
        flex-wrap:wrap;
        margin-bottom:18px;
        justify-content:flex-start;
    }

    .box{
        width:14px;
        height:14px;
        border-radius:3px;
        background:#161b22;
        border:1px solid rgba(255,255,255,0.04);
    }

    .lvl1{ background:#0e4429; }
    .lvl2{ background:#006d32; }
    .lvl3{ background:#26a641; }
    .lvl4{ background:#39d353; }

    .languages{
        margin-top:30px;
    }

    .lang-title{
        color:#58a6ff;
        font-size:14px;
        text-align:center;
        margin-bottom:10px;
    }

    .bar{
        width:100%;
        height:10px;
        border-radius:999px;
        overflow:hidden;
        display:flex;
        background:#161b22;
        margin-bottom:12px;
    }

    .seg{ height:100%; }

    .kotlin{ width:42%; background:#A97BFF; }
    .typescript{ width:18%; background:#3178c6; }
    .css{ width:12%; background:#8b5cf6; }
    .javascript{ width:10%; background:#f1e05a; }
    .php{ width:8%; background:#4F5D95; }
    .stylus{ width:4%; background:#ff6347; }
    .vue{ width:3%; background:#41b883; }
    .html{ width:3%; background:#e34c26; }

    .legend{
        display:flex;
        flex-wrap:wrap;
        gap:14px;
        justify-content:center;
    }

    .legend-item{
        display:flex;
        align-items:center;
        gap:6px;
        font-size:12px;
        color:#8b949e;
    }

    .dot{
        width:9px;
        height:9px;
        border-radius:50%;
    }

    .icon{
        width:16px;
        text-align:center;
        opacity:0.8;
    }
</style>
</head>
<body>

<div class="card">

  <div class="top">

  <div class="profile">

  <h1 class="username">Soitora</h1>

  <div class="line">
                <span class="icon">🕒</span>
                <span>Joined GitHub 11 years ago</span>
            </div>

  <div class="line">
                <span class="icon">👥</span>
                <span>Followed by 509 users</span>
            </div>

  <div class="stats">

  <div class="stat">
                    <span>📈</span>
                    <a href="#">Activity</a>
                </div>

  <div class="stat">
                    <span>📝</span>
                    <span>10961 Commits</span>
                </div>

  <div class="stat">
                    <span>🔀</span>
                    <span>3 Pull requests reviewed</span>
                </div>

  <div class="stat">
                    <span>📦</span>
                    <span>5 Pull requests opened</span>
  </div>

   <div class="stat">
                    <span>⚠️</span>
                    <span>6 Issues opened</span>
                </div>

  <div class="stat">
                    <span>💬</span>
                    <span>883 issue comments</span>
                </div>

   <div class="stat">
                    <span>📁</span>
                    <a href="#">24 Repositories (including 7 forks)</a>
                </div>

  <div class="stat">
                    <span>🏷️</span>
                    <span>Prefers MPL-2.0 license</span>
                </div>

  <div class="stat">
                    <span>🚀</span>
                    <span>24 Releases</span>
                </div>

<div class="stat">
                    <span>📦</span>
                    <span>1 Package</span>
                </div>

   <div class="stat">
                    <span>⌨️</span>
                    <span>1.27 GB used</span>
                </div>

 <div class="stat">
                    <span>➕</span>
                    <span>0 added, 0 removed</span>
                </div>

  </div>

  </div>

  <div class="right">

  <div class="contrib">
                <div class="box lvl4"></div>
                <div class="box lvl3"></div>
                <div class="box lvl2"></div>
                <div class="box lvl3"></div>
                <div class="box"></div>
                <div class="box"></div>
                <div class="box lvl2"></div>
                <div class="box lvl3"></div>
                <div class="box lvl3"></div>
                <div class="box lvl4"></div>
                <div class="box lvl3"></div>
                <div class="box lvl2"></div>
                <div class="box"></div>
                <div class="box"></div>
            </div>

<div class="stats">

  <div class="stat">
                    <span>📤</span>
                    <span>Contributed to 11 repositories</span>
                </div>

<div class="stat">
                    <span>📊</span>
                    <a href="#">Community stats</a>
                </div>

 <div class="stat">
                    <span>🏢</span>
                    <span>Member of 4 organizations</span>
                </div>

 <div class="stat">
                    <span>👤</span>
                    <span>Following 5 users</span>
                </div>
 <div class="stat">
                    <span>❤️</span>
                    <span>Sponsoring 1 repository</span>
                </div>

   <div class="stat">
                    <span>⭐</span>
                    <span>Starred 196 repositories</span>
                </div>

   <div class="stat">
                    <span>👀</span>
                    <span>Watching 26 repositories</span>
                </div>

 <div class="stat">
                    <span>❤️</span>
                    <span>1 Sponsor</span>
                </div>

   <div class="stat">
                    <span>⭐</span>
                    <span>49 Stargazers</span>
                </div>

  <div class="stat">
                    <span>🍴</span>
                    <span>9 Forkers</span>
                </div>

<div class="stat">
                    <span>👁️</span>
                    <span>10 Watchers</span>
                </div>

</div>

 </div>

   </div>

   <div class="languages">

  <div class="lang-title">
            Most used languages
        </div>

   <div class="bar">
            <div class="seg kotlin"></div>
            <div class="seg typescript"></div>
            <div class="seg css"></div>
            <div class="seg javascript"></div>
            <div class="seg php"></div>
            <div class="seg stylus"></div>
            <div class="seg vue"></div>
            <div class="seg html"></div>
        </div>

  <div class="legend">

<div class="legend-item">
                <div class="dot kotlin"></div>
                Kotlin
            </div>

   <div class="legend-item">
                <div class="dot typescript"></div>
                TypeScript
            </div>

  <div class="legend-item">
                <div class="dot css"></div>
                CSS
            </div>

  <div class="legend-item">
                <div class="dot javascript"></div>
                JavaScript
            </div>

  <div class="legend-item">
                <div class="dot php"></div>
                PHP
            </div>

 <div class="legend-item">
                <div class="dot stylus"></div>
                Stylus
            </div>

 <div class="legend-item">
                <div class="dot vue"></div>
                Vue
            </div>

   <div class="legend-item">
                <div class="dot html"></div>
                HTML
            </div>

  </div>

  </div>

</div>
