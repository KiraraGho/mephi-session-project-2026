# Сессионный проект по курсу «Операционные системы семейства Unix»

Выполнил студент группы М25-555 Шинкаренко Виктория

## Описание проекта

В рамках сессионного проекта была выполнена настройка серверной системы на базе Fedora Server 44.

Выполнены следующие задачи:

* настройка сети и hostname;
* проверка сетевой связности;
* установка и настройка nginx;
* установка и настройка tcpdump;
* работа с RPM-пакетами;
* создание и монтирование файловой системы ext4;
* настройка автоматического монтирования через `/etc/fstab`;
* создание пользователей и групп;
* настройка прав доступа;
* настройка SELinux;
* настройка Linux capabilities для tcpdump;
* ограничение входа root через PAM;
* публикация web-страницы с персональным идентификатором студента.

## Проверка web-сервера

Результат проверки:

```text id="5h85k0"
Hello from Student: 371024
```

## Содержимое репозитория

В репозитории находятся следующие файлы:

* `project_history.txt`
* `network_check.txt`
* `nginx_recent_logs.txt`
* `fstab.txt`
* `selinux_status.txt`
* `file_contexts.txt`
* `tcpdump_capabilities.txt`
* `permissions.txt`
* `users_groups.txt`
* `index.html`
* `curl_output.txt`

## Используемая система

* Fedora Server 44
* nginx
* SELinux
* ext4
* systemd
* NetworkManager
