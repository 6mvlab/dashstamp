# DashStamp — 개인정보처리방침 / Privacy Policy

DashStamp 안드로이드 앱의 개인정보처리방침을 게시하는 저장소입니다.
앱 소스 코드는 들어 있지 않습니다.

*This repository publishes the privacy policy for the DashStamp Android app.
It contains no application source code.*

## 게시된 문서 / Published

- **[개인정보처리방침 / Privacy Policy](privacy-policy.html)**

| 파일 | 내용 |
|---|---|
| `privacy-policy.html` | 게시되는 페이지. Play Console에 넣는 주소 |
| `privacy-policy.md` | 같은 내용의 원본 마크다운 |
| `index.html` | 방침으로 가는 표지 |
| `.nojekyll` | GitHub Pages가 파일을 그대로 서빙하게 함 |

## 설정 / Setup

GitHub Pages: **Settings → Pages → Deploy from a branch → `master` / `/ (root)`**

## 갱신 / Updating

이 저장소의 파일은 **직접 편집하지 마세요.** 원본은 비공개 앱 저장소의
`docs/privacy-policy.md` 이고, 거기서 다음 명령으로 복사됩니다.

```
node scripts/export-policy.js ../dashstamp-policy
```

HTML은 마크다운에서 생성되므로 둘이 어긋날 수 없습니다. 여기서 손으로 고치면
다음 갱신 때 덮어쓰여지고, 그보다 나쁘게는 **앱이 하는 일과 방침이 말하는 일이
갈라집니다.**

*Do not edit these files here. The source is `docs/privacy-policy.md` in the
private app repository and is copied out with the command above; the HTML is
generated from the markdown so the two cannot disagree. An edit made here is
overwritten on the next export - and worse, splits what the policy says from
what the app does.*

## 문의 / Contact

6mvlab@gmail.com
