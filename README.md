# Репозиторий для Pull request

## Работа с удаленным репозиторием

* Для загрузки данных в удаленный репозиторий сначала нужно к нему подключиться. Для этого нужно иметь аккаунт на [github.com](https://github.com/). Чтобы связать свой локальный репозиторий с удаленным, нужно выполнить команду 
```
git remote add origin https://github.com/"путь до вашего репозитория"
```
* Когда мы подключились к удаленному репозиторию, можно отправить на него локальный файл. Отправка осуществляется с помощью команды `push`, которая имеет 2 параметра: имя удаленного репозитория (origin) и ветку, в которую вносим изменения (по умолчанию master). 
```
git push origin master
```
* Для клонирования удаленного репозитория к себе необходимо выполнить команду `clone`
```
git clone https://github.com/"путь до репозитория"
```
* Для получения информации об изменениях удаленного репозитория используется команда `pull`
```
git pull origin master
```
