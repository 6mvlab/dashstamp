# DashStamp 개인정보처리방침 / Privacy Policy

**최종 수정일 / Last updated: 2026-10-19**

DashStamp(이하 "앱")는 주행 영상을 촬영하고, 촬영 시각과 위치를 영상에 직접
새겨 넣는 안드로이드 앱입니다.
이 문서는 앱이 회원님의 영상과 위치 정보를 어떻게 다루는지 설명합니다.

*DashStamp ("the app") records driving footage and burns the time and place it
was taken into the picture itself. This document explains how it handles your
footage and your location.*

---

## 요약 / Summary

**회원님의 영상은 이 기기를 벗어나지 않습니다.**
모든 녹화와 처리는 기기 안에서 이루어지며, 앱에는 서버가 없습니다.
영상을 업로드하거나 전송하거나 개발자가 열람하는 일은 없습니다.

**다만 위치에는 두 가지 짚을 점이 있습니다.**

1. 스탬프를 좌표 대신 **주소로 표시**하면, 좌표가 주소로 바꾸기 위해 안드로이드
   시스템 지오코더로 전송됩니다
   ([1-1](#1-1-주소-표시를-켜셨을-때--if-you-choose-the-address-stamp)).
   기본값인 **좌표 표시**에서는 이 전송이 없습니다.
2. 위치를 **알아내는** 일은 안드로이드가 하며, 위성이 잡히기 전에는 안드로이드가
   네트워크를 쓸 수 있습니다
   ([1-2](#1-2-안드로이드-위치-서비스에-대해--about-androids-location-service)).

**위치 표시를 끄시면 둘 다 일어나지 않습니다.**

앱은 **무료이며 광고가 있습니다.** 직접 촬영한 영상을 저장한 뒤에 전면 광고가
한 번 나옵니다. **한 번 결제하면 광고가 사라집니다**(3항).

*__Your footage never leaves this device.__ Everything happens on the phone,
the app has no server, and no recording is uploaded, transmitted, or seen by
the developer.*

*__Two things are worth naming about location.__ First, setting the stamp to
show an address sends your coordinates to the Android system geocoder to be
turned into one (1-1); on the default coordinates setting that never happens.
Second, working out the position is Android's job, and before the satellites
lock on Android may use the network to do it (1-2). Turn the location stamp off
and neither happens. The app is free and shows an advertisement after a manual
recording is saved; one payment removes them for good - see section 3.*

---

## 1. 위치 정보 / Location

이 앱에서 위치는 **영상에 찍어 넣기 위한 것**입니다.

**설정에서 위치 표시를 끄실 수 있습니다.** 끄면 앱은 위치 권한을 **요청하지도
않고**, 위치를 받지도 않습니다. 영상에는 시간만 찍힙니다.

*__You can turn the location stamp off in settings.__ With it off the app does
not even ask for the permission, takes no position, and stamps the time alone.*

- 위치는 **안드로이드의 위치 서비스**에서 받습니다. 위성 GPS를 우선 쓰고, 위성이
  아직 안 잡히는 동안에는 안드로이드가 주변 Wi-Fi·기지국으로 잡아주는 위치를
  씁니다 ([1-2](#1-2-안드로이드-위치-서비스에-대해--about-androids-location-service))
- 위치를 받는 때는 **앱이 화면에 있을 때**와 **녹화가 돌아가는 동안**입니다.
  녹화 중이라면 화면을 벗어나도 계속 받습니다 — 블랙박스가 그래야 하기 때문입니다
- 녹화하지 않는 상태로 앱을 벗어나면 **즉시 멈춥니다.** 주차 모드로 대기하는
  동안에도 받지 않습니다. 쓰지 않을 위치를 붙잡고 배터리를 쓸 이유가 없습니다
- 좌표는 **영상 화면에 그려지고**, 그 영상은 기기에 저장됩니다
- 앱은 위치를 **따로 기록하거나 목록으로 쌓아두지 않습니다.** 영상 안의 글자가
  전부입니다
- 측정된 지 몇 초가 지난 좌표에는 **측정 시각이 함께 찍힙니다.** 터널처럼 신호가
  끊긴 곳에서, 영상이 지나간 위치를 현재인 것처럼 주장하지 않기 위해서입니다

위치 권한을 거부하셔도 녹화는 됩니다. 영상에는 좌표 대신 `GPS 꺼짐`이 찍힙니다
(앱 언어에 따라 표시됩니다).

*Location exists in this app for one purpose: to be written onto the picture.
It comes from Android's location service - satellite GPS first, with Android's
Wi-Fi and cell positioning filling the gap until the satellites lock on. It is
read while the app is on screen and while a recording is running - a blackbox
recording keeps its position after the screen goes off, which is the point of
one - and stops as soon as you leave the app with nothing recording, parking
mode included. It is drawn into the frame, and that frame is saved on your
device. The
app keeps no separate location log: the text in the video is the whole of it. A
fix more than a few seconds old is stamped with the time it was taken, so
footage from a tunnel does not present an old position as the current one.
Decline the permission and recording still works; the frame says so in your
language instead of a position.*

### 1-1. 주소 표시를 켜셨을 때 / If you choose the address stamp

스탬프를 좌표 대신 **주소로 표시**하도록 설정하시면, 앱은 좌표를 **안드로이드
시스템 지오코더**에 넘겨 주소를 받아옵니다. 대부분의 기기에서 이 지오코더는
**구글이 운영하는 서버**입니다. 따라서 이 설정에서는 **좌표가 기기를
벗어납니다.**

- 이것이 **앱 자신이** 데이터를 기기 밖으로 보내는 **유일한 경로**입니다
- 전송되는 것은 **좌표뿐**입니다. 영상은 어떤 경우에도 전송되지 않습니다
- 약 20초에 한 번 요청합니다
- 구글이 이 요청을 어떻게 다루는지는 구글의 개인정보처리방침을 따릅니다. 개발자는
  이 요청의 내용을 받지도, 저장하지도 않습니다

**좌표 표시(기본값)로 두시면 이 요청은 전혀 발생하지 않습니다.**

*Set the stamp to show an address and the app hands your coordinates to the
Android system geocoder to get one back. On most devices that geocoder is a
Google-run service, so on this setting your coordinates do leave the device.
It is the only path by which the app itself sends anything out: what goes is the coordinates
alone, never the footage, roughly once every twenty seconds. What Google does
with the request is governed by Google's privacy policy; the developer neither
receives nor stores it. Leave the stamp on coordinates - the default - and the
request is never made.*

### 1-2. 안드로이드 위치 서비스에 대해 / About Android's location service

위치를 알아내는 일은 **앱이 아니라 안드로이드가** 합니다. 앱은 안드로이드에
"지금 어디입니까"를 묻고 좌표를 돌려받습니다.

- **위성 GPS**는 받기만 합니다. 전송이 없습니다
- 위성이 아직 안 잡혔을 때 안드로이드는 **주변 Wi-Fi와 기지국 정보로** 위치를
  추정하며, 이 방식은 구글 서버와 통신합니다

처음엔 위성만 쓰도록 만들었는데, **그러면 실내에서 위치가 아예 안 잡히고 야외에서도
1분 가까이 걸렸습니다.** 위치를 못 찍는 블랙박스는 의미가 없어서 되돌렸습니다.

이것은 **위치를 쓰는 모든 안드로이드 앱에 공통인 동작**이며, 앱이 끄거나 켤 수
있는 것이 아닙니다. 기기 설정의 `위치 → 위치 정확도 향상`(기기에 따라 이름이
다릅니다)에서 **회원님이** 끌 수 있고, 끄면 위성만 쓰게 됩니다.

위치 표시를 끄시면 앱은 안드로이드에 아무것도 묻지 않습니다.

*Working out where the phone is, is Android's job, not the app's: the app asks
Android and is handed coordinates. Satellite GPS only listens and sends
nothing. Until the satellites lock on, Android estimates the position from
nearby Wi-Fi and cell towers, and that method does talk to Google's servers.
This app was first written to use satellites only - and indoors it never got a
position at all, while outdoors it took close to a minute. A dashcam that
cannot stamp where it is has no point, so that was reverted. This is how every
Android app that uses location works and is not something an app can switch
off; you can switch it off yourself under Location in your phone's settings,
which leaves satellites only. Turn the location stamp off and the app asks
Android nothing.*

---

## 2. 영상 / Your footage

### 저장 위치 / Where it is kept

| 모드 / Mode | 저장되는 곳 / Stored |
|---|---|
| 직접 촬영 / Manual | 갤러리의 `DashStamp` 앨범 / The `DashStamp` album in your gallery |
| 블랙박스 / Blackbox | 앱 내부 저장공간 / The app's own storage |

블랙박스 영상이 갤러리로 가지 않는 이유는, 한 번 주행하면 짧은 영상이 수십 개
생겨 갤러리가 묻히기 때문입니다. 앱 안의 목록에서 보시고, 남기고 싶은 것만
갤러리로 내보내실 수 있습니다.

*Blackbox clips stay out of the gallery because one drive produces dozens of
them and would bury everything else in there. They live in the app's own list,
and you export the ones worth keeping.*

### 덮어쓰기 / Overwriting

블랙박스 모드는 **설정하신 용량만큼만 보관**하고, 넘으면 **가장 오래된 것부터
삭제**합니다.

잠근 영상과 충격이 감지된 영상은 **건너뜁니다** — 평범한 주행 영상 때문에 사고
기록을 잃는 일은 없습니다. 다만 **무제한은 아닙니다.** 잠긴 영상만으로 설정하신
용량의 두 배를 넘으면, 그중 가장 오래된 것부터 삭제됩니다. 그 지점에서는 가장
오래된 기록을 잃는 것과 **앞으로 아무것도 기록하지 못하는 것** 중 하나를 택해야
하기 때문입니다.

*Blackbox mode keeps the amount of footage you set and deletes the oldest to
make room. Locked clips and clips recorded after an impact are passed over, so
ordinary driving never costs you an incident - but they are not unlimited.
Once locked clips alone exceed twice your budget, the oldest of those go too:
at that point the choice is between losing the oldest incident and recording
nothing further at all.*

### 끝나지 못한 녹화 / Recordings that did not finish

직접 촬영한 영상은 앱 안에서 먼저 만들어진 뒤 갤러리로 옮겨집니다. 그 사이에
앱이 꺼지거나 저장이 실패하면 영상은 앱 안에 남고, **다음 실행 때 갤러리로
옮겨집니다.** 옮겨진 뒤에야 앱 안의 사본이 지워집니다.

예전에는 이것을 **지웠습니다.** 블랙박스에서는 녹화를 끝내지 못하게 만든 사건이
바로 찍고 싶었던 장면이므로, 버리지 않고 복구하도록 바꾸었습니다.

*A manual recording is made inside the app and then moved to your gallery. If
the app stops in between, or the move fails, the recording stays in the app and
is moved to the gallery on the next launch - the copy inside the app is removed
only once the gallery has it. These used to be deleted instead. On a dashcam
the recording that could not be finished is often the one worth having, so it
is recovered rather than thrown away.*

### 삭제 / Deleting

앱을 삭제하면 **앱 내부에 있던 블랙박스 영상도 함께 삭제됩니다.**
갤러리로 내보내신 영상은 남습니다.

*Uninstalling removes the blackbox clips held inside the app. Anything you
exported to the gallery stays.*

---

## 3. 광고와 구매 / Ads and the purchase

### 광고가 나오는 때 / When an ad appears

**직접 촬영한 영상이 갤러리에 저장된 뒤**에 전면 광고가 한 번 나옵니다.
저장이 끝난 다음입니다 — 광고가 녹화와 저장 사이에 끼는 일은 없습니다.

**블랙박스 구간에는 광고가 나오지 않습니다.** 주차 중 충격 영상도 마찬가지입니다.
블랙박스는 1~10분마다 자동으로 구간을 저장하는데, 주행 중에 몇 분마다 전면
광고가 도로 화면을 덮는 것은 수익이 아니라 **위험**이기 때문입니다. 운전자가
안전하게 닫을 수도 없습니다.

*An advertisement appears once, after a manually recorded clip has been saved
to your gallery - after the saving, never between the recording and it.
Blackbox clips never show one, and neither do parked impact clips: a blackbox
closes a segment every few minutes while the car is moving, and a full-screen
advertisement over the road on that schedule is a hazard rather than a business
model. The driver could not safely dismiss it either.*

### 광고가 수집하는 것 / What the advertising collects

광고는 **구글의 AdMob**이 제공합니다. 광고를 받아오려면 구글 서버와 통신해야
하고, 그 과정에서 구글은 다음을 받습니다.

- **광고 ID** (기기의 광고 식별자)
- 기기 정보와 IP 주소
- 광고를 보았는지, 눌렀는지

**이 정보는 구글이 받는 것이며, 개발자는 받지 않습니다.** 개발자가 보는 것은
AdMob 대시보드의 합계(노출 수, 수익)뿐이고, 거기에 개인을 식별할 수 있는 것은
없습니다.

구글이 이 정보를 어떻게 다루는지는 **구글의 개인정보처리방침**을 따릅니다.

- 구글 개인정보처리방침: https://policies.google.com/privacy
- 광고 개인설정: https://adssettings.google.com

**영상과 위치는 광고와 무관합니다.** 광고 SDK에 전달되지 않습니다.

*The advertisements come from Google AdMob. Fetching one means talking to
Google's servers, and in doing so Google receives the device's advertising ID,
device information, your IP address, and whether the advertisement was seen or
tapped. Google receives it; the developer does not. What the developer sees is
the totals on the AdMob dashboard - impressions and revenue - with nothing in
them that identifies anybody. Google's own privacy policy governs what happens
to it. Your footage and your location are no part of this and are never handed
to the advertising SDK.*

### 광고 제거 구매 / Removing the ads

설정 화면에서 **한 번 결제하면 광고가 사라집니다.** 구독이 아니라 1회 구매입니다.

- 결제는 **구글 플레이**가 처리합니다. 앱은 카드 번호를 보지도, 다루지도 않습니다
- 앱이 아는 것은 **"이 구글 계정이 이 상품을 샀는가"** 라는 예/아니오뿐입니다
- 그 답은 기기 안에 저장해 두고, 앱을 열 때마다 구글 플레이에 다시 확인합니다.
  비행기 모드에서도 구매자가 광고를 보지 않게 하기 위해서입니다
- 기기를 바꾸시면 **설정 → 구매 복원**으로 되살릴 수 있습니다. 구매하신 구글
  계정으로 로그인되어 있어야 합니다

**구매하시면 광고를 요청하지 않습니다.** 띄우지 않는 정도가 아니라 광고를
받아오는 통신 자체가 일어나지 않습니다. 다만 광고 SDK는 여전히 앱에 포함되어
있고 앱이 켜질 때 초기화됩니다.

*One payment in the settings screen removes the advertisements for good - a
purchase, not a subscription. Google Play handles the payment; the app never
sees or handles a card. All the app learns is a yes or no: whether this Google
account owns the product. That answer is kept on the device and checked with
Google Play again on each launch, so a purchaser in a tunnel is not shown
advertisements while the question is still being asked. Changing phones is
covered by Restore purchase in the settings, signed in with the Google account
that bought it. Once bought, no advertisement is requested at all - not merely
not displayed - though the advertising SDK remains inside the app and still
starts up with it.*

---

## 4. 권한 / Permissions

| 권한 / Permission | 이유 / Why |
|---|---|
| 카메라 / Camera | 영상을 촬영하기 위해 / To record |
| 마이크 / Microphone | 소리를 함께 녹음하기 위해. 설정에서 끌 수 있습니다 / For sound; can be turned off in settings |
| 위치 / Location | 영상에 좌표를 찍기 위해. 설정에서 끌 수 있으며, 끄면 요청하지 않습니다 / To stamp the coordinates onto the picture; can be turned off in settings, and is not requested when it is |
| 동영상 저장·접근 / Video storage | 결과를 저장하기 위해 / To save what it records |
| 알림 / Notifications | 백그라운드 녹화 중임을 알리기 위해 / To say that it is recording in the background |
| 동작 감지 / Motion sensing | 충격 감지와 주차 판단을 위해. 권한이 필요 없는 센서이며 기기를 벗어나지 않습니다 / For impact detection and deciding the car has stopped; needs no permission and never leaves the device |
| 인터넷 / Internet | 광고를 받아오기 위해, 그리고 주소 표시를 켜셨을 때의 주소 조회를 위해 / To fetch advertisements, and for the address lookup when the address stamp is on |
| 백그라운드 실행 / Foreground service | 블랙박스 녹화가 화면을 벗어나도 이어지게 하기 위해. 녹화 중에는 알림이 계속 표시됩니다 / So blackbox recording survives leaving the screen; a notification shows throughout |

`다른 앱 위에 표시`, `진동`, `사진 접근` 권한은 **요청하지 않습니다.** 안드로이드
빌드 도구가 기본으로 넣는 것들까지 빌드 설정에서 **제거했습니다.**

앱은 **회원님의 기존 사진이나 영상을 읽지 않습니다.** 갤러리에 대해서는 자신이
만든 `DashStamp` 앨범에 쓰는 것이 전부이며, 목록을 훑어보는 코드는 없습니다.
연락처와 통화 기록은 요청하지도, 접근하지도 않습니다.

**안드로이드 12 이하에서는** 권한 창이 "사진, 미디어, 파일에 접근"이라고
넓게 표시됩니다. 당시 안드로이드에는 영상만 허용하는 권한이 없었기 때문이며,
앱이 실제로 하는 일은 위와 같습니다. 안드로이드 13 이상에서는 영상 권한만
요청하고 사진 권한은 **차단해 두었습니다.**

*Draw-over-other-apps, vibration and photo access are not requested: the ones
Android's build tooling adds by default have been stripped out in the build
configuration. The app does not read your existing photos or videos. All it does with the
gallery is write into the `DashStamp` album it made; there is no code in it
that lists your media. Contacts and the call log are neither requested nor
touched. On Android 12 and below the permission dialog says "photos, media and
files" because that version of Android had no video-only permission - what the
app actually does is the above. On Android 13 and up it asks only for video,
and the photo permission is blocked outright.*

---

## 5. 백그라운드 녹화 / Recording in the background

블랙박스 모드는 앱이 화면에서 사라져도 녹화를 계속합니다.
이때 안드로이드 알림이 하나 표시되며, **이 알림은 녹화가 끝날 때까지 지워지지
않습니다.**

의도된 동작입니다. **아무 표시 없이 도로를 녹화하는 앱이어서는 안 됩니다.**

*Blackbox mode carries on recording once the app leaves the screen, and shows a
notification that cannot be dismissed until it stops. That is deliberate:
nothing should be recording the road without saying so.*

---

## 6. 주차 모드 / Parking mode

켜시면, 차가 5분간 움직이지 않을 때 녹화를 멈추고 **가속도계로 충격만
감시합니다.** 충격이 감지되면 짧은 영상 한 편을 녹화하고 잠급니다.

이 동안 앱은 깨어 있으므로 **배터리를 씁니다.** 전원이 공급되는 거치대를
권합니다.

*With parking mode on, the app stops recording after five minutes without
movement and watches the accelerometer instead. A jolt records one short clip
and locks it. The app stays awake throughout, which costs battery - a powered
mount is worth having.*

---

## 7. 수집하지 않는 것 / What is not collected

- 계정이 없습니다. 가입도 로그인도 없습니다
- **영상과 음성은 네트워크로 보내지 않습니다.** 어떤 경우에도 기기 안에만
  있습니다
- 개발자는 **사용 기록이나 분석 데이터를 수집하지 않습니다.** 분석 SDK가 들어
  있지 않습니다
- 개발자가 받는 개인정보가 **하나도 없습니다**
- **앱이 네트워크를 쓰는 곳은 두 군데입니다** — 광고를 받아오는 것(3항)과,
  주소 표시를 켜셨을 때의 주소 조회입니다. 광고를 제거하시면 전자는 사라집니다.
  주소 조회는: 조회가 안 되면 좌표가 찍히고, 이미 받아둔 주소가 있으면 그
  주소에 **측정 시각이 함께** 찍힙니다
- 그 밖에 위치를 **알아내는** 과정에서 안드로이드가 네트워크를 쓸 수 있습니다.
  앱이 하는 일이 아니고 모든 위치 앱에 공통입니다
  ([1-2](#1-2-안드로이드-위치-서비스에-대해--about-androids-location-service))
- 비행기 모드에서도 녹화와 스탬프는 동작합니다. 위성만으로 위치를 잡게 되므로
  처음 잡히기까지 더 오래 걸리고, 광고는 받아올 수 없으니 나오지 않습니다

*There is no account, the developer collects no usage or analytics data and
there is no analytics SDK in the app, and no footage or audio is ever sent
anywhere - it stays on the device in every case. The developer receives no
personal information at all. The app makes network requests in two places:
fetching an advertisement (section 3), which stops once the ads are bought
away, and the address lookup on the address stamp. When it cannot be made
the frame carries coordinates, or an address already found together with the
time it was found. Separately, Android may use the network while working out
the position itself - not the app's doing, and common to every app that uses
location. Recording and stamping both work in aeroplane mode; the first fix
simply takes longer with satellites alone.*

---

## 8. 아동의 개인정보 / Children's privacy

앱은 만 13세 미만 아동을 대상으로 하지 않으며, 아동으로부터 고의로 정보를
수집하지 않습니다.

*The app is not directed at children under 13, and does not knowingly collect
information from them.*

---

## 9. 영상을 공유하실 때 / If you share your footage

위치 표시를 켜두셨다면 영상에는 **촬영 시각과 좌표가 찍혀 있습니다.** 그것이
이 앱의 목적입니다.

다만 그 영상을 다른 곳에 올리시면 **그 시각에 어디 계셨는지도 함께 공개**됩니다.
집 앞이나 직장 앞에서 찍힌 영상이라면 한 번 더 생각해 보시기 바랍니다.

*With the location stamp on, your footage carries the time and the coordinates
- that is the point of the app. But posting it anywhere also publishes where you were at that moment.
Footage taken outside your home or workplace is worth a second thought before
it goes anywhere.*

---

## 10. 보유 기간과 파기 / How long things are kept

개발자가 보관하는 것이 **없습니다.** 서버가 없으므로 보관할 곳도 없습니다.
아래는 **회원님의 기기 안에서** 영상이 얼마나 남는지입니다.

| 대상 | 보유 기간 |
|---|---|
| 직접 촬영한 영상 / Manual recordings | 회원님이 지우실 때까지 (갤러리) |
| 블랙박스 영상 / Blackbox clips | 설정하신 용량이 찰 때까지. 차면 오래된 것부터 자동 삭제 |
| 잠근·충격 영상 / Locked clips | 설정 용량의 두 배까지 보관 후 오래된 것부터 삭제 |
| 위치 좌표 / Coordinates | **별도 보관 없음.** 영상 안의 글자로만 존재 |
| 주소 조회 기록 / Address lookups | **별도 보관 없음.** 앱은 결과를 저장하지 않음 |
| 광고 제거 구매 여부 / Whether the ads were bought | 기기 안에 예/아니오 한 값. 앱을 삭제하면 사라지며, 재설치 후 **구매 복원**으로 되살림 |

**앱을 삭제하면** 앱 내부의 블랙박스 영상과 설정이 **함께 삭제됩니다.** 갤러리로
내보내신 영상은 회원님 것이므로 남습니다.

*The developer keeps nothing: there is no server to keep it on. The table above
is how long footage lives on your own phone. Uninstalling removes the blackbox
clips and the settings held inside the app; anything exported to your gallery is
yours and stays.*

---

## 11. 제3자 제공과 국외 이전 / Third parties and transfers abroad

개발자는 회원님의 정보를 **누구에게도 제공하지 않습니다.** 받는 것이 없으므로
제공할 것도 없습니다.

다만 앱이 정보를 **구글에 넘기는 경로가 둘** 있습니다.

### (1) 광고 / Advertising

| 항목 | 내용 |
|---|---|
| 받는 곳 / Recipient | Google AdMob |
| 넘기는 것 / What is sent | 광고 ID, 기기 정보, IP 주소, 노출·클릭 여부 |
| 목적 / Purpose | 광고 게재와 측정 |
| 시점 / When | 광고를 받아올 때 (광고 제거를 구매하시면 없음) |
| 국외 이전 / Abroad | **있을 수 있습니다.** 구글 서버는 국외에 있을 수 있습니다 |
| 거부 방법 / How to decline | **광고 제거를 구매**하시거나, 기기 설정에서 광고 ID를 삭제·재설정하실 수 있습니다 |

영상과 위치는 광고 SDK에 전달되지 않습니다.

### (2) 주소 조회 / The address lookup

**회원님이 주소 표시를 켜셨을 때**, 앱은 좌표를 안드로이드 시스템
지오코더에 넘깁니다. 대부분의 기기에서 이 서비스는 **구글이 운영**하며, 서버는
**국외에 있을 수 있습니다.**

| 항목 | 내용 |
|---|---|
| 받는 곳 / Recipient | 안드로이드 시스템 지오코더 (대부분의 기기에서 Google) |
| 넘기는 것 / What is sent | 좌표(위도·경도)뿐. 영상·음성·식별자는 보내지 않음 |
| 목적 / Purpose | 좌표를 주소 문자열로 변환 |
| 시점 / When | 주소 표시 설정을 켜신 동안, 약 20초 간격 |
| 보유 / Retention | 구글의 방침에 따릅니다. 개발자는 받지도 저장하지도 않습니다 |
| 거부 방법 / How to decline | 스탬프를 **좌표 표시**(기본값)로 두시거나, 위치 표시를 끄시면 됩니다 |

**기본 설정에서는 이 이전이 일어나지 않습니다.**

이와 별도로, 위치를 알아내는 과정에서 안드로이드 자체가 네트워크를 쓸 수
있습니다([1-2](#1-2-안드로이드-위치-서비스에-대해--about-androids-location-service)).
이는 앱이 아니라 운영체제가 하는 일이며 기기 설정에서 끄실 수 있습니다.

*The developer gives your information to nobody, having none to give. Two paths
do hand information to Google. The first is advertising: fetching one sends the
advertising ID, device information, your IP address and whether the
advertisement was seen or tapped, for serving and measuring it - and buying the
ads away ends it. Your footage and location are no part of it. You can also
clear or reset the advertising ID in your phone's settings. The second is the
address lookup: with the address stamp on, the app hands your coordinates to the Android system
geocoder - on most phones a Google-run service whose servers may sit outside
your country. What goes is latitude and longitude alone: no footage, no audio,
no identifier. Google's own policy governs what happens to it; the developer
neither receives nor stores it. Leave the stamp on coordinates, the default, or
turn the location stamp off, and the transfer never happens. Separately, Android
itself may use the network to work out the position (1-2) - the operating
system's doing, not the app's, and switchable in your phone's settings.*

---

## 12. 회원님의 권리 / Your rights

서버도 계정도 없으므로, 회원님의 정보는 **전부 회원님 기기 안에 있고 회원님이
직접 처리하실 수 있습니다.** 개발자에게 요청하실 필요가 없습니다.

| 하고 싶은 일 | 방법 |
|---|---|
| 위치 수집 중단 | 설정 → **위치 표시 끄기** (권한 요청조차 하지 않습니다) |
| 국외 이전 중단 | 설정 → 표시 방식을 **좌표**로 (기본값) |
| 녹음 중단 | 설정 → **소리 끄기** |
| 광고 중단 | 설정 → **광고 제거** 구매 |
| 광고 ID 초기화 | 안드로이드 설정 → 개인정보 보호 → 광고 |
| 영상 삭제 | 앱의 영상 목록에서 개별 삭제, 또는 갤러리에서 삭제 |
| 전부 삭제 | **앱 삭제** — 앱 내부 영상과 설정이 함께 사라집니다 |
| 권한 회수 | 안드로이드 설정 → 앱 → DashStamp → 권한 |

열람·정정·삭제·처리정지 요청을 개발자에게 보내실 수도 있으나, 개발자가 보관하는
회원님의 정보가 없어 **삭제할 대상이 존재하지 않습니다.** 문의는 아래 이메일로
받습니다.

*There is no server and no account, so everything is on your phone and in your
hands - you do not need to ask the developer. The table above is how. You may
still write to the address below to ask for access, correction, deletion or a
halt to processing; the honest answer will be that the developer holds nothing
of yours to act on.*

---

## 13. 안전성 확보 조치 / Keeping it safe

- 영상은 **기기를 벗어나지 않습니다.** 전송 중 유출될 경로가 없습니다
- 블랙박스 영상은 **앱 전용 저장공간**에 있어 다른 앱이 읽을 수 없습니다
- 계정도 비밀번호도 없으므로 **탈취될 자격 증명이 없습니다**
- 주소 조회는 안드로이드 플랫폼을 통해 **암호화된 연결**로 이루어집니다
- **분석 SDK가 들어 있지 않습니다.** 광고 SDK는 구글의 것이며, 개발자가 회원님의
  정보를 받는 통로는 아닙니다

가장 확실한 보호는 **보관하지 않는 것**이고, 이 앱의 구조가 그렇습니다.

*Footage never leaves the device, so there is no transfer to intercept.
Blackbox clips live in app-private storage that other apps cannot read. There
are no accounts and no passwords, so there are no credentials to steal. The
address lookup goes over the platform's encrypted connection. There is no analytics SDK in the app, and the
advertising SDK is Google's own - not a channel through which the developer
receives anything about you. The strongest protection is not holding
the data, and that is how this app is built.*

---

## 14. 방침 변경 / Changes to this policy

이 방침이 변경되면 앱 업데이트와 함께 이 페이지가 갱신됩니다.

*This page is updated alongside app releases.*

---

## 15. 문의 / Contact

개인정보 처리에 관한 문의와 요청을 받는 곳입니다.

| | |
|---|---|
| 앱 / App | DashStamp (`com.dashstamp.app`) |
| 문의 / Contact | 6mvlab@gmail.com |

*Questions and requests about privacy go to the address above.*
