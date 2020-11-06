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
