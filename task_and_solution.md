### Задание 1

**Что нужно сделать:**

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins [golang](https://golang.org/doc/install).
3. Используя свой аккаунт на GitHub, сделайте себе форк [репозитория](https://github.com/netology-code/sdvps-materials.git). В этом же репозитории находится [дополнительный материал для выполнения ДЗ](https://github.com/netology-code/sdvps-materials/blob/main/CICD/8.2-hw.md).
3. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта ```go test .``` и  ```docker build .```.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---
<img width="930" height="661" alt="image" src="https://github.com/user-attachments/assets/d5d4e3be-187d-4680-bf7b-96b2bae8829f" />
<img width="1185" height="232" alt="image" src="https://github.com/user-attachments/assets/55ee8536-36fc-43bd-853c-75b638f75e0f" />
---

### Задание 2

**Что нужно сделать:**

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---
<img width="1535" height="1251" alt="image" src="https://github.com/user-attachments/assets/12fe5c67-1c39-4b85-9a39-d53aa143f58d" />
<img width="873" height="656" alt="image" src="https://github.com/user-attachments/assets/225dec5f-bb99-4348-83d8-bf1b61d3a674" />
---

### Задание 3

**Что нужно сделать:**

1. Установите на машину Nexus.
1. Создайте raw-hosted репозиторий.
1. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
1. Загрузите файл в репозиторий с помощью jenkins.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.
выполнения сборки.

---
<img width="1560" height="890" alt="image" src="https://github.com/user-attachments/assets/d40670bf-f3a0-44e4-911a-dee1a129a848" />
<img width="846" height="585" alt="image" src="https://github.com/user-attachments/assets/192bbde7-ae0a-424c-af09-9d45209c39ae" />
<img width="1755" height="1098" alt="image" src="https://github.com/user-attachments/assets/0f862b59-0561-4b69-8d49-08ef81023445" />
