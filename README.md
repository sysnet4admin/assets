# assets

강의 소개 페이지처럼 다른 곳에서 링크해서 보여 주는 그림을 모아 둔다. 사용하는 곳별로 폴더를 나눈다.

| 폴더 | 내용 |
|---|---|
| `inflearn/roadmap/` | 인프런 강의 상세소개에 넣는 강의 로드맵. 파일 이름은 인프런 강의 번호다. 그 강의 상자에 "Now"가 붙는다 |

## 주소

jsDelivr로 연결한다.

```
https://cdn.jsdelivr.net/gh/sysnet4admin/assets@main/<경로>
```

예: `https://cdn.jsdelivr.net/gh/sysnet4admin/assets@main/inflearn/roadmap/326651.png`

## 지킬 것

- 파일의 경로와 이름을 바꾸지 않는다. 바꾸면 이미 여러 페이지에 들어간 주소로 그림이 보이지 않는다. 그림을 수정할 때는 같은 경로에 덮어쓴다.
- 그림을 수정한 뒤에는 jsDelivr 캐시를 비운다. `https://purge.jsdelivr.net/gh/sysnet4admin/assets@main/<경로>`를 열면 된다.

## 저작권

이 저장소의 그림은 조훈(Hoon Jo)의 강의와 채널을 소개하려고 만들었다. 다른 용도로 사용하지 않는다. All rights reserved.
