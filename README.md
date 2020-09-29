# Advertisement Classification by the contact information available

## Extensive EDA, Text preprocessing, TFIDF, Tune Logistic Regression

![](https://developers.google.com/machine-learning/guides/text-classification/images/TextClassificationExample.png)

## Задача
Необходимо предсказать, есть ли в объявлении контактная информация.

Есть два датасета `train.csv` и `test_data.csv`:
Обучать модель будем на выборке `train.csv`. Качество модели оценим на тестовой выборке `test_data.csv`.

Оценивать качество классификатора будем по метрике `ROC-AUC`.

### Колонки
* `title` - заголовок,
* `description` - описание,
* `subcategory` - подкатегория,
* `category` - категория,
* `price` - цена,
* `region` - регион,
* `city` - город,
* `datetime_submitted` - дата размещения.

Таргет: `is_bad`
