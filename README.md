# Solving_SQL_ACADEMY
[Ссылка на задания из тренажера](https://sql-academy.org/ru/trainer)
 
# Содержание
- Тренажер
    - [Задание 1](#задание-1)
    - [Задание 2](#задание-2)
    - [Задание 3](#задание-3)
    - [Задание 4](#задание-4)
    - [Задание 5](#задание-5)
    - [Задание 6](#задание-6)
    - [Задание 7](#задание-7)
    - [Задание 8](#задание-8)
    - [Задание 9](#задание-9)
    - [Задание 10](#задание-10)
    - [Задание 11](#задание-11)
    - [Задание 12](#задание-12)
    - [Задание 13](#задание-13)
    - [Задание 14](#задание-14)
    - [Задание 15](#задание-15)
    - [Задание 16](#задание-16)
    - [Задание 17](#задание-17)
    - [Задание 18](#задание-18)
    - [Задание 19](#задание-19)
    - [Задание 20](#задание-20)
    - [Задание 21](#задание-21)
    - [Задание 22](#задание-22)
    - [Задание 23](#задание-23)
    - [Задание 24](#задание-24)
    - [Задание 25](#задание-25)
    - [Задание 27](#задание-27)
    - [Задание 28](#задание-28)
    - [Задание 29](#задание-29)
    - [Задание 30](#задание-30)
    - [Задание 31](#задание-31)
    - [Задание 32](#задание-32)
    - [Задание 34](#задание-34)
    - [Задание 36](#задание-36)
    - [Задание 38](#задание-38)
    - [Задание 39](#задание-39)
    - [Задание 41](#задание-41)
    - [Задание 43](#задание-43)
    - [Задание 46](#задание-46)
    - [Задание 49](#задание-49)
    - [Задание 51](#задание-51)
    - [Задание 52](#задание-52)
    - [Задание 53](#задание-53)
    - [Задание 54](#задание-54)
    - [Задание 56](#задание-56)
    - [Задание 74](#задание-74)
    - [Задание 75](#задание-75)

## Тренажер
# Задание 1
Вывести имена всех людей, которые есть в базе данных авиакомпаний

```sql
 SELECT name FROM Passenger
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Bruce Willis</td></tr><tr><td class="table-row-number">2</td><td>George Clooney</td></tr><tr><td class="table-row-number">3</td><td>Kevin Costner</td></tr><tr><td class="table-row-number">4</td><td>Donald Sutherland</td></tr><tr><td class="table-row-number">5</td><td>Jennifer Lopez</td></tr><tr><td class="table-row-number">6</td><td>Ray Liotta</td></tr><tr><td class="table-row-number">7</td><td>Samuel L. Jackson</td></tr><tr><td class="table-row-number">8</td><td>Nikole Kidman</td></tr><tr><td class="table-row-number">9</td><td>Alan Rickman</td></tr><tr><td class="table-row-number">10</td><td>Kurt Russell</td></tr><tr><td class="table-row-number">11</td><td>Harrison Ford</td></tr><tr><td class="table-row-number">12</td><td>Russell Crowe</td></tr><tr><td class="table-row-number">13</td><td>Steve Martin</td></tr><tr><td class="table-row-number">14</td><td>Michael Caine</td></tr><tr><td class="table-row-number">15</td><td>Angelina Jolie</td></tr><tr><td class="table-row-number">16</td><td>Mel Gibson</td></tr><tr><td class="table-row-number">17</td><td>Michael Douglas</td></tr><tr><td class="table-row-number">18</td><td>John Travolta</td></tr><tr><td class="table-row-number">19</td><td>Sylvester Stallone</td></tr><tr><td class="table-row-number">20</td><td>Tommy Lee Jones</td></tr><tr><td class="table-row-number">21</td><td>Catherine Zeta-Jones</td></tr><tr><td class="table-row-number">22</td><td>Antonio Banderas</td></tr><tr><td class="table-row-number">23</td><td>Kim Basinger</td></tr><tr><td class="table-row-number">24</td><td>Sam Neill</td></tr><tr><td class="table-row-number">25</td><td>Gary Oldman</td></tr><tr><td class="table-row-number">26</td><td>ClINT Eastwood</td></tr><tr><td class="table-row-number">27</td><td>Brad Pitt</td></tr><tr><td class="table-row-number">28</td><td>Johnny Depp</td></tr><tr><td class="table-row-number">29</td><td>Pierce Brosnan</td></tr><tr><td class="table-row-number">30</td><td>Sean Connery</td></tr><tr><td class="table-row-number">31</td><td>Bruce Willis</td></tr><tr><td class="table-row-number">32</td><td>Mullah Omar</td></tr></tbody></table>
</details>

# Задание 2
Вывести названия всеx авиакомпаний
```sql
SELECT name FROM Company
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Don_avia</td></tr><tr><td class="table-row-number">2</td><td>Aeroflot</td></tr><tr><td class="table-row-number">3</td><td>Dale_avia</td></tr><tr><td class="table-row-number">4</td><td>air_France</td></tr><tr><td class="table-row-number">5</td><td>British_AW</td></tr></tbody></table>
</details>


# Задание 3
Вывести все рейсы, совершенные из Москвы
```sql
SELECT * FROM Trip
WHERE town_from = "Moscow"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>id</th><th>company</th><th>plane</th><th>town_from</th><th>town_to</th><th>time_out</th><th>time_in</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1145</td><td>2</td><td>IL-86</td><td>Moscow</td><td>Rostov</td><td>1900-01-01T09:35:00.000Z</td><td>1900-01-01T11:23:00.000Z</td></tr><tr><td class="table-row-number">2</td><td>1182</td><td>1</td><td>TU-134</td><td>Moscow</td><td>Rostov</td><td>1900-01-01T12:35:00.000Z</td><td>1900-01-01T14:30:00.000Z</td></tr><tr><td class="table-row-number">3</td><td>1188</td><td>1</td><td>TU-134</td><td>Moscow</td><td>Rostov</td><td>1900-01-01T22:50:00.000Z</td><td>1900-01-02T00:48:00.000Z</td></tr><tr><td class="table-row-number">4</td><td>1196</td><td>1</td><td>TU-154</td><td>Moscow</td><td>Rostov</td><td>1900-01-01T04:00:00.000Z</td><td>1900-01-01T05:45:00.000Z</td></tr></tbody></table>
</details>

# Задание 4
Вывести имена людей, которые заканчиваются на "man"
```sql
SELECT name 
FROM Passenger
WHERE name LIKE '%man'
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Nikole Kidman</td></tr><tr><td class="table-row-number">2</td><td>Alan Rickman</td></tr><tr><td class="table-row-number">3</td><td>Gary Oldman</td></tr></tbody></table>
</details>


# Задание 5
Вывести количество рейсов, совершенных на TU-134
```sql
SELECT COUNT(*) as count
FROM Trip
WHERE plane LIKE 'TU-134'
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>count</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>4</td></tr></tbody></table>
</details>

# Задание 6
Какие компании совершали перелеты на Boeing
```sql
SELECT comp.name
FROM Trip
	JOIN Company comp ON Trip.company = comp.id
WHERE Trip.plane = 'Boeing'
GROUP BY comp.name
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>air_France</td></tr><tr><td class="table-row-number">2</td><td>British_AW</td></tr></tbody></table>
</details>

# Задание 7
Вывести все названия самолётов, на которых можно улететь в Москву (Moscow)
```sql
SELECT DISTINCT Trip.plane
FROM Trip
WHERE town_to LIKE 'Moscow'
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>plane</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>IL-86</td></tr><tr><td class="table-row-number">2</td><td>TU-134</td></tr><tr><td class="table-row-number">3</td><td>TU-154</td></tr></tbody></table>
</details>

# Задание 8
В какие города можно улететь из Парижа (Paris) и сколько времени это займёт?
```sql
SELECT town_to,
	TIMEDIFF(time_in, time_out) as flight_time
FROM Trip
WHERE town_from = "Paris"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>town_to</th><th>flight_time</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Rostov</td><td>03:33:00</td></tr><tr><td class="table-row-number">2</td><td>London</td><td>01:00:00</td></tr></tbody></table>
</details>

# Задание 9
Какие компании организуют перелеты из Владивостока (Vladivostok)?
```sql
SELECT DISTINCT company.name
FROM Trip
	JOIN Company ON Trip.company = Company.id
WHERE town_from = "Vladivostok"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Dale_avia</td></tr></tbody></table>
</details>

# Задание 10
Вывести вылеты, совершенные с 10 ч. по 14 ч. 1 января 1900 г.
```sql
SELECT *
FROM Trip
WHERE time_out BETWEEN '1900-01-01 10:00:00' AND '1900-01-01 14:00:00'
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>id</th><th>company</th><th>plane</th><th>town_from</th><th>town_to</th><th>time_out</th><th>time_in</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1182</td><td>1</td><td>TU-134</td><td>Moscow</td><td>Rostov</td><td>1900-01-01T12:35:00.000Z</td><td>1900-01-01T14:30:00.000Z</td></tr><tr><td class="table-row-number">2</td><td>7772</td><td>5</td><td>Boeing</td><td>Singapore</td><td>London</td><td>1900-01-01T12:00:00.000Z</td><td>1900-01-02T02:00:00.000Z</td></tr><tr><td class="table-row-number">3</td><td>7774</td><td>5</td><td>Boeing</td><td>Singapore</td><td>London</td><td>1900-01-01T14:00:00.000Z</td><td>1900-01-02T06:00:00.000Z</td></tr></tbody></table>
</details>

# Задание 11
Выведите пассажиров с самым длинным ФИО. Пробелы, дефисы и точки считаются частью имени.
```sql
SELECT name
FROM passenger
ORDER BY LENGTH(name) DESC
LIMIT 0, 1
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Catherine Zeta-Jones</td></tr></tbody></table>
</details>

# Задание 12
Вывести id и количество пассажиров для всех прошедших полётов
```sql
SELECT trip,
	COUNT(passenger) as count
FROM Pass_in_trip
GROUP BY trip
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>trip</th><th>count</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1100</td><td>1</td></tr><tr><td class="table-row-number">2</td><td>1123</td><td>3</td></tr><tr><td class="table-row-number">3</td><td>1124</td><td>1</td></tr><tr><td class="table-row-number">4</td><td>1145</td><td>2</td></tr><tr><td class="table-row-number">5</td><td>1181</td><td>4</td></tr><tr><td class="table-row-number">6</td><td>1182</td><td>2</td></tr><tr><td class="table-row-number">7</td><td>1187</td><td>2</td></tr><tr><td class="table-row-number">8</td><td>1188</td><td>1</td></tr><tr><td class="table-row-number">9</td><td>8882</td><td>2</td></tr><tr><td class="table-row-number">10</td><td>7771</td><td>6</td></tr><tr><td class="table-row-number">11</td><td>7772</td><td>5</td></tr><tr><td class="table-row-number">12</td><td>8881</td><td>1</td></tr><tr><td class="table-row-number">13</td><td>7778</td><td>1</td></tr><tr><td class="table-row-number">14</td><td>7773</td><td>1</td></tr></tbody></table>
</details>


# Задание 13
Вывести имена людей, у которых есть полный тёзка среди пассажиров
```sql
SELECT name
FROM Passenger
GROUP by name
HAVING COUNT(name) > 1
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Bruce Willis</td></tr></tbody></table>
</details>

# Задание 14
В какие города летал Bruce Willis
```sql
SELECT DISTINCT town_to
FROM Trip
	JOIN Pass_in_trip pit ON pit.Trip = Trip.id
	JOIN Passenger pass ON pass.id = pit.passenger
WHERE name LIKE 'Bruce Willis'
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>town_to</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Paris</td></tr><tr><td class="table-row-number">2</td><td>Vladivostok</td></tr><tr><td class="table-row-number">3</td><td>Moscow</td></tr></tbody></table>
</details>


# Задание 15
Выведите дату и время прилёта пассажира Стив Мартин (Steve Martin) в Лондон (London)
```sql
WITH Full_table AS (
	SELECT time_in
	FROM Trip
		JOIN Pass_in_trip pit ON pit.trip = Trip.id
		JOIN Passenger pass ON pass.id = pit.passenger
	WHERE name LIKE "Steve Martin"
		AND town_to LIKE "London"
)
SELECT *
FROM Full_table
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>time_in</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1900-01-02T02:00:00.000Z</td></tr></tbody></table>
</details>

# Задание 16
Вывести отсортированный по количеству перелетов (по убыванию) и имени (по возрастанию) список пассажиров, совершивших хотя бы 1 полет.
```sql
SELECT name, COUNT(*) as count
FROM Passenger
	JOIN Pass_in_trip ON Pass_in_trip.passenger = Passenger.id
GROUP BY name
HAVING COUNT(trip) > 0
ORDER BY COUNT(trip) DESC,
	name
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th><th>count</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Michael Caine</td><td>4</td></tr><tr><td class="table-row-number">2</td><td>Mullah Omar</td><td>4</td></tr><tr><td class="table-row-number">3</td><td>Bruce Willis</td><td>3</td></tr><tr><td class="table-row-number">4</td><td>Harrison Ford</td><td>3</td></tr><tr><td class="table-row-number">5</td><td>Jennifer Lopez</td><td>3</td></tr><tr><td class="table-row-number">6</td><td>Kurt Russell</td><td>3</td></tr><tr><td class="table-row-number">7</td><td>Nikole Kidman</td><td>3</td></tr><tr><td class="table-row-number">8</td><td>Kevin Costner</td><td>2</td></tr><tr><td class="table-row-number">9</td><td>Ray Liotta</td><td>2</td></tr><tr><td class="table-row-number">10</td><td>Steve Martin</td><td>2</td></tr><tr><td class="table-row-number">11</td><td>Alan Rickman</td><td>1</td></tr><tr><td class="table-row-number">12</td><td>George Clooney</td><td>1</td></tr><tr><td class="table-row-number">13</td><td>Russell Crowe</td><td>1</td></tr></tbody></table>
</details>

# Задание 17
Определить, сколько потратил в 2005 году каждый из членов семьи. В результирующей выборке не выводите тех членов семьи, которые ничего не потратили.
```sql
SELECT member_name,
	status,
	SUM(amount * unit_price) AS costs
FROM FamilyMembers
	JOIN Payments ON Payments.family_member = FamilyMembers.member_id
WHERE YEAR(date) = 2005
GROUP by member_name,
	status
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>member_name</th><th>status</th><th>costs</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Headley Quincey</td><td>father</td><td>2474</td></tr><tr><td class="table-row-number">2</td><td>Flavia Quincey</td><td>mother</td><td>74194</td></tr><tr><td class="table-row-number">3</td><td>Andie Quincey</td><td>son</td><td>3500</td></tr><tr><td class="table-row-number">4</td><td>Lela Quincey</td><td>daughter</td><td>650</td></tr><tr><td class="table-row-number">5</td><td>Annie Quincey</td><td>daughter</td><td>1060</td></tr></tbody></table>
</details>


# Задание 18
Узнать, кто старше всех в семьe
```sql
SELECT member_name
FROM FamilyMembers
WHERE birthday = (
		SELECT MIN(birthday)
		FROM FamilyMembers
	)
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>member_name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Headley Quincey</td></tr></tbody></table>
</details>

# Задание 19
Определить, кто из членов семьи покупал картошку (potato)
```sql
SELECT DISTINCT status
FROM FamilyMembers fm
	JOIN Payments p ON fm.member_id = p.family_member
	JOIN Goods g ON g.good_id = p.good
WHERE good_name LIKE "potato"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>status</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>father</td></tr><tr><td class="table-row-number">2</td><td>mother</td></tr></tbody></table>
</details>

# Задание 20
Сколько и кто из семьи потратил на развлечения (entertainment). Вывести статус в семье, имя, сумму
```sql
SELECT status,
	member_name,
	SUM(unit_price * amount) AS costs
FROM FamilyMembers
	JOIN Payments ON Payments.family_member = FamilyMembers.member_id
	JOIN Goods ON Goods.good_id = Payments.good
	JOIN GoodTypes ON Goods.type = GoodTypes.good_type_id
WHERE good_type_name = "entertainment"
GROUP BY status,
	member_name
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>status</th><th>member_name</th><th>costs</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>daughter</td><td>Annie Quincey</td><td>100</td></tr><tr><td class="table-row-number">2</td><td>mother</td><td>Flavia Quincey</td><td>120</td></tr><tr><td class="table-row-number">3</td><td>son</td><td>Andie Quincey</td><td>1200</td></tr></tbody></table>
</details>

# Задание 21
Определить товары, которые покупали более 1 раза
```sql
SELECT good_name
FROM Goods
	JOIN Payments ON Payments.good = Goods.good_id
GROUP BY good
HAVING COUNT(*) > 1
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>good_name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>apartment fee</td></tr><tr><td class="table-row-number">2</td><td>red caviar</td></tr><tr><td class="table-row-number">3</td><td>cinema</td></tr><tr><td class="table-row-number">4</td><td>music school fee</td></tr><tr><td class="table-row-number">5</td><td>potato</td></tr></tbody></table>
</details>

# Задание 22
Найти имена всех матерей (mother)
```sql
SELECT member_name
FROM FamilyMembers
WHERE status LIKE "mother"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>member_name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Flavia Quincey</td></tr><tr><td class="table-row-number">2</td><td>Constance Forrest</td></tr></tbody></table>
</details>

# Задание 23
Найдите самый дорогой деликатес (delicacies) и выведите его цену
```sql
SELECT good_name,
	unit_price
FROM Goods
	JOIN Payments ON Payments.good = Goods.good_id
	JOIN GoodTypes ON GoodTypes.good_type_id = Goods.type
WHERE good_type_name = "delicacies"
ORDER BY unit_price DESC
LIMIT 1
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>good_name</th><th>unit_price</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>red caviar</td><td>350</td></tr></tbody></table>
</details>

# Задание 24
Определить кто и сколько потратил в июне 2005
```sql
SELECT member_name,
	SUM(unit_price * amount) as costs
FROM FamilyMembers
	JOIN Payments ON Payments.family_member = FamilyMembers.member_id
WHERE MONTH(date) = 06
	AND YEAR(date) = 2005
GROUP BY member_name
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>member_name</th><th>costs</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Flavia Quincey</td><td>450</td></tr><tr><td class="table-row-number">2</td><td>Headley Quincey</td><td>300</td></tr><tr><td class="table-row-number">3</td><td>Andie Quincey</td><td>1200</td></tr></tbody></table>
</details>

# Задание 25
Определить, какие товары не покупались в 2005 году
```sql
SELECT good_name
FROM Goods
WHERE good_id NOT IN (
		SELECT good
		FROM Payments
		WHERE YEAR(date) = 2005
	)
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>good_name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>phone fee</td></tr><tr><td class="table-row-number">2</td><td>bread</td></tr><tr><td class="table-row-number">3</td><td>pineapples</td></tr><tr><td class="table-row-number">4</td><td>television</td></tr><tr><td class="table-row-number">5</td><td>vacuum cleaner</td></tr></tbody></table>
</details>

# Задание 27
Узнать, сколько потрачено на каждую из групп товаров в 2005 году. Вывести название группы и сумму
```sql
SELECT good_type_name,
	SUM(amount * unit_price) as costs
FROM Payments
	JOIN Goods ON Goods.good_id = Payments.good
	JOIN GoodTypes ON Goods.type = GoodTypes.good_type_id
WHERE YEAR(date) = 2005
GROUP BY good_type_name
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>good_type_name</th><th>costs</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>communal payments</td><td>4100</td></tr><tr><td class="table-row-number">2</td><td>food</td><td>748</td></tr><tr><td class="table-row-number">3</td><td>delicacies</td><td>650</td></tr><tr><td class="table-row-number">4</td><td>entertainment</td><td>1420</td></tr><tr><td class="table-row-number">5</td><td>education</td><td>6460</td></tr><tr><td class="table-row-number">6</td><td>clothes</td><td>68200</td></tr><tr><td class="table-row-number">7</td><td>treatment</td><td>300</td></tr></tbody></table>
</details>

# Задание 28
Сколько рейсов совершили авиакомпании из Ростова (Rostov) в Москву (Moscow) ?
```sql
SELECT COUNT(*) AS count
FROM Trip
WHERE town_from = "Rostov" AND town_to = "Moscow"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>count</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>4</td></tr></tbody></table>
</details>

# Задание 29
Выведите имена пассажиров улетевших в Москву (Moscow) на самолете TU-134
```sql
SELECT DISTINCT name
FROM Passenger
	JOIN Pass_in_trip ON Pass_in_trip.passenger = Passenger.id
	JOIN Trip ON Trip.id = Pass_in_trip.trip
WHERE town_to = "Moscow"
	AND plane = "TU-134"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Bruce Willis</td></tr><tr><td class="table-row-number">2</td><td>Ray Liotta</td></tr><tr><td class="table-row-number">3</td><td>Nikole Kidman</td></tr><tr><td class="table-row-number">4</td><td>Jennifer Lopez</td></tr><tr><td class="table-row-number">5</td><td>Kurt Russell</td></tr></tbody></table>
</details>

# Задание 30
Выведите нагруженность (число пассажиров) каждого рейса (trip). Результат вывести в отсортированном виде по убыванию нагруженности.
```sql
SELECT trip,
	COUNT(Passenger) as count
FROM Pass_in_trip
GROUP BY trip
ORDER BY count DESC
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>trip</th><th>count</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>7771</td><td>6</td></tr><tr><td class="table-row-number">2</td><td>7772</td><td>5</td></tr><tr><td class="table-row-number">3</td><td>1181</td><td>4</td></tr><tr><td class="table-row-number">4</td><td>1123</td><td>3</td></tr><tr><td class="table-row-number">5</td><td>1187</td><td>2</td></tr><tr><td class="table-row-number">6</td><td>8882</td><td>2</td></tr><tr><td class="table-row-number">7</td><td>1145</td><td>2</td></tr><tr><td class="table-row-number">8</td><td>1182</td><td>2</td></tr><tr><td class="table-row-number">9</td><td>1188</td><td>1</td></tr><tr><td class="table-row-number">10</td><td>1100</td><td>1</td></tr><tr><td class="table-row-number">11</td><td>1124</td><td>1</td></tr><tr><td class="table-row-number">12</td><td>8881</td><td>1</td></tr><tr><td class="table-row-number">13</td><td>7778</td><td>1</td></tr><tr><td class="table-row-number">14</td><td>7773</td><td>1</td></tr></tbody></table>
</details>

# Задание 31
Вывести всех членов семьи с фамилией Quincey.
```sql
SELECT *
FROM FamilyMembers
WHERE member_name LIKE "%Quincey"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>member_id</th><th>status</th><th>member_name</th><th>birthday</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1</td><td>father</td><td>Headley Quincey</td><td>1960-05-13T00:00:00.000Z</td></tr><tr><td class="table-row-number">2</td><td>2</td><td>mother</td><td>Flavia Quincey</td><td>1963-02-16T00:00:00.000Z</td></tr><tr><td class="table-row-number">3</td><td>3</td><td>son</td><td>Andie Quincey</td><td>1983-06-05T00:00:00.000Z</td></tr><tr><td class="table-row-number">4</td><td>4</td><td>daughter</td><td>Lela Quincey</td><td>1985-06-07T00:00:00.000Z</td></tr><tr><td class="table-row-number">5</td><td>5</td><td>daughter</td><td>Annie Quincey</td><td>1988-04-10T00:00:00.000Z</td></tr></tbody></table>
</details>

# Задание 32
Вывести средний возраст людей (в годах), хранящихся в базе данных. Результат округлите до целого в меньшую сторону.
```sql
SELECT FLOOR(AVG(YEAR(CURDATE()) - YEAR(birthday))) as age
FROM FamilyMembers
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>age</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>46</td></tr></tbody></table>
</details>

# Задание 34
Сколько всего 10-ых классов
```sql
SELECT COUNT(*) as count
FROM Class
WHERE name LIKE "10%"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>count</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>2</td></tr></tbody></table>
</details>

# Задание 35
Сколько различных кабинетов школы использовались 2.09.2019 в образовательных целях ?
```sql
SELECT COUNT(classroom) as count
FROM Schedule
WHERE date = "2019-09-02"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>count</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>5</td></tr></tbody></table>
</details>

# Задание 36
Выведите информацию об обучающихся живущих на улице Пушкина (ul. Pushkina)?
```sql
SELECT *
FROM Student
WHERE address LIKE "ul. Pushkina%"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>id</th><th>first_name</th><th>middle_name</th><th>last_name</th><th>birthday</th><th>address</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1</td><td>Nikolaj</td><td>Fedorovich</td><td>Sokolov</td><td>2000-10-01T00:00:00.000Z</td><td>ul. Pushkina, d. 36, kv. 5</td></tr><tr><td class="table-row-number">2</td><td>2</td><td>Vyacheslav</td><td>Evgenevich</td><td>Eliseev</td><td>2000-11-21T00:00:00.000Z</td><td>ul. Pushkina, d. 40, kv. 7</td></tr><tr><td class="table-row-number">3</td><td>3</td><td>Ivan</td><td>Antonovich</td><td>Efremov</td><td>2000-09-19T00:00:00.000Z</td><td>ul. Pushkina, d. 58, kv. 16</td></tr><tr><td class="table-row-number">4</td><td>4</td><td>Anatolij</td><td>Valentinovich</td><td>ZHdanov</td><td>2007-07-15T00:00:00.000Z</td><td>ul. Pushkina, d. 21, kv. 7</td></tr><tr><td class="table-row-number">5</td><td>5</td><td>Georgij</td><td>Dmitrievich</td><td>Noskov</td><td>2000-03-03T00:00:00.000Z</td><td>ul. Pushkina, d. 45, kv. 65</td></tr><tr><td class="table-row-number">6</td><td>6</td><td>Artyom</td><td>Borisovich</td><td>Sergeev</td><td>2007-01-01T00:00:00.000Z</td><td>ul. Pushkina, d. 1, kv. 5</td></tr><tr><td class="table-row-number">7</td><td>7</td><td>Arina</td><td>Fyodorovna</td><td>Evseeva</td><td>2000-08-11T00:00:00.000Z</td><td>ul. Pushkina, d. 21, kv. 51</td></tr><tr><td class="table-row-number">8</td><td>11</td><td>Leonid</td><td>Nikitich</td><td>Ignatov</td><td>2007-12-30T00:00:00.000Z</td><td>ul. Pushkina, d. 78, kv. 9</td></tr><tr><td class="table-row-number">9</td><td>12</td><td>Snezhana</td><td>YAkovlevna</td><td>Seliverstova</td><td>2000-07-23T00:00:00.000Z</td><td>ul. Pushkina, d. 78, kv. 56</td></tr><tr><td class="table-row-number">10</td><td>26</td><td>Dmitrij</td><td>Leonidovich</td><td>Trofimov</td><td>2001-05-06T00:00:00.000Z</td><td>ul. Pushkina, d. 78, kv. 9</td></tr><tr><td class="table-row-number">11</td><td>35</td><td>Svyatoslav</td><td>Vyacheslavovich</td><td>Tarasov</td><td>2002-01-14T00:00:00.000Z</td><td>ul. Pushkina, d. 5, kv. 6</td></tr><tr><td class="table-row-number">12</td><td>50</td><td>Nataliya</td><td>Igorevna</td><td>Myasnikova</td><td>2002-04-02T00:00:00.000Z</td><td>ul. Pushkina, d. 1, kv. 23</td></tr><tr><td class="table-row-number">13</td><td>54</td><td>Roman</td><td>Nikolaevich</td><td>SHilov</td><td>2003-08-06T00:00:00.000Z</td><td>ul. Pushkina, d. 56, kv. 80</td></tr><tr><td class="table-row-number">14</td><td>60</td><td>Aleksandra</td><td>Andreevna</td><td>Belozyorova</td><td>2003-02-12T00:00:00.000Z</td><td>ul. Pushkina, d. 3, kv. 21</td></tr><tr><td class="table-row-number">15</td><td>78</td><td>Vera</td><td>Lvovna</td><td>Evseeva</td><td>2004-07-04T00:00:00.000Z</td><td>ul. Pushkina, d. 5, kv. 13</td></tr></tbody></table>
</details>

# Задание 38
Сколько Анн (Anna) учится в школе ?
```sql
SELECT COUNT(*) AS count
FROM Student
WHERE first_name = "Anna"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>count</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>2</td></tr></tbody></table>
</details>

# Задание 39
Сколько обучающихся в 10 B классе ?
```sql
SELECT COUNT(*) AS count
FROM Class
	JOIN Student_in_class ON Student_in_class.class = Class.id
WHERE name = "10 B"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>count</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>11</td></tr></tbody></table>
</details>

# Задание 41
Во сколько начинается 4-ый учебный предмет по расписанию ?
```sql
SELECT start_pair
FROM Timepair
LIMIT 3, 1
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>start_pair</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>11:05:00</td></tr></tbody></table>
</details>

# Задание 43
Выведите фамилии преподавателей, которые ведут физическую культуру (Physical Culture). Отcортируйте преподавателей по фамилии.
```sql
SELECT last_name
FROM Teacher
	JOIN Schedule ON Schedule.teacher = Teacher.id
	JOIN Subject ON Subject.id = Schedule.subject
WHERE name = "Physical Culture"
ORDER BY last_name
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>last_name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Romashkin</td></tr><tr><td class="table-row-number">2</td><td>Vaulina</td></tr></tbody></table>
</details>

# Задание 46
В каких классах введет занятия преподаватель "Krauze" ?
```sql
SELECT DISTINCT name
FROM class
	JOIN Schedule ON Schedule.class = Class.id
	JOIN Teacher ON Teacher.id = Schedule.teacher
WHERE last_name = "Krauze"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>11 A</td></tr><tr><td class="table-row-number">2</td><td>11 B</td></tr></tbody></table>
</details>

# Задание 49
Какой процент обучающихся учится в 10 A классе ?
```sql
SELECT (
		(
			SELECT COUNT(*)
			FROM Student_in_class
				JOIN Class ON class.id = Student_in_class.class
			WHERE class.name = "10 A"
		) / COUNT(*)
	) * 100 AS percent
FROM Student_in_class
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>percent</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>11.9048</td></tr></tbody></table>
</details>

# Задание 51
Добавьте товар с именем "Cheese" и типом "food" в список товаров (Goods).
```sql
INSERT INTO Goods
SET good_id = (
		SELECT COUNT(*) + 1
		FROM Goods as a
	),
	good_name = "Cheese",
	type = (
		SELECT good_type_id
		FROM GoodTypes
		WHERE good_type_name = "food"
	)
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>good_id</th><th>good_name</th><th>type</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1</td><td>apartment fee</td><td>1</td></tr><tr><td class="table-row-number">2</td><td>2</td><td>phone fee</td><td>1</td></tr><tr><td class="table-row-number">3</td><td>3</td><td>bread</td><td>2</td></tr><tr><td class="table-row-number">4</td><td>4</td><td>milk</td><td>2</td></tr><tr><td class="table-row-number">5</td><td>5</td><td>red caviar</td><td>3</td></tr><tr><td class="table-row-number">6</td><td>6</td><td>cinema</td><td>4</td></tr><tr><td class="table-row-number">7</td><td>7</td><td>black caviar</td><td>3</td></tr><tr><td class="table-row-number">8</td><td>8</td><td>cough tablets</td><td>5</td></tr><tr><td class="table-row-number">9</td><td>9</td><td>potato</td><td>2</td></tr><tr><td class="table-row-number">10</td><td>10</td><td>pineapples</td><td>3</td></tr><tr><td class="table-row-number">11</td><td>11</td><td>television</td><td>8</td></tr><tr><td class="table-row-number">12</td><td>12</td><td>vacuum cleaner</td><td>8</td></tr><tr><td class="table-row-number">13</td><td>13</td><td>jacket</td><td>7</td></tr><tr><td class="table-row-number">14</td><td>14</td><td>fur coat</td><td>7</td></tr><tr><td class="table-row-number">15</td><td>15</td><td>music school fee</td><td>6</td></tr><tr><td class="table-row-number">16</td><td>16</td><td>english school fee</td><td>6</td></tr><tr><td class="table-row-number">17</td><td>17</td><td>Cheese</td><td>2</td></tr></tbody></table>
</details>


# Задание 52
Добавьте в список типов товаров (GoodTypes) новый тип "auto".
```sql
INSERT INTO GoodTypes
SET good_type_id = (
		SELECT COUNT(*) + 1
		FROM GoodTypes AS a
	),
	good_type_name = "auto"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>good_type_id</th><th>good_type_name</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1</td><td>communal payments</td></tr><tr><td class="table-row-number">2</td><td>2</td><td>food</td></tr><tr><td class="table-row-number">3</td><td>3</td><td>delicacies</td></tr><tr><td class="table-row-number">4</td><td>4</td><td>entertainment</td></tr><tr><td class="table-row-number">5</td><td>5</td><td>treatment</td></tr><tr><td class="table-row-number">6</td><td>6</td><td>education</td></tr><tr><td class="table-row-number">7</td><td>7</td><td>clothes</td></tr><tr><td class="table-row-number">8</td><td>8</td><td>equipment</td></tr><tr><td class="table-row-number">9</td><td>9</td><td>auto</td></tr></tbody></table>
</details>


# Задание 53
Измените имя "Andie Quincey" на новое "Andie Anthony".
```sql
UPDATE FamilyMembers
SET member_name = "Andie Anthony"
WHERE member_name = "Andie Quincey"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>member_id</th><th>status</th><th>member_name</th><th>birthday</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1</td><td>father</td><td>Headley Quincey</td><td>1960-05-13T00:00:00.000Z</td></tr><tr><td class="table-row-number">2</td><td>2</td><td>mother</td><td>Flavia Quincey</td><td>1963-02-16T00:00:00.000Z</td></tr><tr><td class="table-row-number">3</td><td>3</td><td>son</td><td>Andie Anthony</td><td>1983-06-05T00:00:00.000Z</td></tr><tr><td class="table-row-number">4</td><td>4</td><td>daughter</td><td>Lela Quincey</td><td>1985-06-07T00:00:00.000Z</td></tr><tr><td class="table-row-number">5</td><td>5</td><td>daughter</td><td>Annie Quincey</td><td>1988-04-10T00:00:00.000Z</td></tr><tr><td class="table-row-number">6</td><td>6</td><td>father</td><td>Ernest Forrest</td><td>1961-09-11T00:00:00.000Z</td></tr><tr><td class="table-row-number">7</td><td>7</td><td>mother</td><td>Constance Forrest</td><td>1968-09-06T00:00:00.000Z</td></tr><tr><td class="table-row-number">8</td><td>8</td><td>daughter</td><td>Wednesday Addams</td><td>2005-01-13T00:00:00.000Z</td></tr></tbody></table>
</details>

# Задание 54
Удалить всех членов семьи с фамилией "Quincey".
```sql
DELETE FROM FamilyMembers
WHERE member_name LIKE "%Quincey"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>member_id</th><th>status</th><th>member_name</th><th>birthday</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>6</td><td>father</td><td>Ernest Forrest</td><td>1961-09-11T00:00:00.000Z</td></tr><tr><td class="table-row-number">2</td><td>7</td><td>mother</td><td>Constance Forrest</td><td>1968-09-06T00:00:00.000Z</td></tr><tr><td class="table-row-number">3</td><td>8</td><td>daughter</td><td>Wednesday Addams</td><td>2005-01-13T00:00:00.000Z</td></tr></tbody></table>
</details>

# Задание 56
Удалить все перелеты, совершенные из Москвы (Moscow).
```sql
DELETE FROM Trip
WHERE town_from = "Moscow"
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>id</th><th>company</th><th>plane</th><th>town_from</th><th>town_to</th><th>time_out</th><th>time_in</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1100</td><td>4</td><td>Boeing</td><td>Rostov</td><td>Paris</td><td>1900-01-01T14:30:00.000Z</td><td>1900-01-01T17:50:00.000Z</td></tr><tr><td class="table-row-number">2</td><td>1101</td><td>4</td><td>Boeing</td><td>Paris</td><td>Rostov</td><td>1900-01-01T08:12:00.000Z</td><td>1900-01-01T11:45:00.000Z</td></tr><tr><td class="table-row-number">3</td><td>1123</td><td>3</td><td>TU-154</td><td>Rostov</td><td>Vladivostok</td><td>1900-01-01T16:20:00.000Z</td><td>1900-01-02T03:40:00.000Z</td></tr><tr><td class="table-row-number">4</td><td>1124</td><td>3</td><td>TU-154</td><td>Vladivostok</td><td>Rostov</td><td>1900-01-01T09:00:00.000Z</td><td>1900-01-01T19:50:00.000Z</td></tr><tr><td class="table-row-number">5</td><td>1146</td><td>2</td><td>IL-86</td><td>Rostov</td><td>Moscow</td><td>1900-01-01T17:55:00.000Z</td><td>1900-01-01T20:01:00.000Z</td></tr><tr><td class="table-row-number">6</td><td>1181</td><td>1</td><td>TU-134</td><td>Rostov</td><td>Moscow</td><td>1900-01-01T06:12:00.000Z</td><td>1900-01-01T08:01:00.000Z</td></tr><tr><td class="table-row-number">7</td><td>1187</td><td>1</td><td>TU-134</td><td>Rostov</td><td>Moscow</td><td>1900-01-01T15:42:00.000Z</td><td>1900-01-01T17:39:00.000Z</td></tr><tr><td class="table-row-number">8</td><td>1195</td><td>1</td><td>TU-154</td><td>Rostov</td><td>Moscow</td><td>1900-01-01T23:30:00.000Z</td><td>1900-01-02T01:11:00.000Z</td></tr><tr><td class="table-row-number">9</td><td>7771</td><td>5</td><td>Boeing</td><td>London</td><td>Singapore</td><td>1900-01-01T01:00:00.000Z</td><td>1900-01-01T11:00:00.000Z</td></tr><tr><td class="table-row-number">10</td><td>7772</td><td>5</td><td>Boeing</td><td>Singapore</td><td>London</td><td>1900-01-01T12:00:00.000Z</td><td>1900-01-02T02:00:00.000Z</td></tr><tr><td class="table-row-number">11</td><td>7773</td><td>5</td><td>Boeing</td><td>London</td><td>Singapore</td><td>1900-01-01T03:00:00.000Z</td><td>1900-01-01T13:00:00.000Z</td></tr><tr><td class="table-row-number">12</td><td>7774</td><td>5</td><td>Boeing</td><td>Singapore</td><td>London</td><td>1900-01-01T14:00:00.000Z</td><td>1900-01-02T06:00:00.000Z</td></tr><tr><td class="table-row-number">13</td><td>7775</td><td>5</td><td>Boeing</td><td>London</td><td>Singapore</td><td>1900-01-01T09:00:00.000Z</td><td>1900-01-01T20:00:00.000Z</td></tr><tr><td class="table-row-number">14</td><td>7776</td><td>5</td><td>Boeing</td><td>Singapore</td><td>London</td><td>1900-01-01T18:00:00.000Z</td><td>1900-01-02T08:00:00.000Z</td></tr><tr><td class="table-row-number">15</td><td>7777</td><td>5</td><td>Boeing</td><td>London</td><td>Singapore</td><td>1900-01-01T18:00:00.000Z</td><td>1900-01-02T06:00:00.000Z</td></tr><tr><td class="table-row-number">16</td><td>7778</td><td>5</td><td>Boeing</td><td>Singapore</td><td>London</td><td>1900-01-01T22:00:00.000Z</td><td>1900-01-02T12:00:00.000Z</td></tr><tr><td class="table-row-number">17</td><td>8881</td><td>5</td><td>Boeing</td><td>London</td><td>Paris</td><td>1900-01-01T03:00:00.000Z</td><td>1900-01-01T04:00:00.000Z</td></tr><tr><td class="table-row-number">18</td><td>8882</td><td>5</td><td>Boeing</td><td>Paris</td><td>London</td><td>1900-01-01T22:00:00.000Z</td><td>1900-01-01T23:00:00.000Z</td></tr></tbody></table>
</details>

# Задание 74
Выведите идентификатор и признак наличия интернета в помещении. Если интернет в сдаваемом жилье присутствует, то выведите «YES», иначе «NO».
```sql
SELECT id,
	IF(has_internet, 'YES', 'NO') AS has_internet
FROM Rooms
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>id</th><th>has_internet</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>1</td><td>YES</td></tr><tr><td class="table-row-number">2</td><td>2</td><td>YES</td></tr><tr><td class="table-row-number">3</td><td>3</td><td>NO</td></tr><tr><td class="table-row-number">4</td><td>4</td><td>NO</td></tr><tr><td class="table-row-number">5</td><td>5</td><td>YES</td></tr><tr><td class="table-row-number">6</td><td>6</td><td>YES</td></tr><tr><td class="table-row-number">7</td><td>7</td><td>NO</td></tr><tr><td class="table-row-number">8</td><td>8</td><td>NO</td></tr><tr><td class="table-row-number">9</td><td>9</td><td>NO</td></tr><tr><td class="table-row-number">10</td><td>10</td><td>NO</td></tr><tr><td class="table-row-number">11</td><td>11</td><td>YES</td></tr><tr><td class="table-row-number">12</td><td>12</td><td>NO</td></tr><tr><td class="table-row-number">13</td><td>13</td><td>NO</td></tr><tr><td class="table-row-number">14</td><td>14</td><td>NO</td></tr><tr><td class="table-row-number">15</td><td>15</td><td>NO</td></tr><tr><td class="table-row-number">16</td><td>16</td><td>NO</td></tr><tr><td class="table-row-number">17</td><td>17</td><td>NO</td></tr><tr><td class="table-row-number">18</td><td>18</td><td>YES</td></tr><tr><td class="table-row-number">19</td><td>19</td><td>YES</td></tr><tr><td class="table-row-number">20</td><td>20</td><td>NO</td></tr><tr><td class="table-row-number">21</td><td>21</td><td>YES</td></tr><tr><td class="table-row-number">22</td><td>22</td><td>NO</td></tr><tr><td class="table-row-number">23</td><td>23</td><td>YES</td></tr><tr><td class="table-row-number">24</td><td>24</td><td>YES</td></tr><tr><td class="table-row-number">25</td><td>25</td><td>NO</td></tr><tr><td class="table-row-number">26</td><td>26</td><td>YES</td></tr><tr><td class="table-row-number">27</td><td>27</td><td>YES</td></tr><tr><td class="table-row-number">28</td><td>28</td><td>YES</td></tr><tr><td class="table-row-number">29</td><td>29</td><td>NO</td></tr><tr><td class="table-row-number">30</td><td>30</td><td>YES</td></tr><tr><td class="table-row-number">31</td><td>31</td><td>NO</td></tr><tr><td class="table-row-number">32</td><td>32</td><td>NO</td></tr><tr><td class="table-row-number">33</td><td>33</td><td>YES</td></tr><tr><td class="table-row-number">34</td><td>34</td><td>NO</td></tr><tr><td class="table-row-number">35</td><td>35</td><td>NO</td></tr><tr><td class="table-row-number">36</td><td>36</td><td>NO</td></tr><tr><td class="table-row-number">37</td><td>37</td><td>YES</td></tr><tr><td class="table-row-number">38</td><td>38</td><td>NO</td></tr><tr><td class="table-row-number">39</td><td>39</td><td>YES</td></tr><tr><td class="table-row-number">40</td><td>40</td><td>YES</td></tr><tr><td class="table-row-number">41</td><td>41</td><td>NO</td></tr><tr><td class="table-row-number">42</td><td>42</td><td>YES</td></tr><tr><td class="table-row-number">43</td><td>43</td><td>NO</td></tr><tr><td class="table-row-number">44</td><td>44</td><td>YES</td></tr><tr><td class="table-row-number">45</td><td>45</td><td>YES</td></tr><tr><td class="table-row-number">46</td><td>46</td><td>NO</td></tr><tr><td class="table-row-number">47</td><td>47</td><td>NO</td></tr><tr><td class="table-row-number">48</td><td>48</td><td>YES</td></tr><tr><td class="table-row-number">49</td><td>49</td><td>YES</td></tr><tr><td class="table-row-number">50</td><td>50</td><td>NO</td></tr></tbody></table>
</details>

# Задание 75
Выведите фамилию, имя и дату рождения студентов, кто был рожден в мае.
```sql
SELECT last_name,
	first_name,
	birthday
FROM Student
WHERE MONTH(birthday) = 5
```
<details>
<summary>Показать результат запроса:</summary>
<table><thead><tr><th class="table-row-number"></th><th>last_name</th><th>first_name</th><th>birthday</th></tr></thead><tbody><tr><td class="table-row-number">1</td><td>Voroncova</td><td>Angelina</td><td>2000-05-21T00:00:00.000Z</td></tr><tr><td class="table-row-number">2</td><td>Bolshakova</td><td>Valentina</td><td>2001-05-30T00:00:00.000Z</td></tr><tr><td class="table-row-number">3</td><td>Trofimov</td><td>Dmitrij</td><td>2001-05-06T00:00:00.000Z</td></tr><tr><td class="table-row-number">4</td><td>Sidorova</td><td>Polina</td><td>2002-05-18T00:00:00.000Z</td></tr><tr><td class="table-row-number">5</td><td>Makarova</td><td>Viktoriya</td><td>2002-05-03T00:00:00.000Z</td></tr><tr><td class="table-row-number">6</td><td>Markov</td><td>YUrij</td><td>2003-05-15T00:00:00.000Z</td></tr><tr><td class="table-row-number">7</td><td>Nesterov</td><td>Gleb</td><td>2004-05-05T00:00:00.000Z</td></tr><tr><td class="table-row-number">8</td><td>Makarov</td><td>Denis</td><td>2004-05-09T00:00:00.000Z</td></tr></tbody></table>
</details>
