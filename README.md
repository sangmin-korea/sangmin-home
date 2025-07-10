<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>나만의 홈페이지</title>
  <style>
    body { font-family: 'Segoe UI', Arial, sans-serif; margin: 40px; background: #f9f9f9; }
    h1, h2 { color: #2d3436; }
    section { margin-bottom: 40px; background: #fff; padding: 24px; border-radius: 12px; box-shadow: 0 2px 8px #eee; }
    .item-list { display: flex; gap: 32px; flex-wrap: wrap; }
    .item { width: 180px; text-align: center; }
    .item img { width: 100%; height: 120px; object-fit: cover; border-radius: 8px; background: #eee; }
    .routine-table { width: 100%; border-collapse: collapse; margin-top: 12px; }
    .routine-table th, .routine-table td { border: 1px solid #ccc; padding: 8px; text-align: center; }
    .routine-table th { background: #f1f2f6; }
  </style>
</head>
<body>
  <h1>나만의 홈페이지</h1>

  <section>
    <h2>나의 취미</h2>
    <div class="item-list">
      <div class="item">
        <img src="images/hobby1.jpg" alt="멍때리기">
        <div>멍때리기</div>
      </div>
      <div class="item">
        <img src="images/hobby2.jpg" alt="친구들과 수다떨기">
        <div>친구들과 수다떨기</div>
      </div>
      <div class="item">
        <img src="images/hobby3.jpg" alt="가족과 외식하기">
        <div>가족과 외식하기</div>
      </div>
    </div>
  </section>

  <section>
    <h2>운동(헬스) 루틴</h2>
    <table class="routine-table">
      <tr>
        <th>요일</th>
        <th>운동 부위</th>
      </tr>
      <tr><td>월요일</td><td>가슴</td></tr>
      <tr><td>화요일</td><td>등</td></tr>
      <tr><td>수요일</td><td>어깨</td></tr>
      <tr><td>목요일</td><td>가슴</td></tr>
      <tr><td>금요일</td><td>등</td></tr>
      <tr><td>토요일</td><td>어깨</td></tr>
      <tr><td>일요일</td><td>휴식</td></tr>
    </table>
  </section>

  <section>
    <h2>내가 좋아하는 연예인들</h2>
    <div class="item-list">
      <div class="item">
        <img src="images/jaehoon.jpg" alt="박재훈">
        <div>보디빌더 박재훈</div>
      </div>
      <div class="item">
        <img src="images/mbappe.jpg" alt="음바페">
        <div>축구선수 음바페</div>
      </div>
      <div class="item">
        <img src="images/songhayoung.jpg" alt="프로미스나인 송하영">
        <div>프로미스나인 송하영</div>
      </div>
      <div class="item">
        <img src="images/homies.jpg" alt="호미들">
        <div>래퍼 호미들</div>
      </div>
    </div>
  </section>

  <section>
    <h2>내가 좋아하는 음식</h2>
    <div class="item-list">
      <div class="item">
        <img src="images/tuna.jpg" alt="통조림 참치캔">
        <div>통조림 참치캔</div>
      </div>
    </div>
  </section>

  <section>
    <h2>나의 일대기</h2>
    <p>
      <!-- 여기에 본인의 성장 과정, 추억, 목표 등 자유롭게 작성하세요! -->
      예시: 2000년에 태어나서, 어린 시절에는 ...<br>
      (나는 2002년에 태어나서 어린 시절에는 바둑과 드럼을 배웠고 22살에 군대를 다녀와 지금은 한국기술교육대학교를 다니며 현재 컴퓨팅사고를 듣고 있다.)
    </p>
  </section>
</body>
</html>
