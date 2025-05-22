## Processo de Monitoramento e Validação de Repositórios

### 1. Verificação de Correções

- Verificar os repositórios (PRs, commits, merges) para confirmar se as correções foram feitas.
- Em seguida, realizar os testes do componente.

- Verificar os repositórios (PRs, commits, merges) para confirmar se as correções **não** foram feitas.
- Em seguida, reportar a necessidade de atender à **Issue** deste repositório no grupo específico.

### 2. Criação de Issues

Ao criar issues, você pode:

- Adicionar **checklists** com etapas claras;
- Adicionar **labels** para categorizá-las;
- **Atribuir responsáveis (assignees)** para definir quem irá atuar;
- **Vincular a issue a uma milestone** correspondente à sprint ou entrega prevista;
- **Comentar com atualizações frequentes**;
- **Mencionar pessoas ou times** (`@usuário` ou `@equipe`) para direcionar a atenção.

### 3. Inspeção de Issues

- Inspecionar as Issues e reportá-las no grupo específico do projeto.
- Caso a issue tenha sido **resolvida com Pull Request**, solicitar o merge e **fechar a issue**.
- Caso **não esteja resolvida**, reportar ao grupo específico do projeto ou à pessoa responsável.

### 4. Monitoramento de Commits

- Monitorar os commits feitos pelos desenvolvedores.
  - Quando o repositório **tiver commits recentes**, verificar com atenção o que foi desenvolvido.
  - Quando o repositório **não tiver commits recentes**, enviar uma mensagem ao responsável.

### 5. Testes de Componentes (Pull Request)

- **Testar os componentes indicados no Pull Request** utilizando **PowerShell** ou **DartPad**, inspecionando:
  - A execução,
  - O funcionamento,
  - E o layout.

- **Se os testes forem bem-sucedidos**:
  - Fechar o Pull Request;
  - Solicitar ao consultor que faça o merge.

- **Se os testes não forem bem-sucedidos**:
  - Abrir uma **issue**;
  - Reportar especificamente os problemas encontrados.




