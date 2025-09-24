<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>권찬희 — Flutter Developer Portfolio</title>
  <style>
    :root{--accent:#0b72ff;--muted:#6b7280;--bg:#f7f9fc;font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;}
    body{margin:0;background:var(--bg);color:#111827;line-height:1.45}
    .container{max-width:980px;margin:36px auto;padding:28px;background:white;border-radius:12px;box-shadow:0 6px 24px rgba(15,23,42,0.06)}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:92px;height:92px;border-radius:14px;background:linear-gradient(135deg,var(--accent),#6c9eff);display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:28px}
    h1{margin:0;font-size:22px}
    p.lead{margin:6px 0 0;color:var(--muted)}
    .meta{display:flex;gap:10px;margin-top:12px;flex-wrap:wrap}
    .chip{background:#f1f5f9;padding:8px 10px;border-radius:999px;font-size:13px;color:#0f172a}
    section{margin-top:26px}
    h2{font-size:18px;margin:0 0 12px}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px}
    .card{background:#fff;padding:16px;border-radius:10px;border:1px solid #eef2f6}
    ul.clean{padding:0;margin:0;list-style:none}
    .timeline{display:flex;flex-direction:column;gap:10px}
    .role{padding:12px;border-radius:8px;background:#f8fafc;border-left:4px solid var(--accent)}
    .small{font-size:13px;color:var(--muted)}
    table.info{width:100%;border-collapse:collapse}
    table.info td{padding:6px 8px;border-bottom:1px dashed #eef2f6}
    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .skill{background:#f1f5f9;padding:6px 10px;border-radius:999px;font-size:13px}
    .projects .project{padding:12px;border-radius:8px;border:1px solid #eef2f6;background:#fff;margin-bottom:10px}
    footer{margin-top:22px;color:var(--muted);font-size:13px;text-align:center}
    @media (max-width:880px){.grid{grid-template-columns:1fr;padding:0}.container{margin:18px;padding:18px}}
  </style>
</head>
<body>
  <div class="container" role="main">
    <header>
      <div class="avatar">KC</div>
      <div>
        <h1>권찬희 (Kwon Chanhee) — Flutter Developer</h1>
        <p class="lead">Flutter v1 부터 시작해 7년 이상 모바일 앱 개발을 해온 개발자입니다. 다양한 팀과 협업하며 안정적인 앱 설계와 배포, 유지보수를 경험했습니다.</p>
        <div class="meta">
          <div class="chip">총 경력: 7년 1개월</div>
          <div class="chip">전문분야: Flutter, 모바일 앱 아키텍처, Firebase, BLE</div>
          <div class="chip">직전 연봉: ₩55,000,000</div>
        </div>
      </div>
    </header>

    <section class="grid">
      <div>
        <div class="card">
          <h2>Contact</h2>
          <table class="info">
            <tr><td>이름</td><td>권 찬 희</td></tr>
            <tr><td>생년월일</td><td>1996.12.11</td></tr>
            <tr><td>전화</td><td>010-4955-7347</td></tr>
            <tr><td>주소</td><td>부천시 소사구 심곡본동 617-11 (부천 롯데아파트 2동 509호)</td></tr>
            <tr><td>병역</td><td>육군 병장 전역 (2016.10 ~ 2018.07)</td></tr>
          </table>
        </div>

        <div class="card" style="margin-top:12px">
          <h2>Core Competencies</h2>
          <div class="skills" style="margin-bottom:8px">
            <span class="skill">Flutter (Dart)</span>
            <span class="skill">State: GetX / Bloc / Provider</span>
            <span class="skill">RESTful / GraphQL</span>
            <span class="skill">Firebase (Push, Realtime DB, Firestore)</span>
            <span class="skill">Git / SVN</span>
            <span class="skill">Figma / Zeplin / Jira</span>
            <span class="skill">Bluetooth (Firmware comms)</span>
            <span class="skill">Social Login / OAuth</span>
          </div>
          <p class="small">프로젝트에 맞는 아키텍처(MVVM, MVC 등)를 적용하고, 라이브러리를 필요에 맞게 커스터마이징하여 유지보수성 높은 코드를 작성합니다.</p>
        </div>

        <div class="card" style="margin-top:12px">
          <h2>Education</h2>
          <ul class="clean">
            <li class="small">2016.03 ~ 2019.07 서일대학교 (소프트웨어 공학과) — 3학년 중퇴</li>
            <li class="small">2012.03 ~ 2015.02 용산공업고등학교 (전자과)</li>
          </ul>
        </div>

        <div class="card" style="margin-top:12px">
          <h2>Work History (요약)</h2>
          <div class="timeline">
            <!-- 최신순 -->
            <div class="role">
              <strong>2024.12 ~ 재직중 — 티피엘엔디 (책임연구원 / 매니저)</strong>
              <div class="small">주요직무: SI 개발 · (진행 프로젝트는 아래 TPLND 상세에 기입 예정)</div>
            </div>

            <div class="role">
              <strong>2024.01 ~ 2025.07 (1년 7개월) — Augustlab (과장 / 팀장)</strong>
              <div class="small">주요직무: 앱 개발자 · 팀 리딩</div>
            </div>

            <div class="role">
              <strong>2024.04 ~ 2024.12 (9개월) — Hillserion (힐세리온) (선임연구원 / 팀장)</strong>
              <div class="small">주요직무: 앱 개발자 · 연봉: ₩55,000,000</div>
            </div>

            <div class="role">
              <strong>2023.11 ~ 2024.01 (3개월) — 현대오일뱅크 (프리랜서)</strong>
              <div class="small">전기차 충전소 앱: 환경부 데이터 기반 200,000개 지도 마커 표시 · 베트남 개발자 협업 · Git 기반 코드 공유</div>
            </div>

            <div class="role">
              <strong>2023.09 ~ 2023.11 (3개월) — MSX (프리랜서)</strong>
              <div class="small">블록체인 연동 앱: 코인/게임/투자 기능 개발</div>
            </div>

            <div class="role">
              <strong>2023.07 ~ 2023.09 (3개월) — 농협 IT 센터 (프리랜서, 과장/팀장)</strong>
              <div class="small">하나로마트 앱을 React Native → Flutter 마이그레이션 · 기존 API 재사용</div>
            </div>

            <div class="role">
              <strong>2022.10 ~ 2023.07 (10개월) — WorldChanger (대리)</strong>
              <div class="small">블록체인 지갑 · DApp 개발 · 연봉: ₩53,000,000</div>
            </div>

            <div class="role">
              <strong>2021.11 ~ 2022.10 (1년) — People&Job (대리)</strong>
              <div class="small">앱 개발자 · 연봉: ₩45,900,000</div>
            </div>

            <div class="role">
              <strong>2020.07 ~ 2021.11 (1년 5개월) — NetMix</strong>
              <div class="small">앱 개발자</div>
            </div>

            <div class="role">
              <strong>2018.08 ~ 2020.05 (1년 10개월) — OnIO</strong>
              <div class="small">앱 개발자 (입사 후 실무 경험 시작)</div>
            </div>

          </div>
        </div>

      </div>

      <aside>
        <div class="card">
          <h2>Quick Facts</h2>
          <p class="small">프리랜서 월 단가: ₩550 ~ 600만<br>MS Office: 중급</p>
        </div>

        <div class="card" style="margin-top:12px">
          <h2>Technical Tools</h2>
          <div class="skills">
            <span class="skill">VSCode / Android Studio</span>
            <span class="skill">Fastlane / CI-CD</span>
            <span class="skill">Firebase</span>
            <span class="skill">Socket / REST / GraphQL</span>
            <span class="skill">Docker (기초)</span>
          </div>
        </div>

        <div class="card" style="margin-top:12px">
          <h2>Languages</h2>
          <p class="small">한국어 (원어민), 영어 (기술문서 읽기/협업 가능)</p>
        </div>
      </aside>
    </section>

    <section class="projects card" style="margin-top:18px">
      <h2>Selected Projects</h2>

      <div class="project">
        <strong>티피엘엔디 (TPLND) — 진행 중</strong>
        <p class="small">(여기에 사용자가 제공할 상세 프로젝트 설명을 넣겠습니다 — 예: 기간, 역할, 핵심기능, 사용 기술, 성과)</p>
      </div>

      <div class="project">
        <strong>Augustlab — (2024.01 ~ 2025.07)</strong>
        <p class="small">앱 개발 및 팀 리딩. Flutter 기반 앱 설계 · 코드 리뷰 · 배포 파이프라인 구성 등</p>
      </div>

      <div class="project">
        <strong>힐세리온 (Hillserion) — (2024.04 ~ 2024.12)</strong>
        <p class="small">의료/헬스 관련 앱 개발. 주요 기능: 데이터 시각화, BLE 연동, 백그라운드 작업 최적화</p>
      </div>

      <div class="project">
        <strong>현대오일뱅크 — (2023.11 ~ 2024.01)</strong>
        <p class="small">전기차 충전소 앱: 환경부 데이터(약 200,000건) 지도 시각화 및 성능 최적화, 다국적(베트남) 개발자와 협업</p>
      </div>

      <div class="project">
        <strong>MSX / WorldChanger / Others</strong>
        <p class="small">블록체인 지갑, DApp, 코인 연동 앱 등 다양한 금융/블록체인 관련 프로젝트 참여</p>
      </div>

    </section>

    <section class="card" style="margin-top:18px">
      <h2>Summary</h2>
      <p class="small">Flutter (v1 부터 시작) 기반의 모바일 앱 개발자로서, 프론트엔드 설계, 상태관리, 네트워크/백엔드 통신, BLE 통신, 그리고 다양한 외부 API 연동 경험이 있습니다. 팀 내외부와의 원활한 커뮤니케이션으로 프로젝트를 주도하고, 유지보수성 높은 코드를 작성합니다. 티피엘엔디에서 진행한 프로젝트들은 별도 제공해주시는 설명을 받아 해당 섹션에 추가하겠습니다.</p>
    </section>

    <footer>
      © 권찬희 · Flutter Developer
    </footer>
  </div>
</body>
</html>
