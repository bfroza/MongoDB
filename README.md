# Sistema de Cadastro de Usuários

## Desenvolvido por Bruno Froza e Marcio Lima

Este sistema foi desenvolvido para realizar operações CRUD (Create, Read, Update, Delete) de usuários. Ele utiliza integração com o banco de dados MongoDB, por meio do mongoose, e é compatível com HTML para interface de usuário.

### Funcionalidades Implementadas

1. **Cadastro de Usuários:**
   - Abra o arquivo `index.html` para acessar a tela de cadastro.
   - A tela de cadastro possui formulários com validações de CPF, e-mail, etc.
   - Preencha os campos necessários e submeta o formulário. Os dados serão enviados em formato JSON para o banco de dados.

2. **Visualização de Usuários:**
   - Existe uma tela para visualizar todos os usuários cadastrados.
   - É possível filtrar os usuários por nome, se necessário.

3. **Atualização de Informações:**
   - Na tela de visualização de usuários, há dois ícones disponíveis.
   - Um ícone permite atualizar as informações do usuário.
   - Ao clicar neste ícone, você será redirecionado para outra página com os mesmos formulários de validação.
   - Após fazer as alterações desejadas, clique no botão para enviar as informações atualizadas para o banco de dados.

4. **Exclusão de Usuários:**
   - Na tela de visualização de usuários, há um ícone para excluir o usuário.
   - Ao clicar neste ícone, será exibida uma confirmação para garantir que deseja excluir o usuário.
   - Confirmando a exclusão, o usuário será removido do banco de dados.

### Como Usar

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter o MongoDB instalado e em execução.
3. Abra o arquivo `index.html` em seu navegador para começar a usar o sistema.
4. Explore as diferentes funcionalidades disponíveis e gerencie os usuários conforme necessário.

### Dependências do Projeto

Certifique-se de ter as seguintes dependências instaladas para executar o projeto e os testes:

```bash
npm install --save-dev @babel/core @babel/preset-env babel-jest
npm test para rodar os testes unitários
