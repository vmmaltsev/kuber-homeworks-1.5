# Домашнее задание к занятию «Сетевое взаимодействие в K8S. Часть 2» - `Мальцев Виктор`

---

Задание 1. Создать Deployment приложений backend и frontend

    1. Создать Deployment приложения frontend из образа nginx с количеством реплик 3 шт.
    2. Создать Deployment приложения backend из образа multitool.
    3. Добавить Service, которые обеспечат доступ к обоим приложениям внутри кластера.
    4. Продемонстрировать, что приложения видят друг друга с помощью Service.
    5. Предоставить манифесты Deployment и Service в решении, а также скриншоты или вывод команды п.4.

Ответ:

Манифиесты Deployment и Service в директории https://github.com/vmmaltsev/kuber-homeworks-1.5/tree/main/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201

Скриншоты:

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_118.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_119.png)

---

Задание 2. Создать Ingress и обеспечить доступ к приложениям снаружи кластера

    1. Включить Ingress-controller в MicroK8S.
    2. Создать Ingress, обеспечивающий доступ снаружи по IP-адресу кластера MicroK8S так, чтобы при запросе только по адресу открывался frontend а при добавлении /api - backend.
    3. Продемонстрировать доступ с помощью браузера или curl с локального компьютера.
    4. Предоставить манифесты и скриншоты или вывод команды п.2.

Ответ:

Манифиесты в директории https://github.com/vmmaltsev/kuber-homeworks-1.5/tree/main/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%202

Скриншоты:

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_121.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_122.png)