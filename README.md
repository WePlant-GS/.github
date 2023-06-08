![Design do Aplicativo](WePlantCapa.png)

O WePlant é um aplicativo voltado para auxiliar moradores de comunidades na prática da agricultura vertical. A agricultura vertical é uma técnica que permite o cultivo de plantas em espaços reduzidos, aproveitando a verticalidade dos ambientes urbanos. O objetivo do WePlant é fornecer suporte e orientação aos agricultores urbanos, ajudando-os a otimizar o uso de recursos, gerenciar suas plantações e maximizar a produção de alimentos.

<br/>

# <span style="color: #63C71F;">Tecnologias Utilizadas</span>

          
<div align="center">
    <img align="center" alt="weplant-html5" height="40" width="12%" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" />
    <img align="center" alt="weplant-java" height="40" width="12%" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original-wordmark.svg" />
    <img align="center" alt="weplant-react" height="40" width="12%" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original-wordmark.svg" />
    <img align="center" alt="weplant-illustrator" height="40" width="12%" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original-wordmark.svg" />
    <img align="center" alt="weplant-nodejs" height="40" width="12%" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original-wordmark.svg" />
    <img align="center" alt="weplant-nodejs" height="40" width="12%" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" />


</div>

<br/>

<br/>

# <span style="color: #63C71F;">Configuração e Execução </span>

Para executar o aplicativo em um ambiente de desenvolvimento, siga as instruções abaixo conforme cada tecnologia:

-
-
-
-

<br/>

# <span style="color: #63C71F;">Endpoints </span>

## Adicionar novo post
Requisição: POST /posts/add/user/{id}

 **Body:**
 
    ```json
    {
    "username": "USERNAME_DO_USUARIO",
    "password": "SENHA_DO_USUARIO"
    }
    ```
    <br/>

## Buscar post por ID

Requisição: GET /posts/{id}
Exemplo de uso: GET /posts/456

    ``json
    {
      "id": 456,
      "title": "Título do post",
      "content": "Conteúdo do post"
    }
    ``` 
 <br/>
    
## Buscar todos os comentários de um post

Requisição: GET /posts/{id}/comments/all

Exemplo de uso: GET /posts/789/comments/all?page=2&size=10

    ``json
            {
          "content": [
            {
              "id": 1,
              "postId": 789,
              "text": "Comentário 1"
            },
            {
              "id": 2,
              "postId": 789,
              "text": "Comentário 2"
            }
          ],
          "page": 2,
          "size": 10,
          "totalElements": 20,
          "totalPages": 2
        }

     ```
 
  <br/>

## Adicionar novo comentário a um post

Requisição: POST /posts/{id}/comments/add

``json
{
  "text": "Conteúdo do comentário"
}
``


Exemplo de uso: POST /posts/789/comments/add
Resposta: 204 No Content

## Excluir post por ID

Requisição: DELETE /posts/{id}/del
Exemplo de uso: DELETE /posts/456/del
Resposta: 204 No Content

## Excluir comentário por ID

Requisição: DELETE /posts/{id}/comments/{commentId}/del
Exemplo de uso: DELETE /posts/789/comments/1/del
Resposta: 204 No Content

# <span style="color: #63C71F;">Equipe</span>

     A equipe responsável por esse projeto é composta por:

- <span style="color: #63C71F;">RM: 93915 - Jaelson dos Santos </span> 
- <span style="color: #63C71F;">RM: 94311 - Marcos Bilobram </span> 
- <span style="color: #63C71F;">RM: 96320 - Nathália Maia </span> 
- <span style="color: #63C71F;">RM: 94972 - Rafaela da Silva </span> 

        Cada membro da equipe desempenha um papel fundamental no desenvolvimento e no sucesso do projeto, contribuindo com suas habilidades e conhecimentos na área de tecnologia.

<br/>

# <span style="color: #63C71F;">Considerações Finais</span>

        O desenvolvimento do WePlant é um projeto realizado como parte da prova semestral da faculdade FIAP, com o tema "Combate à fome através da agricultura sustentável".

        A equipe se empenhou para criar uma solução eficiente e inovadora, que visa promover a segurança alimentar, incentivar a agricultura sustentável e combater a fome nas comunidades.

O projeto WePlant está disponível na íntegra, incluindo todos os códigos-fonte e entregas, na organização do GitHub: 
[https://github.com/WePlant-GS].

<br/>

# <span style="color: #63C71F;">Licença</span>
Este projeto está licenciado sob a MIT License.
