Стемминг – это грубый эвристический процесс, который отрезает «лишнее» от корня слов, часто это приводит к потере словообразовательных суффиксов.

Лемматизация – это более тонкий процесс, который использует словарь и морфологический анализ, чтобы в итоге привести слово к его канонической форме – лемме.

Наивный байесовский классификатор - в основе лежит теорема байеса, суть в том что пытаемся найти класс, к которому принадлежит документ с наибольшей вероятностью

Цель классификации состоит в том чтобы понять к какому классу принадлежит документ, поэтому нам нужна не сама вероятность, а наиболее вероятный класс. Байесовский классификатор использует оценку апостериорного максимума (Maximum a posteriori estimation) для определения наиболее вероятного класса. Грубо говоря, это класс с максимальной вероятностью.


про Pipeline
https://stackoverflow.com/questions/33091376/what-is-exactly-sklearn-pipeline-pipeline


про ROC-кривую - http://www.machinelearning.ru/wiki/index.php?title=ROC-%D0%BA%D1%80%D0%B8%D0%B2%D0%B0%D1%8F
График показывает зависимость верно положительных классификаций от ложно положительных классификаций

W2V
sg=1 - алгоритм обучения skip-gram, его суть в том что мы пытаемся угадать соседние слова по текущему слову