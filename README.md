# Wikid
자신과 지인들의 위키를 작성하고 공유하는 서비스 플랫폼.

## 개발 기간
2024.06.22 ~ 2024.07.09

## 참여 인원
|      **고한샘**|                                                           **김승래**|                 **신승헌**|                                                        **이율**|                                                               **장소희**|
| :-: | :-: | :-: | :-: | :-: |
|[<img src="https://avatars.githubusercontent.com/u/155063714?v=4" height=100> <br/> @gohansaem1](https://github.com/gohansaem1)| [<img src="https://avatars.githubusercontent.com/u/160004698?v=4" height=100> <br/> @JustDevRae](https://github.com/JustDevRae) | [<img src="https://avatars.githubusercontent.com/u/137388618?v=4" height=100> <br/> @AdamSeungheonShin](https://github.com/AdamSeungheonShin) | [<img src="https://avatars.githubusercontent.com/u/21290609?v=4" height=100> <br/> @yulrang](https://github.com/yulrang) | [<img src="https://avatars.githubusercontent.com/u/77830806?v=4" height=100> <br/> @han9898](https://github.com/han9898) |

## 기술스택
- **Typescript**
- **Next.js(Page Router)** 
- **TailwindCSS** 
- **Axios** 
- **React-Query** 
- **React-Hook-Form**
- **Zod**
- **MatineUI**

## 주요 기능
1️⃣ 로그인/회원가입/계정 설정 <br> 
2️⃣ 나의 위키페이지 생성, 콘텐츠 업로드, 수정, 삭제, 댓글기능 <br>
3️⃣ 자유게시판 콘텐츠 업로드, 수정, 삭제, 댓글기능 <br>
4️⃣ 좋아요, 알림 기능 <br>



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

