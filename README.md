
# Rotina do Gestor de Projetos - CooCree (Fluxo GitHub)

Fluxo organizado do início ao fim de um ciclo de projeto, desde o alinhamento com stakeholders até a entrega via merge ou CI/CD.

| **Ordem** | **Tarefa**                                          | **Descrição / Objetivo**                                                                 |
|-----------|-----------------------------------------------------|-------------------------------------------------------------------------------------------|
| 01        | **Reunião com stakeholders / cliente**              | Iniciar o projeto, alinhar objetivos, entender escopo inicial e marcos.                  |
| 02        | **Reunião de alinhamento estratégico**              | Garantir que o projeto esteja aderente à visão da empresa/parceiro.                      |
| 03        | **Pesquisa e construção de referência técnica e visual** | Levantar exemplos, componentes semelhantes, layout ou design system como material base para orientar os desenvolvedores. |
| 04        | **Gerenciar mudanças de escopo ou orçamento**       | Negociar e registrar qualquer ajuste antes de execução técnica.                          |
| 05        | **Criação de repositório**                          | Criar repositórios no GitHub conforme escopo e estrutura acordada.                       |
| 06        | **Distribuição de repositórios**                    | Organizar tecnicamente os repositórios para a equipe de desenvolvimento.                 |
| 07        | **Reunião de planejamento de 30 min**               | Planejar ciclo inicial com prioridades, papéis e entregas.                               |
| 08        | **Planejamento da próxima sprint**                  | Definir backlog e organizar tarefas no quadro GitHub semanalmente.                       |
| 09        | **Atualizar cronograma geral**                      | Espelhar planejamento no cronograma geral do projeto.                                    |
| 10        | **Registrar decisões e mudanças**                   | Atualizar documentação no repositório com decisões técnicas e de negócio.                |
| 11        | **Levantamento de pagamento**                       | Avaliar entregas vinculadas a pagamentos no contrato.                                    |
| 12        | **Solicitação de pagamento**                        | Formalizar a requisição de pagamento de acordo com progresso validado.                   |
| 13        | **Check-in com equipe (watzapp rápida/ meet)**      | Acompanhar equipe e remover bloqueios no dia a dia.                                      |
| 14        | **Acompanhamento das Issues**                       | Verificar o andamento técnico e o progresso no GitHub.                                   |
| 15        | **Atualizar quadro de tarefas**                     | Manter board no GitHub atualizado com status real das tarefas.                           |
| 16        | **Abertura de Issue de dúvidas**                    | Registrar perguntas e bloqueios no repositório de forma rastreável.                      |
| 17        | **Checking e inspeção de PR**                       | Analisar pull requests conforme critérios de qualidade técnica.                          |
| 18        | **Solicitar Revisão do consultor**                  | Chamar revisão técnica especializada para garantir padrões de código.                    |
| 19        | **Checkout de entregas via PR**                     | Confirmar que a entrega cumpre o escopo e requisitos dos testes.                         |
| 20        | **Testes de componentes finalizados**               | Validar funcionalidades entregues no ambiente (PowerShell / DartPad).                    |
| 21        | **Monitorar prazos e entregas**                     | Confirmar aderência ao cronograma e ajustar se necessário.                               |
| 22        | **Revisar riscos e plano de ação**                  | Avaliar riscos emergentes e documentar planos de mitigação.                              |
| 23        | **Análise de desempenho do projeto**                | Revisar indicadores de entrega, retrabalho e progresso.                                  |
| 24        | **Relatório mensal para stakeholders**              | Consolidar entregas, pendências e próximos passos.                                       |
| 25        | **Merge ou CI/CD (entrega final)**                  | Concluir a entrega técnica via merge no branch principal ou deploy automático.           |





✅ Checklist Operacional do Processo

📋 Templates de Issue e Pull Request

🗂️ Modelo de Quadro Kanban no GitHub Projects

🔧 Soluções para Vencer as Ameaças e Fraquezas do SWOT

✅ Checklist Operacional (Passo a Passo Diário)
Para o Desenvolvedor

 Testar o componente (PowerShell ou DartPad).

 Verificar conformidade com requisitos.

 Caso necessário:

 Abrir uma issue descritiva.

 Criar branch específica para a issue.

 Testar e revisar o PR.

 Aprovar ou comentar com melhorias.

 Se aprovado, solicitar merge ao Diretor de TI.

Solicitar Validação do código e funcionamento.

Solicitar merge na branch main.

### Evidência
Inclua prints, vídeos ou links (ex: DartPad).

### Responsável
@dev_responsável

### Descrição
Breve explicação da alteração feita.

### Issue Relacionada
Closes #123 (link direto à issue)

### Como Testar
1. Copie o código e teste no DartPad/PowerShell.
2. Verifique se o erro relatado não ocorre mais.

### Checklist
- [ ] Testado em DartPad/PowerShell
- [ ] Segue padrão do projeto
- [ ] Revisado por outro dev ou gestor

### Observações
(Se houver dependências, observações técnicas etc.)


🗂️ Sugestão de Quadro Kanban (GitHub Projects)
Colunas:

Backlog

Ideias e melhorias ainda não iniciadas.

To Do

Issues priorizadas e prontas para desenvolvimento.

Em Desenvolvimento

Issues com branch criada e código em andamento.

Em Revisão

Pull Requests aguardando revisão/teste do gestor.

Aguardando Merge

PRs aprovados, esperando o Diretor de TI.

Concluído

Merge finalizado na main.
