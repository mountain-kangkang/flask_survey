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
- `def home():`
    - 처음 `http://127.0.0.1:5000`으로 접속하면 보이는 화면을 띄우는 route
    ![def_home()](/img/def_home.png)
    ![home](/img/home_html.png)

---
### DB Relationship
![db relationship](/img/DB_Diagram.png)