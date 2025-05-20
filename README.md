# Rotina do Gestor de Projetos - CooCree (Fluxo GitHub)

Fluxo de interlocução com cliente, entrada das demandas, entrega de recursos do pedido, devolução com o componente ou a aplicação.
![image](https://github.com/user-attachments/assets/daf73c0e-0c35-4631-879f-25bf67f01eb2)



Lista de tarefas em ordem que deve ser inspecionado diariamente no desenvolvimento de componente.

| **Ordem**   | **Tarefa**                                        | **Descrição / Objetivo**                                                                |
|-------------|---------------------------------------------------|-----------------------------------------------------------------------------------------|
| **01**      | Check-in dos Repositorios no GitHub               | Acompanhar andamento dos status do Repositorios.                                        |
| **02**      | Monitorar prazos e entregas                       | Checar se as tarefas estão no tempo previsto, agir se algo estiver atrasado.            |
| **03**      | Check-in da equipe status GitHub                  | Acompanhar andamento das tarefas e commits dos desenvolvedores.                         |
| **04**      | Seleciona os Commits a serem testados             | cria uma lista dos componentes indicado para teste pelo desenvolvedor.                  |
| **05**      | Atualizar status no quadro de tarefas (Kanban etc)| Verificar o progresso de cada tarefa e manter o projeto visualmente organizado.         |
| **06**      | Aplica o teste de componentes                     | Testa o componente em Power Shel ou DartPad, inspecionar, execução, funcionamento e layout  |
| **07**      | Registrar falhas, comentarios e mudanças          | Abrir uma Issue para atualizar documentação sempre que houver alterações no projeto .   |
| **08**      | Associar a Branch                                 | Verificar se a Issue tem uma Branch, caso não tenha, deve criar.                        |
| **09**      | Certificar a comunicação                          | Divulgar em grupos de watzapp a Issue, Status e prazo para correção.                    |




Classificação dos tipos de Entradas na CooCree.
Componentes
Aplicação
Software
Agentes de IA

---

## ✅ Dicas para um bom planejamento:

- Use ferramentas como Trello, Asana, Jira, Notion ou MS Project.
- Organize sua agenda com blocos de tempo para cada tipo de tarefa.
- Reserve tempo para análise estratégica, não apenas execução.
- Documente decisões, riscos e aprendizados ao longo do caminho.
- Adapte as rotinas conforme o ritmo e escopo de cada projeto.







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
