# Здесь будет подробная инструкция как я хочу чтобы мои тиммейты писали код

1. одна сущность - один файл
- не правильно  
```file.py```
```python
  class A:
    def __init__(self): print('object one')
  class B:
    def __init__(self): print('object two') 
```

- правильно  
```A.py```
```python
  class A:
    def __init__(self): print('object one')
 ```
```B.py```
```python
  class B:
    def __init__(self): print('object two')
 ```
### Хочу заметить что я называю файлы в которых находятся сущности названием этих самых сущностей
2.общая архитектура приложения:<pre>  
├── main  - это исполнительный файл, нужен для запуска приложения
├── package.json  - это файл конфигурации, нужен для npm run build и проч
├── scripts  - здесь мы храним все сущности, всю логику упакованную в классы и функции
│   ├── NameTwo  
│   └── NamoOne  
├── styles - здесь мы храним стили наших документов
│   └── style.css  
└── templates  - здесь мы храним все html файлы
│   └── Name.html</pre> 
