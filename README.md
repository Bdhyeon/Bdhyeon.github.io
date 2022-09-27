# 🌿백다현
읽기 쉬운 코드를 지향합니다.   
주로 Java를 공부하고 있습니다.
<br/>
<br/>

## Contact  
```
email: bdhn1100@gmail.com   
GitHub: https://github.com/Bdhyeon
blog: https://bdhn1100.tistory.com/
```   

## Skill
<img src="https://img.shields.io/badge/Java-4B4B77?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/OracleDB-F80000?style=flat-square&logo=Oracle&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/>
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/>
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/>   
<br/>
<br/>

## Project
### 🥞 1. 쩝쩝박사 | 레시피 공유 사이트
#### + 개요

- 프로젝트 종류: 팀 프로젝트   
- 개발기간: 2022/07 ~ 2022/09   
- 개발환경:   
![프로젝트개발환경](https://user-images.githubusercontent.com/101542378/190292906-92dd22b9-141d-40da-90b4-e7ff618cf6c3.png)   
- 맡은 역할: 레시피 게시판 총괄(DB설계와 관리, 게시판 구현)   
- GitHub: https://github.com/stilinskii/jjeopjjeopRecipe   

#### + 주요 기능
[프레젠테이션 자료](https://www.miricanvas.com/design/11e0d7v)   


#### + 테스트 사이트
- 사이트 url: [http://43.200.210.41:8081/](http://43.200.210.41:8081/)
```
테스트 아이디/비밀번호1: aa111 / aa111(일반유저)
테스트 아이디/비밀번호2: admin / admin(관리자)
```   

#### + 후기
<details>
<summary>배운 것</summary>
thymeleaf와 intelliJ를 사용해보는 계기가 되었다.
thymeleaf는 mvc 패턴으로 웹사이트를 만들 때 자주 이용할 것 같고, intelliJ는 STS에 비해 가벼워서 계속 쓸 것 같다.   

Ajax 기법을 제대로 사용한 적이 없었는데 레시피 스크랩/신고/덧글 처리를 하며 공부할 수 있었다.   

AWS 배포 과정을 경험할 수 있었다. (도중에 문제가 많았고 지금도 인스턴스에 자주 문제가 생기지만..)
war 파일로 배포했기 때문에 tomcat이나 oracleDB도 서버에 함께 설치해줘야 했는데, 그래서 오히려 공부가 더 되었다.
Linux 명령어도 직접 사용하며 공부할 수 있었다.   

GitHub을 더 잘 알게 되었다. branch를 따로 빼서 내 파트 push 후 merge하는 방식 등등...
</details>
<details>
<summary>아쉬운 점</summary>
원래 오픈API를 사용해보고 싶었는데, 오픈API 데이터와 로컬 데이터를 동시에 처리하기 어려워서 포기했다.
오픈API는 다음 개인 프로젝트에서 시도해 보려고 한다.
프로젝트를 설계할 때, 자신이 사용할 기술을 고려해서 정확하고 디테일하게 해야 한다는 것을 실감했다...   

내가 맡은 파트의 CRUD 작업에는 집중할 수 있었지만, 다른 팀원들이 맡은 파트는 신경쓰기 어려웠던 게 아쉽다.
세션을 이용한 로그인 처리, email로 비밀번호 찾기, 카카오 결제 api, 첨부파일 관리 방법, 게시판 상세검색 등등...
배울 것이 많았지만 당시에는 기한 내에 프로젝트를 마쳐야 한다는 생각에 찬찬히 공부하지 못했다.
지금은 프로젝트도 끝났으니 다른 파트 코드도 분석해 봐야겠다.   

각 파트에서 공통적인 부분이 많았는데(페이징, 첨부파일 처리 등) 제대로 통합하지 못했다.
마찬가지로 DB도 공통 기능을 고려했다면 훨씬 간단하게 짤 수 있었을 것 같다.
협업할 때에는 공통적으로 구현해야 할 기능이 어떤 것들이 있는지도 처음부터 고려해야 함을 배웠다.   

내 파트의 코드를 좀 더 깔끔하고 효율적으로 짤 수 있지 않았을까... 하는 아쉬움이 있다.
이것도 당시에는 그냥 '기능하는 것'을 만드는 것에만 집중했기 때문이다.
겉보기에 깔끔하게 쓰였는지는 둘째치고, 특히 효율적인지는 거의 신경쓰지 못했다.
다른 파트 코드를 분석하면서 내 파트 코드도 다시 살펴보며 리팩토링을 해야겠다.
</details>
<details>
<summary>총평</summary>
열의 있는 팀원들 사이에서 다양한 기술을 접할 수 있었고, 스스로도 더 노력해서 팀에 기여하고 싶다는 의욕을 갖게 되는 좋은 경험이었다.
CS지식이 한참 부족하다는 걸 느끼는 계기도 되어서, 아무튼 공부해야겠구나 하는 깨달음을 얻었다.
</details>
<br/>
<br/>

### 📚 2. 마이리딩(임시) | 독서 기록 사이트
#### + 개요

- 프로젝트 종류: 개인 프로젝트   
- 개발기간: 2022/09 ~ 진행중
- 개발환경:   
- blog: https://bdhn1100.tistory.com/2
- GitHub: https://github.com/Bdhyeon/myreading

#### + 주요 기능


#### + 테스트 사이트


#### + 후기
<details>
<summary>배운 것</summary>
</details>
<details>
<summary>아쉬운 점</summary>
</details>
<details>
<summary>총평</summary>
</details>

