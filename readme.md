# Projeto: BI Estratégico para Autogestão em Saúde - VidaSã Saúde

## Visão Geral
Este projeto simula uma solução de Business Intelligence para uma operadora fictícia de saúde suplementar chamada **VidaSã Saúde**, inspirada em um case real apresentado em entrevista. O objetivo é demonstrar, de forma ética e profissional, como transformar fluxos de dados operacionais e administrativos em painéis gerenciais com alto valor estratégico para a tomada de decisões.

## Objetivos
- Automatizar o processo de ETL com Python.
- Criar dashboards estratégicos com Power BI.
- Integrar notificações automatizadas por e-mail e Telegram para gestores.
- Simular indicadores reais de uma operadora de autogestão.
- Entregar relatórios executivos em PDF de forma recorrente.

## Estrutura do Repositório
```
📁 Projeto_VidaSa_Saude/
├── data/
│   └── raw/                          # Dados simulados: beneficiários, autorizações, rede credenciada, NPS
├── scripts/
│   ├── etl_pipeline.py              # Pipeline completo de ingestão, limpeza e padronização dos dados
│   ├── scheduler.py                 # Agendador para rotinas automáticas
├── notificacoes/
│   ├── email_alerta.py              # Envio de alertas por e-mail
│   └── telegram_alerta.py           # Envio de alertas por Telegram
├── dashboard/
│   └── vidaSa_powerbi.pbix          # Arquivo do dashboard Power BI
├── relatorios/
│   └── relatorio_execucao.pdf       # Relatório estratégico para diretoria
└── eda_analise.ipynb                # Análise exploratória de dados (EDA)
```

## Tecnologias Utilizadas
- Python (pandas, numpy, matplotlib, seaborn, smtplib, requests)
- Power BI
- Git e GitHub
- Power Automate (opcional)

## Indicadores Simulados
- Total de vidas ativas
- Sinistralidade mensal
- Tempo médio de autorização
- NPS (Net Promoter Score)
- Taxa de reinternação em até 30 dias
- Distribuição regional de atendimentos

## Resultados Esperados
- Redução do tempo de acesso à informação gerencial.
- Padronização das fontes de dados para consumo confiável.
- Visão estratégica orientada a dados para superintendência e núcleos.
- Automatização de alertas e notificações para ações proativas.

## Observação
Os dados utilizados neste projeto são **inteiramente fictícios** e criados apenas para fins educacionais. Nenhuma informação sensível ou real foi utilizada.

---

🧠 *Este projeto é uma prova de conceito sobre como aplicar Data Science e BI com responsabilidade, proatividade e foco em resultado.*

👤 Autor: Leonardo Barbosa  
🔗 LinkedIn: [leonardo-barbosa777](https://www.linkedin.com/in/leonardo-barbosa777/)  
💼 GitHub: [leojoker](https://github.com/leojoker)
