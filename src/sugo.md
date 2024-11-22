---
layout: page
title: Súgó
---

Bootstrap [Dokumentáció](https://getbootstrap.com/docs) és [Ikonok](https://icons.getbootstrap.com).

---

HTML elemek szerkezete (a mi esetünkben):
```
<elem-típusa
  speciális-tulajdonságok
  class="sablon-stílusok"
  style="egyedi-stílusok"
>
  Tartalom
</elem-típusa>
```
### Ahol:

`elem-típusa`:
  + `div` - osztás
  + `p` - bekezdés
  + `span` - szövegrész (bekezdésen belül, például eltérő stílushoz)
  + `img` - kép
  + `a` - link

`speciális-tulajdonságok` (szóközzel elválasztva):
  + `src="/assets/images/picture.jpg"` - kép elérési útja
  + `href="https://google.com"` - link célpontja 

`sablon-stílusok` (szóközzel elválasztva):
  + `bg-primary`: elsődleges háttérszín
  + `mx-2`: két egységnyi oldalsó margó
  + ...

`egyedi stílusok` (pontosvesszővel elválasztva):
  + `height: 200px`: 200 pixel magasság
  + `font-size: 50px`: 50 pixel betűméret
  + ...
