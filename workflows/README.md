# Workflows operacionais do Manus
Esta pasta NÃO representa GitHub Actions. Ela contém pipelines de execução para os agentes da Skill.

## Seleção
- `CRIAR-PAGINA.md`: criação ou reconstrução controlada de página APEX.
- `CORRIGIR-ERRO.md`: diagnóstico e correção.
- `NOVA-FUNCIONALIDADE.md`: evolução funcional.
- `AUDITORIA.md`: revisão técnica completa.

## Regra
O orquestrador seleciona automaticamente o workflow. O usuário não precisa descrever todas as etapas.
Cada workflow deve consultar fontes, executar, revisar e validar.
