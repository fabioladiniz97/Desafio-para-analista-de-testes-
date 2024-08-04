=====================================================================================
# 👨🏻‍👩🏻‍👦🏻‍👦🏻 User Stories
=====================================================================================

## US - 1: Cadastrar Curso 

### Funcionalidade: Cadastrar Curso

**Como** usuário da aplicação Desafio de QA Beedoo  
**Quero** poder cadastrar um curso  
**Para que** ele seja exibido na lista dos meus cursos disponíveis

### Critérios de Aceitação

1. **Acesso ao Formulário de Cadastro**
   - O usuário deve acessar o formulário de cadastro de curso ao clicar no botão do menu "Cadastrar curso".

2. **Campos do Formulário**
   - O formulário de cadastro deve conter os seguintes campos obrigatórios:
     - Nome do curso
     - Descrição do curso
     - Instrutor
     - URL da imagem de capa
     - Data de início
     - Data de fim
     - Número de vagas
     - Tipo de curso (Presencial ou Online)

3. **Validações dos Campos**
   - O campo "Nome do curso" deve aceitar até 50 caracteres.
   - O campo "Descrição do curso" deve aceitar até 256 caracteres.
   - O campo "Instrutor" deve aceitar até 50 caracteres.
   - O campo "URL da imagem de capa" deve aceitar apenas URLs válidas.
   - Os campos "Data de início" e "Data de fim" devem permitir a seleção de datas pelo calendário.
   - O campo "Data de fim" não deve aceitar uma data anterior à "Data de início".
   - O campo "Número de vagas" deve aceitar um valor máximo de 1000 vagas.

4. **Mensagens de Validação**
   - O usuário deve ser alertado sobre campos obrigatórios com a mensagem padrão "O campo é obrigatório" exibida abaixo de cada campo relevante.

5. **Requisitos de Preenchimento**
   - O usuário não deve conseguir finalizar o cadastro se qualquer campo obrigatório estiver vazio.

6. **Redirecionamento Após Sucesso**
   - Após a conclusão bem-sucedida do cadastro, o usuário deve ser redirecionado para a lista de cursos.

### Contexto

**Dado** que o usuário está na plataforma  
**Quando** o usuário navega para a página de criação de curso  
**E** preenche o nome do curso com "Curso de Teste"  
**E** preenche a descrição do curso com "Descrição do Curso de Teste"  
**E** preenche o campo "Instrutor" com "Instrutor Teste"  
**E** insere uma URL válida para a imagem de capa  
**E** seleciona uma data de início e uma data de fim válidas para o curso  
**E** define o número de vagas como 30  
**E** escolhe o tipo de curso como "Online"  
**E** clica no botão "Cadastrar curso"  
**Então** o curso é salvo  
**E** uma mensagem de confirmação "Curso criado com sucesso" é exibida  
**E** o novo curso aparece na lista de cursos
