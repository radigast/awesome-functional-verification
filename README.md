# awesome-functional-verification

Список ресурсов, книг, курсов и тренингов, связанных с функциональной верификацией проектов интегральных схем под ASIC и FPGA.

# Index

* [Resureces in Internet](#resureces-in-internet)
* [Courses and workshops](#courses-and-workshops)
* [Opensource or free software for functional verification](#opensource-or-free-software-for-functional-verification)
* [Conferences](#conferences)
* [Books](#Books)
* [Awesome lists](#awesome-lists)
* [Keywords and desired experience](#keywords_and_desired_experience)

# Resureces in Internet

информационные, обучающие и новостные ресурсы в интернете, связанные с темой функциональной верификации или содержащие метериалы, посвященные данной тематике.

* [accellera](http://www.accellera.org) - Группы по стандартизации, воплотившие в жизнь большинство современных стандартов типа SystemC, OVL, UVM, IP-XACT и.т.п. Собственно содержит сами стандарты и материалы и презентации их поясняющие (качество дополнительных материалов на мой взгляд среднее)
* [doulos](http://www.doulos.com) - ресурс направленный на обучение современным методикам верификации, работы с ПЛИC и разработки встроенного ПО. Содержит бесплатные материалы (в том числе видео) базового уровня (хорошего качества) и ссылки на платные курсы
* [verificationacademy](http://www.verificationacademy.com) - ресурс направленный на обучение современным методикам верификации. Создан под патронажем Mentor Graphics. Содержит обучающие материалы хорошего качества, большое число видео + сообщество.
* [verificationguide](http://www.verificationguide.com) - Неплохие вводные туториалы по SV, UVM, SystemC. Примеры кода с линками на [edaplayground](https://www.edaplayground.com/)
* [chipverify](http://www.chipverify.com) - Вводные туториалы по Verilog, SV, UVM. Плюс ресурса - большой объем примеров кода, иногда встречаются хорошие картинки или гифки поясняющие материал. При этом субъективно на
* [verificationguide](http://www.verificationguide.com)  даются более доходчивые и полные текстовые пояснения.
* [testbench.in](http://www.testbench.in) - Туториалы и примеры по SV, UVM, концепциям построения тестбенчей и старым методологиям типа VMM, OpenVera. Визульно менее приятный чем тот же [verificationguide](http://www.verificationguide.com), однако в качестве доп источника может быть интересен.
* [asicguru](http://www.asicguru.com/) - Материалы по verilog, vmm, ovm. Ресурс выглядит недоделанным и заброшенным, многие ссылки давно не проверялись
* [Cadence](http://www.cadence.com) - Официальный сайт поставщика САПР. При регистрации даёт доступ к материалам, в том числе, связанным с методикам верификации. Возможна свободная регистрация, однако привязка аккаунта к фирме, использующей данный САПР дает более широкий доступ к информации. Естественно материалы ориентированы на использование САПР компании.
* [Synopsys](http://www.synopsys.com) - Официальный сайт поставщика САПР. При регистрации даёт доступ к материалам, в том числе, связанным с методикам верификации. Возможна свободная регистрация, однако привязка аккаунта к фирме, использующей данный САПР дает более широкий доступ к информации. Естественно материалы ориентированы на использование САПР компании.
* [Mentor(Siemens)](http://www.mentor.com) - Официальный сайт поставщика САПР. При регистрации даёт доступ к материалам, в том числе, связанным с методикам верификации. Возможна свободная регистрация, однако привязка аккаунта к фирме, использующей данный САПР дает более широкий доступ к информации. Естественно материалы ориентированы на использование САПР компании.
* [verilab](http://www.verilab.com/resources/papers-and-presentations/) - материалы, статьи и тренинги по верификации
* [sunburst-design](http://www.sunburst-design.com/papers/)
* [Verification Horizons (Mentor)](https://www.mentor.com/products/fv/verificationhorizons/)
* [edacafe](http://www10.edacafe.com) - журнал. Есть материалы по верификации
* [chipdesignmag](http://chipdesignmag.com)
* [systemverilog](http://systemverilog.ru/) - SystemVerilog по русски
* [edaplayground sandbox](https://www.edaplayground.com/) - онлайн сервис. Сайт  предоставляет возможность бесплатно  попробовать компиляцию и симуляцию HDL кода и окружений на коммерческих симуляторах.

## Code examples

* [SV/UVM patterns examples and tricks](https://github.com/tenthousandfailures/systemverilog-design-patterns) - Примеры применения паттернов программирования в SystemVerilog и ряд других интересных примеров от специалиста из Intel
* [custom_uvm_report_server](https://github.com/kaushalmodi/custom_uvm_report_server) - Пример реализации пользовательского UVM сервера печати

## Patterns

Для понимания структуры кода и принципов построения библиотеки UVM, а также для написания хорошо поддерживаемого верификационного кода (окружений и тестов) полезно иметь представление о паттернах проектирования. В частности, таких как factory, builder (в uvm можно найти применение и других паттернов)

* [Паттерны на refactoring.guru](https://refactoring.guru/ru/design-patterns)
* [Шпаргалка по паттернами на habr](https://habr.com/ru/post/210288/)
* [Паттерны на wiki](https://ru.wikipedia.org/wiki/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)

## Codyng Style

[Easier UVM Coding Style](https://www.doulos.com/knowhow/sysverilog/uvm/easier_uvm_guidelines/summary/)

Подходы, изложенные в приведенных ниже книгах применимы и для верификацонного кода, особенно если речь идет о ООП коде на UVM/SystemVerilog

* Чистый код: создание, анализ и рефакторинг. Роберт Мартин
* Совершенный код: [практическое руководство по разработке программного обеспечения : пер. с англ.]. Стив Макконнелл

# Courses and workshops

Специализированные курсы и программы обучения

* [“Проектирование и верификация СФ-блоков”, Национальный исследовательский университет "МИЭТ", Кафедра интегральной электроники и микросистем (ИЭМС), Ф.М. Путря](https://miet.ru/upload/iblock/401/Annot_PRO_13_2.pdf)
* ["Верификация цифровых схем" От белорусских коллег](http://simhard.com/wiki/index.php/%D0%A1%D0%BF%D0%B5%D1%86_%D0%BA%D1%83%D1%80%D1%81_(%D0%92%D0%B5%D1%80%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F_%D1%86%D0%B8%D1%84%D1%80%D0%BE%D0%B2%D1%8B%D1%85_%D1%81%D1%85%D0%B5%D0%BC)
* [nand2tetris](https://www.nand2tetris.org/) - открытый образовательный проект, позволяющий за относительно короткое время пройти курс разработчика процессоров от архитектуры и RTL до компиляторов и операционных систем
* [Профессиональный стандарт: Специалист по функциональной верификации и разработке тестов функционального контроля наноразмерных интегральных схем](http://www.garant.ru/products/ipo/prime/doc/70563026/) - не курс, но содержит ключевые слова для поиска материалов для саморазвития
* [“Введение в формальные методы верификации программ”, МГУ, Факультет вычислительной математики и кибернетики,  А. С. Камкин ](http://sp.cs.msu.ru/courses/vmp/kamkin_mc2018.pdf) Явно к верификации ИС не относится, однако сожержит фундаментальные подходы, применяющиеся в том числе и для верификации ИС
* [“Функциональная верификация наноразмерных интегральных схем”,  Путря Ф.М, Фролова С.Е., Зайцев В.С. Авдеев Н.А. ](https://edunano.ru/courses/funktsionalnaya-verifikatsiya-nanorazmernykh-integralnykh-skhem/) Курс по функциональной верификации, разработанный по заказу eNano


# Opensource or free software for functional verification

## Editors, code assistance

* [sveditor for eclipse](http://marketplace.eclipse.org/content/sveditor) - Плагин для eclipse. Дает возможность редактирования иерархических SV проектов (навигация, Code assistance, подсветка…)
* [kactus2 IP-XACT editor](https://sourceforge.net/projects/kactus2/) - Опенсорс инструмент для редактирования IP-XACT описаний

## Simulation and debug

* [Verilator](http://www.veripool.org/wiki/verilator) базируется на преобразовании verilog в С
* [ICARUS](http://iverilog.icarus.com) открытый RTL ситмулятор
* [QEMU](http://wiki.qemu.org/Main_Page) платформа для создания высокоуровневых симуляторов
* [GTKWAVE](http://gtkwave.sourceforge.net) GTKWAVE - свободный просмотрщик waveform (vcd support)
* [impulse waveforms](https://marketplace.eclipse.org/content/impulse#group-screenshots) - Плагин для elclipse, позволяющий просматривать вэйвформы (vcd)
* [covered](https://http://covered.sourceforge.net) - инструмент для анализа покрытия verilog кода (не проверял)




## Frameworks

* [https://cocotb.readthedocs.io](https://cocotb.readthedocs.io) платформа для создания тестбенчей на Python

## IP and VIP

* [opencores](https://opencores.org/howto/eda) IP and VIP (С верификационном кодом там конечно все скромнее чем с IP)

## Control

* [redmine](http://www.redmine.org/) - Трекер задач и ошибок
* [jenkins](https://jenkins.io/)  - Средство непрерывной интеграции, запуск регрессий
* [git](https://www.git-scm.com/)  - Система контроля версий
* [svn](https://subversion.apache.org/)  -  Система контроля версий

# Conferences

* [Design Automation Conference (DAC)](https://dac.com/)
* [Design and Verification Conference (DVCON)](https://dvcon.org/)
* [Design, Automation And Test In Europe (DATE)](https://www.date-conference.com/)
* [IEEE EAST-WEST DESIGN & TEST SYMPOSIUM (EWDTS)](https://conf.ewdtest.com/)
* [Проблемы разработки перспективных  микро- и наноэлектронных систем (МЭС)](http://www.mes-conference.ru/index.php?ls=ru)
* [Cadence CDNLive](https://www.cadence.com/content/cadence-www/global/en_US/home/cdnlive.html)
* [Synopsys User Conference SNUG](https://www.synopsys.com/community/snug.html)

# Books

* Логическое проектирование верификация систем на SystemVerilog (2019)  авторы: Дональд Томас (перевод на русский). Введение в цифровую схемотехнику (с самых азов) и SystemVerilog
* SystemVerilog for Verification Second Edition A Guide to Learning the  Testbench Language Features (2008)  Авторы: Chris Spear
* Проектирование и верификация цифровых систем на кристаллах. Verilog,  System Verilog (2010).     Авторы: Хаханов В.И. Первая полноценная книга по SV на русском языке.
* Professional Verification. A Guide to Advanced Functional Verification. Авторы: Paul Wilcox (2004)
* UVM Golden Reference Guide (2013). Авторы: Doulos.  Учебник по UVM от Doulos
* The Power of Assertions in SystemVerilog (2010) Авторы: Eduard Cerny
* The Easier UVM Coding Guidelines (2015). Авторы: Doulos. Рекомендации по стилю написания UVM кода.
* Systemverilog golden reference guide-Doulos (2012). Авторы: Doulos. Systemverilog golden reference guide
* A Practical Guide to Adopting the Universal Verification Methodology UVM  (2010). Авторы: Sharon Rosenberg
* A Practical Guide for SystemVerilog Assertions (2005). Авторы: Srikanth Vijayaraghavan
* Post-Silicon and Runtime Verification for Modern Processors (2010). Авторы: Ilya Wagner
* Principles of Verifiable RTL Design: A functional coding style  supporting verification processes in Verilog (2001). Авторы: Lionel Bening
* C.  Baier, J.-P. Katoen. Principles of Model Checking. MIT Press, 2008. Проверка моделей
* Карпова: Ю.Г. Карпов. Model Checking. Верификация параллельных и распределенных программных систем. БХВ-Петербург, 2010.
* J.  Yuan, C. Pixley, A. Aziz. Constraint-Based Verification. Springer, 2006.  По  использованию ограничений в верификации есть такая обзорная книжка


# Awesome lists

* [languages for HDL creation](https://github.com/drom/awesome-hdl)
* [awesome-software-quality(ENG)](https://github.com/ligurio/awesome-software-quality#formal-software-verification) - смежная область верификация ПО
* [awesome-software-quality(RUS)](https://github.com/ligurio/awesome-software-quality#%D0%A4%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%B2%D0%B5%D1%80%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F-%D0%9F%D0%9E) - смежная область верификация ПО


