friends.get

$description
Возвращает идентификаторы пользователей, являющихся друзьями текущего пользователя.

$params#uid
Идентификатор пользователя, от имени которого нужно запросить список друзей. Укажите uid при вызове этого метода без ключа сессии.

$params#fid
Идентификатор пользователя, список друзей которого нужно получить. Если не указано возвращается список друзей текущего пользователя.

$params#sort_type
Тип сортировки. На данный момент доступны следующие типы:

* PRESENT — сортирует друзей на основании того, как часто uid дарит другу подарки на портале. Наиболее часто одариваемые подарками друзья будут впереди.

$additional
**Ограничения**

На портале количество друзей ограничено:

* для звёзд не более 10000
* для обычных пользователей не более 5000
