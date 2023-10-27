https://alperennucr.github.io/travel-website/


- [Important Code Notes](#Important-Code-Notes)
- [What I learned](#what-i-learned)
- [Continued development](#Topics-I'm-missing-and-want-to-improve-myself)
- [Useful resources](#Resources-that-helped-me-with-this-project)
- [Creator](#Creator)

### Important Code Notes

Kodlarda BEM syntax kullanımının örnekleri verilmiştir.

```html

<a class="btn btn--big btn--orange" href="https://css-tricks.com">
  <span class="btn__price">$9.99</span>
  <span class="btn__text">Subscribe</span>
</a>

```

```css

/* BEM Example */
/* Block component */
.btn {}

/* Element that depends upon the block */ 
.btn__price {}

/* Modifier that changes the style of the block */
.btn--orange {} 
.btn--big {}

```

### What I learned 

Turkish Explain
-----------------
    1- Genelde XD dökerken yapılan şeylerden biri de, çoğu yerde aynı olan yapıları(butonlar,kartlar gibi) tek bir class'a tanımlayıp
    çok yerde kullanmaktır. Mesela sayfadaki başlıkları inceleyip aynı yapıda olanları sayıp ona göre kaç class oluşacağını da hesaplayabilirsin.
    2- Header'ı her zaman ikiye parçala,gerekirse 3'e.
    3- Artık projelerde reset.css oluşturup tüm tarayıcılarda reset atan kodları kullanacağım. Reset.css'i style.css'in üstüne yaz ki style.css'i
    ezmesin.
    4- CSS kodlarını BEM syntax ile yazmaya başla, bu sayede gereksiz kod kullanımı ortadan kalkar.
    5- Tüm divlere tek tek margin verip ortalamak yerine ortak container'da ortalamak daha mantıklı olur.
    6- XD dökerken web sitesi zoom'u %75 olmalı, tam ekran boyut için.
    7- Bu projede ilk defa BEM syntax deniyorum hatalarıyla vs. elimden geleni yaptım, şuan yapmak istediğim birşey var ama BEM'i ilk defa
    denediğim ve bazı yerlerde hata yapmış olabileceğim için şuan denemeyeceğim. XD'yi siteye çevirirken XD yapısında bazı şeyler klon
    halinde oluyor yani materyal özellikleri aynı oluyor, bir materyalin birçok nesneye atanması gibi. Bunu C#'da constructor olarak 
    düşünebilir, inşa edilen yapıyı birçok yerde kullanmak diyebiliriz. İşte XD'lerde bu constructor halde birçok nesne var. Bir sonraki XD'lerde
    bunları tespit ederek constructor yapısını CSS'de oluştur; hem kod kalabalığı kalkıyor(temiz kod),hem daha az kod yazıldığı için hız 
    açısından da verimli oluyor, hem de zamandan oldukça tasarruf ediliyor. Normalde yapmam gerekirdi ama projeye başlarken dağınık 
    başladığım için şuan uygulaması gerçekten zor olur.Not: Projenin sonlarındayım, BEM syntax o kadar efsane ki eğer bunu uygulamasaydım
    aşırı uzun sürerdi
    8- Scrollbar özelleştirmeyi öğrendim.
    9-CSS'den Background ile atılan resimlerin boyutlandırılması için background-size olduğunu öğrendim.
    10-SASS'ın özelliği olan @mixin leri öğrendim ve daha sık kullanmaya başladım.
    .
    .
    BEM kullanmanın faydaları:
    --------------------------
    1- If we are reading the markup instead of CSS, we should be able to quickly get an idea of which element depends on another (in the previous example we can 
    see that .btn__price depends on .btn, even if we don’t know what that does just yet.)
    2- Designers and developers can consistently name components for easier communication between team members.
    3- This is the main reason we end up with bloated code bases, full of legacy and unknown CSS that we daren’t touch. We lack the confidence to be able to work with and modify existing styles because we fear the consequences of CSS’ globally operating and leaky nature. Almost all problems with CSS at scale boil down to confidence (or lack thereof): People don’t know what things do any more. People daren’t make changes because they don’t know how far reaching the effects will be.
If you follow strict BEM conventions, you will be able to update and add to your CSS in the future with the full confidence that your changes will not have side effects.
    -------------------
    Üstteki yazıyı ingilizce bir kaynaktan aldım ve çeviriden bozuk bir türkçe ile atmaktansa
    nasıl olsa anlıyorum,ingilizcesini attım.




### Topics I'm missing and want to improve myself

1- Grid Layout 
2- Bootstrap or something else(CSS Framework)
3- BEM syntax

### Resources that helped me with this project

- [Adobe-xd](https://www.youtube.com/watch?v=VgsA3X1ITfI&list=PLnxg6aKjxXxglseWB4nj9TYSxRAjOd_CU&index=1&t=11s) - xd dökmek için yardım aldım.

## Creator

- Website - [Project-Site]()
- Frontend Mentor - [@alperennucr](https://www.frontendmentor.io/profile/alperennucr)
- Github - [@alperennucr](https://github.com/alperennucr)
- LinkedIn - [Alperen Uçar](https://www.linkedin.com/in/alperen-u%C3%A7ar-a26434247/)
