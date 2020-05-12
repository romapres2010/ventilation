# Приточная вентиляция совмещенная с канальным кондиционером (часть 1 - электрическая)

![схема_малая](./img/smal_plan1.png)

Хочу поделиться опытом проектирования, монтажа и эксплуатации своей системы приточной вентиляции совмещенной с канальным кондиционером. [Система](./img/full_plan2.png)
 собиралась в 2012-2013 годах и с тех пор находится в постоянной эксплуатации.

Статью разделил на две части:

- в первой части описана классическая схема приточная вентиляции с использованием электрического канального подогревателя  
- во второй части расскажу про неоднозначный опыт переработки системы под водяной калорифер с питанием от общедомовой системы отопления

<cut />

## Благодарность мастерам

Будучи новичком в проектировании и монтаже систем вентиляции я прибегал к постоянной помощи и советам мастеров с форума [my.mastergrad.com](https://my.mastergrad.com/).

Огромное спасибо за конструктивные и критические советы специалистов, без которых я не смог бы создать и настроить систему.

- пользователя **[Ким](https://my.mastergrad.com/users/36632/)** за крайне ценные советы и внимательно отношение к моим вопросам
- пользователя **[Fresh](https://my.mastergrad.com/users/60668/)** за постоянную поддержку
- пользователя **[mr-h](https://my.mastergrad.com/users/125310/)** за ценные советы и активное участие

## Характеристики системы

Для себя решил, что нужно минимум 80 м<sup>3</sup> на комнату, с двумя людьми. Если хотите почувствовать свежесть, то нужно около 120 м<sup>3</sup>.

Приточная вентиляция:

- четыре комнаты, от 80 до 120 м<sup>3</sup> на комнату
- вытяжка осуществляется в родные вытяжные каналы (3 канала: кухня, ванная, туалет)
- возможность балансировать воздушный поток между комнатами
- требования к фильтрации EU5-EU7

Кондиционирование:

- цель - охлаждение поступающего воздуха
- забор воздуха с улицы - до 300 м<sup>3</sup>
- рециркуляция в квартире - до 300 м<sup>3</sup>
- подача воздуха в каждую комнату (три комнаты) до 200 м<sup>3</sup>

Итого:

- в режиме вентиляции от 320  м<sup>3</sup> до 480  м<sup>3</sup> на квартиру.
- в режиме кондиционирования до 600 м<sup>3</sup> на квартиру.

## Борьба с шумом

В предыдущей квартире я уже пробовал собирать приточную вентиляцию на компонентах [Soler&Palau](https://www.solerpalau.com/ru-ru/in-line-duct-fans-td-silent-94-serie/). Было выявлено несколько недостатков:

- высокий шум вентиляторов при использовании стандартных регуляторов, особенно в диапазоне от 0 до 50%
- низкий ресурс - примерно 2 года непрерывной работы и они начинают гудеть
- низкое давление - с трудом продавливает фильтр

В новой квартире решил сделать приточку на промышленных компонентах.

В первую очередь, у меня были высокие требования к шуму. А из источников в приточке несколько:

- шум двигателя вентилятора, особенно при регулировании. Если регулятор симисторный, то от шума ни куда не деться. Либо переходить на трансформаторный регулятор, либо использовать вентиляторы с EC двигателями, которые управляются сигналом 0-10 В.
- шум в каналах. Здесь все просто, нужно снизить скорость воздушного потока до 1,5-2 м/с и повысить жесткость каналов. Отказаться от прямоугольных пластиковых и гибких и перейти на витые оцинкованные.
- шум в распределительных устройствах. Нужно во первых создать перед решеткой зону статического давления и, во вторых, понизить скорость в самой решетке.

В качестве производителя компонент я выбрал продукцию [Systemair](https://systemair-rus.ru/). Отличное качество и очень дорого. Но в 2012 году было вполне еще доступно.

## Камеры статического давления

Камера статического давления используется вместе с вентиляционными решетками для снижения давления, выравнивания воздушного потока и глушения шума. Камеры очень громоздкие, но без них бесполезно браться за подобный проект.

Для подачи воздуха в комнаты я использовал камеры статического давления [Systemair ODEN-1-300x100](https://systemair-rus.ru/systemair-kamery).

Мне нужно на каждую комнату от 120 до 250  м<sup>3</sup> - это от 33 до 70 л/с [конвертер единиц измерения](https://air-part.ru/konverter-edinic-izmerenija/).  

По [installation instructions](https://shop.systemair.com/upload/assets/PP-89_ODEN_EN_20190426_184315212.PDF) на камеру статического давления, для меня подходит размер 100 мм на 300 мм - поток для него около 74 л/с при разнице давлений 22 Pa или 52 л/с при разнице давлений 11 Pa.

Проникся уважением к шведам - все отверстия в камерах и глушителях были закрыты полиэтиленовыми "шапочками". Несколько фото:

<img src="./img/plenum_box/plenum_box1.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/plenum_box/plenum_box2.jpeg?raw=true" alt="drawing" width="350"/>  

<img src="./img/plenum_box/plenum_box3.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/plenum_box/plenum_box4.jpeg?raw=true" alt="drawing" width="350"/> 

Черная трубочка это оплетка тросика, которым передвигается круглый перфорированный рассеиватель. Назначение рассеивателя - регулировать поток, увеличивая или уменьшая сопротивление потоку, ну и сам поток естественно рассеивать в камере, чтобы он не бил прямо на выход из камеры узкой струей, а распределился по всему сечению выхода.  
Прозрачные трубочки предназначены для подключения к дифференциальному манометру при проведении пусконаладки. На ярлыке указан K-фактор, по которым можно, измерив разницу давления дифференциальным манометром, получить расход воздуха через камеру.

## Вентиляционные решетки

Для распределения воздуха по комнате я использовал регулируемые (по вертикали и горизонтали) приточные вентиляционные решетки [Systemair NOVA-A-2-2-300x100](https://systemair-rus.ru/ventilyatsionnyie-reshetki).  

Решетки лучше заказывать в комплектации с регулятором - очень удобно регулировать поток или, например, отключить одну из комнат.

<img src="./img/grilles/grilles1.png?raw=true" alt="drawing" width="350"/>  <img src="./img/grilles/grilles2.png?raw=true" alt="drawing" width="350"/>  

На сайте есть отличный калькулятор для проверки параметров каждого из компонент. Например, для [NOVA-A-2-2-300x100](https://design.systemair.com/Global/en-GB/catalogue/NOVA_A?accessories=0&blades=0&damper=1&height=100&length=300&market=0&mounting=2&mounting_frame=0&oden_fixing=1&rows=2&surface_finish=0).  

Основное преимущество таких регулируемых решеток - можно создать воздушную струю с прилипанием к потолку, которая "пробивает всю комнату".

Например, так выглядит распределение воздушного потока в моей комнаты (4,5 х 3,5 м, высота потолков 2,7, расположение решетки в 15 см от потолка в углу комнаты) при разном расходе воздуха (температура в комнате 20 С, температура подачи 20 С):  

- 60 м<sup>3</sup> и терминальной скорости потока 0,1 м/с  
<img src="./img/grilles/grilles3_60_1.png?raw=true" alt="drawing" width="350"/>  <img src="./img/grilles/grilles3_60_2.png?raw=true" alt="drawing" width="350"/> 

- 120 м<sup>3</sup> и терминальной скорости потока 0,2 м/с  
<img src="./img/grilles/grilles3_120_1.png?raw=true" alt="drawing" width="350"/>  <img src="./img/grilles/grilles3_120_2.png?raw=true" alt="drawing" width="350"/> 

- 250 м<sup>3</sup> и терминальной скорости потока 0,3 м/с  
<img src="./img/grilles/grilles3_250_1.png?raw=true" alt="drawing" width="350"/>  <img src="./img/grilles/grilles3_250_2.png?raw=true" alt="drawing" width="350"/> 

## Разводка воздуховодов

На предыдущей квартире я использовал обычные пластиковые каналы 100 мм или прямоугольные 60х120 мм. Мастера с [my.mastergrad.com](https://my.mastergrad.com/) убедили отказаться от пластика и перейти на витые оцинкованные.

Чтобы снизить шум, в канале желательно держать скорость не выше 2.0-2.5 м/с. Есть отличная бесплатная программа [Vent-Calc v2.0](http://www.sibclim.ru/2009/06/18/vent-calc-v2.0-programma-dlja-rascheta.html). С ее помощью можно посчитать скорость потока и потери давления для различных элементов системы вентиляции.

Например:

- при расходе 120 м<sup>3</sup> желательно использовать трубу диаметром 160 мм, скорость потока при этом составит - 1,66 м/с, потеря давления - 1,8 Па на метр трубы
- при расходе 250 м<sup>3</sup> желательно использовать трубу диаметром 200 мм, скорость потока при этом составит - 2,21 м/с, потеря давления - 2,2 Па на метр
- при расходе 250 м<sup>3</sup> и диаметре 160 мм скорость потока составит 3,45 м/с, потеря давления резко увеличится до 6,6 Па на метр
- при расходе 300 м<sup>3</sup> и диаметре 200 мм скорость потока составит 2,65 м/с, потеря давления - 3,1 Па на метр

Входной воздуховод я решил использовать 200 мм, разводку по комнатам сделать 160 мм. Все трубы и камеры обклеил пенофолом 5 мм.

Нитки каналов в комнаты у меня короткие (кроме одной), я решил заложиться на более мощный вентилятор, в надежде, что он прокачает всю сеть.

Вход выполнен со стороны балкона, обсадная труба 250 мм, внутри нее проходит приточная труба 200 мм + провода.

В комнатах смонтированы камеры статического давления.

Подборка фото:  

<img src="./img/tube/tube1.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/tube/tube2.jpeg?raw=true" alt="drawing" width="350"/> 

<img src="./img/tube/tube3.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/tube/tube4.jpeg?raw=true" alt="drawing" width="350"/> 

<img src="./img/tube/tube5.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/tube/tube6.jpeg?raw=true" alt="drawing" width="350"/> 

<img src="./img/tube/tube7.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/tube/tube8.jpeg?raw=true" alt="drawing" width="350"/> 

## Подключение канального кондиционера

В качестве канального кондиционера был выбран инвертор [Mitsubishi Electric SEZ-KD35VAQ.TH](https://www.mitsubishi-aircon.ru/product/products/gs18_pac.php?m=2029).

- Холодопроизводительность - 3.50 кВт
- Потребляемая мощность (охлаждение) - 1.010 кВт
- Энергоэффективность (EER) - 3.61
- Расход воздуха (макс.) - 660 м<sup>3</sup>/ч
- Теплопроизводительность - 4.00 кВт
- Потребляемая мощность (нагрев) - 1.130 кВт

Как справедливо меня предупреждали мастера с форумов, мощности этого кондиционера не достаточно, чтобы быстро охладить 3 комнаты общей площадью 55 м2. Конечно, быстро охладить квартиру такая система не сможет, но в режиме постоянной эксплуатации она отлично справляется с поддержкой комфортной атмосферы (Московская область, окна на запад). Летом кондиционер включен круглосуточно на средней скорости, на ночь увеличиваю температуру до 26 гр. На линию кондиционера поставил отдельный счетчик - получается примерно 10 кВт/час в сутки.

Кондиционер встроен в систему по следующей схеме:

- на входе стоит небольшой "светофор" на два входа по 200 мм
- первый вход забирает воздух из коридора
- второй вход соединен с каналом приточной вентиляции с улицы
- на выходе из кондиционера стоит "светофор" на 4 выхода по 160 мм
- для балансировки воздушной сети на двух коротких ветках стоят ирисовые регуляторы
- дополнительно сделан обход кондиционера "байпас" трубой 200 мм из приточки в "светофор". Это режим используется для зимней эксплуатации, чтобы не гнать воздушный поток через кондиционер 

<img src="./img/air_conditioning/air_conditioning0.png?raw=true" alt="drawing" width="400"/>


Фото монтажа:  

<img src="./img/air_conditioning/air_conditioning1.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/air_conditioning/air_conditioning2.jpeg?raw=true" alt="drawing" width="350"/> 

<img src="./img/air_conditioning/air_conditioning3.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/air_conditioning/air_conditioning4.jpeg?raw=true" alt="drawing" width="350"/> 

<img src="./img/air_conditioning/air_conditioning5.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/air_conditioning/air_conditioning6.jpeg?raw=true" alt="drawing" width="350"/> 

## Приточная вентиляция

В качестве канального вентилятора выбрал [Systemair K 250 EC](https://shop.systemair.com/en/k--250--ec--sileo/p97597).

- Input power - 115 W
- Input current - 0.874 A
- Air flow - max 979 m³/h
- Motor type - EC

Как я выбирал вентилятор:

- номинальный поток на квартиру планируется 200 м<sup>3</sup> до 400 м<sup>3</sup>
- потери давления на фильтре тонкой очистки планировались от 75 до 250 Па
- общие потери на сети составляли около 150 Па
- итого мне нужно 400 м<sup>3</sup> при внешнем давлении 400 Па

Ниже показана кривая производительности вентилятора от внешнего давления. Выбранная мной модель как раз укладывается в предельные характеристики.  

<img src="./img/vent/vent0.png?raw=true" alt="drawing" width="800"/>

Фото монтажа:

- перед вентилятором стоит фильтр грубой очистки и шумоглушитель
- после вентилятора стоит клапан, чтобы заглушить систему, и фильтр тонкой очистки
- далее стоит канальный подогреватель и еще один шумоглушитель
- в коридоре стоит еще один фильтр тонкой очистки для фильтрации воздуха в кондиционер (рециркуляция)

<img src="./img/vent/vent1.jpg?raw=true" alt="drawing" width="350"/>  <img src="./img/vent/vent2.jpg?raw=true" alt="drawing" width="350"/> 

<img src="./img/vent/vent3.jpg?raw=true" alt="drawing" width="350"/>  <img src="./img/vent/vent4.jpg?raw=true" alt="drawing" width="350"/> 

<img src="./img/vent/vent5.jpg?raw=true" alt="drawing" width="350"/>  <img src="./img/vent/vent6.jpg?raw=true" alt="drawing" width="350"/> 

## Фильтрация воздуха

Для тонкой очистки воздуха выбрал кассетный фильтр [Systemair FFR 200](https://shop.systemair.com/en/ffr--200--filter--cassette/p403766).
Фильтрующие элементы планировал использовать:

- класса G3 [BFR 200 Coarse](https://shop.systemair.com/en/bfr--200--coarse--50--filter/p94598). При  потоке 300 м<sup>3</sup> потери на новом фильтре составляют 20 Па. Замена рекомендуется при потере давления 170 Па.
- класса F7 [BFR 200 ePM1](https://shop.systemair.com/en/ffr--200--filter--cassette/p403766). При  потоке 300 м<sup>3</sup> потери на новом фильтре составляют 75 Па. Замена рекомендуется при потере давления 250 Па.

Последний фильтр [BFR 200 ePM1](https://shop.systemair.com/en/ffr--200--filter--cassette/p403766) отделяет 60% частиц размера PM1 (от 0,3 до 1 мкм по ISO 16890). И у него очень приличная цена [98,00 EUR](https://shop.systemair.com/ru-RU/bfr--200--epm1--60--filter/p93085).

После года эксплуатации озадачился вопросом замены фильтров. Решил поискать на рынке, какие есть аналоги.

Вариант 1 - купить фильтрующий материал и сшить фильтр самому.

- разобрал один старый фильтр и сделал выкройку - размер листа 350х2000 мм.
- заказал листовой фильтрующий материал класса [G5](https://filters.ru/catalog/filtruyushchie-materialy/filtruyushchiy-material-dlya-okrasochno-sushilnykh-kamer/) Для сравнения взял несколько несколько разных материалов: NF300/1, NF400/P, NF500/PS
- ниже фото материала:
  - Материал прогрессивной плотности. Снаружи рыхлый, внутри - очень плотный.
  - NF300 - очень похож на то, из чего был сделан оригинальный фильтр. Легко гнется, сшить из него фильтр легко.
  - NF500/PS - очень плотный, даже жесткий. Сделать из него что-то похожее на оригинал не получится.
  - NF400/P - как раз то, что надо
- Шитьем пока не занимался.

<img src="./img/filter/filter1.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/filter/filter3.jpeg?raw=true" alt="drawing" width="350"/> 

<img src="./img/filter/filter4.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/filter/filter5.jpeg?raw=true" alt="drawing" width="350"/> 

Вариант 2 - заказать фильтр в сборе.

- Одновременно с материалом заказал фильтр в сборе класса [F6](https://filters.ru/catalog/karmannye-vozdushnye-filtry/filtr-vozdushnyy-karmannyy-tonkoy-ochistki-s-filtruyushchim-materialom-meltblown-fvk/) по следующей спецификации ФВК-233-233-300-4-F6/20.

Качество изготовления отличное, идеально сел в родной корпус FFR 200. Для себя решил, что буду заказывать - это 2-3 кратная экономия к оригиналу.

<img src="./img/filter/filter6.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/filter/filter7.jpeg?raw=true" alt="drawing" width="350"/> 

## Автоматика

Сделал небольшой щиток:

<img src="./img/automatic/automatic1.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/automatic/automatic2.jpeg?raw=true" alt="drawing" width="350"/> 

В щитке оставил запас для контролера автоматики и небольшого трансформатора. Схема максимально простая:

- основной выключатель, который отключает и приточку и кондиционер.
- отдельный выключатель на кондиционер
- отдельный выключатель на калорифер
- маломощное реле (1А) подключено к выключателю скорости вращения вентилятора приточки (0-10В)
- маломощное реле коммутирует два реле - 16А-на вентилятор и 25А-на контролер управления калорифером

В качестве контролера управления 3 кВт калорифером использовал [PULSER](http://www.arktika.ru/html/pulser.htm).

Датчик температуры поставил в канале сразу после входа воздуховода в квартиру.

Протестировал два режима работы системы:

1-работает только приточка и калорифер

- приточка гонит воздух в обход канального кондиционера
- скорость воздуха на выходе их решеток - 0,8 м/с (соответствует расходу примерно 60 м<sup>3</sup>/час, 250 м<sup>3</sup>/час на всю квартиру).
- воздух из решетки распространяется не очень далеко, практически сразу падает на пол.
- комфортность полностью устраивает, в квартире не чувствуется недостатка воздуха.
- температура на регуляторе установлена на 20 °C. На выходе из решеток температура около 21 °C.
- расход электричества несколько удручает, за ночь - 10 кВт/час (на улице было примерно 5 °C)

2-работает приточка и канальный кондиционер в режиме нагрева

- приточка гонит воздух в канальный кондиционер
- кондиционер дополнительно забирает воздух из квартиры
- скорость воздуха на выходе их решеток - 2,0 м/с (соответствует расходу 150 м<sup>3</sup>/час, 600 м<sup>3</sup>/час на всю квартиру, из которых 200-300 м<sup>3</sup>/час из приточки).
- кондиционер работает в режиме нагрева. На выходе из решеток температура около 40 °C.
- воздух из решетки распространяется на всю комнату.
- комфортность полностью устраивает, в квартире не чувствуется недостатка воздуха.
- расход электричества за ночь - 5 кВт/час
- Этот режим мне нравится больше всего. Мы замечательно отапливаем всю квартиру.
- Одна проблема - за ночь наружный блок кондиционера полностью замерзает и превращается в большой морозильник.

## Вытяжка для кухни и зонта

Заодно с приточной вентиляцией решил сделать и "правильную" вытяжку для кухни.

- в качестве вытяжного вентилятора поставил Systemair К 160M на 500м<sup>3</sup>/час
- перед вентилятором стоит глушитель длиной 1 м
- перед глушителем - простой фильтр, чтобы ловить жир с кухонного зонта и обратный клапан подпружиненный
- все собрано 150 трубой, на этот раз пластиком
- родной вентилятор из кухонной вытяжки не включается

Параллельно собрал 125 трубой естественную вытяжку из кухни, так же с обратным клапаном, который подпружинен в открытом состоянии (при включении вытяжного вентилятора обратный клапан закрывается). Отвод от естественной вытяжки сделал в кладовку и уменьшил сечение.

Все собрано в кладовке, которая граничит с кухней.

Результат мне понравился. Шума от вытяжки практически нет, даже на максимуме.
Мощность вентилятора впечатляет, мелкий песок, который был в трубе засосал как пылесос.

И главное, благодаря глушителям, я перестал слышать рабочих с верхнего этажа (звук шел через вентиляционную шахту).

Фото монтажа:  
<img src="./img/kitchen/kitchen1.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/kitchen/kitchen2.jpeg?raw=true" alt="drawing" width="350"/> 

<img src="./img/kitchen/kitchen3.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/kitchen/kitchen4.jpeg?raw=true" alt="drawing" width="350"/> 

Дополнительно в туалете поставим маленький глушитель и ирисовый клапан для регулировки потока.
Без регулировки тяга была такая, что зимой на туалете невозможно сидеть - сдувает. После ирисового поставил обратный клапан.

<img src="./img/kitchen/kitchen5.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/kitchen/kitchen6.jpeg?raw=true" alt="drawing" width="350"/> 

## Финишная отделка

Когда жена посмотрела на все эти трубы она "ласково" назвала их цехом. Но после окончательной отделки большую часть удалось спрятать. Канальный кондиционер и большая часть труб спрятаны под подвесным потолком в маленьком коридоре.

<img src="./img/finish/finish1.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/finish/finish2.jpeg?raw=true" alt="drawing" width="350"/> 

<img src="./img/finish/finish3.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/finish/finish4.jpeg?raw=true" alt="drawing" width="350"/> 

<img src="./img/finish/finish5.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/finish/finish6.jpeg?raw=true" alt="drawing" width="350"/> 

## Стоимость системы

Система получилась недешевая, общая сумма приближается к 200 000 р (в ценах 2012).

- Вентиляторы канальные Systemair - 12 000р.
- Камеры статического давления Systemair (4 шт) - 13 000р.
- Клапана ирисовые 125 (4шт) Systemair - 4 500р.
- Кондиционер SEZ-KD35VAQ - 65 000р.
- Монтаж канального кондиционера 17 000р.
- Нагреватель канальный Systemair CB 200-3.0 - 5 600р.
- Приточные решетки Systemair, регуляторы, рамки - 4 000р.
- Трубы и фасонные части для вентиляции, крепеж, утеплитель - 25 000р.
- Фильтры Systemair FFR 200, FGR 250 - 4 700р.
- Шумоглушители Systemair (4 шт.) - 7 500р.

## Опыт эксплуатации

Наблюдения за расходом электричества:

- ноябрь 2012 - 613 кВт/ч (теплый месяц был)
- декабрь 2012 - 1208 кВт/ч
- январь 2013 - 1128 кВт/ч (работало не полный месяц - на новый год уезжали)

По расходу воздуха - держал все время на минимуме примерно 150-200 м<sup>3</sup>/час на всю квартиру. В целом результатом доволен.  

Шума из решеток нет - то есть вообще нет.  

Чтобы не сомневаться что вентиляция работает - наклеил на решетки новогодний дождик (на радость кошке).  

Была жаркая неделя май 2013 - начал активно использовать кондиционер в режиме охлаждения.

- В режиме приточки расход порядка 300 м<sup>3</sup>/час (по 100 м<sup>3</sup>/час на комнату). Скорость на выходе из решеток - 1,2 м/с
- При включении канального кондиционера на максимальную скорость - расход - 600 м<sup>3</sup>/час, из них 300 м<sup>3</sup>/час с приточки и порядка 300 м<sup>3</sup>/час - рециркуляция. Скорость на выходе из решеток - около 3 м/с.

Субъективные наблюдения при работе кондиционера:

- Температура на выходе из решеток около 11 °C.
- Быстро охладить квартиру таким кондиционером (около 3,5 Квт по холоду) не получается. Но если он постоянно работает на минимальной скорости, то в квартире вполне комфортно (воздух на улице + 28).
- Основной комфорт, по моему мнению, достигается не за счет снижения температуры (не превышает 2-3 градусов), а за счет снижения влажности.
- Шум из приточных решеток не напрягает даже ночью. Решетки отлично регулируют воздушный поток, можно сделать так, чтобы не направлять на кровати детей.
- При скорости на выходе 2-3 м/с поток холодного воздуха проходит под потолком через всю комнату и нет сквозняка.

Из недостатков:

- Так как забор рециркуляционного воздуха сделан возле кондиционера, то в комнатах наблюдается существенный переток воздуха под дверью. При открытых межкомнатных дверях это не заметно, а вот если дверь закрыть - то чувствуется ощутимо.
- Нельзя регулировать температуру в отдельных комнатах. Вечером в восточной комнате хорошо, а вот западную хотелось бы еще охладить.

## Переход на водяной подогрев

Закончился 2013 год эксплуатации приточки совместно с канальным кондиционером.
Было потрачено 6700 КВт электроэнергии. Большая часть пошла на нагрев воздуха зимой электрическим калорифером.

Запланировал переход с электричества на воду. Из чего будет состоять система:

- Контролер автоматики - OPTIMUS 911. Выбрал его по нескольким причинам:
  - умеет управлять моим вентилятором по сигналу 1-10 В
  - умеет одновременно управлять водяным нагревателем по сигналу 1-10 В и плавно электрическим калорифером по ШИМ. Электрический калорифер подключается, если у водяного не хватает мощности.
  - умеет автоматически снижать скорость вентилятора, при снижении температуры обратной воды ниже дежурного значения.
  - имеет несколько режимов защиты от замораживания: по температуре воздуха, по температуре обратной воды, по капиллярному термостату.

- Водяной калорифер Systemair VBC 200-2
- Смесительный узел с трехходовым краном и приводом управления по сигналу 1-10 В
- Рециркуляционный насоса для малого контура

Параметры системы отопления:

- Давление в системе отопления 6-10 Атм
- Температура - от 45 °C (на улице 0 °C) до 70 °C (на улице -28 °C)

Несколько фоток, во что превратилась система после перевода на воду

- так выглядят электрический и водяной калориферы  
<img src="./img/water/water3.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/water/water4.jpeg?raw=true" alt="drawing" width="350"/>

- щиток автоматики  
<img src="./img/automatic/automatic3.jpeg?raw=true" alt="drawing" width="400"/>

- смесительный узел  
<img src="./img/water/water1.jpeg?raw=true" alt="drawing" width="350"/>  <img src="./img/water/water2.jpeg?raw=true" alt="drawing" width="350"/>