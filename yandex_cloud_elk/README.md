# Ansible Collection - my_own_collection

## Модули

- [my_own_module.py](https://github.com/PetrMezentsev/my_own_collection/blob/main/yandex_cloud_elk/plugins/modules/my_own_module.py) - Модуль, создающий файл с заданным содержимым

## Роли

- [role_for_test_module](https://github.com/PetrMezentsev/my_own_collection/tree/main/yandex_cloud_elk/roles/role_for_test_module) - Роль, выполняющая создание файла и наполнение его содержимым. Содержимое файла можно настроить в [tasks](https://github.com/PetrMezentsev/my_own_collection/blob/main/yandex_cloud_elk/roles/role_for_test_module/tasks/main.yml)

## Плэйбуки

- [site.yml](https://github.com/PetrMezentsev/my_own_collection/blob/main/yandex_cloud_elk/site.yml) - Playbook для роли single_task_role
