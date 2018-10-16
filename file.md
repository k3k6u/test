# Работа с файловой системой

**https://api.scorocode.ru/fs/api/v2/files/{pathToFile}**

### Загрузка файла
Метод: `GET`

**Ответы:**

!!! success "Выполнено"
   
```markdown
200: application/*
image/*  
text/plain    
```

!!! failure "Ошибка"
	
```markdown 
404 application/json    
500 application/json
```

### Обновление файла    
Метод: `POST`

!!! success "Выполнено"

```markdown
200: application/json   
```

!!! failure "Ошибка"

```markdown	 
400 application/json
500 application/json
```

### Переименование файла
Метод: `PUT`

!!! success "Выполнено"

```markdown
200: application/json   
```

!!! failure "Ошибка"

```markdown
400 application/json
500 application/json
```

### Удаление файла
Метод: `DELETE`

!!! success "Выполнено"

```markdown
200: application/json   
```

!!! failure "Ошибка"

```markdown
500 application/json
```
    
## Работа с каталогами

**https://api.scorocode.ru/fs/api/v2/folders/{pathToFile}**

### Получение информации о каталоге
Метод: `GET`

!!! success "Выполнено"

```markdown
200: application/json   
```

!!! failure "Ошибка"

```markdown
500 application/json
```
### Создание нового каталога
Метод: `POST`

!!! success "Выполнено"

```markdown
200: application/json   
```

!!! failure "Ошибка"

```markdown
500 application/json
```
### Переименование каталога   
Метод: `PUT`

!!! success "Выполнено"

```markdown
200: application/json   
```

!!! failure "Ошибка"

```markdown
400 application/json
500 application/json
```    
### Удаление каталога    

Метод: `DELETE`

!!! success "Выполнено"
```markdown
200: application/json   
```

!!! failure "Ошибка"
```markdown
500 application/json
```
