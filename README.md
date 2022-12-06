# Universidade Estadual de Campinas
# Instituto da Computação

## Disciplina: MC855-2s2022

#### Professor e Assistente

| Nome                     | Email                   |
| ------------------------ | ------------------------|
| Professora Juliana Borin | jufborin@unicamp.br     |
| Assistente Paulo Kussler | paulo.kussler@gmail.com |


#### Equipe

| Nome               | RA               | Email                      | ID Git                |
| ------------------ | ---------------- | -------------------------- |---------------------- |
| Beatriz Azanha     | 213518           | beatrizdazanha@gmail.com   | beatrizazanha         |
| Daniel Oliveira    | 169400           | olainternet97@gmail.com    | danielNorbitt         |
| Gabriel Branco     | 197197           | gabrielbcbranco@gmail.com  | gabrielbcbranco       |
| Ivan Korsakov      | 199344           | ivan.korsakov2@gmail.com   | Ivan-Korsakov         |
| Patricia Amado     | 223085           | p223085@dac.unicamp.br     | p223085               |
| Vitor Moriya       | 188404           | vitorjmoriya@gmail.com     | vitorjmoriya          |
| Thaissa Rojas      | 224714           | thay.rojasp@gmail.com      | thaissarojas          |

### Descrição do projeto:

#### Vem.de pix
A Vem.de Pix é uma plataforma de vendas digital sem taxa via PIX, direcionada a entidades universitárias e vendedores independentes.


#### Prints das telas com descrição das funcionalidades. 


#### Tecnologias, ferramentas, dependências, versões. etc. 


Front-End desenvolvido em: Angular Material 14.2.0;
                           Typescript 4.7.2


Back-End desenvolvido em: Java 8;
                          Spring Boot 2.7.3;
                          PostgreSQL 42.5.0;
                          Google Cloud Plataform.
    
    
Mobile desenvolvido em: Swift 5.5 (mínimo iOS 15);
                        Ruby 3.1.2


Gerador código PIX desenvolvido em JavaScript.


#### Ambientes
#### Como colocar no ar, como testar, etc

Para testar a aplicação é preciso rodar o banco localmente, para isso, copie o arquivo '.env.example' e renomei-o pra '.env'. Em seguida, vá no arquivo 'application.yml' e colocar no campo url a url do banco com as credenciais q estao no arquivo '.env' (o padrão da url é jdbc:postgresql://localhost:5432/POSTGRES_DB?user=POSTGRES_USER$password=POSTGRES_PASSWORD). 
Por fim, é só rodar './mvnw -DskipTests spring-boot:run' que a aplicação estará rodando na localhost:8080.

Para testar o front da aplicação é necessário ter instalado node.js e seguir as instruções do README do repositório frontend.

Para testar a aplicação em iOS é necessário ter Xcode, pelo menos, na versão 14.0 e seguir as instruções do README do repositório mobile.
