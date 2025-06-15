<h1>이가은의 개인 포트폴리오 웹사이트</h1>
Jekyll과 GitHub Pages를 기반으로, 외부 테마를 사용하지 않고 직접 구축한 개인 포트폴리오 웹사이트입니다.

<h1>🖥️ 홈페이지 바로가기</h1>
Live URL : https://leegaeune.github.io/

<h1>📂 GitHub 저장소</h1>
Source Code : https://github.com/Leegaeune/Leegaeune.github.io

<h1>📌 프로젝트 소개</h1>
이 프로젝트는 저의 개발 역량, 수행한 프로젝트, 그리고 성장 과정을 보여주기 위해 제작된 온라인 이력서입니다. 기존에 배포된 Jekyll 테마를 사용하지 않고, HTML, CSS, 그리고 Jekyll의 기본 기능을 활용하여 처음부터 직접 모든 구조와 디자인을 구현하는 것을 목표로 했습니다.

이를 통해 웹 표준을 준수하는 시맨틱 마크업과 직접 제어 가능한 CSS 스타일링 능력을 보여주고자 했습니다.

<h1>✨ 주요 기능 및 구현 내용</h1>

기능 1) 헤드라인 자기소개
기능 제목 : 핵심 역량을 한눈에 보여주는 헤드라인 섹션

설명 : 방문자가 사이트에 접속하자마자, 개발자로서의 정체성과 비전을 담은 대표 문구를 최상단에 배치하여 포트폴리오의 첫인상을 강화하고 핵심 메시지를 전달하는 이력서의 '헤드라인' 역할을 수행합니다.

코드 위치 : index.md의 .hero-section, assets/css/style.css의 .hero-section 스타일

코드 설명 : 메인 콘텐츠 최상단에 <section class="hero-section">을 배치하고, CSS에서 주목도 높은 배경색과 큰 글씨(h1)를 적용하여 다른 섹션과 시각적으로 차별화했습니다.

기능 2) 가독성을 높인 2단 컬럼 정보 구조
기능 제목 : Flexbox를 이용한 경력/학력 사항 좌우 분리 레이아웃

설명 : 'Experience & Awards' 섹션에서 기간/기관명(좌)과 상세 설명(우)을 명확하게 분리하여, 실제 이력서 양식처럼 정보의 가독성을 극대화했습니다.

코드 위치 : index.md의 .experience-entry, assets/css/style.css의 .experience-left, .experience-right

코드 설명 : 각 항목을 .experience-entry로 묶고 display: flex를 적용하여 자식 요소인 .experience-left와 .experience-right를 가로로 배치했습니다. 각 영역에 고정 너비와 가변 너비를 부여하여 항상 일정한 레이아웃을 유지하도록 설계했습니다.

기능 3) 프로젝트 카드 UI 및 상세 내용 섹션
기능 제목 : 각 프로젝트를 상세히 설명하는 카드형 UI

설명 : 프로젝트 목록을 단순 나열하는 대신, 각 프로젝트를 제목, 기간, 목표, 구현 내용, 사용 기술 등을 포함하는 독립된 '카드' 형태로 구성하여 경력 기술서와 같이 체계적인 정보 전달이 가능하도록 했습니다.

코드 위치 : index.md의 .project-card, assets/css/style.css의 .project-card 관련 스타일

코드 설명 : 각 프로젝트를 <div class="project-card">로 묶어 시각적 경계를 만들고, 내부에는 <h3>, <h4>, <ul> 등 시맨틱 태그를 사용하여 정보의 위계를 명확히 했습니다. CSS에서는 background, border, padding 등을 이용해 각 카드를 디자인했습니다.


🛠️ 사용 기술

HTML5: 웹페이지의 구조와 콘텐츠를 정의합니다.

CSS3: 웹페이지의 전체적인 디자인과 레이아웃, 반응형 처리를 담당합니다.

Jekyll: 정적 사이트 생성기로, 마크다운 파일과 템플릿을 최종 HTML 파일로 빌드합니다.

GitHub Pages: 완성된 정적 웹사이트를 인터넷에 호스팅합니다.




