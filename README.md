# front-start

프론트엔드 트렌드를 자동으로 수집하고 대시보드로 보여주는 프로젝트입니다.

## 프로젝트 개요

원하는 주기(매일/매주)로 온라인 상의 프론트엔드 관련 이슈를 자동으로 수집하여 대시보드에 표시합니다.

## MVP 기능

1. **커뮤니티 이슈/주제 Top 5** - 커뮤니티에서 많이 언급된 이슈와 주제
2. **주목할 만한 라이브러리/프레임워크 Top 5** - 다운로드 수 급증 또는 공식 릴리즈 배포
3. **AI 추천 프론트엔드 토픽** - AI가 추천하는 프론트엔드 관련 주제

## 기술 스택

- **Framework**: Next.js 16.1.1
- **React**: 19.2.3
- **TypeScript**: 5.x
- **스타일링**: Tailwind CSS v4
- **코드 품질**: Biome
- **패키지 매니저**: pnpm (workspaces)

## 프로젝트 구조

```
front-start/
├── apps/
│   ├── client/     # Next.js 프론트엔드
│   └── server/     # 백엔드 서버
└── package.json    # 워크스페이스 루트
```

## 시작하기

### 설치

```bash
pnpm install
```

### 개발 서버 실행

```bash
pnpm dev              # 클라이언트만 실행
pnpm dev:server       # 서버만 실행
pnpm dev:all         # 클라이언트와 서버 동시 실행
```

브라우저에서 [http://localhost:3000](http://localhost:3000)을 열어 확인하세요.

## 스크립트

- `pnpm dev` / `pnpm dev:client` - 클라이언트 개발 서버
- `pnpm dev:server` - 서버 개발 서버
- `pnpm dev:all` - 클라이언트와 서버 동시 실행
- `pnpm build` / `pnpm build:client` - 클라이언트 빌드 (빌드 전 자동으로 `pnpm check` 실행)
- `pnpm build:server` - 서버 빌드
- `pnpm build:all` - 클라이언트와 서버 모두 빌드
- `pnpm check` - Biome 코드 검사 및 자동 수정
- `pnpm format` - Biome 코드 포맷팅
- `pnpm lint` - Biome 린팅 (수정 없음)
