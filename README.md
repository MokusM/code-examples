## Примеры кода БЭМ
#### Эти заготовки используем в обязательном порядке!!! заготовки можна брать по ссылке на gist

### 1. Выбор языков

```html
<div class="box-lang">
  <ul class="list-lang">
    <li class="list-lang__item active">
      <a class="list-lang__link" href="#">Рус</a>
    </li>
    <li class="list-lang__item">
      <a class="list-lang__link" href="#">укр</a>
    </li>
  </ul>
</div> 
```
https://gist.github.com/MokusM/87ba7f6d31424cad745e04fe834c1749

### 2. Элементы форм

```html
<div class="box-form">
  <form>
    <div class="box-field">
      <label for="" class="box-field__label"></label>
      <div class="box-field__input">
        <input type="text" class="form-control" placeholder="Имя">
      </div>
    </div>
    <div class="box-field">
      <label for="" class="box-field__label"></label>
      <div class="box-field__input">
        <select>
          <option>name_1</option>
          <option>name_2</option>
        </select>
      </div>
    </div>
  </form>
</div>
```
https://gist.github.com/MokusM/1fedb0120d3eb29784f1009e435421ea<br>
В текстовых полях параметр type может принимать следующие значения:
text, password, email, number, search, tel, url

#### Списки с радио кнопками: 

```html
<ul class="list-radio">
  <li class="list-radio__item">
    <label class="list-radio__label">
      <input type="radio" name="name_1">
      <span class="label-text">Name_1</span>
    </label>
  </li>
  <li class="list-radio__item">
    <label class="list-radio__label">
      <input type="radio" name="name_1">
      <span class="label-text">Name_2</span>
    </label>
  </li>
</ul>
```
https://gist.github.com/MokusM/932720bb9125e087d9b66736cfef01d0 

## Слова, часто используемые в CSS-классах

### Изображения

`image`, `img`, `picture`, `pic` — картинка
`icon` — иконка
`logo` — логотип
`userpic`, `avatar` — юзерпик, маленькая картинка пользователя
`thumbnail`, `thumb` — миниатюра, уменьшенное изображение

### Текст

`title`, `subject`, `heading`, `headline`, `caption` — заголовок

`subtitle` — подзаголовок

`slogan` — слоган

`lead`, `tagline` — лид-абзац в тексте

`text` — текстовый контент

`desc` — описание, вариант текстового контента

`excerpt` — отрывок текста, обычно используется перед ссылкой «Читать далее...»

`link` — ссылка

`copyright`, `copy` — копирайт

### Списки

`list`, `items` — список

`item` — элемент списка

### Блоки

`page` — корневой элемент страницы

`header` — шапка (страницы или элемента)

`footer` — подвал (страницы или элемента)

`section` — раздел контента (один из нескольких)

`body` — основная часть (страницы или элемента)

`content` — содержимое элемента

`sidebar` — боковая колонка (страницы или элемента)

`aside` — блок с дополнительной информацией

`widget` — виджет, например, в боковой колонке

### Раскладка

`wrapper`, `wrap` — обёртка, обычно внешняя

`inner` — внутренняя обёртка

`container`, `holder`, `box` — контейнер

`grid` — раскладка (страницы или элемента) в виде сетки (обычно содержит в себе `row` и `col`)

`row` — контейнер в виде строки

`col`, `column` — контейнер в виде столбца

### Элементы управления

`button`, `btn` —  кнопка, например, для отправки формы

`control` — элемент управления, например, стрелки «Вперёд/назад» в фотогалерее, кнопки управления слайдером

`dropdown` — выпадающий список

### Медиавыражения

`phone`, `mobile` — мобильные устройства

`phablet` — телефоны с большим экраном (6-7")

`tablet` — планшеты

`notebook`, `laptop` — ноутбуки

`desktop` — настольные компьютеры

### Размеры

`tiny` — маленький, крохотный

`small` — небольшой

`medium` — средний

`big`, `large` — большой

`huge` — огромный

`narrow` — узкий

`wide` — широкий

### Разное

`search` — поиск

`socials` — блок иконок соцсетей

`advertisement`, `adv`, `commercial`, `promo` — рекламный блок (режутся Адблоком, не рекомендуется использовать такие классы для блоков с внутренней рекламой)

`features`, `benefits` — список основных особенностей товара, услуги

`slider`, `carousel` — слайдер, интерактивный элемент с прокруткой содержимого

`pagination` — постраничная навигация

`user`, `author` — пользователь, автор записи или комментария

`meta` — блок с дополнительной информацией, например, блок тегов и даты в посте

`cart`, `basket` — корзина

`breadcrumbs` — навигационная цепочка, «хлебные крошки»

`more`, `all` — ссылка на полную информацию

`modal` — модальное (диалоговое) окно

`popup` — всплывающее окно

`tooltip`, `tip` — всплывающее подсказки

`preview` — анонс, отрывок, например новости или поста, может состоять из заголовка, описания и картинки. Предполагается ссылка на полную версию

### Состояния

`active`, `current` — активный элемент, например, текущий пункт меню

`hidden` — скрытый элемент

`error` — статус ошибки

`warning` — статус предупреждения

`success` — статус успешного выполнения задачи

`pending` — состояние ожидания, например, перед сменой статуса на error или success
