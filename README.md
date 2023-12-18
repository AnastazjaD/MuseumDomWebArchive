# MuseumDomWebArchive
[https://museumdom.narod.ru/](https://museumdom.narod.ru/) - вторая версия сайта.

Сохраняется архитектура исходного проекта: несколько страниц через гиперссылки собранные на главной (разделы, посвященные отдельным “историям” дома: строительство, столетия, участники ВОВ, репрессированные, мероприятия, музей, отчет о работе). Разный тип контента: преимущественно текстовый и графический.

Анализ при помощи утилиты **metawarc**  показал следующие результаты.

![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/museumdom/Images/museumdom.narod.ru_CWindowssystem32cmd.exe1.jpg)

**Преобладающие типы данных**: текст, изображение, интерактивные элементы. Общее число файлов: 1078.

![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/museumdom/Images/museumdom.narod.ru_CWindowssystem32cmd.exe1.jpg)
![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/museumdom/Images/museumdom.narod.ru_CWindowssystem32cmd.exe3.jpg)

 **Анализ**, проведенный при помощи ресурса [https://archiveready.com](https://archiveready.com), дал следующие результаты ([https://archiveready.com/check?url=https%3A%2F%2Fmuseumdom.narod.ru%2F](https://archiveready.com/check?url=https%3A%2F%2Fmuseumdom.narod.ru%2F))
 
Выявлено **значительное число нарушений**, связанных с обращением к протоколам HTML и CSS. 

*Значительно* число *недействительных ссылок*.

![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/museumdom/Images/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B9.jpg)

*Недоступны* заголовки кэширования, что влияет на качество архивации.

![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/museumdom/Images/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B92.jpg)

**Минимально** число проблем, связанных с архивированием *мульти-медиа-файлов* (исключительно время отклика).

![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/museumdom/Images/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B93.jpg)

Также присутствуют команды, блокирующие допуск парсеров к отдельным областям сайта.

![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/museumdom/Images/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B94.jpg)
