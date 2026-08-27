# Regras de banco Oracle
Para FONAR, `database/BD_FONAR_250826.sql` é a referência estrutural disponível.

Antes de gerar DDL/DML/PLSQL, confirme: tabela, coluna, datatype, PK, FK, constraints, sequences, triggers e dependências.
Use bind variables quando aplicável.
Não executar/propor `DROP`, `TRUNCATE` ou `DELETE` amplo sem alerta, impacto, backup/rollback e autorização apropriada.
Não criar objeto paralelo quando o existente atender.
Se a estrutura não puder ser confirmada, declare a limitação.
