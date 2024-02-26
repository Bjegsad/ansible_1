# ansible_1
1) Устанавливаем ansible при помощи команды
  sudo apt install ansible 
2) В настройках виртуалки ставим сеть виртуальный адаптер хоста и сеть NAT, а также пробрасываем порты
3) Создаем файл html и плейбук yaml:
   <br>mkdir ansible_project
   <br>nano playbook.yaml (заполняю разметку yaml)
   <br>nano index.html (копирую html стартовой страницы википедии)
6) Запускаю ansible скрипт
   <br>sudo ansible-playbook playbook.yaml
7) проверяю работу скрипта, открывая в браузере 127.0.0.1
![Screenshot from 2024-02-20 23-41-51](https://github.com/Bjegsad/ansible_proj/assets/91281150/d8684f1b-8454-4523-a9fa-77a22faf08f1)
8) Пуш на гит
