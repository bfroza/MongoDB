# Sistema de Cadastro de Usuários

## Desenvolvido por Bruno Froza e Marcio Lima

Este sistema foi desenvolvido para realizar operações CRUD (Create, Read, Update, Delete) de usuários. Ele utiliza integração com o banco de dados MongoDB, por meio do mongoose, e é compatível com HTML para interface de usuário.

### Funcionalidades Implementadas
1. **Início:**
   - Abra o arquivo `index.html` para acessar a página principal do trabalho.
   - Todos as páginas do trabalho possuem uma nav-bar que direciona as devidas funcionalidades
2. **Cadastro de Usuários:**
   - Clique no opção cadastro da nav-bar
   - A tela de cadastro possui formulários com validações de CPF, e-mail, etc.
   - Preencha os campos necessários e submeta o formulário. Os dados serão enviados em formato JSON para o banco de dados.

3. **Visualização de Usuários:**
   - Existe uma tela para visualizar todos os usuários cadastrados.
   - É possível filtrar os usuários por nome e iniciais, se necessário.

4. **Atualização de Informações:**
   - Na tela de visualização de usuários, há dois ícones disponíveis.
   - Um ícone permite atualizar as informações do usuário.
   - Ao clicar neste ícone, você será redirecionado para outra página com um formulário para a atualização dos dados, esses formulários a mesma validação do cadastro.
   - Após fazer as alterações desejadas, clique no botão `Atualizar` para enviar as informações atualizadas para o banco de dados.

5. **Exclusão de Usuários:**
   - Na tela de visualização de usuários, há um ícone para excluir o usuário.
   - Ao clicar neste ícone, será exibida uma confirmação para garantir que deseja excluir o usuário.
   - Confirmando a exclusão, o usuário será removido do banco de dados.

### Como Usar

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter o MongoDB instalado e em execução.
3. Para inciar o banco escreva no terminal ```node index.js```
4. Abra o arquivo `index.html` em seu navegador para começar a usar o sistema.
5. Explore as diferentes funcionalidades disponíveis e gerencie os usuários conforme necessário.

### Dependências do Projeto

Certifique-se de ter as seguintes dependências instaladas para executar o projeto e os testes:

```bash
npm install mongodb
npm install mongoose
npm install express
npm install jest
npm install --save-dev @babel/core @babel/preset-env babel-jest
npm test <!-- Para rodar os testes unitários -->
```
