# 데일리북 — 보내기 버튼

[데일리북](https://github.com/reepower84-png/daily-book)의 오늘치를 **보낼지 말지 결정하는 한 장짜리 페이지**입니다.

매일 아침 디스코드로 "오늘 데일리북을 전송할까요?" 알림이 오면,
그 링크로 들어와 버튼을 누를 때만 메일이 나갑니다. 누르지 않으면 아무 일도 일어나지 않습니다.

- 주소: <https://reepower84-png.github.io/daily-book-app/>
- 이 저장소는 공개지만 **비밀은 하나도 없습니다.** 읽는 책·진도·메일 주소·발송 설정은
  모두 비공개 저장소 `daily-book` 에 있고, 이 페이지는 브라우저에 저장된 개인 토큰으로
  그 저장소의 발송 워크플로를 실행시킬 뿐입니다.
- 토큰은 이 기기의 `localStorage` 에만 있습니다. 서버로 보내지 않습니다.

## 처음 설정

1. 페이지를 열면 토큰을 물어봅니다.
2. [Fine-grained PAT 발급](https://github.com/settings/personal-access-tokens/new)
   - Repository access: **Only select repositories** → `daily-book`
   - Permissions: **Actions** = Read and write, **Contents** = Read-only
3. 붙여넣고 저장하면 끝. 이후로는 링크만 열면 됩니다.
4. (선택) 브라우저 메뉴 → '홈 화면에 추가' 하면 앱처럼 쓸 수 있습니다.
