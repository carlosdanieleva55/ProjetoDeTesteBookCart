Projeto QA - Plataforma Book Cart
Simula um projeto completo de QA manual, inspirado em um contexto realista com base nos estágios do STLC (Software Testing Life Cycle).
________________________________________
📄 Visão Geral
Este repositório documenta a criação de uma Suíte de Testes manual para a plataforma de e-commerce fictícia Book Cart. O objetivo é demonstrar na prática as habilidades de um QA Jr em:
•	Levantamento de requisitos
•	Rastreabilidade entre histórias, regras e testes
•	Planejamento e execução manual
•	Evidências reais de execução e bugs
•	Próximos passos para automação
________________________________________
📅 Estrutura do Projeto
Projeto Book Cart/
├── docs/                 # Documentos PDF de referência
│   ├— Documento de Requisitos do Cliente
│   ├— User Stories e Regras de Negócio
│   └— Casos de Teste (Gherkin)
|
├── evidencias/          # Evidências em vídeo (.mkv)
│   ├— TC-001 - Buscar livro por título.mkv
│   ├— TC-005 - Remover filtro de preço.mkv
│   └— BD-003 (TC-003) - Bug mensagem não exibida.mkv
|
└── Book Cart - Suíte de Testes.xlsx
     ├— Roteiro de Testes
     ├— Controle de Defeitos
     ├— Matriz de Rastreabilidade
     └— Ambiente de Teste
________________________________________
🔍 Planejamento de Testes
•	Foram priorizadas 3 funcionalidades críticas:
o	Barra de busca
o	Filtro de preço
o	Adicionar ao carrinho
•	As funcionalidades foram desdobradas em 3 user stories, 18 regras de negócio e 17 casos de teste no padrão Gherkin.
•	As evidências foram gravadas em .mkv e armazenadas por ID para rastreabilidade total.
________________________________________
🔍 Casos de Teste Documentados
•	Testes funcionais manuais executados com registros completos:
o	Resultado Obtido
o	Status (Passou/Falhou)
o	Severidade atribuída
o	Requisitos associados
o	Reteste planejado
•	Testes falhos documentados:
o	TC-003: Bug de feedback ausente na busca vazia
o	TC-005: Filtro de preço não removido
o	TC-009: Livro com imagem e título ausente na listagem
________________________________________
📋 Ferramentas Utilizadas
•	Excel (Suíte de Testes + Matriz + Defeitos)
•	OBS Studio (evidências visuais)
•	Jira (Implementação futura)
•	Cypress (planejado para próxima etapa de automação)
•	JMeter (implementação futura)
________________________________________
🚀 Próximos passos
•	Executar retestes (sprint seguinte)
•	Automatizar os principais cenários com Cypress (UI)
•	Integrar testes de API com Postman
________________________________________
📄 Conclusão
Este projeto demonstra um fluxo completo de QA Jr, indo além de apenas escrever testes: foca em valor para o cliente, rastreabilidade e clareza na execução. Ideal para mostrar competências reais a recrutadores ou ao seu futuro time.
________________________________________
Feito por Carlos Evaristo 🚀
