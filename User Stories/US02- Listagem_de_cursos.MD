=====================================================================================
# 👨🏻‍👩🏻‍👦🏻‍👦🏻 User Stories
=====================================================================================
# US - 2: Listar Cursos Disponíveis

## Funcionalidade: Visualizar Lista de Cursos

**Como** usuário da aplicação Desafio de QA Beedoo  
**Quero** acessar a lista de cursos disponíveis  
**Para que** eu possa visualizar e gerenciar os cursos cadastrados

### Critérios de Aceitação

1. **Acesso à Lista de Cursos**
   - O usuário deve acessar a lista de cursos ao clicar no botão do menu "Listar Cursos".

2. **Exibição de Cursos**
   - **Sem Cursos Cadastrados:**
     - Se não houver cursos cadastrados, exibir uma tela com a mensagem "Não existem cursos cadastrados".
   - **Com Cursos Cadastrados:**
     - Exibir os cursos em formato de cards com tamanho padrão.
     - Cada card deve ter um botão "Excluir curso".
     - Ao clicar no botão "Excluir curso", exibir a mensagem "Curso excluído com sucesso".

3. **Ordenação dos Cursos**
   - Os cursos devem ser exibidos por padrão em ordem de data de criação.
   - O usuário deve ter a opção de ordenar os cursos por data de criação ou em ordem alfabética.

4. **Impossibilidade de Edição**
   - O usuário não deve ter a opção de editar os cursos diretamente na lista.

### Contexto

**Dado** que o usuário está na plataforma   
**Quando** o usuário navega para a página de lista de cursos  
**E** há cursos cadastrados  
**Então** os cursos são exibidos em formato de cards  
**E** o usuário pode ordenar os cursos por data de criação ou ordem alfabética  
**E** pode clicar no botão "Excluir curso" em cada card  
**E** após a exclusão, uma mensagem de confirmação "Curso excluído com sucesso" é exibida  
**E** se não houver cursos, a mensagem "Não existem cursos cadastrados" é exibida.
