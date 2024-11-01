# HW01
### Сервера:
```
team-35-jn
team-35-nn
team-35-dn-00
Team-35-dn-01
```

### Установка
1. Заходим на ```team-35-jn``` под пользователем ```team```.
2. Устанавливаем ```ssh-keygen``` в ```.ssh/id_ed25519```
```
ssh-keygen
```

3. Загружаем репозиторий (предварительно добавляем открытый ключ в репозиторий) и копируем в домашнюю директорию
```
git clone git@github.com:EkaterinaAdishcheva/BIG_DATA_HW01.git
mv BIG_DATA_HW01/* .
```            

4. Запускаем установочный скрипт, во время установки нужно указывать пароль ```team```:
```
bash install_hadoop.sh
```


Интерфейс ```hadoop```: http://176.109.91.34:9870/

