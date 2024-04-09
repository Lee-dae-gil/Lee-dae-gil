
Skill

- Front-end : JavaScript, HTML/CSS
- Back-end : Java , Python, JSP, Servlet, Spring
- DataBase : Oracle SQL Developer, MySQL

![js](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
![html](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![css](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JSP](https://img.shields.io/badge/JSS-F7DF1E?style=for-the-badge&logo=JSS&logoColor=white)
![Servlet](https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)


1. 핵심 프로젝트 참여
주제 : G-CAP (광주 문화예술 여행 안내 웹 서비스)
기간 : 2024. 03. 05 ~ 04. 05. 
인원 : 5명
역할 : 
Front → HTML/CSS 페이지 작업, 데이터 전처리 작업
DB → DB 관리, 테이블 작성 및 수정, SQL문 작성
발표 → 산출문서 (WBS / DB요구사항분석서 / 테이블명세서 / 요구사항정의서) 작성
주요 사용 언어 및 스택 : JSP / JS / Oracle SQL Developer / Python / VSCode / tomcat / apachi / D3.js 등

프로젝트 요약 : 데이터 시각화(대시보드)를 활용하여 문화 사각지대 계층을 포함한 사람들에게 광주의 문화-예술 여행지를 안내해주는 웹 서비스

약 1개월의 개발 기간동안 5명의 팀원들과 기획단계부터 회의를 거쳐 원활한 의사소통으로 목적을 달성하였음. 저는 팀에서 주로 DB업무와 Front업무, 문서 작성을 맡았습니다. DB에서는 Oracle SQLDeveloper를 이용하여 데이터베이스의 전반적인 관리와 SQL문을 활용한 테이블의 작성 및 수정 작업, 데이터의 전처리와 추가 작업, E-R Diagram 작성을 맡았습니다. Front에서는 VSCode를 활용하여 HTML/CSS 페이지를 작성했습니다. 산출문서의 경우에는 WBS, 요구사항정의서, 테이블명세서, DB요구사항분석서를 작성했습니다.

테이블을 작성하면서 각 테이블 간 외래키 참조를 위해 식별자 인덱스를 동일하게 맞춰줘야하는 작업이 있었는데, 시 SQL문으로 시퀀스를 설정하였는데, 데이터를 DELETE하여도 시퀀스가 초기화되지 않거나,  ALTER문으로 시퀀스의 수정을 시도했으나 잘 되지 않았습니다. 해당 문제 해결을 위해 시퀀스 자체를 아예 삭제하고 재생성하면서 시작값 1부터 레코드 추가시 1씩 값이 증가하도록 재설정하는 것으로 문제를 해결했습니다. 
또 전처리한 데이터를 테이블에 IMPORT하는 과정에서도 데이터의 라벨링이 제대로 이루어지지 않아 값이 정상 출력되지 않거나 아예 IMPORT자체가 이루어지지 않는 문제가 있었습니다. 해당 문제의 경우 원활한 IMPORT를 위해 컬럼의 제약조건을 임시로 수정하여 값을 추가하고 다시 제약조건을 설정하는 방법을 사용하였습니다. 이 경우 참조 무결성과 관련하여 차후에 문제가 생길수도 있기에 우려되는 부분의 추가적인 점검과 모니터링을 거쳤습니다.

저의 역량은 작은 오류, 오탈자 하나도 거듭 확인하며 놓치지 않는 꼼꼼함과 스스로가 부족하다면 인정하고 기꺼이 도움을 구하는 융통성, 맡은 일을 끝까지 해내고야 마는 열정과 끈기입니다. 프로젝트 진행에서 의사소통의 중요성을 크게 느꼈었습니다. 매일같이 회의를 하고 수시로 의견을 나누며 개발을 진행했는데도, 일의 크고 작은 부분에서 계속 의견이 맞지않아 불필요한 업무를 하게되거나 필요기능은 오히려 작업이 늦어졌고, 또 도움이 필요할 때 제때 피드백을 받지 못하는 문제가 생겼었습니다.
기술 스택의 경우 쓸수록 익숙해지면서도 계속 실제 구현에 어려운 부분들이 있었고, 팀끼리 사용하는 기술의 연계 과정에도 오류가 발생해 실제구현에 애를 많이 먹었습니다. 페이지 작업의 경우  html과 css코드를 서로 맞춰 하나의 페이지로 만들어내는 과정이 쉽지 않았습니다. 데이터 시각화의 경우 대표적으로 경기도 시흥시의 웹페이지인 스마트 시흥의 대시보드 활용을 본보기로 활용해보고 싶었으나 현실적으로 그래프의 다양한 활용이나 애니메이션 효과 등을 사용하기에는 주제나 테마가 조금 어긋나는 부분도 있었고, 학습기간이 길지 않았다보니 팀에서 사용할 수 있는 기술에도 한계가 있었습니다. 다음 프로젝트에서는 기획에 시간을 더 할애하여 세세한 부분까지 확실하게 잡고 간다면 이번의 경험을 거울 삼아 더 좋은 결과물을 낼 수 있을 것이라 생각합니다.

