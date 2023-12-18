# MuseumDomWebArchive

https://dnnmuseum.ru/ - **третья версия** сайта сменила как структуру, так и интерфейс. На новом сайте появляются подкасты, становится сложнее графический дизайн, увеличивается число внешних гиперссылок, становится более разнообразным наполнение.  

![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/dnnmuseum/Images/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B90.jpg)

Анализ при помощи утилиты metawarc дал следующие результаты.
![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/dnnmuseum/Images/CWindowssystem32cmd.exe1%20(1).jpg) 

Преобладающие типы данных: текст, изображение, интерактивные элементы. Общее число файлов увеличилось в прогрессии, видим и значительное расширение ассортимента типов данных, представленных внутри проекта.
![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/dnnmuseum/Images/CWindowssystem32cmd.exe2.jpg) 
![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/dnnmuseum/Images/CWindowssystem32cmd.exe3.jpg) 

Возросло как общее число данных (в 4 раза по сравнению с предшествующей версией сайта), так и количество типов данных (почти в два раза). Появились видео- и аудиофайлы (формат данных mp4), разнообразнее представлены варианты приложений. Стоит отметить резкое увеличение количества файлов с расширением json (было 1, стало  1944). В то же время фактически исчезли файлы gif (было 137, стало 8), резко снизилось количество javascript приложений (371, 29).

**Анализ**, проведенный при помощи ресурса [https://archiveready.com](https://archiveready.com), дал следующие результаты [https://archiveready.com/check?url=https%3A%2F%2Fdnnmuseum.ru%2F](https://archiveready.com/check?url=https%3A%2F%2Fdnnmuseum.ru%2F)  
Выявлены **нарушения**, связанных с обращением к протоколам HTML и CSS. 
*Значительно* число *недействительных ссылок*.
![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/dnnmuseum/Images/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B91.jpg) 
![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/blob/dnnmuseum/Images/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B92.jpg) 
