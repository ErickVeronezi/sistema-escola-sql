
# Estrutura de Pastas do Projeto – Banco de Dados Escola

Este projeto foi organizado com uma estrutura de pastas pensada para facilitar administração, evolução e reutilização do código em múltiplos SGBDs.

---

## 📁 Visão Geral da Estrutura
escola-db/
├── ddl/
│ ├── CREATE_TABLE.sql # Criação das tabelas e tipos
│ ├── CONSTRAINTS.sql # Constraints e foreign keys
│ ├── INSERTS_EXEMPLO.sql # Dados de exemplo (INSERTS)
│ ├── TRIGGERS.sql # Criação de TRIGGERS
│ └── VIEWS.sql # Criação de VIEWS para relatórios
│
├── diagramas/
│ ├── modelo_logico_brmodelo.jpg # Modelo lógico feito no BRModelo
│ └── modelo_logico_dbdiagram.png # Modelo lógico feito no dbdiagram.io
│
└── doc/
├── README.md # Descrição geral do projeto
└── estrutura_pastas.md # (este arquivo)


---

### 📌 Observações

- Todos os scripts foram divididos por finalidade para facilitar testes e manutenção.
- Os modelos lógicos estão disponíveis nos formatos `.jpg` e `.png`, permitindo rápida visualização dos relacionamentos.
- A pasta `doc` concentra a documentação textual do projeto, útil para relatórios ou entrega acadêmica.

---

**Criado por Erick Veronezi** — Projeto acadêmico para estudos com SQL e outros SGBDs.
```
