# 글로컬 AI 디지털북 프로젝트 — 활동지 모음 (포털)

일차별 활동지로 가는 문. **링크만 모읍니다.**

## Production

https://glocal-worksheet.vercel.app/

| 일차 | 장르 | URL |
|---|---|---|
| 1 | 시 | https://glocal-worksheet-day1.vercel.app/ |
| 2 | 그림 에세이 | https://glocal-worksheet-day2.vercel.app/ |
| 3 | 문화탐방기행집 설계 | https://glocal-worksheet-day3.vercel.app/ |
| 4 | 문화탐방기행집 | *(아직)* — 카드만 자리를 잡아 두고 잠가 두었다 |

## 왜 링크만인가

각 활동지의 저장은 `localStorage`이고, `localStorage`는 **출처(origin)마다 갇힌다.**
`glocal-worksheet.vercel.app`에서는 `glocal-worksheet-day1.vercel.app`의 저장을 읽을 수 없다.
그래서 이 포털은 수강생이 적은 내용을 보여 줄 수 없고, 보여 주는 척해서도 안 된다.
그 사실을 페이지 안에 적어 두었다 — 「적은 내용은 어디에 있습니까」.

## 기존 주소는 그대로 둔다

포털은 **대체가 아니라 추가**다. 이미 채팅으로 배포된 세 주소가 계속 살아 있어야 한다.

## 4일차를 열 때

`index.html`의 `card--locked`를 지우고 `<div>`를 `<a href="...">`로 바꾼다. 그게 전부다.

## 로컬

```bash
npx serve .
```
