# ИНЖЕНЕРИЯ БОЛЬШИХ ЯЗЫКОВЫХ МОДЕЛЕЙ  
перевод и редакция ["Build a large language model from scratch"](https://livebook.manning.com/book/build-a-large-language-model-from-scratch/welcome/v-6/)

![Глава 1, что такое языковые модели](01.ipynb)  
![Глава 2, как данные передаются в модель](02.ipynb)  
![Глава 3, механизм внимания](03.ipynb)  
![Глава 4, реализация модели ГПТ](03.ipynb)

Большие языковые модели (ЛЛМ), такие как чатГПТ, представляют собой модели глубоких нейронных сетей, разработанные за последние несколько лет. Они открыли новую эру обработки естественного языка (НЛП). До появления больших языковых моделей традиционные методы (основанные на правилах или не нейронных моделях) использовались для задач категоризации:
 - классификация спама в электронной почте
 - простое распознавание образов.
 
 Однако они плохо справлялись с задачами, требующими сложного понимания и способностей генерирования:
  - анализ подробных инструкций
  - проведение контекстуального анализа
  - создание связного текста. 
  
Например, предыдущие поколения языковых моделей не могли написать электронное письмо, используя список ключевых слов — задача, которая тривиальна для современных ЛЛМ.

ЛЛМ обладают способностями "понимать", генерировать и интерпретировать человеческий язык. Однако важно уточнить: когда мы говорим, что языковые модели "понимают", мы имеем в виду, что они могут обрабатывать и генерировать текст последовательными и контекстуально релевантными, а не то, что они обладают человеческим сознанием или пониманием. Глубокое обучение - разновидность машинного обучения и алгоритмов искусственного интеллекта (ИИ). ЛЛМ обучаются на огромных объемах текстовых данных, что позволяет улавливать более глубокую контекстную информацию и тонкости человеческого языка по сравнению с предыдущими подходами. Еще одно важное различие между "современными" и "традиционными" моделями: последние обычно разрабатывались для конкретных задач, были успешны в своих узких приложениях, тогдка как ЛЛМ демонстрируют более широкие навыки в широком спектре задач.

Успех ЛЛМ основывается на архитектуре трансформеров а также огромных объемах данных для обучения.

#### В этих конспектах исследуется архитектура трансформеров путем пошаговой реализации ЛЛМ.  
