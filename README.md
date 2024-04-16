
## 1.Основные этапы разработки программного продукта

01	Подготовка	Сбор и обработка требований. Предварительное планирование этапов работ, сроков, ресурсов и стоимости.	
02	Проектирование	Получение технических заданий, разработка спецификаций. Партнер получает документальное изложение своих требований и планы проведения работ.	
03	Создание	
		Дизайн — получение графических макетов, визуальных форм, разработка интерфейсов. Создание индивидуального стиля.
		Кодирование — написание исходного кода.
		Тестирование — проверка программы на соответствие всем предъявляемым к ней требованиям.
		Документирование — передача накопленных знаний пользователям и другим разработчикам.
04	Поддержка	
Внедрение — установка программного обеспечения, обучение пользователей.
Сопровождение — исправление выявленных ошибок, поддержка пользователей.





## 2.Приведите основные разделы документа «Техническое задание»

Введение.
1. Основание для разработки.
2. Назначение разработки.
3. Требования к программе или программному изделию.
4. Требования к программной документации.
5. Технико-экономическое обоснование.
6. Стадии и этапы разработки.
7. Порядок контроля и приемки.
8. Приложения.

-------

1. В разделе «Основание для разработки» должны быть указаны:
■ документы, на основании которых ведется разработка;
■ организация, утвердившая этот документ, и дата его утверждения;
■ наименование и (или) условное обозначение темы разработки.

2. Раздел "Назначение разработки" определяет задачи, которые должна выполнять разрабатываемая система для достижения своей цели. Это может быть управление техническим комплексом, проведение различных расчётов, улучшение производственных процессов и другие функции. Если речь идёт о создании программного обеспечения для информационных систем, целью разработки может быть предоставление точной и своевременной информации для принятия обоснованных решений, автоматизация рутинной работы и переход к безбумажной технологии. Также в этом разделе должна быть представлена начальная контекстная диаграмма задачи.

3. В раздел «Требования к программе или программному изделию» входят следующие подразделы:
■ требования к функциональным характеристикам;
■ требования к надежности и безопасности;
■ условия эксплуатации;
■ требования к составу и параметрам технических средств;
■ требования к информационной и программной совместимости;
■ требования к маркировке и упаковке;
■ требования к хранению и транспортированию;
■ специальные требования.

4. «Требования к программной документации». Основными документами, регламентирующими разработку будущих программ, должны быть документы Единой Системы Программной Документации: руководство пользователя, руководство администратора, описание применения.

5. В разделе «Технико-экономическое обоснование» представлены ориентировочная экономическая эффективность разрабатываемого программного продукта, экономические преимущества
разработки по сравнению с имеющимися на предприятии образцами или аналогами (или в сравнении с ручными операциями).

6.-----

7. «Порядок контроля и приемки» предполагает указание на
виды испытаний и общие требования к приему работы




## 3.Перечислите виды диаграмм при структурном подходе проектировании ПП. Что показывает каждая диаграмма?

1.Диаграмма SADT - это инструмент, используемый в системном анализе для моделирования и анализа сложных систем. Она представляет собой графическое средство, которое позволяет описывать функции, связи и взаимодействия между элементами системы. Вот основные аспекты и цели диаграммы SADT:

Цель:

Диаграмма SADT используется для анализа и проектирования систем с целью понять и описать их структуру и функции.
Она помогает выявить ключевые элементы системы, процессы и взаимосвязи между ними.
Что делает:

Описывает функциональные и структурные аспекты системы с использованием графических обозначений.
Позволяет декомпозировать систему на более простые составляющие и выявить их взаимосвязи.
Помогает визуализировать процессы, потоки данных, управление и другие аспекты системы.
Элементы диаграммы SADT:

Блоки (Blocks): Представляют собой основные элементы системы или процессы. Каждый блок выполняет определенную функцию или операцию.
Стрелки (Arrows): Используются для обозначения потоков данных, взаимодействий или связей между блоками.
Текстовые описания: Используются для детализации функций, действий и свойств блоков.
Процесс построения диаграммы SADT:

Идентификация функций: Определение основных функций или операций системы, которые необходимо моделировать.
Построение блоков: Создание блоков, представляющих эти функции.
Установление связей: Определение связей и потоков данных между блоками.
Декомпозиция: Разбиение системы на более мелкие части для подробного анализа.
Назначение:

Помогает команде проектирования и анализа понять структуру и функции системы.
Улучшает коммуникацию между участниками проекта, предоставляя ясное представление о процессах и взаимосвязях.
Позволяет выявлять проблемные зоны или узкие места в проектируемой системе.
Используется в качестве основы для разработки более подробных моделей и спецификаций системы.

#### ------------------------------------------------------------------------------

2.Характеристика диаграмм потоков данных (DFD). Диаграмма
DFD состоит из узлов обработки данных, средств их хранения и
внешних по отношению к используемой диаграмме источников
или потребителей данных.
Диаграмма потоков данных — основное средство моделирования функциональных требований к системе, проектируемой или
реально существующей. В основе модели лежат понятия внешней
сущности, процесса, хранилища (накопителя) данных потока данных. Источники информации (внешние сущности) порождают
информационные потоки (потоки данных), переносящие информацию к подсистемам или процессам; те, в свою очередь, преобразуют информацию и порождают новые потоки, которые переносят
информацию к другим процессам или подсистемам, накопителям
данных или внешним сущностям — потребителям информации

#### ---------------------------------------------------------------------------------

3. Диаграмма сущность-связь (Entity-Relationship Diagram, ERD) - это графическое представление структуры данных, которое используется для описания сущностей (объектов или элементов) в информационной системе и связей между ними. Основное назначение ERD - моделирование базы данных или информационной системы с учетом сущностей, их атрибутов и связей между сущностями.

Основные компоненты диаграммы ERD:

Сущности (Entities):

Сущность представляет собой объект или элемент, который имеет собственные характеристики и может быть сохранен в базе данных.
Например, в системе управления студентами сущность может быть "Студент", которая имеет атрибуты, такие как Имя, Фамилия, Год рождения и т.д.
Каждая сущность обычно представляется в диаграмме в виде прямоугольника с указанием ее имени.


Атрибуты (Attributes):

Атрибуты представляют характеристики или свойства сущности.
Примеры атрибутов для сущности "Студент" могут включать Имя, Фамилию, Год рождения.
Атрибуты обычно указываются внутри прямоугольника сущности.



Связи (Relationships):

Связи определяют отношения между различными сущностями в системе.
Например, между сущностями "Студент" и "Курс" может существовать связь "Участвует в", которая показывает, что студент участвует в определенном курсе.
Связи могут быть однонаправленными или двунаправленными, иметь степень (например, один-к-одному, один-ко-многим, многие-ко-многим) и другие характеристики.
Связи обычно представляются линиями, которые соединяют сущности и указывают тип отношения между ними.



Назначение диаграммы ERD:

Моделирование данных: ERD позволяет моделировать структуру данных, описывая сущности, их атрибуты и связи между ними. Это помогает понять, как данные будут храниться и организованы в базе данных.

Проектирование базы данных: ERD используется при проектировании баз данных для определения сущностей, атрибутов и связей, которые будут представлены в базе данных.

Понимание бизнес-логики: Путем моделирования сущностей и связей ERD помогает понять бизнес-логику и структуру информационной системы.

Визуализация отношений: ERD обеспечивает наглядное представление отношений между данными, что упрощает коммуникацию между участниками проекта, включая разработчиков, аналитиков данных и бизнес-пользователей.


#### -------------------------------------------------------------------------


Диаграмма классов (Class Diagram):

Представляет структуру классов и их взаимосвязи в объектно-ориентированном программировании.
Показывает классы, атрибуты, методы и связи между классами.
Используется для проектирования структуры объектов и их взаимодействия в системе.

## 4.Характеризуйте и покажите диаграмму Вариантов использования

Диаграмма вариантов использования (Use Case Diagram) является одним из ключевых инструментов моделирования в рамках методологии UML (Unified Modeling Language). Она используется для описания функциональности системы с точки зрения её пользователей или акторов. Давайте подробнее рассмотрим характеристики и примеры диаграммы вариантов использования.

Характеристики диаграммы вариантов использования:

Акторы (Actors):

Акторы представляют роли или типы пользователей системы.
Это могут быть реальные люди, другие системы, внешние устройства или другие программные компоненты.
Акторы отображаются на диаграмме в виде стикеров с названием роли.



Варианты использования (Use Cases):

Варианты использования описывают конкретные действия или функции, которые могут выполняться акторами в системе для достижения определенных целей.
Каждый вариант использования отображается на диаграмме в виде эллипса с названием функции.
Отношения между акторами и вариантами использования:

На диаграмме вариантов использования показываются связи между акторами и вариантами использования.
Связи отображаются линиями, обозначающими взаимодействие между актором и определенным вариантом использования.



Расширения и включения (Extensions and Inclusions):

В диаграмме могут быть показаны расширения (extend) и включения (include) вариантов использования.
Расширения показывают дополнительные функции, которые могут быть выполнены в рамках основного варианта использования.
Включения показывают повторяющиеся действия, которые могут включаться в разные варианты использования.






## 5.Для чего создаётся прототип ПП

раммного обеспечения.
Во-первых, пользователю часто бывает трудно сформулировать требования к тому, что он ожидает от системы. В этом случае прототип интерфейса пользователя (User Interface — UI),
оперативно созданный по результатам собеседования, дает ему
возможность увидеть схематичную реализацию того, как разработчик представляет соответствующую часть системы.
При использовании прототипов важен любой результат. Если
программист понял требования заказчика правильно, то очевидно, что разработка программной системы продвигается в верном
направлении. Если пользователь не совсем доволен предложенным ему вариантом реализации системы, польза заключается в
том, что он может указать, в чем заключается непонимание задачи программиста.
Во-вторых, прототипирование дает возможность выбрать одно
из альтернативных концептуальных решений. Любую техническую задачу можно решить различными способами. Это касается
как задачи формулировки требований к программной системе,
так и реализации ее пользовательского интерфейса.
В-третьих, часто бывает так, что комбинация функциональных
и нефункциональных требований такова, что возникает риск невозможности их реализации. Как правило, такой риск связан с
требованиями к быстродействию системы при известных ограничениях на среду ее реализации. В этом случае создаются прототипы (не обязательно связанные с пользовательским интерфейсом), реализующие соответствующую часть системы, имитирующие потоки данных, поступающие на ее вход, и обработку этих
данных.






## 6.Перечислите правила создания интерфейса пользователя

Правило доступности. Система должна быть настолько понятной, чтобы пользователь, никогда раньше не видевший ее, но хорошо разбирающийся в предметной области, мог без всякого обучения начать ее использовать. Это правило служит некоторым идеалом,
к которому надо стремиться, поскольку на практике достичь такой
степени доступности почти никогда не удается. Тем не менее, специалисты продолжают делать в этом направлении все возможное.

Правило эффективности. Система не должна препятствовать
эффективной работе опытных пользователей, работающих с ней
долгое время. Очевидным примером нарушения этого правила является нацеленность системы только на новичков, использование
средств, которые хорошо подходят для неопытного пользователя,
ограничивая его в возможности сделать что-то не так, но неэффективны для эксперта, который и так знает, что и где ему нужно сделать.

Правило непрерывного развития. Система должна способствовать непрерывному росту знаний, умений и навыков пользователя и приспосабливаться к его меняющемуся опыту. Плохие
результаты приносит предоставление только базовых возможностей или оставление начинающего пользователя наедине со сложным интерфейсом, которым уверенно пользуются эксперты. Нарушение непрерывности при переходе от одного набора возможностей к другому также приносит неудобства, поскольку пользователь вынужден разбираться с добавленными возможностями в
новом контексте.
Большинство пользователей можно поместить в три группы:
новички, опытные и средние, которые уже знают больше, чем новички, и не делают столько ошибок, но еще не приобрели автоматизма при выполнении большинства операций и иногда путаются в интерфейсе. Новичкам необходима помощь в освоении новой для них системы и контроль за их действиями, опытным
пользователям — высокая эффективность выполнения часто требующихся действий и возможность гибкого управления системой
в таких ситуациях, которые встречаются реже, но способны вызвать проблемы при их неадекватной поддержке. Про средних же
пользователей часто забывают, хотя подавляющее большинство
пользователей программного обеспечения относится именно к
этой категории. Им нужны достаточно высокие эффективность и
гибкость вместе с возможностью быстро получать адекватную помощь по возникающим время от времени разнообразным вопросам.

Правило соблюдения контекста. Система должна быть согласована с контекстом, в котором ей предстоит работать. Это правило требует от системы быть работоспособной не «вообще», а
именно в том окружении, в котором ею будут пользоваться.
В контекст могут входить специфика и объемы входных и выходных данных, тип и цели организаций, в которых система должна
работать, уровень пользователей, зашумленность помещений и. пр.





## 7.Предотвращение ошибок при вводе информации пользователем

Использование форматирования и масок ввода:

Ограничение пользовательского ввода с помощью форматирования или масок (например, для номера телефона, даты, почтового индекса и т.д.).
Например, вы можете указать формат даты (например, "дд.мм.гггг") или маску для ввода номера телефона ("(XXX) XXX-XXXX").
Валидация на стороне клиента:

Выполнение проверок данных на стороне клиента (в браузере) с использованием JavaScript.
Проверка на соответствие формату, длине, типу данных и другим критериям до отправки данных на сервер.
Например, проверка на правильность введенного адреса электронной почты или проверка обязательных полей перед отправкой формы.
Валидация на стороне сервера:

Проверка данных на сервере после их отправки с клиента.
Проверка на корректность данных, включая проверку на уникальность (например, уникальный логин или адрес электронной почты).
Защита от SQL-инъекций и других атак, связанных с вводом данных.
Подсказки и подсвечивание ошибок:

Предоставление наглядных подсказок и сообщений об ошибках пользователю.
Например, мгновенное подсвечивание неправильно заполненных полей или вывод сообщения об ошибке возле конкретного поля ввода.
Использование выпадающих списков и автозаполнения:

Минимизация возможности ошибок с помощью предложений автозаполнения или выбора из выпадающего списка.
Например, выбор страны из списка вместо ввода названия страны вручную.
Использование адаптивного дизайна:

Создание пользовательского интерфейса, который учитывает различные устройства и экраны, чтобы сделать ввод информации более удобным.
Например, использование адаптивного положения элементов управления на мобильных устройствах для улучшения точности ввода.
Обратная связь и обучение пользователей:

Предоставление четких инструкций и обратной связи пользователю о том, как правильно вводить информацию.
Показ сообщений о правильном формате данных и указание на возможные ошибки.





## 8.Дайте определение ООП. (класс, объект, наследование, полиморфизм, инкапсуляция)


ООП (объектно-ориентированное программирование) - это методология программирования, основанная на концепциях объектов и классов, которая позволяет организовать код в более логически структурированные и модульные блоки. 

Давайте определим основные концепции ООП:

#### Класс (Class):

Класс представляет собой шаблон или абстракцию для создания объектов.
Он определяет атрибуты (поля данных) и методы (функции) объектов данного класса.
Например, класс "Сотрудник" может иметь атрибуты: имя, возраст, зарплата, и методы: увеличение зарплаты, изменение данных и т.д.



#### Объект (Object):

Объект представляет экземпляр класса, созданный на основе его шаблона.
Каждый объект имеет свои собственные значения атрибутов и может вызывать методы, определенные в классе.
Например, объект "сотрудник1" может быть экземпляром класса "Сотрудник" с определенными значениями для имени, возраста и зарплаты.



#### Наследование (Inheritance):

Наследование позволяет создавать новые классы на основе существующих (родительских) классов.
Новый класс (подкласс или производный класс) наследует атрибуты и методы родительского класса.
Это позволяет создавать иерархии классов и повторно использовать код.
Например, класс "Менеджер" может наследовать атрибуты и методы класса "Сотрудник", добавляя дополнительные функции.



#### Полиморфизм (Polymorphism):

Полиморфизм позволяет объектам одного и того же класса вызывать одинаковые методы, но с различным поведением.
Это может быть реализовано через перегрузку методов (method overloading) или переопределение методов (method overriding).
Например, метод "выполнитьРаботу()" у разных объектов класса "Сотрудник" может иметь разную реализацию в зависимости от типа сотрудника (например, менеджер или разработчик).



#### Инкапсуляция (Encapsulation):

Инкапсуляция означает сокрытие деталей реализации объекта от внешнего мира и доступ к ним только через публичные методы класса.
Классы объединяют данные (поля) и методы для работы с этими данными в единый объект.
Это обеспечивает контроль доступа к данным и защиту их от неправильного использования.
Например, атрибуты класса "Сотрудник" могут быть объявлены как закрытые (private), и доступ к ним осуществляется только через методы класса (например, методы установки и получения значений атрибутов - сеттеры и геттеры).




##  Белый Ящик и Черный Ящик

Технология тестирования «белого ящика» (White Box Testing):
Определение:

Тестирование «белого ящика» основано на анализе внутренней структуры и логики программы.
Тестировщики имеют доступ к исходному коду программы и используют знания о его внутреннем устройстве для создания тестов.
Целью тестирования «белого ящика» является проверка корректности логики программы, контрольные пути выполнения, обработка ошибок и другие аспекты внутренней реализации.
Характеристики:

Требуется знание внутренней структуры программы.
Тесты основаны на спецификации исходного кода.
Обычно используются техники, такие как тестирование условий (branch coverage), тестирование пути (path coverage), тестирование потока данных (data flow testing) и т.д.
Примеры методов тестирования «белого ящика» включают модульное тестирование, интеграционное тестирование, системное тестирование.
Технология тестирования «черного ящика» (Black Box Testing):
Определение:

#### ----------------------------------------------------------------------

Тестирование «черного ящика» сосредоточено на функциональном поведении программы без знания ее внутренней структуры.
Тестировщики рассматривают программу как «черный ящик», где они видят только входные данные и результаты работы, но не знают, как программа достигает этих результатов.
Целью тестирования «черного ящика» является проверка соответствия функциональных требований и спецификаций.
Характеристики:

Не требуется знание внутренней структуры программы.
Тесты основаны на внешних требованиях и спецификациях.
Обычно используются техники, такие как эквивалентное разбиение (equivalence partitioning), граничные значения (boundary value analysis), тестирование состояний (state-based testing) и т.д.
Примеры методов тестирования «черного ящика» включают функциональное тестирование, пользовательское тестирование (acceptance testing), тестирование совместимости и т.д.





## 15.Основные виды тестирования

#### Модульное тестирование (Unit Testing):

Модульное тестирование проверяет отдельные компоненты или модули программы независимо от остальной системы.
Целью модульного тестирования является проверка корректности работы отдельных функций, методов или классов.
Тесты обычно создаются разработчиками на ранних этапах разработки для обнаружения и устранения ошибок в изолированных частях кода.



#### Интеграционное тестирование (Integration Testing):

Интеграционное тестирование проверяет взаимодействие между различными компонентами или модулями программы после их объединения.
Целью является обнаружение ошибок, связанных с передачей данных между модулями, интеграцией интерфейсов и работой системы в целом.


#### Системное тестирование (System Testing):

Системное тестирование проверяет работу всей системы в соответствии с ее функциональными требованиями.
Это проверка системы в ее целостности с использованием различных сценариев использования и данных.
Целью является убедиться, что система работает как ожидается пользователем и соответствует требованиям.


#### Приемочное тестирование (Acceptance Testing):

Приемочное тестирование проверяет соответствие программы конечным пользователям или заказчику.
Это последний этап тестирования перед выпуском программы в эксплуатацию.
Целью является подтверждение того, что программа полностью соответствует требованиям заказчика и готова к использованию.



#### Функциональное тестирование (Functional Testing):

Функциональное тестирование проверяет работу программы с точки зрения ее функциональных требований.
Тесты выполняются для проверки каждой функции или возможности программы в соответствии с заданными спецификациями.
Целью является обнаружение ошибок в функциональности, несоответствии требованиям или нежелательных результатов.



#### Нефункциональное тестирование (Non-functional Testing):

Нефункциональное тестирование проверяет характеристики программы, не связанные с ее функциональностью.
Это включает тестирование производительности, нагрузочное тестирование, безопасность, совместимость, устойчивость к отказам и другие аспекты.
Целью является оценка качества программы в различных аспектах, влияющих на ее эффективность и надежность.



#### Регрессионное тестирование (Regression Testing):

Регрессионное тестирование выполняется после внесения изменений в программу для проверки, не привели ли эти изменения к появлению новых ошибок или нарушению существующей функциональности.
Целью является обеспечение того, что старая функциональность остается работоспособной после внесенных изменений.





## Характеризуйте документ «Руководство пользователя». Перечислите разделы этого документа.

«Руководство пользователя»,
предположительно, содержит следующие разделы:
«Назначение программы»;
«Условия выполнения программы»;
«Выполнение программы»;
«Сообщения пользователю».
В зависимости от особенностей программы можно объединять
отдельные разделы или вводить новые.
В разделе «Назначение программы» должны быть указаны сведения о назначении программы, краткое описание ее функций,
реализованных методов и возможных областей применения.
«Условия выполнения программы» должны содержать условия,
необходимые для выполнения программы (минимальный и (или)
максимальный состав аппаратных и программных средств и т.п.).
В разделе «Выполнение программы» следует указать последовательность действий пользователя, обеспечивающих загрузку,
выполнение и завершение программы, привести описание функций и пользовательского интерфейса. В качестве примера приведем небольшой фрагмент «Руководства пользователя».
В разделе «Сообщения пользователю» должны быть приведены сообщения, выдаваемые в ходе выполнения программы, описание их содержания и соответствующие действия пользователя
(в случае сбоя, повторный запуск программы и т.п.).






## Характеризуйте стандарт ЕСПД. Виды программ и программных документов

Стандарт ЕСПД (Единая система программной документации) является набором принятых и стандартизированных правил, методов и требований к документации, используемой при разработке программного обеспечения. Целью стандарта ЕСПД является обеспечение единообразия и качества документации в процессе жизненного цикла программного продукта. Давайте рассмотрим основные характеристики стандарта ЕСПД и виды программ и программных документов, которые включаются в этот стандарт.

Характеристики стандарта ЕСПД:
Стандартизация процесса документирования:

Стандарт ЕСПД определяет правила и методы создания, оформления и поддержки программной документации на всех этапах разработки.
Это включает требования к структуре документов, используемым терминам, форматам представления информации и т.д.
Обеспечение единообразия:

Стандарт ЕСПД помогает установить общие подходы к документированию в рамках организации или индустрии, что упрощает взаимопонимание и обмен информацией между участниками проекта.
Повышение качества программного обеспечения:

Единая система программной документации способствует повышению качества разработки и поддержки программного продукта за счет четкого и структурированного описания всех его аспектов.
Улучшение процесса сопровождения и эксплуатации:

Стандартизированная документация упрощает сопровождение и поддержку программного обеспечения, делая процесс более прозрачным и эффективным.
Виды программ и программных документов в рамках ЕСПД:

------------------------------------------------------------
#### Техническое задание (ТЗ):

Определяет требования к разрабатываемому программному продукту, включая функциональные и нефункциональные требования, архитектуру, интерфейсы и прочее.


-----------------------------------------------------------------------
#### Технический проект (ТП):

Содержит подробное описание архитектуры программного решения, включая блок-схемы, диаграммы, спецификации интерфейсов, базы данных и другие технические аспекты.

-------------------------------------------------------------------
#### Руководство пользователя (User Manual):

Содержит инструкции по установке, настройке и использованию программного продукта, а также описание основных функций и возможностей.

--------------------------------------------------------

#### Руководство администратора (Administrator Manual):

Описывает процедуры установки, настройки, администрирования и обслуживания программного обеспечения.

--------------------------------------------------------
#### Тестовая документация (Test Documentation):

Содержит планы тестирования, сценарии тестирования, отчеты о выполненных тестах и результаты.

------------------------------------------------------------
#### Документация по сопровождению (Maintenance Documentation):

Включает описание алгоритмов работы, процедур устранения ошибок, обновления и поддержки программного продукта.


------------------------------------------------------------------
#### Документация по версионированию (Version Control Documentation):

Содержит информацию о версиях программного продукта, изменениях, внесенных в каждую версию, и прочую связанную информацию.

----------------------------------------------------------------------

#### Справочная документация (Reference Documentation):

Включает описание API (интерфейсов программирования приложений), библиотек, классов, функций и других компонентов программы.




## Стадии разработки программного продукта:

#### Планирование (Planning):

На этой стадии определяются основные цели и требования к разрабатываемому программному продукту.
Осуществляется анализ потребностей заказчика, определение функциональности, распределение задач и ресурсов.


---------------------------------------------------------------
#### Анализ (Analysis):

Проводится детальное изучение требований к программному продукту.
Формулируются функциональные и нефункциональные требования, определяются возможности и ограничения проекта.


----------------------------------------------------------------
#### Проектирование (Design):

На этой стадии определяется архитектура и структура программного решения.
Создаются диаграммы, спецификации интерфейсов, выбираются технологии и инструменты разработки.



----------------------------------------------------------------
#### Разработка (Development):

Происходит написание и тестирование кода, реализация функциональности программного продукта.
Важно соблюдать стандарты кодирования и документирования, указанные в ЕСПД.



----------------------------------------------------------------
#### Тестирование (Testing):

Проводятся тесты для проверки работоспособности, надежности и соответствия программного продукта требованиям.
Разрабатывается и выполняется тестовая документация в соответствии с стандартами ЕСПД.




----------------------------------------------------------------
#### Внедрение (Deployment):

Программное обеспечение устанавливается и запускается на целевом окружении.
Осуществляется обучение пользователей, поддержка и администрирование системы.



----------------------------------------------------------------
#### Сопровождение (Maintenance):

Проводятся работы по поддержке и обновлению программного обеспечения.
Обрабатываются отчеты об ошибках, улучшения функциональности и производительности.







## Сертификация ПО


Сертификация программного обеспечения проводится с целью оценки соответствия программного продукта определенным стандартам, требованиям и критериям качества. Это важный процесс, который помогает убедиться в том, что программное обеспечение выполняет свои функции правильно, соответствует спецификациям и стандартам безопасности, и может быть использовано в определенных условиях.

Вот несколько причин, по которым проводят сертификацию ПО:

Убедиться в соответствии ПО стандартам и требованиям: Сертификация помогает убедиться в том, что ПО соответствует определенным стандартам и требованиям, таким как ISO 9001, ISO 27001, PCI DSS и другим, которые могут быть важными для конкретной отрасли, рынка или клиента.

Улучшение качества ПО: Сертификация ПО может помочь выявить проблемы и улучшить качество программного обеспечения, что может привести к повышению надежности и безопасности продукта.

Увеличение доверия клиентов: Сертификация может помочь убедить клиентов в том, что ПО было проверено и сертифицировано независимыми экспертами, что повышает доверие клиентов к продукту.

Соответствие регуляторным требованиям: Сертификация ПО может быть необходима для соответствия регуляторным требованиям, таким как законодательство в области защиты данных, банковское законодательство и другие.

Снижение рисков: Сертификация может помочь снизить риски, связанные с использованием ПО, такие как возможность нарушения безопасности, ошибки в функциональности и другие.




## Качество ПО


в модель качества входит шесть характеристик, или шесть основных
показателей качества, которые перечислим в порядке их значимости для большинства
пользователей:
 функциональные возможности;
 функциональная надежность;
 удобство применения;
 эффективность;
 сопровождаемость;
 переносимость.


