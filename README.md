# Owen | 풀스택 개발자

안경사로 일하다 개발자가 되었고, 지금은 헬스케어 스타트업에서 제품을 기획부터 배포·운영까지 혼자 만들고 있습니다.

[블로그](https://www.w-owen.com) · [LinkedIn](https://www.linkedin.com/in/seongwon-woo-4a11092a7/) · dnqkr18@gmail.com

<br>

## 🙋 소개

- **웹·모바일·데스크톱·VR**을 오가며 서버부터 화면까지 한 사람이 끝까지 책임지는 제품을 만들어 왔습니다.
- **타입을 먼저 정합니다.** 서버·웹·앱을 모노레포로 묶고, API 요청·응답 타입을 공유 패키지 하나에 두어 한쪽을 바꾸면 컴파일러가 나머지를 알려 주게 합니다.
- **틀리면 안 되는 곳은 데이터베이스로 막습니다.** 결제·재고·문자 발송·인증 토큰처럼 중복되거나 꼬이면 안 되는 흐름은 트랜잭션, 유니크 인덱스, 기록 테이블로 보장하고 테스트로 확인합니다.
- **AI 에이전트로 빠르게, 가드레일로 안전하게.** 명세 → 테스트 → 코드 순서를 훅과 CI로 강제해, 혼자서도 리뷰받은 것처럼 개발합니다.

<br>

## 💼 경력

- **헬스케어 스타트업 · 풀스택 개발자** (2025.05 ~ 현재): 안경원 운영 SaaS와 고객 앱, VR 시기능 진단·훈련 플랫폼(TechCrunch Disrupt 2026 시연), 근시 진행 예측 모델, 회사 웹사이트([icuvc.kr](https://www.icuvc.kr), [icucorp.kr](https://www.icucorp.kr))
- **해운 IT 기업 · 백엔드 개발자** (2024.01 ~ 2025.01): 선박 관리 플랫폼 서버 5종, 통합 로그인(SSO)·권한 관리, 기상 데이터 파이프라인(하루 2,400만 건)

<br>

## 🧩 개인 프로젝트 · 오픈소스

- [**fullstack-monorepo-starter**](https://github.com/wdevelope/fullstack-monorepo-starter): oRPC 계약 하나로 서버·웹·데스크톱(Electron)·모바일(Expo)을 묶은 TypeScript 모노레포. refresh 토큰 회전·재사용 감지 인증, 명세 ↔ 테스트 연결 검사, 테스트 먼저 강제 훅까지 포함
- [**w-life**](https://github.com/wdevelope/myblog) ([사이트](https://www.w-owen.com)): 운영 중인 개인 블로그. Next.js 16 + Supabase, 정적·ISR 공개 화면, RLS로 비공개 글 격리, 작성 칸에 바로 서식이 보이는 마크다운 에디터
- [**WKI**](https://github.com/wdevelope/wki) ([사용해 보기](https://wdevelope.github.io/wki/)): FSRS 간격 반복으로 영어 단어 2,809개를 외우는 오프라인 PWA
- [nativewind/nativewind#1869](https://github.com/nativewind/nativewind/pull/1869): React Native 스타일 라이브러리의 메모리 초과(OOM) 원인을 지수적 재귀로 찾아 수정 제안 (리뷰 중)

<br>

## 🤖 개발 방식

- 기능마다 명세에 시나리오 ID를 붙이고, 테스트 제목과 자동으로 연결해 빠진 테스트를 CI에서 잡습니다.
- Claude Code 훅이 테스트를 먼저 고치지 않은 로직 수정을 막고, 커밋마다 비밀값·타입 우회·`.only`를 검사합니다. ([예시](https://github.com/wdevelope/fullstack-monorepo-starter#development-workflow))
- 여러 에이전트를 git worktree로 나눠 병렬로 작업하고, 결과는 직접 다시 검증한 뒤 합칩니다.

<br>

## 🛠️ 기술

| 분야             | 기술                                                        |
| ---------------- | ----------------------------------------------------------- |
| 언어             | TypeScript, JavaScript, C#, Python                          |
| 프론트엔드       | React, Next.js, TanStack Query, Zustand, Tailwind CSS       |
| 백엔드           | Node.js(Express, NestJS, Hono), FastAPI                     |
| 모바일·데스크톱·VR | React Native(Expo), Electron, Unity 6(OpenXR)            |
| 데이터·ML        | PostgreSQL(Drizzle, TimescaleDB), MongoDB, Supabase, XGBoost |
| 인프라·테스트    | AWS(EC2, S3, CloudFront), Docker, GitHub Actions, Vitest, Playwright |

<br>

## 🎓 학력·자격

안경광학과 전문학사 · 컴퓨터공학과 학사(학점은행제) · 정보처리기사
