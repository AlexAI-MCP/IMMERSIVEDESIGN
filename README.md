# Immersive Studio

VR/AR과 3D 디자인 스튜디오 웹사이트 - Railway 배포용 프로젝트

## 프로젝트 소개

**Immersive Studio**는 몰입형 현실을 디자인하는 스튜디오 웹사이트입니다. VR/AR 디자인, 3D 공간 경험, 인터랙티브 설치물, 디지털 트윈 솔루션을 제공합니다.

## 주요 기능

- 🎨 VR/AR 디자인
- 🌐 3D 공간 경험
- 💫 인터랙티브 설치물
- 🏗️ 디지털 트윈 솔루션

## Railway에서 배포하기

1. [Railway](https://railway.app/) 계정 생성
2. 새 프로젝트 생성
3. GitHub 리포지토리 연결 (`AlexAI-MCP/IMMERSIVEDESIGN`)
4. 브랜치 선택: `claude/railway-deployment-setup-011CV51q5QCXbMH8UXnCkYW1`
5. 자동 배포 완료!

## 로컬에서 실행하기

```bash
# 의존성 설치
npm install

# 서버 실행
npm start
```

브라우저에서 `http://localhost:3000` 을 열어보세요.

## 프로젝트 구조

```
/
├── public/
│   ├── index.html      # Immersive Studio 메인 페이지
│   └── screen.png      # 스크린샷/이미지 자산
├── server.js           # Express 정적 파일 서버
├── package.json        # Node.js 프로젝트 설정
└── README.md
```

## 기술 스택

- **Frontend**: HTML5, Tailwind CSS
- **Backend**: Node.js, Express
- **Deployment**: Railway
- **Design**: Google Stitch
