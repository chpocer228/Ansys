ФИО: Потатуев Артём Иванович
Группа: РИ-231103 
Конспект
Методы расчёта в HFSS:
1.Метод конечных элементов FE
2.Метод интегральных уравнений IE
3.Гибридный метод FE + IE
4.SBR+ 
Метод конечных элементов
Данный метод позволяет рассчитать поле в объёме. В данном объёме он строит сетку на основе уравнений Максвела, по которой и считает поле. Позволяет рассчитать поле внутри и за пределами объекта. Одной из главных проблем является ограниченность относительно вычислительных ресурсов.
Метод интегральных уравнений 
При использование нет вычислений в объёме. Позволят находить поля в ближней и дальней зоне. Не требует области анализа рядом с объектом, что позволяет сократить вычисления. Но данный метод позволяет производить расчёт только проводящих структур.
Гибридный метод
Делит структуры на большие и малые, на большие используется метод IE, а возле малой создается область в которой производится расчёт методом FEM. Данный метод позволяет считать достаточно большие структуры. Используется чаще, чем методы выше
SBR+ лучевой метод 
Создаёт сетку в промежуточной области. Объединяет в себе 4 разных метода

Рефлексия
Программное обеспечение HFSS позволяет анализировать сложные EM-структуры, включая антенны, волноводы и стелс-объекты, с минимальными погрешностями. Наличие FEM и IE методов позволяет достаточно точно, а самое главное быстро проанализировать диаграммны направленности, ЕМ поля и т.д. . Так же данная программа позволяет моделировать все различные объект с разной, иногда очень сложной геометрией, что сильно увеличивает диапазон её использования. 

Задание
В программном пакете Ansys HFSS разработать модель для расчета диаграммы рассеяния (ЭПР) на автомобиле на частоте f = 1 ГГц + 013 МГц при падении волны линейной поляризации из дальней зоны.
Частота: 1.013 Ггц 
Источником излучения является антенная,  волны линейной поляризации из дальней зоны.

Что такое ЭПР (RCS) объекта, какую информацию об объекте дает эта радиотехническая единица измерения?
Эффективная площадь рассеяния (ЭПР), или Radar Cross-Section (RCS) — это радиотехническая характеристика, определяющая способность объекта отражать электромагнитные волны. ЭПР измеряется в квадратных метрах (м²) и является ключевым параметром в радиолокации, поскольку влияет на дальность обнаружения, идентификацию и классификацию целей.
ЭПР — комплексный параметр, зависящий от геометрии, материала, частоты и поляризации. Его анализ позволяет не только обнаруживать объекты, но и определять их свойства, что критически важно для современных радиолокационных систем.

Ссылка на репозиторий гитхаб
https://github.com/chpocer228/Ansys 
