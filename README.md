### <img src="https://www.adopsinsider.com/wp-content/uploads/2016/11/Charles-Proxy-Logo.png" title="database" alt="database" width="400" height="150"/> 
### Charles proxy
<hr>
<h4>С помощью Charles Proxy был выполнен перехват трафик с сайта <a href="https://demowebshop.tricentis.com/"> https://demowebshop.tricentis.com/ </a> согласно следующим заданиям.<h4>
<h3> Задание 1.1</h3>
Необходимо изменить количество товаров в корзине на уже известном ресурсе http://demowebshop.tricentis.com/cart <br>
Например, в запросе отправляется "2 товара", а должны вернуть "500".<br>
<a href="https://github.com/Dzianis-Brahinets/Charles-proxy/blob/225d008f013ed2aad093ffd1fbe3470727566ffa/Charles%201.1.mp4"> Решение </a>

<h3> Задание 1.2</h3>
Смоделировать ситуацию, при которой при обращении к <a href="https://demowebshop.tricentis.com/"> https://demowebshop.tricentis.com/ </a> сервер вернет статус-код 403.<br> Запросы к другим ресурсам должны работать в штатном режиме.<br>
<a href="https://github.com/Dzianis-Brahinets/Charles-proxy/blob/225d008f013ed2aad093ffd1fbe3470727566ffa/Charles%201.2%20(Response).mp4"> Решение используя функцию Response </a><br>
<a href="https://github.com/Dzianis-Brahinets/Charles-proxy/blob/225d008f013ed2aad093ffd1fbe3470727566ffa/Charles%201.2(Rewrite).mp4"> Решение используя функцию Rewrite </a>

<h3> Задание 1.3</h3>
Необходимо перебрасить запросы с одного окружения на другой. Например, не можем проводить прямое тестирование на проде, а должны стучаться к окружению для тестирования. Предположим, что <a href="https://demowebshop.tricentis.com/"> https://demowebshop.tricentis.com/ </a> это продовская версия, а <a href="https://demowebshop.tricentis.com/qa"> https://demowebshop.tricentis.com/qa </a> это QA стенд (этой страницы не существует). Задача перенаправить запрос с Prod на QA.<br>
<a href="https://github.com/Dzianis-Brahinets/Charles-proxy/blob/225d008f013ed2aad093ffd1fbe3470727566ffa/Charles%201.3.mp4"> Решение</a>
<hr>
<h4> Выполнен перехват трафика с мобильного телефона согласно следующим заданиям.</h4>
<hr>
<h3> Задание 2.1</h3>
Необходимо удалить товары из корзины на <a href="https://demowebshop.tricentis.com/cart"> https://demowebshop.tricentis.com/cart </a>.<br>
<a href="https://github.com/Dzianis-Brahinets/Charles-proxy/blob/225d008f013ed2aad093ffd1fbe3470727566ffa/Charles%202.1.mp4"> Решение</a>

<h3> Задание 2.2</h3>
Смоделировать ситуацию, при которой при обращении к <a href="https://demowebshop.tricentis.com/"> https://demowebshop.tricentis.com/ </a> пользователь увидит в браузере любую картинку.<br>
<a href="https://github.com/Dzianis-Brahinets/Charles-proxy/blob/225d008f013ed2aad093ffd1fbe3470727566ffa/Charles%202.2.mp4"> Решение</a>

<h3> Задание 2.3</h3>
Приложить скриншот любого перехваченного HTTPs-запроса с мобильного устройства. В header user-agent должна быть информация о устройстве.<br>
<a href="https://github.com/Dzianis-Brahinets/Charles-proxy/blob/225d008f013ed2aad093ffd1fbe3470727566ffa/Charles%202.3.png"> Решение</a>