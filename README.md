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
   В KEY пишем строки name и age
   В VALUE пишем Sergey и 36
 Сохранияем, жмем Send
 
 Ответ
 [
    "Sergey",
    "36"
]
