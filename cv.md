# Anastasiya Bazarova CV

![img](https://avatars.githubusercontent.com/u/50262635?s=400&u=98013719a24ff125588859cef337eff01492c6fb&v=4)

## Location

Belarus, Minsk

## Contact information:

### my social links

- [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='30'>](https://github.com/BazarovaAnastasiya)
- [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='30'>](https://www.linkedin.com/in/anastasiya-bazarova-9a9043172/)
- [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg' alt='instagram' height='30'>](https://www.instagram.com/baz.a_/)

### contacts for communication

- email [anastasiya.bazarova.85@gmail.com](href="mailto:anastasiya.bazarova.85@gmail.com)
- telegramm [@Bazarova_Anastasiya](https://tlgg.ru/Bazarova_Anastasiya/)
- Discord -Anastasiya#1134

## About me

At the moment I am working as an HTML developer and I am looking for an opportunity to change my career to the position of a junior frontend developer after graduating from RS School

## Skills:

- HTML5
- CSS3
- JavaScript (Basics)
- Visual Studio Code / PhpStorm
- Git/GitHub
- Vue.js | JavaScript Framework (Basics)
- graphic editors ( figma, zeplin, photoshop)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=BazarovaAnastasiya)](https://github.com/anuraghazra/github-readme-stats&theme=dark)

## Education

**RSSchool**

- 'JavaScript/Front-end. Stage 0'

in progress

**Udemy**

- JavaScript

  2021 - present

**IT-INCUBATOR**

- HTML/CSS Developer

  2021 - 2021

**Web hero school**

- HTML/CSS Developer

  2019 – 2019

**International Humanitarian and Economic Institute, Minsk**

- Faculty of Finance and Economics Economics and Enterprise Management (by industry)

  2005 - 2010

**"Industrial Pedagogical College" Educational Institution "Republican Institute of Vocational Education", Minsk**

- commercial activityeconomist for commercial activities; information systems technician

  2001 – 2005

## Experience

since 2021: HTML developer

since 2020: Html-css editor (freelance)

## Code Example

```
const tabs = document.querySelector(".portfolio__nav");
const tabsBtn = document.querySelectorAll(".portfolio__nav-btn");
const tabsItem = document.querySelectorAll(".portfolio__content");
const portfolioImages = document.querySelectorAll(".gallery__img");
const season = ["winter", "spring", "summer", "autumn"];
tabsBtn.forEach(onTabClick);
function onTabClick(item) {
  let currentBtn = item;
  let tabId = currentBtn.getAttribute("data-season");
  let t = tabId;
  item.addEventListener("click", function () {
    if (!currentBtn.classList.contains("")) {
      console.log(tabId);
      portfolioImages.forEach(
        (img, index) =>
          (img.src = "./assets/img/" + t + "/" + (index + 1) + ".jpg")
      );
      tabsBtn.forEach(function (item) {
        item.classList.remove("button--color");
      });
      currentBtn.classList.add("button--color");
    }
  });
}
if (tabs) {
  document.querySelector(".portfolio__nav-btn").click();
}
```

## Languages

Russian - native speaker
English - A1
