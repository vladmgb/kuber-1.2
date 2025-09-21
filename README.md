# Домашнее задание к занятию «Базовые объекты K8S»


## Задание 1. Создать Pod с именем hello-world
1. Создать манифест (yaml-конфигурацию) Pod.
   [Ссылка на манифест](https://github.com/vladmgb/kuber-1.2/blob/main/pod1.yaml).
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.\
   Pod запущен:
    
   <img width="404" height="114" alt="image" src="https://github.com/user-attachments/assets/0c20bbe5-d77f-4c0f-a09e-20fc8be3ec4e" />

3. Подключиться локально к Pod с помощью kubectl port-forward и вывести значение (curl или в браузере).

   <img width="479" height="71" alt="image" src="https://github.com/user-attachments/assets/8540b41a-7a20-40a9-80e2-a0666319fc15" />

    Подключился

   <img width="505" height="477" alt="image" src="https://github.com/user-attachments/assets/2dc679b7-4436-4c8d-9d98-c7c2d9001b0a" />


## Задание 2. Создать Service и подключить его к Pod
1. Создать Pod с именем netology-web.
    [Ссылка на манифест](https://github.com/vladmgb/kuber-1.2/blob/main/pod2.yaml).

2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.\
    Pod запущен:
 
    <img width="416" height="118" alt="image" src="https://github.com/user-attachments/assets/f99d9f3e-1221-4546-8b97-79fb1cbe7381" />

3. Создать Service с именем netology-svc и подключить к netology-web.
   
    [Ссылка на манифест](https://github.com/vladmgb/kuber-1.2/blob/main/service.yaml).

   Service создан.
   
   <img width="527" height="74" alt="image" src="https://github.com/user-attachments/assets/72e27a78-e265-4636-8f39-5014352d2d1e" />

6. Подключиться локально к Service с помощью kubectl port-forward и вывести значение (curl или в браузере).


   <img width="484" height="77" alt="image" src="https://github.com/user-attachments/assets/bd9965d7-b681-4c02-8db9-7805bf0ed73b" />

   Подключился:

   <img width="510" height="415" alt="image" src="https://github.com/user-attachments/assets/909e6d71-e3aa-422d-a931-7860101de8a9" />

   
