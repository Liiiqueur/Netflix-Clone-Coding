# Netflix-Clone-Coding

https://www.postman.com/downloads/

# 🎬 Netflix-Clone-Coding

![React](https://img.shields.io/badge/React-v18-blue?logo=react&logoColor=white&style=flat-square)
![Node.js](https://img.shields.io/badge/Node.js-v18-green?logo=node.js&logoColor=white&style=flat-square)
![Firebase](https://img.shields.io/badge/Firebase-Hosting-orange?logo=firebase&logoColor=white&style=flat-square)

> **이 프로젝트는 넷플릭스를 클론한 풀스택 웹 애플리케이션으로, [해당 유튜브 강의](https://www.youtube.com/watch?v=gRroBZczKAU)를 참고하여 개발되었습니다.**

---

## 📚 목차
1. [프로젝트 소개](#-프로젝트-소개)
2. [주요 기능](#-주요-기능)
3. [기술 스택](#-기술-스택)
4. [설치 및 실행](#-설치-및-실행)
5. [프로젝트 구조](#-프로젝트-구조)
6. [스크린샷](#-스크린샷)
7. [기여 방법](#-기여-방법)
8. [라이선스](#-라이선스)

---

## 📖 프로젝트 소개

이 프로젝트는 넷플릭스의 주요 기능을 구현한 클론 코딩 프로젝트입니다.  
프론트엔드와 백엔드 기술을 활용하여 다음과 같은 기능들을 개발했습니다:

- 사용자 인증 및 관리
- 실시간 영화 데이터 가져오기
- 개인화된 사용자 인터페이스 제공
- 모바일과 데스크톱에 최적화된 반응형 디자인

---

## ✨ 주요 기능

- **사용자 인증**: Firebase Authentication을 활용한 회원가입, 로그인, 로그아웃 기능
- **영화 검색 및 탐색**: TMDB API를 사용하여 영화와 TV 프로그램 정보를 가져와 표시
- **카테고리 분류 및 예고편 보기**: 카테고리별로 콘텐츠를 나누고, 클릭하면 예고편 재생
- **반응형 디자인**: 모바일, 태블릿, 데스크톱 화면에 최적화
- **Firebase Hosting**: 실제 배포 및 접속 가능

---

## 🛠️ 기술 스택

- **프론트엔드**: React, Redux, React Router, Axios
- **백엔드**: Firebase Authentication 및 Firestore
- **API**: [TMDB API](https://www.themoviedb.org/documentation/api)
- **스타일링**: TailwindCSS, 커스텀 CSS
- **배포**: Firebase Hosting

---

## ⚙️ 설치 및 실행

아래 단계에 따라 프로젝트를 로컬에서 실행할 수 있습니다:

1. **저장소 클론**:
    ```bash
    git clone https://github.com/your-username/netflix-clone.git
    cd netflix-clone
    ```

2. **필요한 패키지 설치**:
    ```bash
    npm install
    ```

3. **환경 변수 설정**:
   - 프로젝트 루트 디렉토리에 `.env` 파일을 생성하고 아래 내용을 추가하세요:
     ```env
     REACT_APP_TMDB_API_KEY=your_tmdb_api_key
     REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
     REACT_APP_FIREBASE_PROJECT_ID=your_project_id
     ```

4. **개발 서버 실행**:
    ```bash
    npm start
    ```

5. **배포 (선택사항)**:
   ```bash
   npm run build
   firebase deploy
📂 프로젝트 구조
plaintext
코드 복사
📦 netflix-clone
├── 📁 public        # 정적 파일
├── 📁 src
│   ├── 📁 components # 재사용 가능한 컴포넌트
│   ├── 📁 pages      # 주요 페이지
│   ├── 📁 api        # API 관련 유틸리티
│   ├── 📁 store      # Redux 스토어
│   ├── 📁 styles     # 전역 및 컴포넌트별 스타일
│   └── 📄 App.js     # 메인 애플리케이션
├── 📄 package.json   # 프로젝트 메타데이터
└── 📄 README.md      # 프로젝트 문서
📸 스크린샷
홈 화면

영화 상세 페이지

🤝 기여 방법
이 프로젝트에 기여하고 싶으신가요? 아래 단계를 따라주세요:

이 저장소를 포크합니다.
새로운 브랜치를 생성합니다: (git checkout -b feature-branch-name)
변경 사항을 커밋합니다: (git commit -m "설명")
브랜치를 푸시합니다: (git push origin feature-branch-name)
풀 리퀘스트를 생성합니다.
📜 라이선스
이 프로젝트는 MIT License를 따릅니다. 자유롭게 사용하세요!

Made with ❤️ by Your Name

yaml
코드 복사

---

### 추가로 할 일
1. **환경 변수(.env)**: TMDB와 Firebase API 키를 설정해야 하니 보안을 신경 쓰세요.
2. **GitHub URL**: 저장소 링크를 실제 프로젝트 URL로 변경하세요.
3. **스크린샷**: 프로젝트가 완성되면 실제 화면을 캡처해 업로드하세요.

이 README로 프로젝트의 완성도를 높여보세요! 🚀
