< [на главную](/readme.md)
# Установка и настройка для Windows


## Установка
Скачайте установщик с [git-scm.com](https://git-scm.com/downloads/win). На сайте есть три версии:

* стандартная 32-разрядная версия с последней сборкой;
* автономная версия для установки Git без подключения к интернету;

* портативный установщик для загрузки на флешку.
Во время установки следуйте предложенным шагам и оставляйте настройки по умолчанию. 

Убедитесь, что у вас отмечены следующие пункты:

* Use Git Bash as default shell — выберите программу Git Bash;
* Integrate Git with the Windows Shell — согласитесь работать с Git через командную строку.

## Настройка

После установки Git запустите Git Bash. В этих программах выполняются все команды.

В командной строке укажите имя и почту — это данные, по которым с вами могут связаться другие разработчики для обсуждения коммитов. То есть каждый ваш коммит будет подписан введённым ником и email-адресом.

Имя и фамилию нужно писать латиницей, через пробел, в кавычках:

```
git config --global  user.name "Name Surname"
```

Почту записываем в кавычках:

```
git config --global  user.email "your@email"
```