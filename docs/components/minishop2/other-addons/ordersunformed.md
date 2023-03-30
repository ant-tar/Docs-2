# ordersUnformed

Не всегда пользователь доводит процесс оформления заказа до конца. Причины могут быть разные, от сложности процесса оформления на сайте, до нерешительности человека. Данный компонент отслеживает брошенные корзины (неоформленные до конца заказы) и таким образом дает менеджеру возможность провести работу с клиентом - убедить его совершить покупку.

Когда пользователь добавляет товар в корзину, удаляет или изменяет его количество - OrdersUnformed фиксирует информацию об этих событиях в базе данных и предоставляет менеджеру возможность просмотреть список корзин, заказ на покупку которых еще не был оформлен.

![ordersUnformed - 1](https://file.modx.pro/files/7/f/7/7f7e7f8995cdfbf735a2eb751d19b9ac.png)

При этом сохраняется максимальное количество данных о пользователе. Если не состоявшийся покупатель авторизован на сайте, то к его корзине добавляется ссылка на страницу с учетными данными.

![ordersUnformed - 2](https://file.modx.pro/files/d/c/b/dcb1edd15b2173e40a46494b4c41497d.png)

Если же пользователь не авторизован, но он перейдет на страницу оформления заказа и начнет заполнять форму, все корректно указанные ним данные также сохранятся и будут отображаться в окне с подробной информацией о покупках в его корзине в блоке «Дополнительные данные».

![ordersUnformed - 3](https://file.modx.pro/files/2/d/6/2d6fb7dda7ac04a7c3586fe3575bc517.png)

Если же пользователь оформит заказ, то вся информация о его корзине удалится, таким образов менеджер всегда будет видеть только не оформленные заказы и иметь возможность просмотреть максимально полную информацию о потенциальном клиенте.

## Лексиконы

Для формирования понятных подписей к данным используются лексиконы, и они предусматривает все поля стандартной формы оформления заказа miniShop2.

Если же в Вашей форме есть поля, не предусмотренные лексиконом и Вы хотите чтобы к ним тоже были понятные подписи, нужно добавить в соответствующую запись через управление словарями MODX.