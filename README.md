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

#### Списки с чекбоксами:

```html
<ul class="list-check">
  <li class="list-check__item">
    <label class="list-check __label">
      <input type="checkbox" name="check_1">
      <span class="label-text">Name_1</span>
    </label>
  </li>
  <li class="list- check__item">
    <label class="list-check__label">
      <input type="radio" name="check_2">
      <span class="label-text">Name_2</span>
    </label>
 </li>
</ul> 
```
https://gist.github.com/MokusM/e7f5b6665956c17f1c6624e8d26d545c

### 3.Основное меню: 

```html
<nav class="main-nav">
  <ul class="main-nav-list">
    <li class="main-nav-list__item"><a href="#" class="main-nav-list__link">Компания</a></li>
    <li class="main-nav-list__item"><a href="#" class="main-nav-list__link">Пресс-центр</a></li>
    <li class="main-nav-list__item"><a href="#" class="main-nav-list__link">Партнерство</a></li>
  </ul>
</nav>
```
https://gist.github.com/MokusM/3af9f8f62c0fd7ee35e784d8f88d7d6c

### 4. Кнопки:

Кнопкам задается класс .button изменения цветов фонов, любых параметров  - дописывается модификатором, к примеру .button_primary, .button_default...
```css
.button{
	display: inline-block;
	vertical-align: top;
	padding: 16px 30px 0 30px;
	height: 52px;
	border-radius: 26px;
	position: relative;
	font-size: 16px;
	line-height: 18px;
	letter-spacing: 0.5px;
	color: #0f3755;
	border: 1px solid #ffc601;
	background: #ffc601;
	-moz-transition: all 0.2s linear; -o-transition: all 0.2s linear; -ms-transition: all 0.2s linear; -webkit-transition: all 0.2s linear; transition: all 0.2s linear;
	text-align: center;
}
.button:hover{
	border-color:#0f3755;
	background: #0f3755;
	color: #FFF;
}
button.button, input.button{ padding-top: 0px!important;}
.button_small{
	height:34px;
	padding: 9px 23px 0 23px;
	font-size: 14px;
	line-height: 16px;
}

```
## Слова, часто используемые в CSS-классах

### Изображения

`image`, `img`, `picture`, `pic` — картинка<br>
`icon` — иконка<br>
`logo` — логотип<br>
`userpic`, `avatar` — юзерпик, маленькая картинка пользователя<br>
`thumbnail`, `thumb` — миниатюра, уменьшенное изображение<br>

### Текст

`title`, `subject`, `heading`, `headline`, `caption` — заголовок<br>
`subtitle` — подзаголовок<br>
`slogan` — слоган<br>
`lead`, `tagline` — лид-абзац в тексте<br>
`text` — текстовый контент<br>
`desc` — описание, вариант текстового контента<br>
`excerpt` — отрывок текста, обычно используется перед ссылкой «Читать далее...»<br>
`link` — ссылка<br>
`copyright`, `copy` — копирайт

### Списки

`list`, `items` — список<br>
`item` — элемент списка<br>

### Блоки

`page` — корневой элемент страницы<br>
`header` — шапка (страницы или элемента)<br>
`footer` — подвал (страницы или элемента)<br>
`section` — раздел контента (один из нескольких)<br>
`body` — основная часть (страницы или элемента)<br>
`content` — содержимое элемента<br>
`sidebar` — боковая колонка (страницы или элемента)<br>
`aside` — блок с дополнительной информацией<br>
`widget` — виджет, например, в боковой колонке<br>

### Раскладка

`wrapper`, `wrap` — обёртка, обычно внешняя<br>
`inner` — внутренняя обёртка<br>
`container`, `holder`, `box` — контейнер<br>
`grid` — раскладка (страницы или элемента) в виде сетки (обычно содержит в себе `row` и `col`)<br>
`row` — контейнер в виде строки<br>
`col`, `column` — контейнер в виде столбца

### Элементы управления

`button`, `btn` —  кнопка, например, для отправки формы<br>
`control` — элемент управления, например, стрелки «Вперёд/назад» в фотогалерее, кнопки управления слайдером<br>
`dropdown` — выпадающий список<br>

### Медиавыражения

`phone`, `mobile` — мобильные устройства<br>
`phablet` — телефоны с большим экраном (6-7")<br>
`tablet` — планшеты<br>
`notebook`, `laptop` — ноутбуки<br>
`desktop` — настольные компьютеры<br>

### Размеры

`tiny` — маленький, крохотный<br>
`small` — небольшой<br>
`medium` — средний<br>
`big`, `large` — большой<br>
`huge` — огромный<br>
`narrow` — узкий<br>
`wide` — широкий<br>

### Разное

`search` — поиск<br>
`socials` — блок иконок соцсетей<br>
`advertisement`, `adv`, `commercial`, `promo` — рекламный блок (режутся Адблоком, не рекомендуется использовать такие классы для блоков с внутренней рекламой)<br>
`features`, `benefits` — список основных особенностей товара, услуги<br>
`slider`, `carousel` — слайдер, интерактивный элемент с прокруткой содержимого<br>
`pagination` — постраничная навигация<br>
`user`, `author` — пользователь, автор записи или комментария<br>
`meta` — блок с дополнительной информацией, например, блок тегов и даты в посте<br>
`cart`, `basket` — корзина<br>
`breadcrumbs` — навигационная цепочка, «хлебные крошки»<br>
`more`, `all` — ссылка на полную информацию<br>
`modal` — модальное (диалоговое) окно<br>
`popup` — всплывающее окно<br>
`tooltip`, `tip` — всплывающее подсказки<br>
`preview` — анонс, отрывок, например новости или поста, может состоять из заголовка, описания и картинки. Предполагается ссылка на полную версию<br>

### Состояния

`active`, `current` — активный элемент, например, текущий пункт меню<br>
`hidden` — скрытый элемент<br>
`error` — статус ошибки<br>
`warning` — статус предупреждения<br>
`success` — статус успешного выполнения задачи<br>
`pending` — состояние ожидания, например, перед сменой статуса на error или success<br>
