Простой кубер кластер, с сетью Flannel с стандартной подсетью. Исключительно для тестирования новых серверов.
```
ansible-playbook -i hosts.yml all.yml --tags master_up,worker_up,worker_join
```
три тэга для ясности
