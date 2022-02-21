# Nextjs carrot-market

### requirements

- react : 18 (rc)
- Next js : 12
- tailwindcss : 8.4
- postcss : 3.0
- typescript : 4.5

`yarn add -D tailwindcss postcss autoprefixer`

`yarn tailwindcss init -p`

22년 2월 20일 기준 :TypeError: Cannot set properties of undefined (setting 'reactRoot')

에러가 나타나면

`npm i next@latest react@rc react-dom@rc`가 아닌

`npm i next@12.0.8 react@rc react-dom@rc`로 시도해보자

### Tailwind

tailwind.config.js 파일에서 content는 어디서 tailwind를 사용할지 설정

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8ee1ad18-2321-4260-98a6-dd0196cfc72d/Untitled.png)

page폴더안의 모든폴더안의 모든 js,jsx,ts,tsx파일을 의미

Tailwind CSS는 utility-first framwork → Tailwind가 아주 많은 classname을 가지고 있다는 뜻

Tailwind CSS는 class name을 추가하고 조합하는게 전부이다.

→ 이것을 가지고 반응형 디자인을 만드는 것이 쉽다.

다른 CSS Framework는 각각의 스타일이 있지만 Tailwind는 정해진 스타일이 없다.

주로 사용되는 class들

margin, padding, flex, grid, background color, text color ...
