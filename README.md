
```markdown
# Moimo-Back

모이모(Moimo)는 **실시간 모임 모집 및 채팅 플랫폼**입니다.  
이 레포지토리는 백엔드 서버 코드로, 사용자 인증, 모임 관리, 실시간 채팅 기능을 제공합니다.

---

## 🚀 주요 기능
- 회원가입, 로그인, 로그아웃 (JWT 기반 인증/인가)
- Google OAuth 소셜 로그인
- 프로필 이미지 업로드 (Google Cloud Storage)
- 모임 생성 및 참여 관리
- WebSocket 기반 실시간 채팅
- 데이터베이스 모델링 및 관리 (Prisma + PostgreSQL)

---

## 🛠️ 기술 스택
- **Backend Framework**: NestJS, Express
- **Database**: PostgreSQL, Prisma ORM
- **Authentication**: JWT, Google OAuth
- **Real-time**: WebSocket
- **Cloud**: Google Cloud Storage
- **Deployment**: Vercel, Render
- **Collaboration**: GitHub (PR, Branch 전략)

---

## 📂 프로젝트 구조
```
moimo-back/
 ├── src/
 │   ├── auth/        # 인증 및 인가 로직
 │   ├── users/       # 사용자 관리
 │   ├── meetings/    # 모임 관리
 │   ├── chat/        # 실시간 채팅
 │   └── main.ts      # 엔트리 포인트
 ├── prisma/          # Prisma schema
 ├── .env.example     # 환경 변수 예시
 └── README.md
```

---

## ⚙️ 설치 및 실행 방법

### 1. 레포지토리 클론
```bash
git clone https://github.com/KingJae6721/moimo-back.git
cd moimo-back
```

### 2. 패키지 설치
```bash
npm install
```

### 3. 환경 변수 설정
env 파일은 관리자에게 문의하세요!
```

### 4. 데이터베이스 마이그레이션
```bash
npx prisma migrate dev
```

### 5. 서버 실행
```bash
npm run start:dev
```

---

## 📑 배운 점
- NestJS 인증 구조와 JWT 기반 보안 처리
- WebSocket을 통한 실시간 통신 구현
- Google OAuth 및 Cloud Storage 연동 경험
- Vercel/Render 배포 과정에서 로컬과 프로덕션 환경 차이 이해
- GitHub 협업 (PR, 코드리뷰, 브랜치 전략)

---

## 👥 팀 구성
- Frontend: React, Vite, TanStack Query, Zustand, TailwindCSS
- Backend: NestJS, Prisma, PostgreSQL
- 팀원: 총 5명 (백엔드 2명, 프론트엔드 3명)
```
