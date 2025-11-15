# 📓 Taskify

> 일정 관리와 공유 기능을 제공하는 웹 애플리케이션

## 🌟 프로젝트 소개

Taskify는 커뮤니티를 생성하고 멤버를 초대하여 일정과 할 일을 함께 관리할 수 있습니다. 할 일 카드를 자유롭게 추가, 수정, 삭제할 수 있으며, 멤버 초대, 목록 분류, 댓글 기능을 제공하는 협업 플랫폼입니다.

## 🗓️ 프로젝트 기간

2025/11/18 (화) ~ 2025/12/04 (목)

### ✨ 주요 기능

- 💰 **칼럼 생성 및 멤버 초대**: 원하는 칼럼을 만들고 멤버를 초대하여 협업 시작
- 🗳️ **할 일 카드 관리**: 일정을 카드 형태로 생성, 수정, 삭제하며 시각적으로 관리
- 📊 **실시간 소통**: 카드별 댓글 기능으로 팀원과 즉시 소통
- 👤 **계정 및 멤버 관리**: 개인 계정 생성 및 커뮤니티 멤버 관리

## 🌐 배포 주소

➡️ [Taskify]()

## 🛠 기술 스택

| 구분                | 사용 기술                                                                                                                                                                                                                                                                                                           |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Frontend**        | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=white) |
| **Styling**         | ![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white)                                                                                                                                                                                                                       |
| **상태 관리**       | ![Context-API](https://img.shields.io/badge/Context--Api-000000?style=for-the-badge&logo=react)                                                                                                                                                                                                                     |
| **HTTP 클라이언트** | ![axios](https://img.shields.io/badge/axios-API-blue)                                                                                                                                                                                                                                                               |
| **Routing**         | ![Next.js Pages Router](https://img.shields.io/badge/Next.js_Pages_Router-000000?style=for-the-badge&logo=next.js&logoColor=white)                                                                                                                                                                                  |
| **배포**            | ![AWS S3](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)                                                                                                                                                                                                       |
| **협업**            | ![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion)                                                                                                                          |

## 🚀 시작하기

### 필수 조건

- Node.js 18.0 이상
- npm

### 설치 및 실행

```bash
# 저장소 클론
git clone https://github.com/Sprint-19-part3-1team-Taksify/frontend.git

# 프로젝트 디렉토리로 이동
cd frontend

# 의존성 설치
npm install

# 개발 서버 실행
npm run dev
```

## 📁 프로젝트 구조

```
📦 project
├── 📂 public                    # 정적 파일 (이미지, 폰트 등)
│   ├── 📂 images
│   ├── 📂 fonts
│   └── favicon.ico
├── 📂 src
│   ├── 📂 pages                 # Next.js 페이지 라우팅
│   ├── 📂 components            # 재사용 가능한 컴포넌트
│   │   ├── 📂 common            # 공통 컴포넌트
│   │   ├── 📂 layout            # 레이아웃 컴포넌트
│   │   └── 📂 domain            # 도메인별 컴포넌트
│   ├── 📂 hooks                 # Custom Hooks
│   ├── 📂 lib                   # 외부 라이브러리 설정
│   ├── 📂 api                   # API 호출 함수
│   ├── 📂 store                 # 상태 관리
│   ├── 📂 utils                 # 유틸리티 함수
│   └── 📂 styles                # 전역 스타일
├── .env.local                   # 환경 변수
├── .eslintrc.json               # ESLint 설정
├── .gitignore
├── next.config.js               # Next.js 설정
├── package.json
├── jsconfig.json                # JavaScript 설정 (경로 alias 등)
└── README.md
```

## 🔗 API 문서

- **Swagger UI**: https://sp-taskify-api.vercel.app/docs/
- **Base URL**:

## 👥 팀원

| 이름       | GitHub                                                                                                                             | 역할          |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| **최희락** | [![GitHub](https://img.shields.io/badge/GitHub-Greensod--96-181717?style=flat-square&logo=github)](https://github.com/Greensod-96) | 공통 컴포넌트 |
| **이선영** | [![GitHub](https://img.shields.io/badge/GitHub-sylee86-181717?style=flat-square&logo=github)](https://github.com/sylee86)          | 공통 컴포넌트 |
| **이동국** | [![GitHub](https://img.shields.io/badge/GitHub-cadst-181717?style=flat-square&logo=github)](https://github.com/cadst)              | API 통신      |
| **조지운** |                                                                                                                                    |               |
| **김지현** |                                                                                                                                    |               |

## 🎓 학습 포인트

- **React 컴포넌트 설계**: 재사용 가능한 공용 컴포넌트 개발
- **Next.js Pages Router**: 파일 기반 라우팅 및 SSR 구현
- **비동기 통신**: axios를 활용한 서버 데이터 처리
- **상태 관리**: 전역 상태 관리 및 Context API 활용
- **AWS 인프라**: S3 이미지 스토리지 및 CloudFront CDN 구축
- **팀 협업**: Git 브랜치 전략 및 코드 리뷰 프로세스

## 📜 라이센스

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 감사의 글

이 프로젝트는 **코드잇 스프린트 Front-End 19기** 교육 과정의 팀 프로젝트로 제작되었습니다.
