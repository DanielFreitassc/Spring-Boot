# Spring boot ☕🤓🎓
## Nesse projeto utilizo [Spring boot initializr](https://start.spring.io),[Apidog](https://apidog.com/?utm_source=google_search&utm_medium=g&utm_campaign=18544428894&utm_content=153517438552&utm_term=api%20dog&gad=1&gclid=Cj0KCQjwm66pBhDQARIsALIR2zByk8BoUb-Ct4gCbDc7nmFPbEMg7VLDOFS5o_C2jU6iul_qX712KoQaAvsyEALw_wcB),[H2 Database Engine](https://www.h2database.com/html/main.html).

## Initializr que utilizei.
```
https://start.spring.io/#!type=maven-project&language=java&platformVersion=3.0.11&packaging=jar&jvmVersion=17&groupId=com.dan&artifactId=toDolist&name=toDolist&description=Gerenciador%20de%20arquivos&packageName=com.dan.toDolist&dependencies=web](https://start.spring.io/#!type=maven-project&language=java&platformVersion=3.0.11&packaging=jar&jvmVersion=17&groupId=com.dan&artifactId=toDolist&name=toDolist&description=Gerenciador%20de%20arquivos&packageName=com.dan.toDolist&dependencies=web)https://start.spring.io/#!type=maven-project&language=java&platformVersion=3.0.11&packaging=jar&jvmVersion=17&groupId=com.dan&artifactId=toDolist&name=toDolist&description=Gerenciador%20de%20arquivos&packageName=com.dan.toDolist&dependencies=web
```
# Passo para criat um new request no Apidog
- Abra seu api dog
- Faça login
- Clique em My Project
- Deixe o mouse descansando em cima do ``+`` 
- Escolha new request
- Bote o URL que vc quer fazer está nova request no meu caso é ``http://localhost:8080/users/``
- Selecione o método ``POST``
- Em body selecione ``JSON``
- Exemplo de estrutura JSON utilizada por mim.
  
# Caminho utilizado para a rota de users
```
http://localhost:8080/users/
```
# Exemplo de JSON utilizado por mim para fazer o POST.
```
{
    "name": "xxx",
    "username": "xxx",
    "password": "xxx"
}
```
# Aqui foi utilizado outro caminho.
```
http://localhost:8080/tasks/
```
```
{
    "description":"spring boot é perfeito",
    "title": "Fazendo um spring legal",
    "priority":"ALTA",
    "startAt": "2024-02-08T12:20:00",
    "endAt": "2024-02-07T15:44:00",
    "idUser": "12999827-0edf-466e-8d6a-4c3caf37b9fe"
}
```
