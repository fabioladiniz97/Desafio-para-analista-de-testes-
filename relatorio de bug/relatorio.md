### Cenários e Casos de Testes informações

**Relatório de Bugs:** Para acessar a planilha contendo o relatório de bugs, por favor, clique (#).

**Vulnerabilidades Encontradas no Cadastro de Cursos:**

- **Validação do Campo de URL:** O campo de URL não possui validação, permitindo a entrada de URLs inválidas ou malformadas.
- **Validação de Datas de Início e Fim:** Não há validação adequada para as datas de início e término do curso, o que pode permitir a entrada de datas incoerentes.
- **Validação do Limite de Número de Vagas:** O sistema não valida o número máximo de vagas permitidas para um curso, podendo resultar em inconsistências.

**Técnicas Utilizadas para Realizar os Testes:**

- **Teste de Limites:** Verificação das fronteiras de entrada, como o número máximo e mínimo de caracteres, e o limite de vagas.
- **Teste de Valores Válidos e Inválidos:** Avaliação do comportamento do sistema com dados que são esperados e inesperados.
- **Teste de Usabilidade:** Análise da interface e da experiência do usuário para garantir que o sistema seja intuitivo e fácil de usar.

**Pontos para Esclarecimento:**

1. **Requisitos Funcionais e Não Funcionais:** Quais são os requisitos específicos e as expectativas para a funcionalidade de criação de cursos?
2. **Validações dos Campos do Formulário:** Quais são as validações esperadas para cada campo no formulário de criação de curso?
3. **Mensagens de Erro:** Quais mensagens de erro devem ser apresentadas ao usuário em caso de entrada inválida ou problemas durante a criação do curso?

**Próximos Passos e Garantia de Qualidade:**

1. **Reunião de Esclarecimento:** Agendar uma reunião com a equipe responsável para discutir e esclarecer os pontos críticos identificados.
2. **Documentação:** Atualizar a documentação de requisitos com todas as informações e validações necessárias.
3. **Plano de Testes:** Desenvolver um plano de testes detalhado com base nas informações obtidas durante a reunião.
4. **Execução de Testes:** Realizar os testes conforme o plano, garantindo que todos os casos de uso e fluxos de exceção sejam devidamente cobertos.

**Avaliação na Identificação de Erros:**

- **Reprodução do Erro:** Verificar se o erro pode ser reproduzido de forma consistente seguindo os passos descritos.
- **Análise do Escopo:** Determinar se o erro está diretamente relacionado à funcionalidade da feature em teste.
- **Definição da Causa do Erro:**
  - **Erro Causado pela Feature:** Se o erro estiver diretamente ligado à nova funcionalidade, reportá-lo como um bug da feature e documentar todos os passos e evidências para facilitar a correção.
  - **Erro Não Causado pela Feature:** Se o erro não for relacionado à nova feature, reportá-lo como um problema geral da aplicação.

**Ações para Garantir Qualidade:**

- **Comunicação Eficaz:** Manter uma comunicação clara e contínua com a equipe de desenvolvimento para resolver questões e alinhar expectativas.
- **Documentação Detalhada:** Fornecer documentação completa dos testes, incluindo casos de teste, resultados e logs, para facilitar a análise e resolução de problemas.
- **Revisões de Código:** Participar de revisões de código para identificar e corrigir problemas antes da implementação.
- **Testes de Regressão:** Conduzir testes de regressão para assegurar que novas alterações não introduzam novos bugs na aplicação.
