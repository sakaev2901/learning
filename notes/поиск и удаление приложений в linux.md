**links**: [[linux]]
**tags**:


Поиск всех пакетов локально: 
```
dpkg -l
```

Удаление программы

Поиск всех файла пакета 
```
dpkg -L deluge
```

Принадлежность файла к пакету 
 ```
 dpkg -S путь
 ```

Простое удаление пакета (оставляет конфигурационные файлы)
```
sudo apt-get remove apt
```

Удаление всего 
```
sudo apt-get purge apt
```

Удаление ненужных компонентов 
```
sudo apt-get autoremove
```

Удаляет все не установленные пакеты (/var/cache/apt/archives/)
```
sudo apt-get autoclean
```

Удаляет все пакеты (/var/cache/apt/archives/)
```
sudo apt-get clean
```

Переустановить пакет
```
sudo apt-get --reinstall install apt
```

Обновление всех пакетов безопасным способом (учитывает обратные совместимости)
```sudo apt-get upgrade```

?
```sudo apt-get dist-upgrade```

Обновление списков репозиториев (sourcelist)
```sudo apt-get update```

Установка скачанного
```dpkg -i name.deb```

Подкачка недостающих пакектов
```sudo apt-get -f install ```

От каких пакетов зависит пакет
`apt-cache depends apt`

Какие пакеты зависят от него
`apt-cache rdepends apt`

---
#### source: 
---
2020-12-05
