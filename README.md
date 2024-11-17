<div align="center">
  <h1>🎞️ Movie_search🎞️</h1>
    MySQL을 파이썬에 연결하여 사용자가 원하는 방식으로 영화를 검색해주는 프로그램
  
  <br><br><br><br>

  <h2>⚙️ UI ⚙️</h2>
    <div>
      <img src="https://github.com/user-attachments/assets/f044ec12-c090-45ef-b946-e926b7584cbb"><br>
      1. relation 생성 및 data 추가<br>
      2. 제목을 이용한 검색<br>
      3. 관객수를 이용한 검색<br>
      4. 개봉일을 이용한 검색<br>
    </div>
      
  <br><br><br><br>

  <h2>🗄️ 데이터 🗄️</h2>
    <br><b><i>558 row</i></b><br>
    <table>
        <thead>
            <tr>
                <th>ID</th>
                <th>Title</th>
                <th>Company</th>
                <th>Release Date</th>
                <th>Country</th>
                <th>Total Screens</th>
                <th>Profit&nbsp</th>
                <th>Total Number</th>
                <th>Grade</th>
            </tr>
        </thead>
        <tbody>
          <tr>
            <td>ex..데이터 번호</td>
            <td>ex..영화 제목</td>
            <td>ex..영화사</td>
            <td>ex..개봉일</td>
            <td>ex..국가</td>
            <td>ex..전체 상영관 수</td>
            <td>ex..수익</td>
            <td>ex..총 관객수</td>
            <td>ex..등급&nbsp&nbsp</td>
          </tr>
          <tr>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
          </tr>
          <tr>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
          </tr>
          <tr>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
          </tr>
        </tbody>
    </table>
    
  <br><br><br><br>
  
  <h2>✔️ 사용 예시 ✔️</h2><br>
    <h3>&lt테이블 생성 및 데이터 삽입&gt</h3>
      <img src="https://github.com/user-attachments/assets/61a595c6-fa04-4cdf-bd09-d686ab4136ce"><br>
      - 프로그램을 최초로 실행시키는 경우 테이블 생성과 영화 데이터 삽입을 위해 1번 실행
    <br><br><br><br>
    <h3>&lt제목으로 영화 검색&gt</h3>
      <img src="https://github.com/user-attachments/assets/93e29753-ab3f-4a73-bf57-13a6cf69f722"><br>
      - 사용자가 키워드를 입력하면 제목에 키워드를 포함하는 영화 목록 반환 (예시는 제목에 "바다"를 포함하는 영화 목록)
    <br><br><br><br>
    <h3>&lt관객수로 영화 검색&gt</h3>
      <img src="https://github.com/user-attachments/assets/c771146f-9d63-428d-9270-bce138c6fa70"><br>
      - 사용자가 원하는 관객수를 입력하면 그 관객수 이상의 모든 영화 목록 반환 (예시는 관객수가 500만 이상인 영화 목록)
    <br><br><br><br>
    <h3>&lt개봉일로 영화 검색&gt</h3>
      <img src="https://github.com/user-attachments/assets/fee354fc-5ebf-4811-a566-b9c6b6ba22ad"><br>
      - 사용자가 개봉 시작일과 개봉 마감일을 입력하면 그 기간 내의 영화 목록 반환 (예시는 [2013년 3월 1일 ~ 2013년 3월 10일] 사이의 영화 목록)
    <br><br><br><br>
    <h3>&lt데이터가 없는 경우&gt</h3>
      <img src="https://github.com/user-attachments/assets/849c4ca0-504d-431e-9768-ea7dd0dd5c62"><br>
      - 빈 리스트 반환 ([2, 3, 4]번 검색 모두 동일)
    <br><br><br><br>
    <h3>&lt프로그램 종료&gt</h3>
      <img src="https://github.com/user-attachments/assets/e3d55ad3-2c59-44b9-89cb-1a422c6b2bd6"><br>
</div>
<br><br><br><br><hr>
*2022. 11 ~ 2022. 12*
