

# TodoList - API with SpringBoot

REST API developed using Java principles and naming conventions, along with SpringBoot.

Deployment URL: https://todolist-5h1j.onrender.com

Use a client tool to consume the REST API, such as Postman or Insomnia.

## Routes

There are essentially two routes. The POST route **/_users_/**, where there is only one endpoint for user registration, with the following request body:

![](https://t9011727272.p.clickup-attachments.com/t9011727272/96c523a0-422b-45e7-9cb2-4e1d38b250c1/image.png)

The other route in the application is **/_tasks_/**, which includes GET, POST, and PUT requests. For all requests, basic authentication should be provided using the username and password of the previously created user, as shown in the example below:

![](https://t9011727272.p.clickup-attachments.com/t9011727272/0019e375-401a-46d5-8f44-c65946618c0b/image.png)

In the request body, attributes should be passed depending on the type of request, as demonstrated in the examples below:

**POST**

![](https://t9011727272.p.clickup-attachments.com/t9011727272/1c5e985b-92f9-430a-b71d-f06e4d81a66f/image.png)

**GET**

No attributes are required in the body.

**PUT**

You can pass any attribute (one or more) from the task class that you want to update, as shown in the example below:

![](https://t9011727272.p.clickup-attachments.com/t9011727272/f580ce72-02fe-4c49-9ed2-be5c3053b8c3/image.png)





# TodoList - API com SpringBoot Portuguese

  

API Rest desenvolvida utilizando os princípios e padrões de nomenclatura do Java, juntamente com o SpringBoot.

Url de Deploy: https://todolist-5h1j.onrender.com

Utilizar uma ferramenta client para consumo de API REST como Postman ou Insomnia.

  

## Rotas

  

Basicamente, temos duas rotas. A rota POST **/_users_/**, onde temos apenas um ENDPOINT para cadastro de usuário, com o seguinte corpo de request:

  

![](https://t9011727272.p.clickup-attachments.com/t9011727272/96c523a0-422b-45e7-9cb2-4e1d38b250c1/image.png)

  

A outra rota da aplicação é a rota **/_tasks_/**, possuindo requisições GET, POST e PUT. Em todas as requisições, deve ser passado como autenticação básica o userName e a senha do usuário previamente criado, como no exemplo abaixo:

  

![](https://t9011727272.p.clickup-attachments.com/t9011727272/0019e375-401a-46d5-8f44-c65946618c0b/image.png)

  

Já no body da request será passado atributos dependendo do tipo de requisição, como é demonstrado nos exemplos abaixo:

  

**POST**

![](https://t9011727272.p.clickup-attachments.com/t9011727272/1c5e985b-92f9-430a-b71d-f06e4d81a66f/image.png)

  

**GET**

  

Não necessita de atributos no body.

  

**PUT**

  

Pode ser passado qualquer atributo (1 ou mais) da classe tasks que queira atualizar, como no exemplo abaixo:

![](https://t9011727272.p.clickup-attachments.com/t9011727272/f580ce72-02fe-4c49-9ed2-be5c3053b8c3/image.png)
