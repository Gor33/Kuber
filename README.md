Домашняя работа к занятию “Kubernetes (к8s)”
Цель задания:
Написать kubernetes-манифест чтобы понять, как описывать приложение в манифесте для развертывания в k8s.

Задание:

Ответить на вопросы:

● Что такое k8s? 

● В чём преимущество контейнеризации над виртуализацией? 

● В чём состоит принцип самоконтроля k8s? 

● Как вы думаете, зачем Вам понимать принципы деплоя в k8s? 

● Какое из средств управления секретами наиболее распространено в использовании совместно с k8s? 

● Какие типы нод есть в k8s, каковы их базовые функции?


Написать манифест, который будет содержать в себе следующие условия: 

● apiVersion – v1 

● название – netology-ml 

● внутри него сервер приложений tomcat версии 8.5.69 с портом 8080 

● наличие 2 реплик 

● использование стратегии rollingupdate


Домашнее задание выполните в файле readme.md в github репозитории.

Результат:
В личном кабинете отправьте на проверку ссылку на .md файл, содержащий ответы на вопросы и kubernetes-манифест.


