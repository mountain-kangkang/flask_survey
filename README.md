# a survey using flask
#### flask를 이용한 설문조사
---

### External Libraries
- **flask**
- **plotly**
- **pandas**
- **sqlalchemy**
- **flask-migrate**
---

### Routes
- `route(rule, **options)`
    - 매개변수 `rule`에 URL을... 그리고 `options`에 메소드 CRUD, 즉 POST, GET, PUT, DELETE를 입력받아 맵핑합니다.
- `def home()`
    - 처음 `http://127.0.0.1:5000`으로 접속하면 보이는 화면을 띄우는 route
    - 설문을 시작하거나 admin 페이지로 진입 가능하도록 만들었음
    ![def_home()](/img/def_home.png)
    ![home](/img/home_html.png)
- `def add_participant()`
    - 설문을 시작하면 설문을 시작하기에 앞서 설문 응답자의 정보를 수집하는 route
    - 설문 응답자의 이름, 나이대, 성별을 수집하고, 설문 응답자의 id와 id생성일자를 생성하고 DB에 저장 및 설문 응답자의 id를 가지고 설문을 시작
    ![def_add_participant()](/img/def_add_participant().png)
    ![index](/img/index_html.png)


---
### DB Relationship
![db relationship](/img/DB_Diagram.png)