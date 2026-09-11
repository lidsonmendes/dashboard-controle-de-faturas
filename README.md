# dashboard-controle-de-faturas
Dashboard em Power BI para controle e análise de faturas, com identificação de causa raiz de rejeições
📊 Dashboard de Controle de Faturas — Power BI

Dashboard analítico construído em Power BI para acompanhamento e análise de processos de faturas de um setor de Contas a Pagar, com identificação de causa raiz de rejeições através de investigação orientada por dados.

Nota sobre os dados: os dados utilizados neste projeto são baseados em uma planilha real de controle que desenvolvi e utilizo na minha rotina profissional. Nomes de fornecedores, responsáveis e projetos foram anonimizados para preservar a confidencialidade da empresa — a estrutura, os volumes e os padrões de erro são reais.

🎯 Objetivo

Transformar o controle manual de faturas (originalmente em planilha) em um dashboard interativo capaz de:

Acompanhar volume e tendência de processos ao longo do tempo
Medir a evolução da taxa de rejeição
Identificar quais projetos concentram mais problemas
Investigar causas raiz de rejeições recorrentes, não só reportar números
❓ Perguntas de negócio
Qual o volume de processos analisados mês a mês, e como ele varia ao longo do ano?
Como a taxa de rejeição evoluiu ao longo do período?
Quais projetos concentram o maior volume de contratos e ordens de compra?
Quais projetos têm a maior proporção de erro, controlando por volume mínimo de amostra?
Qual a causa raiz específica por trás dos projetos com maior taxa de rejeição?
🛠️ Tecnologias utilizadas
Power BI Desktop — modelagem e visualização
Power Query — tratamento e transformação dos dados de origem
DAX — medidas customizadas (Taxa de Rejeição %, Total de Processos, Taxa de Erro %)
Excel — estrutura original dos dados antes da modelagem
📈 Principais KPIs / Métricas
Métrica	Valor no período (Jan–Ago/2026)
Total de processos analisados	3.695
Taxa de rejeição	4,7% (média do período)
Tempo médio de processamento	0,26 dias
Contratos e ordens de compra acompanhados (acumulado desde 2024)	~24 mil
🖼️ Prints do Dashboard

(inserir aqui os prints das duas páginas: "Visão Geral" e "Análise por Projeto")

GIF demonstrativo (interatividade): (inserir aqui o GIF navegando pelos filtros de Data e Projeto)

💡 Principais Insights
Taxa de rejeição em queda ao longo do ano: partindo de patamares acima de 6,9% em janeiro, a taxa atingiu mínimas de 1,3% (março) e 1,6% (agosto), com oscilações pontuais associadas a transições de projeto e período de férias da equipe.
Concentração de erro identificada por projeto: ao segmentar a taxa de rejeição por projeto (controlando por volume mínimo de amostra, para evitar distorção estatística de projetos com poucos processos), um projeto específico se destacou com 92,3% de taxa de erro — muito acima da média do grupo.
Causa raiz investigada, não só reportada: a investigação desse projeto revelou que 12 de 13 rejeições tinham o mesmo motivo específico — ausência recorrente do documento "Seguro Fiança" em processos de um mesmo contrato, atribuível a uma lacuna pontual no lançamento. A partir disso, foi possível propor uma ação concreta: checklist de documentos obrigatórios antes do lançamento, específico para contratos com essa exigência.
🔍 Como explorar o dashboard
Baixe o arquivo .pbix deste repositório
Abra no Power BI Desktop (gratuito)
Use o filtro de Data (canto superior) para ajustar o período analisado
Use o filtro de Projeto (na página "Análise por Projeto") para investigar um projeto específico
Passe o mouse sobre os gráficos para ver detalhes adicionais nos tooltips
👤 Autor

Lidson Mendes Ramos LinkedIn · GitHub
