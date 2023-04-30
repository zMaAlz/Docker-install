# Ansible playbook для установки Docker на linux сервер
=========

Playbook для установки Docker на ОС семейства Linux (Ubuntu, Debian, AstraLinux, CentOS, Fedora).

Требуется
----------

* Ansible 2.10 и новее
* ОС семейства Linux

Переменные
----------

ADMIN_USER - Учетная запись для подключения к серверу и для управления docker

WORK_FOLDER - каталог для размещения docker манифестов

DOCKER_COMPOSE_VERSION - Устанавливаемая версия docker compose

CENTOS_VERSION: - Версия репозитория для centos

FEDORA_VERSION: Версия репозитория для fedora
