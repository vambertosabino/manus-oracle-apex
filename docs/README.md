# pasta docs

Esta pasta foi criada para armazenar documentação e arquivos relacionados ao projeto, incluindo os PDFs do FONAR.

Estrutura sugerida:

- docs/fonar/
  - manuals/        ← manuais e guias do usuário
  - forms/          ← formulários e instruções de envio
  - presentations/  ← apresentações

Boas práticas:
- Use nomes em minúsculas e hífen para separar palavras, ex.: `manual-usuario-fonar-eletronico.pdf`.
- Se algum PDF for grande (>50 MB), use Git LFS:
  ```bash
  git lfs install
  git lfs track "docs/fonar/*.pdf"
  git add .gitattributes
  ```

Como adicionar os PDFs localmente e enviar:

1. Crie as pastas localmente (se necessário):
   ```bash
   mkdir -p docs/fonar/manuals docs/fonar/forms docs/fonar/presentations
   ```
2. Copie/renomeie os PDFs para as pastas e commit:
   ```bash
   git add docs/fonar/**/*.pdf
   git add docs/fonar/README.md
   git commit -m "docs(fonar): add FONAR PDFs"
   git push
   ```

Se quiser, posso também:
- criar as subpastas vazias (com arquivos README ou .gitkeep) neste repositório;
- normalizar automaticamente os nomes dos PDFs que você pretende adicionar;
- abrir uma branch e criar um PR contendo os PDFs (você precisa autorizar e fornecer os arquivos ou me permitir acessá-los).

Se preferir que eu crie as subpastas agora, diga quais você quer ou confirme que devo criar `manuals`, `forms` e `presentations`.