
<style>
@keyframes blink{0%,100%{opacity:1}49%{opacity:1}50%,99%{opacity:0}}
@keyframes fadeUp{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:translateY(0)}}
@keyframes s1{0%,100%{animation-timing-function:cubic-bezier(.5,0,1,.5)}0%{transform:scaleY(1)}50%{transform:scaleY(.6);animation-timing-function:cubic-bezier(0,.5,.5,1)}100%{transform:scaleY(1)}}
</style>
<h2 class="sr-only">GitHub Profile README redesign preview for Minta1234 — terminal dark aesthetic with orange accents, about me code block, tech stack, and GitHub stats</h2>

<div style="background:var(--color-background-secondary);border-radius:var(--border-radius-lg);border:0.5px solid var(--color-border-tertiary);overflow:hidden;padding:10px;">

  <!-- Browser chrome -->
  <div style="background:#161b22;border-radius:8px 8px 0 0;padding:9px 14px;display:flex;align-items:center;gap:6px;border-bottom:1px solid #30363d;">
    <div style="width:10px;height:10px;border-radius:50%;background:#ff5f57;flex-shrink:0;"></div>
    <div style="width:10px;height:10px;border-radius:50%;background:#febc2e;flex-shrink:0;"></div>
    <div style="width:10px;height:10px;border-radius:50%;background:#28ca41;flex-shrink:0;"></div>
    <div style="flex:1;background:#0d1117;border-radius:4px;padding:4px 12px;margin:0 8px;font-size:10px;color:#6e7681;font-family:monospace;">
      github.com/<span style="color:#e6edf3;">Minta1234</span>/<span style="color:#6e7681;">Minta1234</span>
    </div>
    <div style="font-size:10px;color:#6e7681;font-family:monospace;flex-shrink:0;">README.md</div>
  </div>

  <!-- GitHub dark page -->
  <div style="background:#0d1117;border-radius:0 0 8px 8px;padding:22px 24px;color:#e6edf3;font-family:'IBM Plex Mono',monospace;">

    <!-- ─── HEADER ─── -->
    <div style="text-align:center;margin-bottom:22px;">
      <div style="margin-bottom:14px;">
        <div style="font-size:23px;font-weight:700;color:#F97316;letter-spacing:-0.3px;line-height:1.4;">
          Hi! I'm Minta 👋<span style="animation:blink 1.1s step-end infinite;color:#F97316;"> ▋</span>
        </div>
        <div style="font-size:12px;color:#8b949e;margin-top:4px;letter-spacing:0.5px;">Embedded &nbsp;·&nbsp; Web &nbsp;·&nbsp; AI Dev</div>
        <div style="font-size:11px;color:#6e7681;margin-top:2px;">Always building something 🔧</div>
      </div>

      <!-- Badge pills -->
      <div style="display:flex;justify-content:center;gap:6px;flex-wrap:wrap;">
        <div style="display:inline-flex;align-items:center;gap:5px;background:#1a1e24;border:1px solid #F97316;color:#F97316;font-size:10px;padding:3px 10px;border-radius:20px;font-family:monospace;">
          <span style="width:5px;height:5px;border-radius:50%;background:#F97316;display:inline-block;"></span>
          1.2k Profile Views
        </div>
        <div style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:3px 10px;border-radius:20px;font-family:monospace;">📍 Thailand</div>
        <div style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:3px 10px;border-radius:20px;font-family:monospace;">🌐 minta0077.online</div>
        <div style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:3px 10px;border-radius:20px;font-family:monospace;">🎵 @minta1826</div>
      </div>
    </div>

    <!-- Divider -->
    <div style="border-top:1px solid #21262d;margin:0 0 20px;"></div>

    <!-- ─── ABOUT ─── -->
    <div style="margin-bottom:20px;">
      <div style="font-size:10px;font-weight:700;color:#F97316;letter-spacing:3px;text-transform:uppercase;margin-bottom:10px;display:flex;align-items:center;gap:8px;">
        <span style="white-space:nowrap;">// About Me</span>
        <div style="flex:1;height:1px;background:#21262d;"></div>
      </div>
      <div style="background:#161b22;border:1px solid #21262d;border-left:2px solid #F97316;border-radius:0 4px 4px 0;padding:12px 16px;font-size:11px;line-height:2.1;font-family:'IBM Plex Mono',monospace;">
        <span style="color:#6e7681;">01 </span><span style="color:#ff7b72;">const</span> <span style="color:#79c0ff;">minta</span> <span style="color:#e6edf3;">=</span> {<br>
        <span style="color:#6e7681;">02 </span>&nbsp;&nbsp;<span style="color:#79c0ff;">role</span><span style="color:#e6edf3;">:</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#a5d6ff;">"Embedded / Web / AI Developer"</span><span style="color:#e6edf3;">,</span><br>
        <span style="color:#6e7681;">03 </span>&nbsp;&nbsp;<span style="color:#79c0ff;">location</span><span style="color:#e6edf3;">:</span>&nbsp;<span style="color:#a5d6ff;">"Thailand 🇹🇭"</span><span style="color:#e6edf3;">,</span><br>
        <span style="color:#6e7681;">04 </span>&nbsp;&nbsp;<span style="color:#79c0ff;">passion</span><span style="color:#e6edf3;">:</span>&nbsp;&nbsp;[<span style="color:#a5d6ff;">"Robotics"</span><span style="color:#e6edf3;">,</span> <span style="color:#a5d6ff;">"AI/ML"</span><span style="color:#e6edf3;">,</span> <span style="color:#a5d6ff;">"Gaming"</span>]<span style="color:#e6edf3;">,</span><br>
        <span style="color:#6e7681;">05 </span>&nbsp;&nbsp;<span style="color:#79c0ff;">building</span><span style="color:#e6edf3;">:</span>&nbsp;<span style="color:#a5d6ff;">"Something cool... always 🔧"</span><br>
        <span style="color:#6e7681;">06 </span>}
      </div>
    </div>

    <!-- ─── TECH STACK ─── -->
    <div style="margin-bottom:20px;">
      <div style="font-size:10px;font-weight:700;color:#F97316;letter-spacing:3px;text-transform:uppercase;margin-bottom:10px;display:flex;align-items:center;gap:8px;">
        <span style="white-space:nowrap;">// Tech Stack</span>
        <div style="flex:1;height:1px;background:#21262d;"></div>
      </div>

      <div style="display:flex;flex-direction:column;gap:10px;">
        <div>
          <div style="font-size:9px;color:#6e7681;letter-spacing:2px;text-transform:uppercase;margin-bottom:6px;">Languages</div>
          <div style="display:flex;flex-wrap:wrap;gap:5px;">
            <span style="background:#1a1e24;border:1px solid rgba(249,115,22,0.55);color:#F97316;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">Python</span>
            <span style="background:#1a1e24;border:1px solid rgba(249,115,22,0.55);color:#F97316;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">JavaScript</span>
            <span style="background:#1a1e24;border:1px solid rgba(249,115,22,0.55);color:#F97316;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">C++</span>
            <span style="background:#1a1e24;border:1px solid rgba(249,115,22,0.55);color:#F97316;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">Dart</span>
            <span style="background:#1a1e24;border:1px solid rgba(249,115,22,0.55);color:#F97316;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">C#</span>
            <span style="background:#1a1e24;border:1px solid rgba(249,115,22,0.55);color:#F97316;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">MicroPython</span>
            <span style="background:#1a1e24;border:1px solid rgba(249,115,22,0.55);color:#F97316;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">HTML / CSS</span>
          </div>
        </div>

        <div>
          <div style="font-size:9px;color:#6e7681;letter-spacing:2px;text-transform:uppercase;margin-bottom:6px;">Embedded &amp; Hardware</div>
          <div style="display:flex;flex-wrap:wrap;gap:5px;">
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">ESP32</span>
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">micro:bit</span>
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">Arduino</span>
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">Raspberry Pi</span>
          </div>
        </div>

        <div>
          <div style="font-size:9px;color:#6e7681;letter-spacing:2px;text-transform:uppercase;margin-bottom:6px;">AI / ML / Frameworks</div>
          <div style="display:flex;flex-wrap:wrap;gap:5px;">
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">YOLO</span>
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">Ollama</span>
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">ChromaDB</span>
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">OpenCV</span>
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">Flutter</span>
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">Firebase</span>
            <span style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:2px 9px;border-radius:3px;font-family:monospace;">RVC</span>
          </div>
        </div>
      </div>
    </div>

    <!-- ─── GITHUB STATS ─── -->
    <div style="margin-bottom:20px;">
      <div style="font-size:10px;font-weight:700;color:#F97316;letter-spacing:3px;text-transform:uppercase;margin-bottom:10px;display:flex;align-items:center;gap:8px;">
        <span style="white-space:nowrap;">// GitHub Stats</span>
        <div style="flex:1;height:1px;background:#21262d;"></div>
      </div>
      <div style="display:grid;grid-template-columns:minmax(0,1fr) minmax(0,1fr);gap:8px;margin-bottom:8px;">
        <div style="background:#161b22;border:1px solid #21262d;border-radius:6px;padding:8px;overflow:hidden;">
          <img src="https://github-readme-stats.vercel.app/api?username=Minta1234&show_icons=true&include_all_commits=true&theme=github_dark&hide_border=true&title_color=F97316&icon_color=F97316&text_color=e6edf3&bg_color=00000000" style="width:100%;height:auto;display:block;" alt="GitHub Stats" />
        </div>
        <div style="background:#161b22;border:1px solid #21262d;border-radius:6px;padding:8px;overflow:hidden;">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Minta1234&layout=compact&theme=github_dark&hide_border=true&title_color=F97316&text_color=e6edf3&bg_color=00000000" style="width:100%;height:auto;display:block;" alt="Top Languages" />
        </div>
      </div>
      <div style="background:#161b22;border:1px solid #21262d;border-radius:6px;padding:8px;overflow:hidden;">
        <img src="https://streak-stats.demolab.com?user=Minta1234&theme=github-dark-blue&hide_border=true&ring=F97316&fire=F97316&currStreakLabel=F97316&sideLabels=F97316" style="width:100%;height:auto;display:block;" alt="GitHub Streak" />
      </div>
    </div>

    <!-- ─── ACTIVITY GRAPH ─── -->
    <div style="margin-bottom:20px;">
      <div style="font-size:10px;font-weight:700;color:#F97316;letter-spacing:3px;text-transform:uppercase;margin-bottom:10px;display:flex;align-items:center;gap:8px;">
        <span style="white-space:nowrap;">// Activity Graph</span>
        <div style="flex:1;height:1px;background:#21262d;"></div>
      </div>
      <div style="background:#161b22;border:1px solid #21262d;border-radius:6px;padding:8px;overflow:hidden;">
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=Minta1234&theme=github-dark&color=F97316&line=F97316&point=ffffff&hide_border=true&area=true&area_color=F97316" style="width:100%;height:auto;display:block;" alt="Activity Graph" />
      </div>
    </div>

    <!-- ─── CONTRIBUTION SNAKE ─── -->
    <div style="margin-bottom:20px;">
      <div style="font-size:10px;font-weight:700;color:#F97316;letter-spacing:3px;text-transform:uppercase;margin-bottom:10px;display:flex;align-items:center;gap:8px;">
        <span style="white-space:nowrap;">// Contribution Snake</span>
        <div style="flex:1;height:1px;background:#21262d;"></div>
      </div>
      <div style="background:#161b22;border:1px solid #21262d;border-radius:6px;padding:8px;overflow:hidden;">
        <img src="https://raw.githubusercontent.com/Minta1234/Minta1234/output/github-snake-dark.svg" style="width:100%;height:auto;display:block;" alt="Contribution Snake" />
      </div>
    </div>

    <!-- ─── FOOTER ─── -->
    <div style="border-top:1px solid #21262d;padding-top:16px;">
      <div style="font-size:10px;font-weight:700;color:#F97316;letter-spacing:3px;text-transform:uppercase;margin-bottom:10px;text-align:center;">// Connect</div>
      <div style="display:flex;justify-content:center;gap:8px;flex-wrap:wrap;margin-bottom:10px;">
        <a href="https://minta0077.online" style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:5px 12px;border-radius:4px;text-decoration:none;font-family:monospace;">🌐 minta0077.online</a>
        <a href="https://github.com/Minta1234" style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:5px 12px;border-radius:4px;text-decoration:none;font-family:monospace;">💻 github/Minta1234</a>
        <a href="https://www.tiktok.com/@minta1826" style="background:#1a1e24;border:1px solid #30363d;color:#8b949e;font-size:10px;padding:5px 12px;border-radius:4px;text-decoration:none;font-family:monospace;">🎵 @minta1826</a>
      </div>
      <div style="text-align:center;font-size:9px;color:#6e7681;font-family:monospace;">Built with 🔧 · Thailand 🇹🇭</div>
    </div>

  </div>
</div>
