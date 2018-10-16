# Работа с файловой системой

**https://api.scorocode.ru/fs/api/v2/files/{pathToFile}**

### Загрузка файла
Метод: `GET`

**Ответы:**

!!! success "Выполнено"
   
   ```200: application/*
    
    image/*
    
    text/plain    
    ```

!!! failure "Ошибка"
	
	```404 application/json
    
    500 application/json
    ```

### Обновление файла    
Метод: `POST`

!!! success "Выполнено"
    ```
    200: application/json   
    ```

!!! failure "Ошибка"
	 ```
    400 application/json
    500 application/json
    ```

### Переименование файла
Метод: `PUT`

!!! success "Выполнено"
    ```
    200: application/json   
    ```

!!! failure "Ошибка"
	 ```
    400 application/json
    500 application/json
    ```

### Удаление файла
Метод: `DELETE`

!!! success "Выполнено"
    ```
    200: application/json   
    ```

!!! failure "Ошибка"
	 ```
    500 application/json
    ```
    
## Работа с каталогами

**https://api.scorocode.ru/fs/api/v2/folders/{pathToFile}**

### Получение информации о каталоге
Метод: `GET`

!!! success "Выполнено"
    ```
    200: application/json   
    ```

!!! failure "Ошибка"
	 ```
    500 application/json
    ```
### Создание нового каталога
Метод: `POST`

!!! success "Выполнено"
    ```
    200: application/json   
    ```

!!! failure "Ошибка"
	 ```
    500 application/json
    ```
### Переименование каталога   
   Метод: `PUT`

!!! success "Выполнено"
    ```
    200: application/json   
    ```

!!! failure "Ошибка"
	 ```
	 400 application/json
    500 application/json
    ```    
### Удаление каталога    
    Метод: `DELETE`

!!! success "Выполнено"
    ```
    200: application/json   
    ```

!!! failure "Ошибка"
	 ```
    500 application/json
    ```
