email - test@mail.com
пароль - 1

# **Тест-кейс 1**

**Предусловие:**
1. Открыта главная страница http://shop.bugred.ru/
2. Пользователь зарегистрирован
3. Пользователь не авторизован

| **Название** | **Описание шагов** | **Ожидаемый результат** |
| --- | --- | --- |
| **Авторизация пользователя** | **В шапке сайта нажать на кнопку “Вход”** | **Открыта форма ввода email и пароля. По умолчанию поля не заполнены** |
| **Заполнить поля email и пароль данными пользователя TestUser1** | **Поля заполнены** |
| **Нажать кнопку “Войти”** | **Осуществлен вход в магазин под пользователем TestUser1** |


# **Тест-кейс 2**

**Предусловие:**

1. Открыта главная страница <http://shop.bugred.ru/>
2. Пользователь авторизован
3. В корзине нет товаров (счетчик равен 0)

| **Название** | **Описание шагов** | **Ожидаемый результат** |
| --- | --- | --- |
| **Добавление товара в корзину** | **Слева в разделе “Категории” выбрать “Верхняя одежда”** | **Открыт раздел “Верхняя одежда” с одной позицией “Пальто”** |
| **Нажать на позицию “Пальто”** | **Открыта позиция “Пальто”.Отображаются атрибуты:Цвет: синийПараметры:dressЦена: 999 р.Присутствует возможность выбрать количество и нажать кнопку “Добавить в корзину”** |
| **В поле “Количество” ввести значение 1** | **В поле “Количество” введено значение 1** |
| **Нажать кнопку “Добавить в корзину”** | **Товар добавлен в корзину, счетчик количества товара в корзине увеличен на 1. Под товаром отображается область “Вы недавно смотрели”** |


# **Тест-кейс 3**

**Предусловие:**

1. Открыта главная страница http://shop.bugred.ru/
2. Пользователь авторизован
3. В корзине присутствует товар (счетчик равен 1)

Телефон - 89991231230
Адрес - г. Уфа, ул. Ленина 13, кв 666

| **Название** | **Описание шагов** | **Ожидаемый результат** |
| --- | --- | --- |
| **Оформление заказа в корзине** | **В правом верхнем углу нажать на кнопку “Корзина”** | **Открыта корзина пользователя с добавленным товаром. На форме отображаются атрибуты:ТоварКоличествоЦена за единицуОбщая цена**<br/>**кнопки:“Удалить товар”“Сохранить”“Оформить заказ”**<br/>**поля для ввода: ТелефонАдрес** |
| **В поля “Телефон” и  “Адрес” ввести значения пользователя** | **Поля заполнены** |
| **Нажать кнопку “Оформить заказ”** | **Заказ оформлен. Пользователь видит сообщение с текстом: “Ваш заказ №\[номер заказа\] собран и отправлен. Ура!”** |


# **Тест-кейс 4**

**Предусловие:**

1. Открыта главная страница <http://shop.bugred.ru/>
2. Пользователь зарегистрирован
3. Пользователь авторизован
4. Пользователь оформил заказ


| **Название** | **Описание шагов** | **Ожидаемый результат** |
| --- | --- | --- |
| **Просмотр заказа в “Личном кабинете”** | **В шапке сайта нажать на кнопку с логином пользователя “TestUser1”** | **Пользователь видит выпадающий список:НастройкиЛичный кабинетВыйти**  |
| **Нажать “Личный кабинет”** | **Открыта форма просмотра истории заказов:Номер заказаСумма заказакнопка: Посмотреть детали** |
| **Нажать “Посмотреть детали”** | **Отображается информация по заказу:Телефон: 89991231230Адрес: г. Уфа, ул. Ленина 13, кв 666Товар: ПальтоКоличество: 1Цена за единицу: 999Общая цена: 999Итого: 999** |


# **Тест-кейс 5**

**Предусловие:**

1. Открыта главная страница <http://shop.bugred.ru/>
2. Пользователь зарегистрирован
3. Пользователь авторизован

| **Название** | **Описание шагов** | **Ожидаемый результат** |
| --- | --- | --- |
| **Выход пользователя из магазина** | **В шапке сайта нажать на кнопку с логином пользователя “TestUser1”** | **Пользователь видит выпадающий список:НастройкиЛичный кабинетВыйти**  |
| **Нажать “Выйти”** | **Осуществлен выход из магазина. Отображается форма ввода логина и пароля** |
