# Arquitetura

O fluxo de dados tem três etapas:

| Etapa | Descrição | Ferramenta |
|-------|-----------|------------|
| Ingestão | Coleta dos arquivos de vendas | Python |
| Transformação | Limpeza e padronização | SQL |
| Carga | Gravação no data warehouse | Banco relacional |