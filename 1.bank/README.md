## Исследование надежности заемщиков банка

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.

Цели исследования - проверка наличия связей между возвратом кредита в срок и наличием детей, семейным положением, уровнем дохода и целью получения кредита.

В ходе исследования была проведена тщательная предобработка данных: по возможности заполнены пропуски в данных, обработаны нереалистичные значения, удалены дубликаты. 

С помощью стемминга мы провели категоризацию - пользователей разбили на группы по целям кредита и на когорты по размеру дохода. 

Исходя из предоставленных данных, напрямую на погашение кредита в срок не влияет ни семейное положение, ни уровень дохода. Есть небольшая корреляция с количеством детей и с возрастом заемщиков. 
Чаще всего возвращают в срок кредиты на собственное жилье, а больше всего задержек по кредитам на автомобили и образование.

### Использованы библиотеки и методы:
- pandas
- matplotlib.pyplot
- seaborn