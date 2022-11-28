

# <center>Бизнес-задача по аналитике датасета резюме компании HeadHunter :bowtie:</center>
![Очистка](https://drive.google.com/uc?export=view&id=1nG6ZRDJOwICCdqUEW7B4jRlDA8P1lf3X)
===============================================================================================
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Проблематика](#Проблематика)
3. [Основные этапы проекта](#Основные-этапы)
4. [Цель проекта](#Цель-проекта)
5. [Ссылки на материалы проекта](#Ссылки-на-материалы-проекта)
6. [Описание данных](#Описание-данных)
7. [Используемые зависимости](#Используемые-зависимости)
8. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование-проекта)
6. [Авторы](#Авторы)
7. [Выводы](#Использование-проекта)

## Описание проекта
Задача состоит в том, чтобы  построить модель для компании HeadHunter, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Для того чтобы построить модель, данные необходимо преобразовать, исследовать и очистить.

## Проблематика
Часть соискателей не указывает желаемую заработную плату, когда составляет своё резюме.

## Основные этапы

- базовый анализ структуры данных
- преобразование данных
- разведывательный анализ
- очистка данных

## Цель проекта
Демонстрация применения различных методов анализа, преобразования и очистки данных на каждом из ее этапов на примере датасета  резюме, выгруженного с сайта поиска вакансий hh.ru.

## Ссылки на материалы проекта
* [Datasets](https://drive.google.com/drive/folders/1CK13opjyPuEG6zelsPRrN9z5OevTHZR5?usp=sharing) - папка с исходными датасетами (датасет резюме HH, датасет с обменным курсом валют)
* [HTML_Plotly_Graphics](https://github.com/RenatK/DS_Project/tree/master/plotly_graph) - папка с HTML файлами интерактивных графиков, данные графики размещены для возможности быстрого просмотра результатов разведовательного анализа без установки дополнительного ПО
* [Project_1 Notebook](https://github.com/RenatK/DS_Project/blob/master/Project-1.%20%D0%9D%D0%BE%D1%83%D1%82%D0%B1%D1%83%D0%BA-%D1%88%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором демонстрируются методы и подходы решения задач проекта

## Описание данных
В этом проекте анализируется и преобразовываются датасет состоящий из 12 столбцов и 44744 строк.

 0   Пол, возраст                    
 1   ЗП                               
 2   Ищет работу на должность:        
 3   Город, переезд, командировки     
 4   Занятость                        
 5   График                           
 6   Опыт работы                      
 7   Последнее/нынешнее место работы  
 8   Последняя/нынешняя должность     
 9   Образование и ВУЗ                
 10  Обновление резюме                
 11  Авто                             

## Используемые зависимости
* Python (3.11.0)
Версии используемых библиотек указаны в файле **requirements.txt**
  
## Установка проекта

```
git clone https://github.com/RenatK/DS_Project
```

## Использование проекта
Вся информация о работе представлена в jupyter-ноутбуке **Project-1. Ноутбук-шаблон.ipynb**

## Авторы

* [Ренат Хасянов](https://github.com/RenatK)

## Выводы
 - Преобразовано несколько признаков датасета с использованием различных методов, для обеспечения возможности их дальнейшего анализа
 - Проведено приведение желаемой заработной платы всех соискателей в рубли в соотвествии с датасетом курсов валют на дату публикации резюме
 - Было создано несколько графических диаграмм, чтобы показать возможное влияние на модель прогнозирования  
 - Проведена очистка данных от дубликатов, пропусков, а также были обработаны выбросы с помощью модели z-оценки.