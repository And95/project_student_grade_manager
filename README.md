Project Student Grade Manager

Projeto Node para ser executado localmente por API

Método: POST

URL: http://localhost:3000/grades

Content-Type: application/json

Body(example):
{
    "studentName": "André",
    "subject": "English",
    "grade": 10
}

----------------------------------------------

Método: GET

URL: http://localhost:3000/grades

----------------------------------------------

Método: PUT

URL: http://localhost:3000/grades/:id

Content-Type: application/json

Body(example):
{
    "studentName": "André Luiz",
    "subject": "English",
    "grade": 10
}

----------------------------------------------

Método: DELETE

URL: http://localhost:3000/grades/:id

