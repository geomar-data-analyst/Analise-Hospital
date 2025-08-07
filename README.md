# Analise-Hospital
🏥 Projeto: Análise de Dados Hospitalares
📁 Descrição
Este projeto realiza uma análise exploratória de dados (EDA) sobre um dataset hospitalar fictício contendo 500 registros de pacientes. O objetivo é extrair insights clínicos, operacionais e financeiros que possam apoiar decisões estratégicas em ambientes hospitalares.

📦 Dataset: hospital.csv
O arquivo hospital.csv contém informações clínicas, administrativas e demográficas de pacientes atendidos em um hospital.
📋 Estrutura das Colunas
| Coluna | Descrição | 
| id_paciente | Identificador único do paciente | 
| idade | Idade do paciente (0 a 100 anos) | 
| sexo | Gênero do paciente: Masculino ou Feminino | 
| tipo_internacao | Tipo de internação: Eletiva, Emergencial ou Urgência | 
| data_entrada | Data em que o paciente foi admitido no hospital | 
| data_saida | Data de alta hospitalar ou saída por outro motivo | 
| dias_internacao | Número total de dias que o paciente permaneceu internado | 
| diagnostico_principal | Doença principal diagnosticada (ex: Pneumonia, AVC, COVID-19) | 
| tratamento_principal | Procedimento ou terapia principal realizada durante a internação | 
| especialidade_medica | Departamento médico responsável (ex: Neurologia, Clínica Geral) | 
| condicao_saida | Situação final do paciente: Alta, Óbito, Transferência, etc. | 
| custo_total | Valor total estimado do tratamento em reais | 
| plano_saude | Nome do plano de saúde utilizado ou "Particular" | 
| satisfacao_paciente | Avaliação do paciente (escala de 1 a 5) sobre o atendimento recebido | 
| reinternacao_30dias | Indica se houve reinternação em até 30 dias após a alta (Sim ou Não) | 


📊 Análises Realizadas
As análises foram feitas com pandas, matplotlib e seaborn, incluindo:
- Distribuição de pacientes por sexo e idade
- Tipos de internação mais comuns
- Diagnósticos e tratamentos mais frequentes
- Tempo médio de internação
- Custo médio por plano de saúde
- Satisfação média por especialidade médica
- Taxa de reinternação em até 30 dias
- Correlações entre dias internado, custo e satisfação
- Visualizações com histogramas, boxplots, gráfic

🧰 Tecnologias Utilizadas
- Python 3.10+
- pandas
- matplotlib
- seaborn
- Jupyter Notebook


📁 Organização do Projeto
📦 hospital-analise/
├── hospital.csv
├── Hospital.ipynb
├── README.md








