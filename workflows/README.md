# workflows

Esta pasta é destinada a armazenar definições, scripts e documentação sobre fluxos de trabalho (workflows) do projeto.

Observações importantes
- Os workflows do GitHub Actions devem ficar em `.github/workflows/` para serem executados automaticamente pelo GitHub. Esta pasta `workflows/` na raiz é útil para:
  - manter modelos, exemplos e documentação de workflows antes de copiá-los para `.github/workflows/`;
  - guardar scripts reutilizáveis, descrições e templates de CI/CD que complementam os arquivos YAML executáveis;
  - organizar fluxos de trabalho que não serão diretamente executados pelo GitHub (por exemplo, workflows de terceiros, documentação detalhada, diagramas, checklists).

Sugestão de estrutura dentro de `workflows/`

- templates/        ← modelos de workflows (YAML) que podem ser copiados para `.github/workflows/`
- scripts/          ← scripts chamados pelos workflows (shell, python, etc.)
- docs/             ← explicações, diagramas e runbooks sobre os pipelines
- examples/         ← exemplos prontos e comentados

Boas práticas
- Mantenha os workflows que devem executar no GitHub em `.github/workflows/` — o GitHub não executa arquivos em `workflows/` na raiz.
- Use nomes claros e comentários nos arquivos YAML e inclua um README explicando o propósito de cada workflow/template.
- Se houver scripts, adicione instruções de permissões/execução e dependências.

O que posso fazer agora
1) Criar as subpastas `workflows/templates`, `workflows/scripts`, `workflows/docs` e `workflows/examples` e adicionar `.gitkeep` ou README em cada uma.  
2) Adicionar um exemplo de workflow em `workflows/templates/` e, se você quiser, também sincronizar para `.github/workflows/` para ativar a execução (preciso da sua confirmação antes de criar/alterar arquivos dentro de `.github/workflows/`).  
3) Criar scripts de apoio em `workflows/scripts/` (me envie o conteúdo ou descreva o que precisa).

Diga qual opção prefere que eu execute a seguir.