# 🌐 Global Nomad
![Image](https://github.com/user-attachments/assets/4a15ce9a-0024-427d-9460-1230703d29a2)
> **" Global Nomad는 캘린더 뷰 SDK와 지도 뷰 SDK를 활용해 예약 가능한 날짜를 설정하고, 체험 상품을 예약하는 기능을 제공하는 웹 애플리케이션입니다."**
> 

---
### 📚 목차
- [👤 팀원 소개 & 역할]
- [🔗 배포 환경 및 기간]
- [✨ 주요 기능 요약]
- [⚙️ 설치 및 실행 방법]
- [🛠 Tech Stack]
- [⭐ 사용된 주요 라이브러리]
- [📂 폴더 및 파일 구조]
- [🧾 네이밍 규칙]
- [🌿 Git Branch 전략]
- [💬 커밋 메시지 컨벤션]

---

### 👤 팀원 소개 & 역할
<table>
  <tr>
    <th>프로필</th>
    <th>이름</th>
    <th>GitHub</th>
    <th>주요 담당 기능</th>
  </tr>
  <tr>
    <td align="center"><img src="https://avatars.githubusercontent.com/u/81224667?v=4" width="140" /></td>
    <td align="center"><strong>나예진</strong><br>(NaYejin)</td>
    <td align="center"><a href="https://github.com/NaYejin94">@JjinJjin</a></td>
    <td>
      <ul>
        <li>API 작성</li>
        <li>datepicker 구현</li>
        <li>체험 상세페이지</li>
        <li>페이지네이션</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><img src="https://avatars.githubusercontent.com/u/81631735?v=4" width="140" /></td>
    <td align="center"><strong>박원현</strong><br>(ParkWonHyun)</td>
    <td align="center"><a href="https://github.com/CIrcle0616">@CIrcle0616</a></td>
    <td>
      <ul>
        <li>App 라우터 폴더구조</li>
        <li>가이드 문서 작성 (라우팅, API 반환값 Type)</li>
        <li>Vercel 배포</li>
        <li>로그인/회원가입 페이지</li>
        <li>메인 페이지</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><img src="https://avatars.githubusercontent.com/u/120624055?v=4" width="140" /></td>
    <td align="center"><strong>박찬영</strong><br>(ParkChanYoung)</td>
    <td align="center"><a href="https://github.com/Parkchanyoung0710">@Parkchanyoung0710</a></td>
    <td>
      <ul>
        <li>global.css</li>
        <li>검색 컴포넌트, Top 버튼</li>
        <li>사이드 프로필</li>
        <li>빈 화면 페이지</li>
        <li>예약 내역 페이지 및 무한스크롤</li>
        <li>404 에러 페이지</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><img src="https://avatars.githubusercontent.com/u/61350224?v=4" width="140" /></td>
    <td align="center"><strong>오종택</strong><br>(OhJongTaek)</td>
    <td align="center"><a href="https://github.com/ohjongteak">@ohjongteak</a></td>
    <td>
      <ul>
        <li>포맷팅 (prettier, eslint, husky)</li>
        <li>공통 모달</li>
        <li>내 체험 관리페이지</li>
        <li>내 체험 등록</li>
        <li>수정 페이지</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><img src="https://avatars.githubusercontent.com/u/16948775?v=4" width="140" /></td>
    <td align="center"><strong>전수영</strong><br>(JeonSuYeong)</td>
    <td align="center"><a href="https://github.com/daonJeon">@daonJeon</a></td>
    <td>
      <ul>
        <li>스토리북</li>
        <li>공통 버튼 컴포넌트</li>
        <li>레포 문서 템플릿</li>
        <li>내정보 관리페이지</li>
        <li>메인 페이지</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><img src="https://avatars.githubusercontent.com/u/192935871?v=4" width="140" /></td>
    <td align="center"><strong>조지현</strong><br>(JoJiHyeon)</td>
    <td align="center"><a href="https://github.com/zeon0xx0">@zeon0xx0</a></td>
    <td>
      <ul>
        <li>gnb</li>
        <li>footer</li>
        <li>공통 드롭다운</li>
        <li>input 컴포넌트</li>
        <li>예약 현황 페이지</li>
        <li>예약 컴포넌트</li>
        <li>알림</li>
      </ul>
    </td>
  </tr>
</table>



### 🔗 배포 환경 및 기간
- **배포 주소**: [Global Nomad](https://global-nomad-black.vercel.app/)
- **배포 환경**: vercel
- **개발 기간**: 2025.05.27 ~ 2025.06.23

---

### 🔐 테스트 로그인 안내

> 회원가입 없이 서비스를 바로 체험해볼 수 있도록 테스트 계정을 제공합니다.
> 로그인 후 예약, 후기 작성, 내정보 수정 등의 기능을 자유롭게 테스트해보세요.
- **이메일:** `test@gmail.com`  
- **비밀번호:** `12341234`
---

### ✨ 주요 기능 
<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/1c878f0f-e5db-4ab6-b872-06ab5b392f5d" width="100%"/><br/>
      <strong>회원가입</strong>
      <p style="text-align: left;">이메일과 비밀번호를 입력하여 간편하게 회원가입할 수 있으며, 유효성 검사를 통해 정확한 정보만 입력됩니다.</p>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/f72a8e83-994d-4890-80b8-06a0ee0840e0" width="100%"/><br/>
      <strong>로그인</strong>
      <p style="text-align: left;">가입한 계정으로 로그인하여 체험 예약 및 후기를 작성할 수 있습니다. 로그인 정보는 안전하게 관리됩니다.</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/e2c919f3-4944-4c7c-bdd2-789b28156080" width="100%"/><br/>
      <strong>체험상세 조회</strong>
      <p style="text-align: left;">체험의 위치, 일정, 가격, 설명 등을 상세히 확인할 수 있어 예약 전 충분한 정보 탐색이 가능합니다.</p>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/ecec065d-d120-4a81-a319-6470bd8b621b" width="100%"/><br/>
      <strong>예약하기</strong>
      <p style="text-align: left;">희망하는 날짜와 인원을 선택하여 체험을 예약할 수 있습니다. 예약 가능 여부는 실시간으로 확인됩니다.</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/c6374df2-9778-45f5-a329-b88bb4530cb4" width="100%"/><br/>
      <strong>예약 승인 및 알림기능</strong>
      <p style="text-align: left;">체험 제공자가 예약을 승인하면, 사용자에게 실시간 알림을 통해 예약 확정 여부를 안내합니다.</p>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/bed6731d-f65c-425f-b6ec-fd6d5297b8ed" width="100%"/><br/>
      <strong>예약내역</strong>
      <p style="text-align: left;">예정된 예약을 무한 스크롤 방식과 필터 기능을 통해 예약 상태도 직접 확인할 수 있다.</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/11760a17-ad01-4493-a320-97325207f392" width="100%"/><br/>
      <strong>체험후기 작성 및 예약취소</strong>
      <p style="text-align: left;">참여한 체험에 대한 후기를 남길 수 있고, 체험 일정 이전에는 예약을 간편하게 취소할 수 있습니다.</p>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/73b1b51c-842c-4ad9-8def-ae1369346ca6" width="100%"/><br/>
      <strong>내정보 수정</strong>
      <p style="text-align: left;">프로필 이미지, 닉네임, 연락처, 비밀번호 등의 개인정보를 수정할 수 있습니다.</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/97a5c658-ca8c-4dd5-a2c6-4f405c0454b4" width="100%"/><br/>
      <strong>체험 등록</strong>
      <p style="text-align: left;">체험 제공자가 새로운 체험을 등록할 수 있는 기능입니다. 일정, 설명, 위치, 이미지를 포함한 정보를 입력할 수 있습니다.</p>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/5e7cec97-b127-4cf5-a2ae-b133b20eb4bb" width="100%"/><br/>
      <strong>체험 수정</strong>
      <p style="text-align: left;">체험 제공자가 불러온 체험을 일정, 설명, 이미지 등을 간편하게 수정할 수 있습니다.</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/1ce698eb-9b59-4547-a774-a477b085839d" width="100%"/><br/>
      <strong>체험 삭제</strong>
      <p style="text-align: left;">운영이 종료된 체험은 삭제하여 더 이상 사용자에게 노출되지 않도록 관리할 수 있습니다.</p>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/109f3191-cdf3-4816-8835-5b70ea30e5a1" width="100%"/><br/>
      <strong>404 페이지</strong>
      <p style="text-align: left;">존재하지 않는 주소로 접근 시, 사용자에게 친절한 안내 메시지를 제공하는 페이지입니다.</p>
    </td>
  </tr>
</table>

### ⚙️ 설치 및 실행 방법

```bash
# 1. 저장소 클론
$ git clone [저장소 URL]
$ cd [프로젝트 디렉토리]

# 2. 의존성 설치
$ npm install

# 3. 개발 서버 실행
$ npm run dev
```

---

### 🛠 Tech Stack
> 본 프로젝트는 아래 기술 스택을 기반으로 구성되었습니다.
---

<table>
  <tr>
    <th>역할</th>
    <th>사용 기술</th>
    <th>도입한 이유</th>
  </tr>
  <tr>
    <td>언어 & 프레임워크</td>
    <td>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=white" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
    </td>
    <td>파일 기반 라우팅과 서버 컴포넌트 지원으로 빠른 렌더링과 유지보수가 용이하기 때문입니다.</td>
  </tr>
  <tr>
    <td>UI & 스타일링</td>
    <td>
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
    </td>
    <td>빠른 스타일링과 일관성 있는 디자인 시스템 구성을 위해 선택했습니다.</td>
  </tr>
  <tr>
    <td>라우팅 & 상태 관리</td>
    <td>
      <img src="https://img.shields.io/badge/App_Router-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=react-query&logoColor=white" />
      <img src="https://img.shields.io/badge/Zustand-000000?style=flat-square&logo=Zustand&logoColor=white" />
    </td>
    <td>서버와 클라이언트 상태를 명확히 분리해 코드 관리와 성능을 개선하기 위해 사용했습니다.</td>
  </tr>
  <tr>
    <td>API & 인증</td>
    <td>
      <img src="https://img.shields.io/badge/Fetch_API-native?style=flat-square&logo=javascript&logoColor=white" />
    </td>
    <td>간단하고 직관적인 네이티브 API로 데이터 요청을 처리하기 위해 사용했습니다.</td>
  </tr>
  <tr>
    <td>빌드 & 배포</td>
    <td>
      <img src="https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
    </td>
    <td>빠른 빌드 및 배포 환경을 구성하고, 최적화된 정적 파일 서비스를 위해 사용했습니다.</td>
  </tr>
  <tr>
    <td>코드 품질</td>
    <td>
      <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white" />
      <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black" />
      <img src="https://img.shields.io/badge/Husky-000000?style=flat-square&logo=git&logoColor=white" />
    </td>
    <td>팀 전체의 코드 스타일을 통일하고 협업 중 충돌을 줄이기 위해 도입했습니다.</td>
  </tr>
  <tr>
    <td>UI 협업</td>
    <td>
      <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white" />
    </td>
    <td>독립적인 UI 컴포넌트 개발과 문서화를 위해 사용했습니다.</td>
  </tr>
</table>


---

### ⭐ 사용된 주요 라이브러리
<table>
  <tr>
    <th>라이브러리</th>
    <th>로고</th>
    <th>도입한 이유</th>
  </tr>
    <td>React Query (useInfiniteQuery)</td>
    <td>
     <img src="https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=react-query&logoColor=white" style="vertical-align: middle;" />
    </td>
    <td>useInfiniteQuery를 사용하면 무한 스크롤 또는 페이지네이션 기능을 손쉽게 구현할 수 있어 사용자 경험을 향상시킵니다</td>
  </tr>
</table>

---

 
### 📂 폴더 및 파일 구조 (Folder Structure)

```
/
├── public/                      # 정적 파일 (이미지, 폰트 등)
├── src/
│   ├── app/                     # Next.js App Router (라우팅, 페이지, 레이아웃, 로딩 UI, 에러 UI 등)
│   │   ├── (auth)/              # 라우트 그룹 (예: 인증 관련 페이지)
│   │   │   └── login/
│   │   │       └── page.tsx
│   │   ├── api/                 # API 라우트 핸들러 (Route Handlers)
│   │   │   └── hello/
│   │   │       └── route.ts
│   │   ├── layout.tsx           # 루트 레이아웃
│   │   ├── page.tsx             # 루트 페이지
│   │   └── global.css           # 전역 스타일 (Tailwind CSS import 등)
│   ├── components/              # 재사용 가능한 UI 컴포넌트
│   │   ├── common/              # 여러 도메인에서 사용되는 범용 컴포넌트 (Button, Input 등)
│   │   │   ├── Button.tsx
│   │   │   └── Input.tsx
│   │   └── domain/              # 특정 도메인에 종속적인 컴포넌트 (예: ProductCard)
│   │       └── product/
│   │           └── ProductCard.tsx
│   ├── constants/               # 전역적으로 사용되는 상수 (API URL, 공통 메시지 등)
│   │   └── index.ts
│   ├── contexts/                # React Context API 사용 시 (Zustand로 대부분 대체 가능)
│   │   └── AuthContext.tsx
│   ├── hooks/                   # 커스텀 React Hooks
│   │   └── useAuth.ts
│   ├── lib/                     # 라이브러리 헬퍼, 유틸리티 함수 (React Query 클라이언트 설정 등)
│   │   ├── queryClient.ts
│   │   └── utils.ts
│   ├── services/                # API 요청 로직 (React Query와 함께 사용)
│   │   ├── userService.ts
│   │   └── productService.ts
│   ├── store/                   # Zustand 스토어 정의
│   │   └── useAuthStore.ts
│   ├── styles/                  # 전역 스타일 또는 테마 관련 스타일 (global.css 외 추가)
│   │   └── theme.ts
│   ├── types/                   # 전역 TypeScript 타입 및 인터페이스
│   │   ├── index.ts             # 모든 타입을 export 하는 메인 파일
│   │   └── user.ts
│   └── middleware.ts            # Next.js 미들웨어
├── .eslintrc.json               # ESLint 설정 파일
├── .prettierrc.json             # Prettier 설정 파일
├── next.config.mjs              # Next.js 설정 파일
├── tailwind.config.ts           # Tailwind CSS 설정 파일
├── tsconfig.json                # TypeScript 설정 파일
└── package.json

```
---

### 🧾 네이밍 규칙

| 항목 | 방식 | 예시 |
|------|------|------|
| 폴더명 | camelCase  | userService |
| 컴포넌트 | PascalCase | UserProfile.tsx |
| css클래스 | kebab-case + .styles.js | wiki-section.styles.js |
| 이미지 | kebab-case | logo-icon.png |
| 변수/함수 | camelCase | getUserInfo |
| 환경변수 | UPPER_SNAKE_CASE | NEXT_PUBLIC_API_URL |
---


### 🌿 Git Branch 전략

| 브랜치명 | 목적 |
|----------|------|
| `main` | 배포 전용 브랜치 |
| `develop` | 통합 개발 브랜치 |
| `feature/*` | 기능 개발 단위 브랜치 |
| `fix/*` | 버그 수정 브랜치 |
| `docs/*` | 문서 관련 브랜치 |

---

### 💬 커밋 메시지 컨벤션

| 태그 | 의미 |
|------|------|
| Feat | ✨ 기능 추가 |
| Fix | 🐛 버그 수정 |
| Style | 💄 스타일 변경 |
| Docs | 📝 문서 변경 |
| Refactor | 🔨 리팩토링 |
| Test | ✅ 테스트 코드 |
| Chore | 🔧 기타 설정 변경 |

```

---

