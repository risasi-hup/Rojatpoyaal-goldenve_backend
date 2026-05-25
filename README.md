## RISASIMANI Token

- **Adı:** RISASIMANI
- **Sembol:** RSM
- **Adres:** `0x081D7F84933076b63EEDd5dB91dD81bb60561759`
- **Logo:** `/assets/rsm_logo.png`
schema_version: 1
name: risasimani
version: "1.0.0"
description: "RISASIMANI token plugin"
author:
  name: "Rojat"
  github: "rojat"
license: MIT
category: utility
tags:
  - token
components:
  skill:
    dir: "."
icon: "assets/rsm_logo.png"
api_calls: []
skills/risasimani/assets/rsm_logo.png
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Token Logoları</title>
  <style>
    .logo-animate {
      width: 120px;
      margin: 16px;
      border-radius: 10px;
      transition: transform 0.3s;
      animation: pulse 2s infinite;
    }
    .logo-animate:hover {
      transform: scale(1.11) rotate(-4deg);
      box-shadow: 0 0 12px #ffaa0080;
    }
    @keyframes pulse {
      0% { filter: brightness(1) drop-shadow(0 0 0px #f6ae2d);}
      50% { filter: brightness(1.16) drop-shadow(0 0 18px #f6ae2d);}
      100% { filter: brightness(1) drop-shadow(0 0 0px #f6ae2d);}
    }
    .token-label {
      font-weight: bold;
      text-align: center;
      display: block;
      margin-bottom: 4px;
    }
  </style>
</head>
<body>
  <h2>Token Logoları</h2>
  <div style="display: flex; gap: 48px;">
    <div>
      <span class="token-label">RISASIMANI (RSM)</span>
      <img src="/assets/rsm_logo.png" alt="RISASIMANI Logo" class="logo-animate" />
    </div>
    <div>
      <span class="token-label">RASEM</span>
      <img src="/assets/rasem_logo.png" alt="RASEM Logo" class="logo-animate" />
    </div>
  </div>
</body>
</html><img src="/assets/rsm_logo.png" alt="RISASIMANI" className="logo-animate" />
<img src="/assets/rasem_logo.png" alt="RASEM" className="logo-animate" />
