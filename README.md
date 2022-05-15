# HW_Postman

**HW_1**

Создать запросы в Postman.

Protocol: http  
IP: 162.55.220.72  
Port: 5005  

Создал новую коллекцию HW_Postman_1_1, вписываем в URL http://162.55.220.72:5005 и сохраняем

# **EP_1**

Method: GET                                                                                          
EndPoint: /get_method  
request url params:  
 name: str  
 age: int  
 
Создаем New Request, переименовываем в EP_1  
Метод GET, URL http://162.55.220.72:5005/get_method  
В params пишем:  
   KEY - name  VALUE - Sergey  
   KEY - age  VALUE - 36  
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
   KEY - name  VALUE - Sergey  
   KEY - age  VALUE - 36  
   KEY - salary  VALUE - 60000  
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
   KEY - name  VALUE - Sergey  
   KEY - age  VALUE - 36  
   KEY - weight  VALUE - 86  
URL меняется на http://162.55.220.72:5005/object_info_1?name=Sergey&age=36&weight=86  
Сохранияем, жмем Send  

Ответ  
{
    "age": 36,
    "daily_food": 1.032,
    "daily_sleep": 215.0,
    "name": "Sergey"
}

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
   KEY - name  VALUE - Sergey  
   KEY - age  VALUE - 36  
    KEY - salary  VALUE - 60000  
URL меняется на http://162.55.220.72:5005/object_info_2?name=Sergey&age=36&salary=60000   
Сохранияем, жмем Send  

Ответ  
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

# **EP_5**
