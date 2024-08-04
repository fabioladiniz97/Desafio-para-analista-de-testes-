=====================================================================================
# 👨🏻‍👩🏻‍👦🏻‍👦🏻 User Stories
=====================================================================================

# US - 3: Excluir Curso

## Funcionalidade: Excluir Curso

**Como** usuário da plataforma  
**Eu quero** excluir um curso existente  
**Para que** cursos obsoletos ou incorretos não estejam disponíveis para os alunos

### Critérios de Aceitação

1. **Seleção e Confirmação da Exclusão**
   - O usuário deve poder selecionar um curso existente para exclusão.
   - O usuário deve confirmar a exclusão do curso antes que ele seja removido.

2. **Remoção do Curso**
   - O curso selecionado deve ser removido da lista de cursos disponíveis após a confirmação.

3. **Mensagem de Confirmação**
   - Após a exclusão bem-sucedida do curso, o usuário deve receber uma mensagem de confirmação "Curso excluído com sucesso".

4. **Mensagens de Erro**
   - Se houver um erro durante a exclusão (por exemplo, se o curso não for encontrado), o sistema deve exibir uma mensagem de erro apropriada, como "Curso não encontrado" ou "Erro ao excluir o curso".

### Contexto

**Dado** que o usuário está autenticado na plataforma  
**Quando** o usuário navega para a página de lista de cursos  
**E** seleciona um curso existente para exclusão  
**E** confirma a exclusão do curso  
**Então** o curso é removido da lista de cursos disponíveis  
**E** uma mensagem de confirmação "Curso excluído com sucesso" é exibida  
**E** se ocorrer um erro (por exemplo, curso não encontrado), uma mensagem de erro apropriada é exibida
