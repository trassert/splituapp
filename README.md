**splituapp** это python приложение которое распаковывает прошивку в формате **update.APP**.

Чтобы извлечь все файлы img:  
```
splituapp -f update.app
``` 
Извлекать только system.img и boot.img:  
```
splituapp -f update.app -l system boot
```

Вы можете запустить `./splituapp -h` на Linux или `python splituapp -h` (Windows), чтобы получить инструкции по использованию для операционной системы, на которой вы работаете.  
Проверка **CRC** под Windows пока не работает (исх.)
