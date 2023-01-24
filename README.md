# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Buildando Dockerfile
Pode ser utilizado o comando `docker build -t conversor-temp .` para criar a imagem do nosso projeto.
Obs. conversor-temp vai ser o nome de nossa imagem, caso queira atribuir outro nome basta trocar.


### Colando imagem em um container
Adicionei um yml para facilitar a execução do container com nossa imagem, basta dar um `docker-compose up -d`.
É importante rodar com a tag -d para rodar o container como background sem travar seu terminal, depois basta dar um docker-compose down para parar o serviço.
Obs. Caso você tenha mudado o nome da image durante o build, mude a linha 4 do yml para o novo nome que você atribuiu.
