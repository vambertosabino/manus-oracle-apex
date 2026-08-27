# Prompts especializados

Esta pasta contém módulos de instruções especializados para complementar a Skill principal de Oracle APEX e FONAR Digital.

Os prompts NÃO substituem as regras do `SKILL.md`. Devem ser utilizados conforme a natureza da tarefa.

## Mapeamento

### PROJECAO-VISUAL.txt

Usar quando o usuário solicitar representação ou projeção visual de uma solução, página, interface ou funcionalidade.

### PROMPT APEX-DIAGRAMA.txt

Usar para diagramas de arquitetura, banco de dados, relacionamentos, componentes ou fluxos do Oracle APEX.

### PROMPT APEX-FLASHCARDS.txt

Usar quando solicitado material de estudo, revisão ou memorização relacionado ao Oracle APEX.

### PROMPT APEX-INTUITIVO.txt

Usar para melhorar usabilidade, navegação, organização, experiência do usuário e operação de páginas APEX.

### PROMPT APEX-LINHA-DO-TEMPO.txt

Usar quando informações, processos, eventos ou etapas precisarem ser apresentados cronologicamente.

### PROMPT APEX-MAPA-MENTAL.txt

Usar para organizar visualmente conceitos, módulos, funcionalidades, requisitos ou arquitetura.

### PROMPT_WEBDESINER.txt

Usar em tarefas relacionadas a interface, UI/UX, responsividade, HTML, CSS, JavaScript e apresentação visual.

## Combinação

Mais de um módulo pode ser utilizado na mesma tarefa.

Exemplo:

`/APEX-INTUITIVO /WEBDESINER`

deve combinar as instruções de usabilidade APEX com as instruções de design de interface.

## Hierarquia

Em caso de conflito, obedecer nesta ordem:

1. Solicitação atual do usuário
2. `SKILL.md`
3. Estrutura e documentação real do projeto
4. Arquivos de `references/`
5. Prompts desta pasta
6. Exemplos e templates

## Regra crítica

Nenhum prompt pode autorizar a criação de tabelas, colunas, páginas, itens, processos, regras de negócio ou relacionamentos apresentados como existentes sem comprovação na documentação ou estrutura fornecida.
