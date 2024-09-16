
<div align="center">
   <h2>⚜️ N E X U S ⚜️</h2>
</div>

<h3>👥 Integrantes do Grupo</h3>

- Matheus O.A.C Silva - RM 98502
- Amorgan M. Lopes - RM 98552
- Guilherme C. de Matos - RM 98874
- Gustavo G. da Silva - RM 99585
- Erick K. da Silva - RM 550371

- --------------------------------------------------
## 📚 Projeto 

<p>Bem-vindo ao Nexus. O projeto consiste no desenvolvimento de um Chatbot funcional que utiliza o WhatsApp como plataforma principal. Esse Chatbot será capaz de se integrar a diversos sistemas externos, como APIs de inteligência artificial, e-commerce, e sistemas de recomendações. Isso permitirá oferecer um atendimento personalizado e eficaz aos clientes e usuários.</p>
<p>O público-alvo do projeto Nexus são empresas que buscam soluções inovadoras para melhorar o atendimento ao cliente, aumentando assim, sua satisfação e consequentemente otimizando suas operações comerciais.</p>

<br/>

## 📋 Endpoints

#### **Usuários**
- `GET /api/Users` - Retorna todos os usuários.
- `GET /api/Users/{id}` - Retorna um usuário específico por ID.
- `POST /api/Users` - Cria um novo usuário.
- `PUT /api/Users/{id}` - Atualiza um usuário existente por ID.
- `DELETE /api/Users/{id}` - Exclui um usuário por ID.

#### **Produtos**
- `GET /api/Produtos` - Retorna todos os produtos.
- `GET /api/Produtos/{id}` - Retorna um produto específico por ID.
- `POST /api/Produtos` - Cria um novo produto.
- `PUT /api/Produtos/{id}` - Atualiza um produto existente por ID.
- `DELETE /api/Produtos/{id}` - Exclui um produto por ID.

#### **Pedidos**
- `GET /api/Pedidos` - Retorna todos os pedidos.
- `GET /api/Pedidos/{id}` - Retorna um pedido específico por ID.
- `POST /api/Pedidos` - Cria um novo pedido.
- `PUT /api/Pedidos/{id}` - Atualiza um pedido existente por ID.
- `DELETE /api/Pedidos/{id}` - Exclui um pedido por ID.


## 🚀 Deploy da Aplicação
Utilizamos o deploy integrado da IDE Visual Studio. A partir dela é possível utilizar o arquivo de Perfil de Publicação do Webapp da Azure para implementar a aplicação na plataforma de maneira prática.
Basta seguir os seguintes passos: 

1. Selecione a API clicando com o botão direito e, depois, em **Publicar**.
   
![image](https://github.com/user-attachments/assets/283210ac-b7a6-49f1-afa1-2ef59e96c561)

3. Clique em **Adicionar Perfil > Importar perfil** e importe o arquivo de Perfil de Publicação instalado a partir do Webapp da Azure.

4. Agora, basta clicar em **Publicar**.


# ⚙ Configurações da Máquina
- Sistema Operacional: Linux
- Plano F1 (1GB RAM, 1GB HDD, vCPU Compartilhada)
- Pilha de Runtime: .NET Core - 8.0
- Server: Brazil South
