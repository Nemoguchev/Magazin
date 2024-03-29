# Требования к проекту
### Содержание
1. [Введение](#1)
2. [Требования пользователя](#2) <br>
  2.1. [Программные интерфейсы](#2.1) <br>
  2.2. [Интерфейс пользователя](#2.2) <br>
  2.3. [Характеристики пользователей](#2.3) <br>
3. [Системные требования](#3) <br>
  3.1 [Функциональные требования](#3.1) <br>
  3.2 [Нефункциональные требования](#3.2) <br>
    3.2.1 [Атрибуты качества](#3.2.1) <br>
      3.2.1.1 [Требования к удобству использования](#3.2.1.1) <br>
      3.2.1.2 [Требования к безопасности](#3.2.1.2) <br>
	3.2.2 [Ограничения](#3.2.2) <br>
 4. [Аналоги](#4) <br>
 
 ### Глоссарий
 * Товар - ресурс, предлагаемый пользователям.
 * Корзина - это интерфейс, куда пользователь добавляет товары с целью покупки.
 * Заказ - документ, создаваемый покупателем, на поставку определенного продукта.
 
 ### 1. Введение <a name="1"></a>
2	На текущий момент существует различные приложения для покупки товаров используемые интернет-магазинами. Большая часть из них требует регистрации и с указыванием личных данных, таких как почта, номер телефона и т.д. Данное веб-приложение будет предоставлять безопасный способ заказа товаров без регистрации, а также иметь простой и удобный интерфейс. Приложение будет предоставлять возможность увидеть ранее просмотренные товары, возможность поиска, а также сортировок.
### 2. Требования пользователя <a name="2"></a>
#### 2.1. Программные интерфейсы <a name="2.1"></a>
Проект использует язык Java, а также Servlet API, для хранения данных используется база данных MySQL, для реализации пользовательского интерфейса JSP API.
#### 2.2. Интерфейс пользователя <a name="2.2"></a>
- Окно просмотра всех товаров
  https://github.com/Nemoguchev/Magazin/blob/master/documentation/Mockups/список%20товаров.png
- Окно просмотра детальной информации о товаре
  https://github.com/Nemoguchev/Magazin/blob/master/documentation/Mockups/Инф-я%20о%20товаре.png
- Окно просмотра корзины
  https://github.com/Nemoguchev/Magazin/blob/master/documentation/Mockups/корзина.png
- Окно оформления заказа
  https://github.com/Nemoguchev/Magazin/blob/master/documentation/Mockups/оформление%20зак.png
#### 2.3. Характеристики пользователей <a name="2.3"></a>
Целевая аудитория:
* Пользователи персональных устройств (ПК, ноутбуки и т.д.) интересующиеся в покупке товаров.

### 3. Системные требования <a name="3"></a>
#### 3.1. Функциональные требования <a name="3.1"></a>
Пользователю предоставлены возможности:

| Функция | Требования | 
|:---|:---|
| Просмотр товаров | ППользователю будет предоставлен список доступных товаров со всеми возможностями поиска и сортировок. |
| Просмотр информации о товаре | Пользователю будет предоставляться информация о выбранном товаре (цена, наличие, подробное описание товара) и возможность добавления выбранного товара в корзину |
| Просмотр корзины | Пользователю будет возможно редактировать корзину: удалять товары и редактировать количество приобретаемых копий. |
| Оформление покупки | Пользователь сможет ввести данные, необходимые для корректного оформления заказа. |
| История просмотра | Пользователю будет предоставляться список из 3 последних просмотренных товаров. |

### 3.2 Нефункциональные требования <a name="3.2"></a>
#### 3.2.1 Атрибуты качества <a name="3.2.1"></a>
Приложение позволит получать доступ к товарам расходуя минимум ресурсов используемого устройства и без регистрации в приложении.
##### 3.2.1.1 Требования к удобству использования <a name="3.2.1.1"></a>
1. Все функциональные элементы интерфейса пользователя должны быть понятны всему возможному спектру пользователей.
2. Элементы товаров содержат ссылки на соответствующие товары;
##### 3.2.1.2 Требования к безопасности <a name="3.2.1.2"></a>
1. Все действия в приложении должны осуществляться без использования личных данных посетителей сайта.
2. При оформлении заказа необходимые данные должны храниться в базе данных, доступной только менеджменту приложения.
#### 3.2.2 Ограничения <a name="3.2.2"></a>
* Приложение реализовано на языке Java.
* Приложение доступно для браузера GoogleChrome версии не ниже 3.29, для остальных браузеров ограничений нет.
 