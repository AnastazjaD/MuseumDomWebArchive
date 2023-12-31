# MuseumDomWebArchive
# Музей “Дом на Набережной”. История проекта.

Архив содержит следующие сайты:

- [base.memo.ru](https://base.memo.ru)
- [gmig.ru](https://gmig.ru)
- [dnnmuseum.ru](https://dnnmuseum.ru)
- [ex.dnnmuseum.ru](http://ex.dnnmuseum.ru)
- [museumdom.narod.ru](https://museumdom.narod.ru)


В выборку попали *пять сайтов*: три из них разные версии (от ранней до более поздней) сайта “Музей Дом на Набережной”, четвертый сайт - сайт музея истории ГУЛАГа (“Музей Дом на Набережной - Отдел Музея истории ГУЛАГа)”, пятый - “Жертвы политического террора в СССР”. В 2014 году музей «Дом на набережной» стал отделом музейного объединения «Музей Москвы», а в апреле 2017 года вошел в состав Государственного музея истории ГУЛАГа. Выбор сайтов обусловлен связью с биографией Советского писателя Ю.В.Трифонова.
В данном репозитории представлено подробное описание **трех из пяти представленных сайтов** (страницы сайта-музея "Дом на Набережной").

- [dnnmuseum.ru](https://dnnmuseum.ru)
- [ex.dnnmuseum.ru](http://ex.dnnmuseum.ru)
- [museumdom.narod.ru](https://museumdom.narod.ru)
  
Название музея (“Дом на набережной”) - отсылка к творчеству Ю.В.Трифонова, заглавие его одноименной книги. В музее хранятся вещи жильцов, рукописи самого Юрия Валентиновича, воспоминания и дневниковые записи.

![Рисунок](https://github.com/AnastazjaD/MuseumDomWebArchive/raw/main/Common_1.jpg)

Трифонов известен своими художественными текстами, но часть из его работ документальные (_“Отблеск костра”, “Старик”_). В “**Отблеске костра**” писатель “_проследил за революционной судьбой двух братьев, Валентина и Евгения Трифоновых: первая русская революция в Ростове, затем многократные ссылки и каторга в Сибири, Февральская революция в Питере, создание Красной гвардии (оба брата были членами Главного штаба Красной гвардии), Октябрьское восстание и гражданская война на Восточном, Юго-Восточном и Кавказском фронтах, где В. Трифонов был членом Реввоенсовета”_.

Для сохранения памяти о писателе, в том числе сохранения связи с его документальными текстами, нужны свидетельства о репрессиях. Это обусловило добавление в полную выборку еще двух сайтов: Музей истории ГУЛАГа, "База памяти репрессированных” (Жертвы политического террора в СССР). На сайте содержится информация об отце писателя, в том числе указание на квартиру в Доме Правительства.

Ценность проекта в возможности проследить трансформацию сайта музея от ранней до поздней версии (сопоставить информацию, представленную в разных версиях, увидеть изменения в содержательном и визуальном наполнении); выявить особенности архивирования в процессе сохранения столь разных ресурсов как локальный сайт небольшого музей и база памяти.

Архивация всех сайтов произведена с помощью утилиты wpull. Для сохранения архивов сайтов запускалась команда, содержащая идентичные опции; заменялись лишь наименования папок, файлов и url.

`wpull https://gmig.ru/  --strip-session-id --no-check-certificate --no-robots --span-hosts --page-requisites --sitemaps --inet4-only --timeout 20 --tries 3 --waitretry 5 --recursive --level inf --retry-connrefused --retry-dns-error --delete-after --warc-append --warc-cdx -U "Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:101.0) Gecko/20100101 Firefox/101.0" -d -a gmig.ru.log --database sitearchive-gmig.ru.db --warc-file "gmig.ru" --warc-header "operator: Anastasiia Vasilenko" --warc-header "downloaded-by: Ruarxive.org" --domains gmig.ru --concurrent 4`

Непосредственно перед архивацией был проведен **анализ сайтов** при помощи ресурса [archiveready](https://archiveready.com/).  Анализ был направлен на выявление трудностей, которые могут возникнуть при архивации (ср. обнаружение компонентов сайтов, которые могут быть сохранены некорректно или утеряны при сохранении).
![Описание изображения](https://github.com/AnastazjaD/MuseumDomWebArchive/raw/main/Common.jpg)

Наиболее удобными для архивации оказались “небольшие” старые сайты музея “Дом на набережной”. Этот результат может быть обусловлен минимальным числом отсылок к внешним ресурсам, использованием условно однородного контента (преимущественно тексты), небольшим объемом контента.

Анализируя показатели архивируемости, видим, что наиболее проблемными выступают показатели “_Accessibility_” и “_Cohesion_”; показатели “_Metadata_” и “_Standards Compliance_” на их фоне демонстрируют положительную динамику.

Подробный анализ показателей **archiveready** для каждого из сайтов приведен в "ветвях" проекта. Описания архивов и их метаданных доступны в папках репозитория.

Файлы с архивами доступны [по ссылке в облаке](https://disk.yandex.ru/d/gIx6i4wKNgw7fA). Доступ к облачному хранилищу предоставляется по запросу.

**Контакты для связи:** Василенко Анастасия Геннадьевна, agvasilenko@edu.hse.ru

**Условия использования:** Creative Commons BY 4.0.

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/AnastazjaD/MuseumDomWebArchive">MuseumDomWebArchive </a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/AnastazjaD">AnastazjaD</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>

