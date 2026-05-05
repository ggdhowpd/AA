<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>AA</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background: #f5f5f5;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  h1 { font-size: 2rem; color: #2D2D2D; margin-bottom: 2.5rem; }
  .cards { display: flex; gap: 1.5rem; flex-wrap: wrap; justify-content: center; }
  .card {
    background: #fff;
    border: 1px solid #e0e0e0;
    border-radius: 12px;
    padding: 2rem 2.5rem;
    width: 240px;
    text-align: center;
    text-decoration: none;
    color: #2D2D2D;
    transition: transform 0.15s, box-shadow 0.15s, border-color 0.15s;
  }
  .card:hover { transform: translateY(-4px); box-shadow: 0 8px 24px rgba(0,0,0,0.12); border-color: #D04A02; }
  .card-icon { font-size: 2.5rem; margin-bottom: 1rem; }
  .card-title { font-size: 1.1rem; font-weight: 600; margin-bottom: 0.4rem; }
  .card-desc { font-size: 0.85rem; color: #888; }
</style>
</head>
<body>
  <h1>AA</h1>
  <div class="cards">
    <a class="card" href="SmartSchedule.html">
      <div class="card-icon">📅</div>
      <div class="card-title">Smart Schedule</div>
      <div class="card-desc">일정 관리 도구</div>
    </a>
    <a class="card" href="MRLdraft">
      <div class="card-icon">📝</div>
      <div class="card-title">MRL Draft</div>
      <div class="card-desc">MRL 초안 작성 도구</div>
    </a>
  </div>
</body>
</html>
