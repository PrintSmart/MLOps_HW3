# MLOps. Практическое задание №3 (vo-HW)
При выполнении итоговой самостоятельной работы по модулю «Управление потоком операций (xFlow)» вам необходимо:

1. Определить какой-нибудь внешний источник получения данных и способ получения этих данных (http, curl, wget, API, SQL, SparQL, ...) (3 балла).
YouTube через API
2. Поставить задачу для алгоритма машинного обучения, выбрать модель и метрику (4 балла).
По поисковому запросу «Print DTF» получить списки комментариев роликов YouTube, которые дает платформа по этому поисковому запросу.
В полученном json файле можно достать значение параметра likeCount, которое и сохраняется в используемом далее наборе данных, в файле data.csv.
3. Создать инфраструктуру, например, виртуальные машины virtualbox, установить и настроить для работы необходимое программное обеспечение, в том числе airflow и mlflow, а также venv для организации работы виртуального окружения (5 баллов).
      <img src="https://github.com/PrintSmart/MLOps_HW3/blob/main/screen/VB.JPG" />
Виртуальная машина
      <img src="https://github.com/PrintSmart/MLOps_HW3/blob/main/screen/venv.JPG" />
Виртуальное окружение
      <img src="https://github.com/PrintSmart/MLOps_HW3/blob/main/screen/af.JPG" />
airflow
      <img src="https://github.com/PrintSmart/MLOps_HW3/blob/main/screen/mlf.JPG" />
mlflow

4. Создать python скрипты для (6 баллов):
(файлы открываются по клику)

[получения данных из внешнего источника](scripts/get_data.py)
получения данных из внешнего источника,
преобразования данных,
формирования рабочего набора данных для обучения (train) и тестирования (test) модели,
обучения модели на тренировочных (train) данных и ее сохранения,
загрузки модели и проверки качества ее работы на тестовых (test) данных.
6. Добавить код airflow, позволяющий создавать и запускать на регулярной основе описанные операции проекта (6 баллов).
      <img src="https://github.com/PrintSmart/MLOps_HW3/blob/main/screen/airflow.JPG" />
airflow
7. Добавить код mlflow, позволяющий мониторить ход выполнения конвейера, сохранять и анализировать полученные артефакты (6 баллов).
      <img src="https://github.com/PrintSmart/MLOps_HW3/blob/main/screen/mlflow.JPG" />
mlflow
      <img src="https://github.com/PrintSmart/MLOps_HW3/blob/main/screen/requirements.txt.JPG" />
requirements.txt

