## 📝 Audit 

O módulo de **Audit** é responsável por garantir a rastreabilidade e transparência das operações realizadas no sistema de caixa e vendas.  
Ele permite acompanhar todas as movimentações feitas por operadores, consolidar informações em relatórios e manter um histórico completo de auditoria para fins de controle interno, segurança e conformidade.  

### Principais responsabilidades:
- Registrar e disponibilizar todas as transações realizadas por cada operador.
- Fornecer resumos consolidados de movimentações por operador.
- Disponibilizar logs completos de auditoria com filtros por data, operador ou tipo de operação.
- Apoiar processos de compliance e segurança, garantindo integridade das informações financeiras.

---

## 🔹 Endpoints

- **GET /audit/operators/{operatorId}/transactions** → Lista todas as movimentações realizadas por um operador específico, com detalhes de cada operação.  

- **GET /audit/operators/{operatorId}/summary** → Retorna um resumo consolidado das operações de um operador (quantidade de transações, valores totais movimentados).  

- **GET /audit/logs** → Exibe o histórico completo de auditoria do sistema, com filtros opcionais por data, operador ou tipo de operação.  
