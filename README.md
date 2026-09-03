
<div align="center">
  <img src="wave-header.svg" width="100%" alt="wersennyy header" />
  <br>
  
  <b>AI • Linux • Network Security • VPN Architect • Programming</b>
<br>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,bash,linux,vim,arduino,git,github,vscode" />
</p>
</div>
<br>
 
## 👤 About Me
### 🖥️ My Tech Profile
*    **Age:** 15-year-old student & tech enthusiast.
*    **Main Goal:** Mastering advanced network architectures, Linux administration, and full-stack development to build secure, scalable open-source projects.
*    **Favorite OS:** Linux (`Ubuntu`, `Debian`).
*    **WM & Ricing:** Crafting custom, polished setups and configurations for `Hyprland`. 
### ⚙️ Core Interests & Focus
*    **Hyprland Customization** — Building and optimizing clean dotfiles, status bars, and desktop environments.
*    **Networking** — Designing high-performance, censorship-resistant routing .
*    **Cybersecurity** — Hardening server environments.
*    **Web Dev** — Creating fast, responsive and pixel-perfect web interfaces.

---

<p align="center">
  <a href="https://www.readmecodegen.com/custom-github-card-generator">
    <img src="https://www.readmecodegen.com/api/github-stats/svg?username=wersennyy" alt="GitHub Stats" width="48%"/>
  </a>
  <a href="https://www.readmecodegen.com/custom-github-card-generator">
    <img src="https://www.readmecodegen.com/api/github-stats/svg?username=wersennyy&cardType=streak" alt="GitHub Stats" width="48%"/>
  </a>
</p>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 430" width="1200" height="430" role="img" aria-labelledby="t d">
  <title id="t">Daily Temperatures solved with a monotonic stack</title>
  <desc id="d">Temperatures 73, 74, 75, 71, 69, 72, 76, 73. Index 2 holds 75 and waits on the stack until index 6 brings 76, so the answer for index 2 is 6 minus 2, which is 4 days. Every index is pushed once and popped once, so the scan costs O(n) time and O(n) memory.</desc>

  <rect width="1200" height="430" rx="12" fill="#0E0E10"/>

  <!-- header -->
  <text x="48" y="56" font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" font-size="26" font-weight="700" fill="#E8FF4A">monotonic stack</text>
  <text x="48" y="88" font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" font-size="20" fill="#8B8B93">739 · Daily Temperatures · how many days until it gets warmer</text>

  <!-- the wait arc, drawn before the cells so the cells stay crisp -->
  <path d="M 316 132 C 316 106, 828 106, 828 132" fill="none" stroke="#E8FF4A" stroke-width="2.5" stroke-linecap="round"/>
  <path d="M 828 132 l -9 -12 l 18 0 z" fill="#E8FF4A"/>
  <!-- подложка разрывает дугу под подписью: без неё линия перечёркивает знак минуса -->
  <rect x="466" y="96" width="212" height="30" fill="#0E0E10"/>
  <text x="572" y="118" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" font-size="22" font-weight="700" fill="#E8FF4A">6 − 2 = 4 days</text>

  <!-- temperature cells: x = 48 + i*128 -->
  <g font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" text-anchor="middle">
    <g>
      <rect x="48" y="140" width="112" height="78" rx="10" fill="#1F1F26"/>
      <text x="104" y="188" font-size="28" fill="#F5F5F5">73</text>
      <text x="104" y="240" font-size="18" fill="#8B8B93">0</text>
    </g>
    <g>
      <rect x="176" y="140" width="112" height="78" rx="10" fill="#1F1F26"/>
      <text x="232" y="188" font-size="28" fill="#F5F5F5">74</text>
      <text x="232" y="240" font-size="18" fill="#8B8B93">1</text>
    </g>
    <g>
      <rect x="304" y="140" width="112" height="78" rx="10" fill="#1F1F26" stroke="#E8FF4A" stroke-width="2.5"/>
      <text x="360" y="188" font-size="28" font-weight="700" fill="#E8FF4A">75</text>
      <text x="360" y="240" font-size="18" fill="#E8FF4A">2</text>
    </g>
    <g>
      <rect x="432" y="140" width="112" height="78" rx="10" fill="#1F1F26"/>
      <text x="488" y="188" font-size="28" fill="#F5F5F5">71</text>
      <text x="488" y="240" font-size="18" fill="#8B8B93">3</text>
    </g>
    <g>
      <rect x="560" y="140" width="112" height="78" rx="10" fill="#1F1F26"/>
      <text x="616" y="188" font-size="28" fill="#F5F5F5">69</text>
      <text x="616" y="240" font-size="18" fill="#8B8B93">4</text>
    </g>
    <g>
      <rect x="688" y="140" width="112" height="78" rx="10" fill="#1F1F26"/>
      <text x="744" y="188" font-size="28" fill="#F5F5F5">72</text>
      <text x="744" y="240" font-size="18" fill="#8B8B93">5</text>
    </g>
    <g>
      <rect x="816" y="140" width="112" height="78" rx="10" fill="#1F1F26" stroke="#E8FF4A" stroke-width="2.5"/>
      <text x="872" y="188" font-size="28" font-weight="700" fill="#E8FF4A">76</text>
      <text x="872" y="240" font-size="18" fill="#E8FF4A">6</text>
    </g>
    <g>
      <rect x="944" y="140" width="112" height="78" rx="10" fill="#1F1F26"/>
      <text x="1000" y="188" font-size="28" fill="#F5F5F5">73</text>
      <text x="1000" y="240" font-size="18" fill="#8B8B93">7</text>
    </g>
  </g>

  <!-- what the stack holds while 75 waits -->
  <text x="48" y="300" font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" font-size="20" fill="#8B8B93">stack keeps indices, temperatures never increase upwards</text>

  <g font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" text-anchor="middle">
    <rect x="48" y="318" width="104" height="52" rx="10" fill="#1F1F26" stroke="#E8FF4A" stroke-width="2"/>
    <text x="100" y="352" font-size="22" fill="#E8FF4A">2 · 75</text>
    <rect x="168" y="318" width="104" height="52" rx="10" fill="#1F1F26"/>
    <text x="220" y="352" font-size="22" fill="#F5F5F5">5 · 72</text>
  </g>
  <text x="292" y="352" font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" font-size="20" fill="#8B8B93">← 76 arrives and pops both</text>

  <!-- the point -->
  <rect x="48" y="392" width="1104" height="2" fill="#1F1F26"/>
  <text x="48" y="424" font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" font-size="22" fill="#F5F5F5">every index is pushed once and popped once <tspan fill="#E8FF4A" font-weight="700">→ O(n) time, O(n) memory</tspan></text>
</svg>

## 🌐 Social Media

<p align="center">
  <a href="https://stepik.org/users/677636941/profile" target="_blank"><img src="Stepik.svg" height="35"alt="Stepik" style="vertical-align: middle;"/></a>
 &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://tiktok.com/@prityxo" target="_blank"><img src="Tiktok.svg" height="45" alt="TikTok" style="vertical-align: middle;"/></a>
   &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;
 <a href="https://t.me/@snown999" target="_blank"><img src="Telegram.svg" height="35" alt="Telegram" style="vertical-align: middle;"/></a>
</p>
<br>

<div align="center">
  <img src="wave-footer.svg" width="100%" alt="wersennyy footer" />
</div>
