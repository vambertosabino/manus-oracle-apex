# FONAR

Esta pasta contém documentos relacionados ao FONAR (formularios, manuais, apresentações).

Estrutura sugerida dentro de docs/FONAR:

- manuals/        ← manuais e guias do usuário
- forms/          ← formulários e instruções de envio
- presentations/  ← apresentações

Boas práticas
- Use nomes em minúsculas e hífen para separar palavras: `manual-usuario-fonar-eletronico.pdf`.
- Se algum PDF for grande (>50 MB), use Git LFS:
  ```bash
  git lfs install
  git lfs track "docs/FONAR/*.pdf"
  git add .gitattributes
  ```

Notas
- Esta README serve para indicar o propósito da pasta e guiar colaboradores sobre onde colocar cada tipo de documento.
- Se quiser, posso criar também as subpastas `manuals`, `forms` e `presentations` e adicionar `.gitkeep` ou READMEs nelas.