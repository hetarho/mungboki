# 멍보기 (Mungboki)

강아지와 함께하는 산책 만보기 앱

## 프로젝트 구조

```
mungboki/
├── app/       # Flutter 모바일 앱
├── web/       # React 웹 프론트엔드
└── server/    # Express API 서버
```

## 기술 스택

### Mobile (app/)
- Flutter 3.11+ / Dart
- Riverpod (상태관리)
- Supabase Flutter (인증/DB)
- Google Maps, Geolocator (지도/위치)
- Pedometer, Sensors Plus (걸음수/센서)
- Hive CE (로컬 저장소)
- FL Chart (차트)

### Web (web/)
- React 19 + TypeScript
- Vite 7 + TailwindCSS 4
- Zustand (상태관리)
- TanStack Query (서버 상태)
- Leaflet (지도)
- Recharts (차트)
- React Hook Form + Zod (폼/검증)

### Server (server/)
- Node.js + Express 5
- Supabase (PostgreSQL)
- Firebase Admin (푸시 알림)
- Swagger (API 문서)
- Winston (로깅)
- Zod (검증)

## 시작하기

```bash
# 웹
cd web && pnpm install && pnpm dev

# 서버
cd server && pnpm install

# 모바일
cd app && flutter pub get && flutter run
```
