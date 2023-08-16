# Solving_SQL_ACADEMY

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

