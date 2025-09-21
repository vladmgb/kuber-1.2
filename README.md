# Домашнее задание к занятию «Базовые объекты K8S»


## Задание 1. Создать Pod с именем hello-world
1. Создать манифест (yaml-конфигурацию) Pod.
   [Ссылка на манифест](https://github.com/vladmgb/kuber-1.2/blob/main/pod1.yaml).
3. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.\
   Pod запущен:
    
   <img width="404" height="114" alt="image" src="https://github.com/user-attachments/assets/0c20bbe5-d77f-4c0f-a09e-20fc8be3ec4e" />

5. Подключиться локально к Pod с помощью kubectl port-forward и вывести значение (curl или в браузере).

   <img width="479" height="71" alt="image" src="https://github.com/user-attachments/assets/8540b41a-7a20-40a9-80e2-a0666319fc15" />

    Подключился

   <img width="505" height="477" alt="image" src="https://github.com/user-attachments/assets/2dc679b7-4436-4c8d-9d98-c7c2d9001b0a" />



