<img style="border: 1px solid black !important; border-radius:20px;" src="https://kyrics.s3.ap-northeast-2.amazonaws.com/%ED%82%A4%EB%A6%AD+%EB%A1%9C%EA%B3%A0-01.jpg" width="100%" />

<br/>

<a href="www.kyrics.org">www.kyrics.org</a>

### Kyrics frontend repository currently moved to --> <a href="https://github.com/pa-rang/kyrics-frontend/">here</a>

<br/>

.  
.  
.  

<br/>


## ๐ซ `kyrics`๋ ์ด๋ฐ ์๋น์ค์๋๋ค!

๐ถ Learn Korean through your favorite K-Pop artists and songs!

์ผ์ดํ ๊ฐ์ฌ๋ก ๋ฐฐ์ฐ๋ ์ฐ๋ฆฌ๋ง, ํค๋ฆญ์ค โจ  
ํค๋ฆญ์ค๋ฅผ ํตํด ์ฐ๋ฆฌ๋ง์ ์ฝ๊ณ  ์ฌ๋ฏธ์๊ฒ ๋ฐฐ์๋ณด์ธ์!

<br/>

## ๊ธฐ๋ฅ ์๊ฐ

1. Home View
![image](https://user-images.githubusercontent.com/24906022/125967698-4f128db9-3430-477e-b39b-3265e082b402.png)

- ์ํฐ์คํธ๋ฅผ ์ ํํ๋ ํ๋ฉด์๋๋ค. 
<br/> 

2. Artist View
![image](https://user-images.githubusercontent.com/24906022/125967749-9f6a3f96-a83d-4d71-956f-9b3774589479.png)

- ์ํฐ์คํธ์ ๋ธ๋๋ฅผ ์ ํํ๋ ํ๋ฉด์๋๋ค.  
<br/>

3. Study View
![image](https://user-images.githubusercontent.com/24906022/125967825-8ea8848f-9ecf-4159-8126-156df3f3062a.png)

- ํ์ต์ด ๊ฐ๋ฅํ๋๋ก player๋ฅผ ๋ง๋ค๊ณ , Key Expressions ์ ๊ณตํฉ๋๋ค.
- ์์์ด ํ๋ฌ๊ฐ์ ๋ฐ๋ผ ๊ฐ์ฌ๊ฐ ํ์ด๋ผ์ดํ ๋ฉ๋๋ค.
- ๊ฐ์ฌ๋ฅผ ํด๋ฆญํ๋ฉด, ํด๋น ๊ฐ์ฌ๊ฐ ํ๋ฌ๋์ค๋ ์๊ฐ์ผ๋ก ์ด๋ํฉ๋๋ค.  
<br/>

4. Login View
![image](https://user-images.githubusercontent.com/24906022/125967851-c8c4252c-825d-48e5-b332-b9efc46c8bac.png)

- Google, Facebook Social Login์ ์ ๊ณตํฉ๋๋ค.  
<br/>

5. My Songs View
![image](https://user-images.githubusercontent.com/24906022/125967884-d0668dbc-7e0d-4f38-8cd1-975e79489ff2.png)

- ์ฆ๊ฒจ์ฐพ๊ธฐ ์ถ๊ฐํ ๋ธ๋๋ฅผ ๋ชจ์๋ก๋๋ค.  
<br/>

6. My Vocab View
![image](https://user-images.githubusercontent.com/24906022/125967911-6efbf948-c6f9-4643-97c2-32198bc4c267.png)

- ์ฆ๊ฒจ์ฐพ๊ธฐ ์ถ๊ฐํ ๋จ์ด๋ฅผ ๋ชจ์๋ก๋๋ค.  

<br/>
<br/>

## ๐  ์ฌ์ฉํ ๊ธฐ์ 

<img src="https://img.shields.io/badge/-ReactJs-61DAFB?logo=react&logoColor=white&style=flat" height=40>&nbsp;&nbsp;<img src="https://img.shields.io/badge/-Typescript-3074BF?logo=Typescript&logoColor=white&style=flat" height=40>&nbsp;&nbsp;<img src="https://img.shields.io/badge/-Next.js-000000?logo=Next.js&logoColor=white&style=flat" height=40>

```json
"@emotion/react": "^11.4.0",
"@emotion/styled": "^11.3.0",
"axios": "^0.21.1",
"next": "11.0.1",
"react": "17.0.2",
"react-dom": "17.0.2",
"recoil": "^0.3.1",
"reset-css": "^5.0.1",
"swr": "^0.5.6"
```

<br/>

## ๐ ํ๋ก์ ํธ ๊ตฌ์กฐ

```
.
โโโ components
โย ย  โโโ common
โย ย  โย ย  โโโ Footer.tsx
โย ย  โย ย  โโโ Header.tsx
โย ย  โโโ home
โย ย  โย ย  โโโ Title.tsx
โย ย  โโโ mypage
โย ย  โย ย  โโโ MySong.tsx
โย ย  โย ย  โโโ MyVoca.tsx
โย ย  โย ย  โโโ Setting.tsx
โย ย  โโโ study
โย ย      โโโ AddVocab.tsx
โย ย      โโโ KeyExpression.tsx
โย ย      โโโ Lyrics.tsx
โย ย      โโโ Player.tsx
โย ย      โโโ PlayerBtns.tsx
โโโ hooks
โย ย  โโโ useExample.ts
โโโ lib
โย ย  โโโ constants
โย ย  โย ย  โโโ example.ts
โย ย  โโโ utils
โย ย      โโโ example.ts
โโโ next-env.d.ts
โโโ next.config.js
โโโ pages
โย ย  โโโ _app.tsx
โย ย  โโโ category.tsx
โย ย  โโโ index.tsx
โย ย  โโโ login.tsx
โย ย  โโโ mypage
โย ย  โย ย  โโโ [id].tsx
โย ย  โโโ study.tsx
โโโ public
โย ย  โโโ assets
โย ย      โโโ icons
โย ย      โย ย  โโโ favicon.ico
โย ย      โโโ images
โย ย          โโโ example.ts
โโโ styles
โย ย  โโโ globals.css
โโโ types
    โโโ index.ts
```

## ๐ฅ Contributer
- [๊น์์ง](https://github.com/euijinkk)
- [๋ฐ๋ํฌ](https://github.com/Nahee-Park)
- [์ด๋ค์](https://github.com/Daeun-Danna-Lee)
- [์ด์ ์ฐ](https://github.com/pa-rang)
