**Dados e automação com Python** · Campo Grande, MS

Trabalho transformando dados brutos em informação útil: pipelines de dados, indicadores, dashboards e robôs que
tiram tarefas repetitivas das mãos das pessoas. Venho da Engenharia Civil e migrei para tecnologia pelo caminho
dos dados.

- 🎓 Graduação em **Engenharia Civil**, especialização em **Engenharia de Software** e **MBA em Data Science** pela **USP**
- 📚 Graduação **Análise e Desenvolvimento de Sistemas**
- ⚙️ No dia a dia: pipelines em Python/pandas sobre dados de telemetria (Parquet), cálculo de indicadores de
  disponibilidade e assertividade, consultas em Oracle/SQL, dashboards em Power BI e robôs de automação (RPA)
  para o setor elétrico

## 🛠️ Stack

**Dados:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Apache Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Bancos e BI:**
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

**Automação e web:**
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## ⚡ Gestão de ativos da distribuição

Uma série de projetos com **dados abertos da ANEEL e do ONS**, do diagnóstico à decisão de investimento.
Cada um valida os resultados contra baselines e números oficiais e explica as premissas e limitações.

| Projeto | Pergunta | Resultado principal |
|---|---|---|
| [Gestão de ativos baseada em risco](https://github.com/CaioNepomuceno2/distribution-asset-risk) | Onde investir primeiro para reduzir DEC, FEC e compensações? | DEC recalculado bate com o oficial; com as eficácias medidas no projeto ao lado, a carteira otimizada de R$ 20 mi gera VPL de R$ 53 mi contra R$ 22 mi da regra "piores primeiro" |
| [Quanto vale um religador](https://github.com/CaioNepomuceno2/automation-impact) | Quanto DEC um religador realmente evita, e quanto custa a indisponibilidade da telemetria? | Diferenças em diferenças: −16,6% no CHI do alimentador (IC 95% −24,8% a −7,5%); cada 1 p.p. de indisponibilidade custa 0,7 a 1,4 min de DEC/ano |
| [Desempenho e posicionamento de religadores](https://github.com/CaioNepomuceno2/recloser-performance) | Os religadores estão no lugar certo? Onde instalar os próximos? | Topologia da rede de MT reconstruída (99,9% dos clientes ligados); 10% das zonas de proteção concentram 60% do risco; pelo modelo, 100 religadores nos locais indicados evitam 53 min de DEC/ano contra 10 min da regra por extensão |
| [Saúde e criticidade de subestações](https://github.com/CaioNepomuceno2/substation-health-index) | Quais subestações têm maior risco, e por quê? | SEs sem folga N-1 foram ampliadas 3× mais que as demais (38% vs 14%); 56% dos clientes estão em alimentadores sem rota de transferência para outra SE |
| [Vida útil de religadores e disjuntores](https://github.com/CaioNepomuceno2/switchgear-survival) | Quanto tempo duram e quantos trocar por ano? | Tábua de vida por safra e Weibull: vida mediana de ~28 anos para religadores; ~635 substituições previstas de 2026 a 2035 |
| [Indicadores de telemetria SCADA](https://github.com/CaioNepomuceno2/scada-telemetry-kpis) | Como medir disponibilidade e assertividade da telemetria e priorizar a manutenção pelo valor? | Biblioteca aberta (DuckDB) validada contra a verdade em dados sintéticos; detecta degradação 21 dias antes; 12 milhões de eventos em 24 s |
| [GD × capacidade da rede](https://github.com/CaioNepomuceno2/gd-hosting-capacity) | Quais transformadores vão saturar com a solar dos telhados, e quando? | 11,6 mil trafos com GD acima da potência (5× em 3 anos); dos 1.000 apontados com dados até 2022, 802 saturaram até 2025 |
| [Monitor de risco regulatório](https://github.com/CaioNepomuceno2/continuity-risk-monitor) | Em junho, quais conjuntos vão estourar o limite de DEC/FEC até dezembro? | 84% das violações identificadas com 85% de precisão; robô mensal no GitHub Actions, modelo para Power BI e painel |

**Stack:** Python, pandas, DuckDB, SQL, LightGBM, inferência causal, análise de sobrevivência, grafos, otimização (MILP), GitHub Actions, Streamlit, Power BI.

## 🔌 Operação do sistema elétrico

| Projeto | Pergunta | Resultado principal |
|---|---|---|
| [Curtailment de eólicas e solares](https://github.com/CaioNepomuceno2/renewables-curtailment) | Quanta energia renovável o Brasil está jogando fora, onde e por quê? | 39 TWh cortados em 12 meses (22% da geração possível); previsor do dia seguinte erra 34% menos que a persistência |
| [Previsão de carga × ONS](https://github.com/CaioNepomuceno2/ons-load-forecast) | Um modelo aberto prevê a carga de amanhã tão bem quanto o ONS? | Empata no SIN e erra menos no Sul, Nordeste e Norte; a média modelo + ONS reduz o erro do ONS em 12% |

## 🛠️ Outros projetos

| Projeto | O que é | Stack |
|---|---|---|
<!-- | [Controle financeiro pessoal](https://github.com/CaioNepomuceno2/controle-financeiro-pessoal) | Projeção de fluxo de caixa de 18 meses com regras brasileiras (fatura de cartão, 13º, INSS), simuladores e testes | Python, Streamlit, SQLite, pytest | -->
<!-- | [Independência financeira](https://github.com/CaioNepomuceno2/independencia-financeira) | Planejador financeiro em grade de 18 meses: dívidas, cartões, financiamentos e meta de patrimônio | React, TypeScript, Vite, Tailwind | -->
| [Envio de e-mails com Python](https://github.com/CaioNepomuceno2/Basic_Email_Send) | CLI com templates, anexos, simulação, controle de ritmo e testes | Python, SMTP, Jinja2, pytest |
| [Sistema de Gestão Universitária](https://github.com/CaioNepomuceno2/senac-university-management) | Projeto acadêmico em grupo com login e painéis por perfil | Python, Flask, SQLite |
| [Automação para WhatsApp Web](https://github.com/CaioNepomuceno2/RoboWhatsapp) | Estudo de automação web com planilhas e testes; o README explica suas limitações | Python, Selenium, pandas |

<details>
<summary><b>Outros estudos</b></summary>

- [TypeScript: exemplos e desafios](https://github.com/CaioNepomuceno2/typescript-studies)
- [Clone de interface com HTML e CSS](https://github.com/CaioNepomuceno2/instagram-login-clone)

</details>

## 📈 Trajetória

```
2021  HTML, CSS e Git: primeiros repositórios
2022  JavaScript, TypeScript, C# e Java: lógica e orientação a objetos
2023  Python e Flask: sistema acadêmico no SENAC
2024  Automação: robôs com Selenium e RPA, integração com Oracle
2025  Engenharia de dados: pipelines em Parquet, indicadores, Power BI e apps em Streamlit
2026  Gestão de ativos com dados abertos do setor elétrico: previsão, inferência causal e otimização;
      ETL com modelagem dimensional e projetos pessoais em Godot + Blender
```

## 📫 Contato

- GitHub: [@CaioNepomuceno2](https://github.com/CaioNepomuceno2)
