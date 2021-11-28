# Cities API

## Como rodar o projeto
1. Fazer o clone do projeto
2. Importar o projeto no intellij
3. Rodar o comando do docker para criar o container do banco postgres
    ```shell script
    docker run --name cities-db -d -p 5432:5432 -e POSTGRES_USER=postgres_user_city -e POSTGRES_PASSWORD=super_password -e POSTGRES_DB=cities postgres
    ```
4. Executar classe ```CitiesApplication``` no Intellij
5. Acessar url com a api swagger http://localhost:8080/swagger-ui.html