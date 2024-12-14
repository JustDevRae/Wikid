# Wikid

## 프로젝트 소개
자신과 지인들의 위키를 작성하고 공유하는 서비스 플랫폼.

## 개발 기간
2024.06.22 ~ 2024.07.09

## 참여 인원
|      **고한샘**|                                                           **김승래**|                 **신승헌**|                                                        **이율**|                                                               **장소희**|
| :-: | :-: | :-: | :-: | :-: |
|[<img src="https://avatars.githubusercontent.com/u/155063714?v=4" height=100> <br/> @gohansaem1](https://github.com/gohansaem1)| [<img src="https://avatars.githubusercontent.com/u/160004698?v=4" height=100> <br/> @JustDevRae](https://github.com/JustDevRae) | [<img src="https://avatars.githubusercontent.com/u/137388618?v=4" height=100> <br/> @AdamSeungheonShin](https://github.com/AdamSeungheonShin) | [<img src="https://avatars.githubusercontent.com/u/21290609?v=4" height=100> <br/> @yulrang](https://github.com/yulrang) | [<img src="https://avatars.githubusercontent.com/u/77830806?v=4" height=100> <br/> @han9898](https://github.com/han9898) |

## 기술스택
**Typescript :** 컴파일에서 타입 에러를 발견하여 프로젝트 안정성을 높이기 위해 사용.

**Next.js(Page Router) :** PageRouter의 파일 기반 라우팅 시스템을 통해 별도로 라우팅 설정을 할 필요 없이 파일 구조만으로 라우팅을 자동으로 처리하여, 개발 속도 향상과 간편한 유지보수를 위해 사용.

**TailwindCSS :** 직관적이고 효율적으로 UI를 구성하기 위해 사용.

**Axios :** 자동 JSON 파싱과 인터셉트 기능으로 중복 코드 개선하기 위해 사용.

**React-Query:** 간편한 데이터 패칭과 자동으로 캐싱하고 데이터를 실시간으로 동기화하기 위해 사용.

**React-Hook-Form & Zod :** 유효성 검증을 단순화하고 일관성을 유지하면서, 사용자에게 즉각적인 피드백을 제공하기 위해 사용.

**MatineUI :** MatineUI에서 제공하는 컴포넌트들을 사용하여 간결하고 일관성 있는 코드를 작성하기 위해 사용.

## 폴더구조
```
📦 src
├─ apis 
├─ components
│  ├─ AddBoard
│  ├─ board
│  ├─ DetailBoard 
Layout
│  │  └─ Header
│  ├─ MyPage
│  ├─ Wiki
│  ├─ WikiList
│  └─ PageNation.tsx
├─ constants
├─ contexts
├─ hooks
├─ pages
│  ├─ addboard
│  │  └─ index.tsx
│  ├─ boards
│  │  ├─ [id]
│  │  │  └─ index.tsx
│  │  └─ index.tsx
│  ├─ login
│  │  └─ index.tsx
│  ├─ signup
│  │  └─ index.tsx
│  ├─ mypage
│  │  └─ index.tsx
│  ├─ wiki
│  │  ├─ [id]
│  │  │  └─ index.tsx
│  │  └─ index.tsx
│  ├─ wikilist
│  │  └─ index.tsx
│  ├─ _app.ts
│  ├─ _document.ts
│  └─ index.ts
├─ schema
├─ styles
├─ types
└─ utils
```
## 주요 기능
### 로그인/회원가입/계정 설정
- Zod로 스키마화된 유효성 검증을 적용해 중복 로직을 제거하고 코드를 간결화.
- React-Hook-Form의 `mode: "all"`을 사용해 실시간 검증 및 즉각적인 피드백 제공.
- MantineUI 컴포넌트와 동적 스타일링으로 일관된 UI와 시각적 피드백을 구현하여 UX 개선.

### 알림
- react-query를 활용하여 알림의 상태를 최신으로 유지.
- ContextAPI를 활용하여 유저의 로그인 상태를 전역으로 관리.

### 위키 작성

### 모달을 통한 인증

### 댓글/답글 작성
