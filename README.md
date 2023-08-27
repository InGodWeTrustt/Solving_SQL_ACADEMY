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
    - [Задание 22](#задание-22)
    - [Задание 23](#задание-23)
    - [Задание 27](#задание-27)
    - [Задание 28](#задание-28)
    - [Задание 29](#задание-29)
    - [Задание 31](#задание-31)
    - [Задание 32](#задание-32)

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