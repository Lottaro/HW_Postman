## [Домашнее задание по Postman №1](#1)  
  ***  
## HW_Postman

# **HW_Postman_1** <a name="1"><a>

Создать запросы в Postman.

Protocol: http  
IP: 162.55.220.72  
Port: 5005  

Создал новую коллекцию HW_Postman_1

# **EP_1_1**

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

# **EP_1_2**

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
# **EP_1_3**

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
# **EP_1_4**

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
# **EP_1_5**

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

# **EP_1_6**

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
# **EP_1_7**

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

# **HW_Postman_2**  

# **EP_2_1**
Создаем New Request, переименовываем в EP_2_1  
Метод GET, URL http://162.55.220.72:5005/first  

**1. Отправить запрос**  
Жмем *Send*  
Ответ  
```
This is the first responce from server!  
```
**2. Статус код 200**   
В поле тест выбираем из списка SNIPPETS *Status code is 200*, в поле ввода кода появляется:  
```js
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
Во вкладке *Test Results*  
```
PASS EP_2_1. Status code is 200
```
3. Проверить, что в body приходит правильный string  
ответ в *body*  
```
This is the first responce from server!   
```   

# **EP_2_2**  
Создаем New Request, данные берем из EP_1_2  
Метод POST, http://162.55.220.72:5005/user_info_3 (EP_1_2 из HW_Postman_1)  
  
**1. Отправить запрос**  
  
Жмем *Send*  

**2. Статус код 200**   
  
В поле тест выбираем из списка SNIPPETS *Status code is 200*, в поле ввода кода появляется:  
```js
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
Во вкладке *Test Results*  
```
PASS EP_2_2. Status code is 200
```
**3. Спарсить response body в json**  
  
В окне редактирования тестов пишем:
```js
let responseData = pm.response.json();  
console.log(responseData);
```
В консольной строке смотрим ответ:  
```
{age: "36", family: {…}, name: "Sergey"…}
```
**4. Проверить, что name в ответе равно name s request (name вбить руками.)**  
  
В окне *Test scripts* выбираем *Response body: JSON value check* и и в   
окне *Tests* редактируем 1 и 3 строки, отредактировав 3 строку:  
```js
pm.test("Your test name", function () {
    pm.expect(responseData.name).to.eql("Sergey");
});
```
Во вкладке *Test Results*  
```
PASS EP_2_2. Your test name
```
**5. Проверить, что age в ответе равно age s request (age вбить руками.)**  
   
В окне *Test scripts* выбираем *Response body: JSON value check* и в   
окне *Tests* редактируем 1 и 3 строки, отредактировав строки:  
```js
pm.test("Your test name", function () {
    pm.expect(responseData.age).to.eql("36");
});
```
Во вкладке *Test Results*  
```
PASS EP_2_2. Your test Age
```
**6. Проверить, что salary в ответе равно salary s request (salary вбить руками.)**  
  
В окне *Test scripts* выбираем *Response body: JSON value check* и в   
окне *Tests* редактируем 1 и 3 строки, отредактировав строки:  
```js
pm.test("Your test salary", function () {
    pm.expect(responseData.salary).to.eql(60000);
});
```
Во вкладке *Test Results*  
```
PASS EP_2_2. Your test salary
```
**7. Спарсить request**  
  
В окне редактирования тестов пишем:  
```js
let requestData = request.data;  
console.log('request data:', requestData);
```
В консольной строке смотрим ответ:  
```
 request data: {name: "Sergey", age: "36", salary: "60000"}
 ```
**8. Проверить, что name в ответе равно name s request (name забрать из request.)**  
  
В окне *Test scripts* выбираем *Response body: JSON value check* и в   
окне *Tests* редактируем 1 и 3 строки, отредактировав строки:  
```js
pm.test("Your test name", function () {
    pm.expect(responseData.name).to.eql(requestData.name);
});
```
Во вкладке *Test Results*  
```
PASS EP_2_2. Your test name
```
**9. Проверить, что age в ответе равно age s request (age забрать из request.)**  
  
В окне *Test scripts* выбираем *Response body: JSON value check* и в   
окне *Tests* редактируем 1 и 3 строки, отредактировав строки:  
```js
pm.test("Your test age", function () {
    pm.expect(responseData.age).to.eql(requestData.age);
});
```
Во вкладке *Test Results*  
```
PASS EP_2_2. Your test age
```
**10. Проверить, что salary в ответе равно salary s request (salary забрать из request.)**  
  
В окне *Test scripts* выбираем *Response body: JSON value check* и в   
окне *Tests* редактируем 1 и 3 строки, отредактировав строки:  
```js
pm.test("Your test salary", function () {
    pm.expect(responseData.salary).to.eql(Number(requestData.salary));
});
```
Во вкладке *Test Results*  
```
PASS EP_2_2. Your test salary
```
**11. Вывести в консоль параметр family из response**  
  
В окне редактирования тестов пишем:    
```js
console.log('Family: ', responseData.family)
```
В консольной строке смотрим ответ:  
```
Family: {children: [2], u_salary_1_5_year: 240000}
```
**11.  Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)**  
  
В окне *Test scripts* выбираем *Response body: JSON value check* и в   
окне *Tests* редактируем 1 и 3 строки, отредактировав строки:  
```js
pm.test("Your test u_salary_1_5_year", function () {
    pm.expect(responseData.family.u_salary_1_5_year).to.eql(requestData.salary*4);
});
```
Во вкладке *Test Results* 
```
PASS EP_2_2. Your test u_salary_1_5_year
```
  
# **EP_2_3**  
Создаем New Request, данные берем из EP_1_5  
Метод GET, http://162.55.220.72:5005/object_info_3 (EP_1_5 из HW_Postman_1)  
  
  **1. Отправить запрос**  
  
Жмем *Send*  
  
**2. Статус код 200**   
  
В поле тест выбираем из списка SNIPPETS *Status code is 200*, в поле ввода кода появляется:  
```js
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```
Во вкладке *Test Results*  
```
PASS EP_2_3. Status code is 200
```
**3. Спарсить response body в json**  
  
В окне редактирования тестов пишем:
```js
let responseData = pm.response.json();  
console.log(responseData)
```
В консольной строке смотрим ответ:
```
{age: "36", family: {…}, name: "Sergey"…}
```
**4. Спарсить request**  
  
В окне редактирования тестов пишем:
```js
let requestData = pm.request.url.query.toObject();
console.log(requestData)
```
В консольной строке смотрим ответ:
```
{name: "Sergey", age: "36", salary: "60000"}
```
**Проверить, что name в ответе равно name s request (name забрать из request.)**  
  
В окне *Test scripts* пишем:  
```js
pm.test("Your test name", function () {
    pm.expect(responseData.name).to.eql(requestData.name);
});
```
Во вкладке *Test Results*  
```
PASS EP_2_3. Your test name
```
**6. Проверить, что age в ответе равно age s request (age забрать из request.)**  
  
В окне *Test scripts* пишем:  
```js
pm.test("EP_2_3. Your test age", function () {
    pm.expect(responseData.age).to.eql(requestData.age);
});
```
Во вкладке *Test Results*  
```
PASS EP_2_3. Your test age
```
**7. Проверить, что salary в ответе равно salary s request (salary забрать из request.)**  
  
В окне *Test scripts* пишем:  
```js
pm.test("EP_2_3. Your test salary", function () {
    pm.expect(responseData.salary).to.eql(Number(requestData.salary));
});
```
Во вкладке *Test Results*  
```
PASS EP_2_3. Your test salary
```
