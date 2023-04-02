<p align="center">
  <img width="500" src="src/logoOnebitflix.svg">
</p>

#

## Nessa parte do projeto tem o planejamento do banco de dados, seus endpoints, sua API e seu painel administrativo.

### Alguns campos que meu modelo utiliza:

+ Nome
+ Descrição
+ user_id
+ Imagens
+ Videos
+ Tempo em exibição
+ Lançamentos

### Campos do usuário que meu modelo utiliza:
+ Name
+ Email
+ CPF
+ Birth
+ Token de acesso
+ Favoritos
+ Likes

### Além do CRUD, implementei outras funcionalidades como:

* Todo um sistema de verificação para validar formulários com mensagens personalizadas.
* Perfil editável.
* Login com web Json token para proteção das rotas.

### Tecnologias usadas e sua versão: 

<table>
  <tr>
    <td>Typescript</td>
    <td>Adminjs</td>
    <td>Express</td>
    <td>Sequelize</td>
    <td>Postgre</td>
    <td>JsonwebToken</td>
  </tr>
  <tr>
    <td>4.5</td>
    <td>5.5</td>
    <td>4.17.2</td>
    <td>6.13</td>
    <td>8.7.1</td>
    <td>8.5.1</td>
  </tr>
</table>
