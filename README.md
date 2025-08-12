# Hospital-Analysis
🏥 Project: Hospital Data Analysis
📁 Description
This project performs exploratory data analysis (EDA) on a fictitious hospital dataset containing 500 patient records. The goal is to extract clinical, operational, and financial insights that can support strategic decisions in hospital settings.

📦 Dataset: hospital.csv
The hospital.csv file contains clinical, administrative, and demographic information for patients treated at a hospital.
📋 Column Structure
| Column | Description |
| patient_id | Unique patient identifier |
| age | Patient age (0 to 100 years) |
| sex | Patient gender: Male or Female |
| hospital_type | Type of admission: Elective, Emergency, or Urgent |
| admission_date | Date the patient was admitted to the hospital |
| discharge_date | Date of hospital discharge or discharge for another reason |
| days_hospitalized | Total number of days the patient remained hospitalized |
| main_diagnosis | Main illness diagnosed (e.g., pneumonia, stroke, COVID-19) |
| main_treatment | Main procedure or therapy performed during hospitalization |
| medical_specialty | Responsible medical department (e.g., neurology, general practice) |
| discharge_condition | Final patient status: discharge, death, transfer, etc. |
| total_cost | Estimated total cost of treatment in reais |
| health_plan | Name of health plan used or "Private" |
| patient_satisfaction | Patient's evaluation (scale of 1 to 5) of the care received |
| rehospitalization_30days | Indicates whether there was a rehospitalization within 30 days of discharge (Yes or No) |

📊 Analyses Performed
The analyses were performed with pandas, matplotlib, and seaborn, including:
- Distribution of patients by sex and age
- Most common types of hospitalization
- Most frequent diagnoses and treatments
- Average length of stay
- Average cost by health plan
- Average satisfaction by medical specialty
- Readmission rate within 30 days
- Correlations between hospitalization days, cost, and satisfaction
- Visualizations with histograms, boxplots, and graphs

🧰 Technologies Used
- Python 3.10+
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

📁 Project Organization
📦 hospital-analise/
├── hospital.csv
├── Hospital.ipynb
├── README.md





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








