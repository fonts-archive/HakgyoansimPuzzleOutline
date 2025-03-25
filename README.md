# 학교안심 퍼즐 Outline

[배포처 바로가기](https://copyright.keris.or.kr/wft/fntDwnldView?fntGrpId=GFT202408200000000000010)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Hakgyoansim Puzzle Outline`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HakgyoansimPuzzleOutline/HakgyoansimPuzzleOutline.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HakgyoansimPuzzleOutline/HakgyoansimPuzzleOutline.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Hakgyoansim Puzzle Outline';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/HakgyoansimPuzzleOutline/HakgyoansimPuzzleOutline.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/HakgyoansimPuzzleOutline/HakgyoansimPuzzleOutline.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/HakgyoansimPuzzleOutline/HakgyoansimPuzzleOutline.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/HakgyoansimPuzzleOutline/HakgyoansimPuzzleOutline.ttf') format('truetype');
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Hakgyoansim Puzzle Outline", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
국제 SIL(Summer Institute of Linguistics)에서 만든 오픈폰트 라이선스로, OFL 폰트는 이용 대상 및 목적에 제한없이 자유롭게 이용 가능 합니다.
```
