https://habr.com/ru/company/ods/blog/328372/ - про метрики

accuracy - доля правильных ответов, посчатить на скольких объектах даем верный ответ и разделить на кол-во всех ответов, метрика очень плоха на несбалансированной выборке

precision (точность) - (сколько раз мы верно классифицировали объект к классу X) / (сколько раз мы всего отнесли классифицировали к классу X). показывает способность отличать этот класс от других классов. Чем выше точность, тем меньше ложных срабатываний

recall -  показывает. способность алгоритма обнаруживать данный класс вообще. Чем выше полнота тем меньше ложных пропусков

f-мера - сглаженный минимум между precision и recall (гарманическое среднее)

https://www.coursera.org/learn/vvedenie-mashinnoe-obuchenie/lecture/kVz6T/rieshaiushchiie-dieriev-ia - про решающие деревья

решающее дерево - в каждом узле дерева есть предикат, по значению в какое поддерево нужно идти, в листах расположены классы 

https://www.coursera.org/learn/vvedenie-mashinnoe-obuchenie/lecture/jCkvu/mietod-blizhaishikh-sosiediei - про метод ближайших соседей

считаем меру расстояния от текущего объекта до всех других объектов, ранжируем в порядке убывания меры расстояния все объекты выборки, среди них выбираем сверху К объектов, относим текущий к тому классу, которого больше всего среди этих K объектов

проблемы
1) если K=6 3 объекта одного класса и 3 объекта другого класса, к какому отнести текущий объект
2) нужно изначально знать K - количество соседей. Кроссвалидация помогает выбрать K


https://www.coursera.org/learn/vvedenie-mashinnoe-obuchenie/lecture/n6JbA/beghghingh-i-sluchainyi-lies - про случайный лес

метод по сути является голосованием из некоторого числа случайных деревьев. Признак для каждого узла в дереве выбирается из случайного подмножества K из n признаков

количество деревьев можно подобрать при помощи кросс валидации, можно так же по критерию out-of-bag