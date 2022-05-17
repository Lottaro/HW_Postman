## HW_Postman

# **HW_Postman_1**

Создать запросы в Postman.

Protocol: http  
IP: 162.55.220.72  
Port: 5005  

Создал новую коллекцию HW_Postman_1

# **EP_1**

Method: GET                                                                                          
EndPoint: /get_method  
request url params:  
 name: str  
 age: int  
 
Создаем New Request, переименовываем в EP_1  
Метод GET, URL http://162.55.220.72:5005/get_method  
В params пишем:  
   KEY - name,  VALUE - Sergey  
   KEY - age,  VALUE - 36  
URL меняется на http://162.55.220.72:5005/get_method?name=Sergey&age=36  
Сохранияем, жмем Send  
 
Ответ  
[
    "Sergey",
    "36"
]

# **EP_2**

Method: POST  
EndPoint: /user_info_3  
request form data:  
 name: str  
 age: int  
 salary: int  
 
Создаем New Request, переименовываем в EP_2  
Метод POST, URL http://162.55.220.72:5005/user_info_3  
В body выбираем from-data и пишем:  
   KEY - name,  VALUE - Sergey  
   KEY - age,  VALUE - 36  
   KEY - salary,  VALUE - 60000  
URL не меняется   
Сохранияем, жмем Send  

Ответ  
```json
 {
    "age": "36",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "u_salary_1_5_year": 240000
    },
    "name": "Sergey",
    "salary": 60000
}
```
# **EP_3**

Method: GET  
EndPoint: /object_info_1  
request url params:  
 name: str  
 age: int  
 weight: int  

Создаем New Request, переименовываем в EP_3  
Метод GET, URL http://162.55.220.72:5005/object_info_1  
В params пишем:  
   KEY - name,  VALUE - Sergey  
   KEY - age, VALUE - 36  
   KEY - weight,  VALUE - 86  
URL меняется на http://162.55.220.72:5005/object_info_1?name=Sergey&age=36&weight=86  
Сохранияем, жмем Send  

Ответ 
```json
{
    "age": 36,
    "daily_food": 1.032,
    "daily_sleep": 215.0,
    "name": "Sergey"
}
```
# **EP_4**

Method: GET  
EndPoint: /object_info_2  
request url params:  
 name: str  
 age: int  
 salary: int  
 
Создаем New Request, переименовываем в EP_4  
Метод GET, URL http://162.55.220.72:5005/object_info_2  
В params пишем:  
   KEY - name,  VALUE - Sergey  
   KEY - age,  VALUE - 36  
    KEY - salary,  VALUE - 60000  
URL меняется на http://162.55.220.72:5005/object_info_2?name=Sergey&age=36&salary=60000   
Сохранияем, жмем Send  

Ответ 
```json
{
    "person": {
        "u_age": 36,
        "u_name": [
            "Sergey",
            60000,
            36
        ],
        "u_salary_5_years": 252000.0
    },
    "qa_salary_after_1.5_year": 198000.0,
    "qa_salary_after_12_months": 162000.0,
    "qa_salary_after_3.5_years": 228000.0,
    "qa_salary_after_6_months": 120000,
    "start_qa_salary": 60000
}
```
# **EP_5**

Method: GET  
EndPoint: /object_info_3  
request url params:  
 name: str  
 age: int  
 salary: int  
 
 Создаем New Request, переименовываем в EP_5  
 Метод GET, URL http://162.55.220.72:5005/object_info_3  
В params пишем:  
   KEY - name,  VALUE - Sergey  
   KEY - age,  VALUE - 36  
    KEY - salary,  VALUE - 60000  
URL меняется на http://162.55.220.72:5005/object_info_3?name=Sergey&age=36&salary=60000  
Сохранияем, жмем Send  

Ответ
```json
{
    "age": "36",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "pets": {
            "cat": {
                "age": 3,
                "name": "Sunny"
            },
            "dog": {
                "age": 4,
                "name": "Luky"
            }
        },
        "u_salary_1_5_year": 240000
    },
    "name": "Sergey",
    "salary": 60000
}
```

# **EP_6**

Method: GET  
EndPoint: /object_info_4  
request url params:  
 name: str  
 age: int  
 salary: int  

Создаем New Request, переименовываем в EP_6  
Метод GET, URL http://162.55.220.72:5005/object_info_4  
В params пишем:  
   KEY - name,  VALUE - Sergey  
   KEY - age,  VALUE - 36  
    KEY - salary,  VALUE - 60000  
URL меняется на http://162.55.220.72:5005/object_info_4?name=Sergey&age=36&salary=60000  
Сохранияем, жмем Send  

Ответ
```json
{
    "age": 36,
    "name": "Sergey",
    "salary": [
        60000,
        "120000",
        "180000"
    ]
}
```
# **EP_7**

Method: POST  
EndPoint: /user_info_2  
request form data:  
 name: str  
 age: int  
 salary: int  
 
Создаем New Request, переименовываем в EP_7  
Метод POST, URL http://162.55.220.72:5005/user_info_2  
В body выбираем from-data и пишем:  
   KEY - name,  VALUE - Sergey  
   KEY - age,  VALUE - 36  
   KEY - salary,  VALUE - 60000  
URL не меняется   
Сохранияем, жмем Send  
```json
{
    "person": {
        "u_age": 36,
        "u_name": [
            "Sergey",
            60000,
            36
        ],
        "u_salary_5_years": 252000.0
    },
    "qa_salary_after_1.5_year": 198000.0,
    "qa_salary_after_12_months": 162000.0,
    "qa_salary_after_3.5_years": 228000.0,
    "qa_salary_after_6_months": 120000,
    "start_qa_salary": 60000
}
```

# **HW_Postman_1**  

Создаем New Request, переименовываем в EP_2_1  
Метод GET, URL http://162.55.220.72:5005/first  

1. Отправить запрос  
Жмем *Send*  
Ответ  
```
This is the first responce from server!  
```
2. Статус код 200   
В поле тест выбираем из списка SNIPPETS *Status code is 200*, в поле ввода кода появляется:  
```js
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
Во вкладке *Test Results*  
```
PASS Status code is 200
```
3. Проверить, что в body приходит правильный string  
ответ в *body*  
```
This is the first responce from server!
```
