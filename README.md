# goit-markup-hw-04

При создании svg елемента необходимо делать следующим способом:

1. Все елементы svg сжимаем и создается спрайт, который в свою очередь так же сжимается.
2. По необходимости удаляется цвет с svg спрайта, а именно переходим в файл svg спрайта и путем
   поиска свойств fill или style color удаляем весь цвет с необходимого symbol.
3. После этого внутри сылки указывается svg елемент с задаными атрибутами ширины и высоты по макету.
4. После переходим к реакдиторванию svg елемента и сылки, а именно для ссылки display: flex;
   justify-content: center; align-items: center; что бы выровнять svg елемент и с сылкой, после
   этого указываем для svg "fill: currentColor" и данное свойство унаследует любой цвет ссылки, даже
   цвет при hovere будет наследован svg елементом.
5. Если уже был создан ранее svg спрайт, для того что бы добавить в него svg елемент нам
   необходимо - создать svg спрайт данного элемента и скопирровать с него symbol вместе с
   внутренностью и после этого вставить этот код в наш готовый svg спрайт.
   
 6. **Выпадающее меню**
 7.  Что бы сделать выпадающее меню необходимо для начала сделать основное меню из которого уже соотвественно будет выпадать второе меню.
 Пример кода 

 ```html 
      <ul class="menu">
      <li class="list-menu ">
        <a href="" class="link-list-menu">Техника</a>
        <ul class="submenu">
          <li class="list-submenu">
            <a href="" class="link-list-submenu">Духи</a>
          </li>
          <li class="list-submenu">
            <a href="" class="link-list-submenu">Пасты</a>
          </li>
        </ul>
      </li>
      <li class="list-menu">
        <a href="" class="link-list-menu">Косметика</a>
        <ul class="submenu">
          <li class="list-submenu">
            <a href="" class="link-list-submenu">Духи</a>
          </li>
          <li class="list-submenu">
            <a href="" class="link-list-submenu">Пасты</a>
          </li>
        </ul>
        ```
        Суть в том что бы второй список разместить в данном случае например под первым списком необходимо сделать следующее, 1. Задаем основному `<li>` 
        
 
