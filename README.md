# PROJECT-3.-EDA-Feature-Engineering
  ссылка на проект [https://colab.research.google.com/drive/1xwfnXUaP8w2dc-riTp5c_DDAJN0eKe_w?usp=sharing)](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/blob/main/baseline_saveleva_v2.ipynb)
  
  ссылка на датасет [hotels_train.csv](https://drive.google.com/file/d/1--3ZGooerTN7jOdDdMuwVqW6aCnKCEG7/view?usp=share_link)
  [hotels_test.csv](https://drive.google.com/file/d/14v4zBMVeVdt6Lr6WuoZTPTeiCpsPTVgq/view?usp=share_link)
  [submission.csv](https://drive.google.com/file/d/1--ZgyB_LJvFuoiMPuyk1EAcsDAuanqFn/view?usp=share_link)

## Оглавление
1. [Описание проекта](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#описание-проекта#Описание-проекта)
2. [Основная проблема проекта?]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#Основная проблема проекта?)
3. [Краткая информация о данных]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#Краткая-информация-о-данных)
4. [Этапы работы над проектом]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#Этапы-работы-над-проектом)
5. [Результат]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#описание-проекта)#Результат)
6. [Выводы]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#Выводы)


### Описание проекта
Представьте, что вы работаете датасаентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов нахождения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель играет нечестно, и его стоит проверить.
Вам поставлена задача создать такую модель. 

:arrow_up:[к оглавлению]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#описание-проекта)#Оглавление)


### Основная проблема проекта?
Необходимо подготовить имеющиеся данные путем их преобразования для дальнейшего их использования для обучения модели, которая будет предсказывать рейтинг отеля.


**Условия выполнения проекта:**
- Очистка данных.
- Исследование данных (качество визуализации, наличие идей, гипотез, комментариев).
- Генерация признаков.
- Отбор признаков.
- Преобразование признаков.
- Качество решения: результат метрики MAPE.


**Оценка результатов:**
Результаты оцениваются согласно требованиям, указанным к проекту. 
Необходимо: подготовить данные и обучить модель (максимум 21 балл), сдать проект на проверку, загрузив ноутбук-шаблон со своим решением на GitHub и в Kaggle


**Чему учимся:**
Учимся корректно писать код на Python для анализа и преобразовывать исходные данные, практикуем методы очистки данных, навыки по представлению проекта на GitHub и в Kaggle


:arrow_up:[к оглавлению]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#описание-проекта)#Оглавление)


### Краткая информация о данных
В данном проекте первоначальные данные представлены в виде 2х датасетов размерами: hotel_train.csv - 386803  строк, 17 столбцов, типа object, int64, float64  и hotel_test.csv - 128935 строк, 16 столбцов типа object, int64, float64,  в отдельных столбцах присутствуют пропуски. В связи с этим необходимо более детально проанализировать первоначальные данные, сделать выводы о дальнейших преобразованиях. 

данные используемые в проекте:
- hotels_train.csv - набор данных для обучения
- hotels_test.csv - набор данных для оценки качества
- submission.csv - файл сабмишна в нужном формате


:arrow_up:[к оглавлению]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#описание-проекта)#Оглавление)


### Этапы работы над проектом
- Ознакомление с описанием задачи
- Базовый анализ исходных данных
- Преобразование данных
- Разведывательный анализ
- Очистка данных
- Проверка соответствия написанного кода стандарту PEP8
- Оформление проекта
- Загрузка проекта на GitHub и в Kaggle 


:arrow_up:[к оглавлению]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#описание-проекта)#Оглавление)


### Результат
Проект модели, которая будет предсказывать рейтинг отеля представлен в репозитории на GitHub и в Kaggle


:arrow_up:[к оглавлению]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#описание-проекта)#Оглавление)


### Выводы
В процессе выполнения проекта первоначальные данные были проанализированы, преобразованы, проведен разведывательный анализ данных с последующей визуализацией результатов с целью выявления взаимосвязей между признаками, данные были очищены от пропусков. Таким образом первоначальный датасет подготовлен для дальнейшего использования при обучении модели. 


:arrow_up:[к оглавлению]([https://github.com/ElenaSaveleva/Project_1/blob/main/README.md](https://github.com/ElenaSaveleva/PROJECT-3.-EDA-Feature-Engineering/edit/main/README.md#описание-проекта)#Оглавление)
