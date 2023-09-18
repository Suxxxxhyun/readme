# readme
## ⭐ 프로젝트 소개

---

- **Who’s Breeder?**
    
    **우수한 견종보존을 위해 동물보호 의식과 견종표준의 이해를 기반으로,**
    
    **견종의 짝짓기, 출산, 질병, 위생 자견분양 등 번식에 전문적인 지식을 갖추어**
    
    **강아지나 고양이의 혈통을 유지하고 올바르게 번식해 애견문화 발전에 기여**
    
- Breeder와 Adopter(분양희망자)를 연결하여, 강아지를 분양받도록 도와주는 프로젝트

### ⏰개발 기간

- 2023.04.17 ~ 2023.11.05

### 📎배포 사이트

- 펫트리

## 👤 팀원 소개
---
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/Suxxxxhyun"><img src="./team/박수현.jpg" width="150" height="150"/><br /><sub><b>BE 팀장 : 박수현</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/granen32"><img src="./team/권규형.jpg" width="150" height="150" alt=""/><br /><sub><b>FE 부팀장 : 권규형</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/ChanghyeonO"><img src="./team/오창현.png" width="150" height="150" alt=""/><br /><sub><b>FE 팀원 : 오창현</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/kjungit"><img src="./team/권범준.jpg" width="150" height="150" alt=""/><br /><sub><b>FE 팀원 : 권범준</b></sub></a><br /></td>
      <td align="center"><a href=""><img src="./team/이지수.png" width="150" height="150" alt=""/><br /><sub><b>BE 팀원 : 이지수</b></sub></a><br /></td>
      <td align="center"><a href=""><img src="" width="100px;" alt=""/><br /><sub><b>디자이너 : 이수언</b></sub></a><br /></td>
    </tr>
    <tr>
      <td> 1. 첫번째
           2. 두번째
           3. 세번째 
      </td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

## 🏷️폴더 구조
---
<pre>
    <code> 
        backend
        ├─ .github
        ├─ .gitlab
        ├─ .idea
        ├─ gradle
        │  └─ wrapper
        │  │  ├─ gradle-wrapper.jar
        │  │  ├─ gradle-wrapper.properties
        ├─ src
        │  ├─ main
        │  │  ├─ java
        │  │  │  ├─ com
        │  │  │  │  ├─ example
        │  │  │  │  │  ├─ example
        │  │  │  │  │  │  ├─ petree
        │  │  │  │  │  │  │  ├─ domain
        │  │  │  │  │  │  │  │  ├─ adopter
        │  │  │  │  │  │  │  │  │  ├─ controller
        │  │  │  │  │  │  │  │  │  ├─ domain
        │  │  │  │  │  │  │  │  │  ├─ dto
        │  │  │  │  │  │  │  │  │  ├─ repository
        │  │  │  │  │  │  │  │  │  ├─ schema
        │  │  │  │  │  │  │  │  │  ├─ service
        │  │  │  │  │  │  │  │  ├─ basic_test
        │  │  │  │  │  │  │  │  │  ├─ controller
        │  │  │  │  │  │  │  │  │  ├─ domain
        │  │  │  │  │  │  │  │  │  ├─ dto
        │  │  │  │  │  │  │  │  │  ├─ repository
        │  │  │  │  │  │  │  │  │  ├─ schema
        │  │  │  │  │  │  │  │  │  ├─ service
        │  │  │  │  │  │  │  │  ├─ breeder
        │  │  │  │  │  │  │  │  │  ├─ controller
        │  │  │  │  │  │  │  │  │  ├─ domain
        │  │  │  │  │  │  │  │  │  ├─ dto
        │  │  │  │  │  │  │  │  │  ├─ repository
        │  │  │  │  │  │  │  │  │  ├─ schema
        │  │  │  │  │  │  │  │  │  ├─ service
        │  │  │  │  │  │  │  │  ├─ dog
        │  │  │  │  │  │  │  │  │  ├─ controller
        │  │  │  │  │  │  │  │  │  ├─ domain
        │  │  │  │  │  │  │  │  │  ├─ dto
        │  │  │  │  │  │  │  │  │  ├─ repository
        │  │  │  │  │  │  │  │  │  ├─ schema
        │  │  │  │  │  │  │  │  │  ├─ service
        │  │  │  │  │  │  │  │  ├─ main_breed
        │  │  │  │  │  │  │  │  │  ├─ controller
        │  │  │  │  │  │  │  │  │  ├─ domain
        │  │  │  │  │  │  │  │  │  ├─ dto
        │  │  │  │  │  │  │  │  │  ├─ repository
        │  │  │  │  │  │  │  │  │  ├─ schema
        │  │  │  │  │  │  │  │  │  ├─ service
        │  │  │  │  │  │  │  │  ├─ matching
        │  │  │  │  │  │  │  │  │  ├─ controller
        │  │  │  │  │  │  │  │  │  ├─ domain
        │  │  │  │  │  │  │  │  │  ├─ dto
        │  │  │  │  │  │  │  │  │  ├─ repository
        │  │  │  │  │  │  │  │  │  ├─ schema
        │  │  │  │  │  │  │  │  │  ├─ service
        │  │  │  │  │  │  │  │  ├─ member
        │  │  │  │  │  │  │  │  │  ├─ controller
        │  │  │  │  │  │  │  │  │  ├─ domain
        │  │  │  │  │  │  │  │  │  ├─ dto
        │  │  │  │  │  │  │  │  │  ├─ repository
        │  │  │  │  │  │  │  │  │  ├─ schema
        │  │  │  │  │  │  │  │  │  ├─ service
        │  │  │  │  │  │  │  │  ├─ verification
        │  │  │  │  │  │  │  │  │  ├─ controller
        │  │  │  │  │  │  │  │  │  ├─ domain
        │  │  │  │  │  │  │  │  │  ├─ dto
        │  │  │  │  │  │  │  │  │  ├─ repository
        │  │  │  │  │  │  │  │  │  ├─ schema
        │  │  │  │  │  │  │  │  │  ├─ service
        │  │  │  │  │  │  │  ├─ global
        │  │  │  │  │  │  │  │  ├─ config
        │  │  │  │  │  │  │  │  ├─ error
        │  │  │  │  │  │  │  │  ├─ jwt
        │  │  │  │  │  │  │  │  ├─ util
        │  │  │  │  │  │  │  │  └─ web
        │  │  │  └─ resources
        │  │  │  └─ querydsl
        │  │  │  └─ test
        │  ├─ .gitignore
        │  ├─ build.gradle
        │  ├─ docker-compose.yml
        │  ├─ Dockerfile
        │  ├─ Dockerfile-dev
        │  ├─ gradlew
        │  ├─ gradlew.bat
        │  ├─ README.md
        │  └─  settings.gradle
    </code>
</pre>
