# Immersive Design

Google Stitch로 디자인한 UI를 Railway에 배포하는 프로젝트입니다.

## 배포 방법

### Railway에서 배포하기

1. [Railway](https://railway.app/) 계정 생성
2. 새 프로젝트 생성
3. GitHub 리포지토리 연결
4. 자동으로 배포됩니다!

### 로컬에서 실행하기

```bash
# 의존성 설치
npm install

# 서버 실행
npm start
```

브라우저에서 `http://localhost:3000` 을 열어보세요.

## 파일 구조

```
/
├── public/          # 정적 파일 (HTML, CSS, JS, 이미지 등)
│   ├── index.html
│   ├── styles.css
│   └── script.js
├── server.js        # Express 서버
├── package.json
└── README.md
```

## UI 파일 추가하기

Google Stitch로 디자인한 파일들을 `public/` 폴더에 추가하세요:
- HTML 파일은 `public/index.html`에 붙여넣기
- CSS 파일은 `public/styles.css`에 추가
- JavaScript는 `public/script.js`에 추가
- 이미지/폰트는 `public/assets/` 폴더에 추가
