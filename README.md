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
![image](https://github.com/Bjegsad/ansible_1/assets/91281150/475f2911-65be-4b62-9003-ff5202d62013)

8) Пуш на гит
