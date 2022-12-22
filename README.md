# Лабораторные работы по дисциплине "Интернет-технологии"

## Лабораторная работа №1

Работа с GitHub: 
1. Была произведена регистрация в GitHub;
2. Был создан [репозиторий](https://github.com/QueTuePlay/Internet-technologies);
3. Была создана [личная страница](https://QueTuePlay.github.io/Internet-technologies);
4. Был размещен код личной страницы в [репозитории](https://github.com/QueTuePlay/Internet-technologies);
5. Было произведено размещение личной страницы на [хостинге](https://QueTuePlay.github.io/Internet-technologies).


## Лабораторная работа №2
В рамках данной лабораторной работы был спланирован и разработан [веб-сайт](https://idmit.ru) интернет-конкурса студенческих проектов дисциплины "Интернет-технологии".

Были выполнены следующие этапы при разработке системы:
1. Определение функциональных требований;
2. Определение программных требований;
3. Анализ определенных требований;
4. Проектирование системы;
5. Разработка системы;
6. Тестирование системы;
7. Введение в эксплуатацию.

Были реализованы основные функции системы (ее подсистемы), а именно:
- подсистема регистрации участников конкурса;
- подсистема аутентификации голосующих по номеру телефона;
- подсистема выполнения голосования;
- подсистема подсчета голосов;
- и другие.

Технологии, которые были использованы в процессе разработки:
- **UML** - унифицированный язык моделирования. С помощью него была спроектирована диаграмма классов системы интернет-конкурса, в которую входят подсистемы регистрации участников, подсистемы аутентификации по номеру мобильного телефона, подсистемы голосования и подсчета голосов.
- **SQL** - язык представления реляционных запросов к SQL-базам данных. После построения диаграммы классов были описаны основные SQL-запросы.
- **PHP/Laravel** - с помощью данных технологий происходила непосредственная реализация backend-системы.
- **HTML/CSS/JS/jQuery/AJAX** - данные языки и технологии были использованы для реализации графической составляющей сайта (frontend).
- **HTTPS-TLS** - для соответствия должных стандартов безопасности, доступ к системе производится только через защищенные каналы связи по протоколу TLS.
- **OpenAPI** - система авторизации по номеру мобильного телефона использует сторонний платный сервис звонков, функции которого доступны через OpenAPI.

Работа производилась в команде [kvazi](https://github.com/kvazi-team/idmit.ru), состав команды:
- ИДМ-22-03 Берковец А.Г. (РП, БА, АД, КО);
- ИДМ-22-08 Бондарь Е.Е. (СП, ВН, АД, ПП).

**Для выполнения работы были распределены роли, задачи и временные рамки в проекте, а также использованы ранее полученные умения и навыки в бакалавриате для оперативной реализации системы в поставленные сроки.** 

> Созданный [проект](https://kvazi-team.github.io/idmit.ru) принимает участие в [веб-конкурсе](https://idmit.ru) в категории "Голосование";

> Также [проект](https://quetueplay.github.io/Internet-technologies-Pomge) принимает участие в [веб-конкурсе](https://idmit.ru) в категории "Визитка (портфолио)".

## Лабораторная работа №3
В рамках данной лабораторной работы были изучены технологии протоколов обеспечения информационной безопасности на границе сетей на основе списков контроля доступа.

Лабораторная работа выполнялась в среде Cisco Packet Tracer в файле-сценарии формата "pka". [Сценарий](https://github.com/QueTuePlay/Internet-technologies/blob/main/IDM-22-03%20Berkovets%20A.G..pka) содержал созданную заранее логическую топологию в виде составной сети, моделирующей корпоративную сеть условного предприятия, подключенную к сети Интернет.

В ходе выполнения лабораторной работы была произведена настройка устройств. Отчет доступен по [ссылке](https://github.com/QueTuePlay/Internet-technologies/blob/main/IDM-22-03%20Berkovets%20A.G..pdf).

### Данные, которые были использованы для настройки устройств:
| Название сети | Количество узлов | Устройство |
| ------------- | ---------------- | ---------- |
| VLAN A        | 32               | PC1        |
| VLAN B        | 1843             | PC2        |
| VLAN C        | 100              | PC3        |
| VLAN D        | 23               | PC4        |

### Правила ограничения трафика, которые были использованы для настройки устройств:
1. Пользователям из "VLAN A" должен быть разрешен доступ по любому протоколу к любым узлам сети, в т.ч. к сети Интернет;
2. Пользователям из "VLAN B" должны иметь доступ к сети Интернет и к серверам PUBLIC и DNS по протоколам HTTP и DNS соответственно. Доступ к серверу LOCAL должен быть закрыт;
3. Пользователям из "VLAN C" должен быть доступен только сервер LOCAL по протоколу HTTP;
4. Пользователям из "VLAN D" должен быть доступен только Интернет, к серверам LOCAL и PUBLIC доступ должен быть закрыт;
5. Между виртуальными сетями должен быть разрешен трафик протокола ICMP;
6. Из сети Интернет должен быть открыт доступ только по протоколам DNS и HTTP, и только к серверам DNS и PUBLIC.

## Экзаменационный билет
В качестве экзаменационного билета был выбран [билет №20](https://github.com/stankin/inet-2022/wiki/exam20) ([личный вклад](https://github.com/stankin/inet-2022/wiki/exam20/_compare/24565e9542ad332611bdf1400bee1570d19ee45c...f0461a69e1c930450ce0aade025096d589f73c06) + оформление)
