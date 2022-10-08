# kata_postman

Request:
![изображение](https://user-images.githubusercontent.com/81150853/194700549-a795d30b-9262-4d09-afc8-d5e916e8818f.png)



Response:
{
    "user": {
        "username": "artem",
        "email": "artem@mail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNDE0MjVjM2NmNzA1MWIwMDgyYWI4ZCIsInVzZXJuYW1lIjoiYXJ0ZW0iLCJleHAiOjE2NzA0MDUyMTIsImlhdCI6MTY2NTIyMTIxMn0.WksjWbQrmf2zfyEwK0g8-Jr8ezodrCG-lvj5wxGsLuQ"
    }
}





Request:
![изображение](https://user-images.githubusercontent.com/81150853/194700629-5718f7b6-1ae3-4328-a9e2-08381bb88975.png)



Response:
{
    "user": {
        "username": "artem",
        "email": "artem@mail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNDE0MjVjM2NmNzA1MWIwMDgyYWI4ZCIsInVzZXJuYW1lIjoiYXJ0ZW0iLCJleHAiOjE2NzA0MDUzNzcsImlhdCI6MTY2NTIyMTM3N30.6cHZ1mbeDZa2dW0F2DxSoiVOpNKZXNPPKy07nBBzjfI"
    }
}





Request (using token from previous response as authorization header):
![изображение](https://user-images.githubusercontent.com/81150853/194700784-e3f4e36f-aa7e-43c3-bd6f-9284c1139ee0.png)



Response:
{
    "user": {
        "username": "artem",
        "email": "artem@mail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNDE0MjVjM2NmNzA1MWIwMDgyYWI4ZCIsInVzZXJuYW1lIjoiYXJ0ZW0iLCJleHAiOjE2NzA0MDU0OTYsImlhdCI6MTY2NTIyMTQ5Nn0.ce1xn5hUd2rDpNg6iE00OmKjhDykCHeEd51l4rXz1Cw"
    }
}
