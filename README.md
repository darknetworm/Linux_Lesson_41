# Linux_Lesson_41
## Dinamic web
### Описание репозитория
Лабораторный стенд с использованием динамических систем управления контентом веб-приложений.

- **Vagrantfile** - создает виртуальную машину на основе Ubuntu 20.04 с тремя типами систем динамического управления содержимым сайта: WordPress, Django и Node.js.
- **provision.yml** - основной файл Ansible playbook для установки и настройки виртуальной машины стенда.
> [!IMPORTANT]
> В системе WordPress используется СУБД mysql. Для ее настройки с помощью ansible playbook на хостовую машину необходимо добавить библиотеку для работы с СУБД:
> 
    ansible-galaxy collection install community.mysql
- **hosts** - файл для быстрого доступа к виртуальной машине из playbook.


![php](https://github.com/darknetworm/Linux_Lesson_41/assets/82410807/a85080e5-7a6f-42b6-a7a6-02b0a4ea80dc)

![python](https://github.com/darknetworm/Linux_Lesson_41/assets/82410807/79e5fdb9-bc61-4858-ae7a-125a72e5a5ef)

![js](https://github.com/darknetworm/Linux_Lesson_41/assets/82410807/09b3ac4c-e6af-4064-b7c7-14343008b0b0)
