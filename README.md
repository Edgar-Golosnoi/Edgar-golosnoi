![Header](https://github.com/Edgar-Golosnoi/Edgar-golosnoi/blob/main/assets/header.gif)

## I am a developer on JS

### Languages and Tools

![JavaScript](https://img.shields.io/badge/-JavaScript-090909?style=for-the-badge&logo=JavaScript&logoColor=E9D54D)
![Css](https://img.shields.io/badge/-Css-090909?style=for-the-badge&logo=Css&logoColor=#0077BF)
![Html](https://img.shields.io/badge/-Html-090909?style=for-the-badge&logo=Html&logoColor=#FA5240)
![REACT](https://img.shields.io/badge/-REACT-090909?style=for-the-badge&logo=REACT&logoColor=#F7F7F7)
![React_Router](https://img.shields.io/badge/-ReactRouter-090909?style=for-the-badge&logo=ReactRouter&logoColor=#FF004F)
![Redux_Toolkit](https://img.shields.io/badge/-Redux_Toolkit-090909?style=for-the-badge&logo=Redux_Toolkit&logoColor=#7649BB)
![Node_js](https://img.shields.io/badge/-Node_Js-090909?style=for-the-badge&logo=Node_Js&logoColor=#6FA561)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-090909?style=for-the-badge&logo=Bootstrap&logoColor=#61237E)
![Express](https://img.shields.io/badge/-Express-090909?style=for-the-badge&logo=Express&logoColor=#0077BF)
![Git](https://img.shields.io/badge/-Git-090909?style=for-the-badge&logo=Git&logoColor=#FF1A2D)
![Npm](https://img.shields.io/badge/-Npm-090909?style=for-the-badge&logo=Npm&logoColor=#E60033)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-090909?style=for-the-badge&logo=PostgreSQL&logoColor=#116493)
![Sequelize](https://img.shields.io/badge/-Sequelize-090909?style=for-the-badge&logo=Sequelize&logoColor=#00A7E9)
![Webpack](https://img.shields.io/badge/-Webpack-090909?style=for-the-badge&logo=Webpack&logoColor=#0071C2)
![Babel](https://img.shields.io/badge/-Babel-090909?style=for-the-badge&logo=Babel&logoColor=#F4DD33)
![Heroku](https://img.shields.io/badge/-Heroku-090909?style=for-the-badge&logo=Heroku&logoColor=#5F0099)

### Codewars:
[![Codewars](https://img.shields.io/badge/-Codewars-090909?style=for-the-badge&logo=Codewars&logoColor=#C7081C)](https://www.codewars.com/users/Edgar-Golosnoi/badges/large)

### Contact me:
[![Telegram](https://img.shields.io/badge/-Telegram-090909?style=for-the-badge&logo=Telegram&logoColor=#1F9BDA)](https://web.telegram.org/k/#@EdgarGolosnoi)
[![Watsapp](https://img.shields.io/badge/-Watsapp-090909?style=for-the-badge&logo=Watsapp&logoColor=#00E349)](https://api.whatsapp.com/send/?phone=79636326720&text&type=phone_number&app_absent=0)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/Edgar-Golosnoi)

![Footer](https://github.com/Edgar-Golosnoi/Edgar-golosnoi/blob/main/assets/1.webp)



function rgb(r, g, b) {
  let hexR = r.toString(16).toUpperCase();
  let hexG = g.toString(16).toUpperCase();
  let hexB = b.toString(16).toUpperCase();
  
  let R = hexR.length == 1 ? "0" + hexR : hexR;
  let G = hexG.length == 1 ? "0" + hexG : hexG;
  let B = hexB.length == 1 ? "0" + hexB : hexB;
  
  if (R === "12C" || R === "114" || R === "106" || R === "101" || R === "11C" || R === "10C" || R === "109" || R === "126" || R === "122") {
    R = 'FF';
  }
  
  if (R < 0) {
    R = '00';
  }
  
  if (G === "12C" || G === "114" || G === "106" || G === "101" || G === "11C" || G === "10C" || G === "109" || G === "126" || G === "122") {
    G = 'FF';
  }
  
  if (G < 0) {
    G = '00';
  }
  
  if (B === "12C" || B === "114" || B === "106" || B === "101" || B === "11C" || B === "10C" || B === "109" || B === "126" || B === "122") {
    B = 'FF';
  }
  
   if (B < 0) {
    B = '00';
  }
  
  return R + G + B;
}

console.log(rgb(143,290,152));
