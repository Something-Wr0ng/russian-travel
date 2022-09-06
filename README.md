# **Путешествие по России**
Проект, написанный мной на курсе Веб-дизайн от Яндекс Практикума. Написан по макету в Figma с применением знаний, полученных в теории и практических заданиях, оформлен по методологии БЭМ. В проекте применены иструменты для создания адаптивных страниц.

Страница содержит полезную информацию о возможностях путешествия по России.

## Языки
* HTML
* CSS

## Примеры используемых технологий и инструментов
* Grid
```css 
.photo-grid {
  max-width: 1184px;
  margin: 0 auto 0;
  padding: 0 48px 0;
  display: grid;
  grid-template-columns: repeat(4, fit-content(284px));
  gap: 16px;
}
```
* Медиазапросы
```css 
@media screen and (max-width: 1024px) and (min-width: 769px) {
  .photo-grid {
    max-width: 928px;
    grid-template-columns: repeat(3, fit-content(300px));
    gap: 14px;
  } 
}
```
## Проект на GitPages
https://something-wr0ng.github.io/russian-travel/