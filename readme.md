<h3>ASweb Watermark</h3>

<div>

<p> Наложение водяного знака на изображение</p>

## О библиотеке <a name = "about"></a>

Библиотека для Фреймворка ASCommerce. Может быть использована отдельно

## Установка и начало работы <a name = "getting_started"></a>


### Установка

Рекомендуется установка через Composer:

```
composer require alexsuleymanov/watermark
```

- Imageresizer совместим с PHP 8.0 to 8.1
- Imageresizer совместим с PHP 7.0 до 7.4
- Imageresizer совместим с PHP 5.4 до 5.6


### Использование

Чтобы сохранить файл, укажите имя конечного файла в $dst_filename.
<br>
Чтобы вывести фото в виде изображения, укажите $dst_filename = null. 

```
$dst_filename = "img.jpg";
$Watermark = new ASweb\Watermark\Watermark();
$Watermark->add(1, $dst_filename);
```


## Авторы <a name = "authors"></a>

- [@alexsuleymanov](https://github.com/alexsuleymanov) - Alex Suleimanov
