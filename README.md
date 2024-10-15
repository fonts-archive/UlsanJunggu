# 울산중구전용서체

[배포처 바로가기](https://www.junggu.ulsan.kr/index.ulsan?menuCd=DOM_000000305001010000)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Ulsan Junggu`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/UlsanJunggu/UlsanJunggu.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/UlsanJunggu/UlsanJunggu.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Ulsan Junggu';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/UlsanJunggu/UlsanJunggu.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/UlsanJunggu/UlsanJunggu.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/UlsanJunggu/UlsanJunggu.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/UlsanJunggu/subsets/UlsanJunggu-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/UlsanJunggu/subsets/UlsanJunggu-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Ulsan Junggu", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
울산중구전용서체는 영상, 인쇄, 인터넷 등 다양한 매체에 특별한 허가절차없이 누구나 무료로 다운로드 받아 사용하실 수 있습니다. 다만 전용서체를 유료로 양도하거나 판매 할수 없으며 배포되는 형태 그대로 사용해야 합니다. (장·평 조절 및 과도한 자간, 행간 적용 금지)
```
