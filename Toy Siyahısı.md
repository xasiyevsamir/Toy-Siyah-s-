<br/>
<h1 align="center">

   `↘️ Samir Toy Siyahısı 28.08.2026 ↙️`

   </h1>
<br/><br/>


## ` Yığma (Set) Funksiyaları`

_Sütundakı fərqli və ya təkrarlanan dəyərlərlə işləmək üçün istifadə olunur_
| __`Funksiya`__ | __`Təsviri`__ | __`Nümunə Sorğu`__ |
| --- | --- | --- |
| __GROUPING()__ | _ROLLUP və ya CUBE nəticəsində yaranan sətirləri müəyyən edir._ | `SELECT GROUPING(Department) FROM Employees;` |
| __GROUPING_ID()__ | _GROUPING-dən daha çox dəyərləri fərqləndirmək üçün istifadə olunur._ | `SELECT GROUPING_ID(Department, Role) FROM Employees;` |
| __CHECKSUM_AGG()__ | _Sütundakı rəqəmlərin kontrol cəmini qaytarır._ | `SELECT CHECKSUM_AGG(Salary) FROM Employees;` |
| __STRING_AGG()__ | _Sütundakı sətirləri birləşdirib mətni bir sətirdə qaytarır (ayırıcı ilə)._ | `SELECT STRING_AGG(Name, ', ') FROM Employees;` |