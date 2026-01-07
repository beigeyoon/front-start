# front-start

프론트엔드 트렌드를 자동으로 수집하고 대시보드로 보여주는 프로젝트입니다.

## 프로젝트 개요

원하는 주기(매일/매주)로 온라인 상의 프론트엔드 관련 이슈를 자동으로 수집하여 대시보드에 표시합니다.

## MVP 기능

1. **커뮤니티 이슈/주제 Top 5**
   - 커뮤니티에서 많이 언급된 이슈와 주제를 상위 5개 표시

2. **주목할 만한 라이브러리/프레임워크 Top 5**
   - 갑자기 다운로드 수가 급증한 npm 패키지
   - 공식 릴리즈가 배포된 라이브러리/프레임워크

3. **AI 추천 프론트엔드 토픽**
   - AI가 추천하는 프론트엔드 관련 주제

## 기술 스택

- **Framework**: Next.js 16.1.1
- **React**: 19.2.3
- **TypeScript**: 5.x
- **스타일링**: Tailwind CSS v4
- **코드 품질**: Biome
- **패키지 매니저**: pnpm

## 시작하기

### 설치

```bash
pnpm install
```

### 개발 서버 실행

```bash
pnpm dev
```

브라우저에서 [http://localhost:3000](http://localhost:3000)을 열어 확인하세요.

## 스크립트

- `pnpm dev` - 개발 서버 실행
- `pnpm build` - 프로덕션 빌드 (빌드 전 자동으로 `pnpm check` 실행)
- `pnpm start` - 프로덕션 서버 실행
- `pnpm check` - Biome으로 코드 검사 및 자동 수정
- `pnpm format` - Biome으로 코드 포맷팅
- `pnpm lint` - Biome으로 린팅만 실행 (수정 없음)

