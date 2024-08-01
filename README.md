# Análise de KPIs de um Serviço de Nutrição Hospitalar Fictício

As análises realizadas como parte do projeto de banco de dados do curso de Gestão da Tecnologia da Informação PUC-Minas. Todos os dados apresentados nos datasets são **fictícios**, gerados de forma randomizada por IA para preenchimento das colunas e simulação dos resultados.

## Apresentação do Escopo do Projeto

Como objeto de estudo foi utilizada uma unidade de Serviço de Nutrição e Dietética Hospitalar fictícia para avaliação das demandas informacionais e funcionais do locais e estabelecer KPIs estratégicas que impactam diretamente na segurança do paciente. 
Foram eleitos dois indicadores estratégicos do setor para se trabalhar com as análises e identificar pontos de melhoria, conforme demonstramos a seguir. Visando a melhoria contínua, julgamos seu monitoramento e análise crítica primordiais para estabelecer ações e frente que englobam não apenas o Serviço de Nutrição, quanto demais setores envolvidos nos resultados. 
Serão observadas a seguir as análises dos seguintes KPIs: Absenteísmo de colaboradores e Percentual de Infusão de Dietas Enterais.

## Absenteísmo de colaboradores

Refere-se à frequência e duração das ausências não programadas dos funcionários do trabalho, seja por motivos de saúde, problemas pessoais ou outras razões não relacionadas ao trabalho. O absenteísmo pode ter um impacto significativo nas operações e no desempenho geral da empresa, incluindo a produtividade, a moral da equipe, a qualidade do trabalho e os custos associados à contratação de substitutos ou horas extras.  
Existem várias causas potenciais para o absenteísmo dos colaboradores, incluindo: Doenças e Lesões; Problemas Pessoais; Insatisfação no Trabalho; Cultura Organizacional e Condições de Trabalho. Ao cruzar os dados das escalas dos colaboradores com o número de faltas cometidas em um período de 30 dias, estes deverão ser classificados de acordo com o cargo exercido e o turno de trabalho. Desta forma, é possível realizar uma análise crítica das informações para elaborar planos de ação futuros de acordo com os principais motivos levantados. 

![Visualização do dataset: Absenteísmo de Colaboradores](https://github.com/kellyfsantos/Power_BI_PUC/blob/main/Print%20planilha%20absente%C3%ADsmo.png)

## Percentual de Infusão de Dietas

O percentual de infusão de dietas é uma medida utilizada na área da nutrição clínica para determinar a adequação com que uma dieta enteral ou parenteral é administrada a um paciente. Esse percentual é expresso como a quantidade de dieta administrada durante um determinado período em relação ao volume total prescrito para o mesmo período. Quanto menor o percentual de infusão da dieta, maior é a inadequação do volume de calorias e proteínas necessários à manutenção do estado nutricional do paciente, que pode contribuir para aumento do tempo de internação hospitalar e risco de mortalidade.
Foi utilizada a planilha com os controles diários realizados, conforme apresentado a seguir: 

![Visualização do dataset: Taxa de Infusão de Dietas](https://github.com/kellyfsantos/Power_BI_PUC/blob/main/Print%20planilha%20infus%C3%A3o.png)

# Análise exploratória dos dados

## Absenteísmo de colaboradores

![Dashboard com dados sobre absenteísmo](https://github.com/kellyfsantos/Power_BI_PUC/blob/main/Dashboard%20Absente%C3%ADsmo.png)

Foram realizadas correlações dos dados, encontrando os seguintes resultados:

### Ausências por turno

Em um total de 62 dias de ausências apresentadas no período, 28 dias (45,16%) compreendem ausências de colaboradores do turno da tarde.

### Ausências e tempo de empresa

Com a correlação destes dois dados, observa-se que 38,8% das ausências foram oriundas de colaboradores que apresentam menos de um ano de empresa.

### Ausência por cargo

O gráfico de barras demonstra claramente que a maior parte das ausências ocorreram no cargo copeira.

## Percentual de Infusão de Dietas

![Dashboard Percentual de Infusão de Dietas](https://github.com/kellyfsantos/Power_BI_PUC/blob/main/Dashboard%20Infus%C3%A3o.png)

### Comparativo entre calorias prescritas e calorias infundidas por unidade de internação

Observa-se que nenhuma das unidades de internação apresentam simularidade entre as calorias prescritas e as calorias infundidas, porém a maior disporidade encontra-se na Unidade de Internação Bloco 4 e a maior proximidade, na Unidade de Internação Bloco 2.

### Comparativo entre o percentual de adequação entre calorias prescritas e calorias infundidas

Nesta representação fica clara a maior adequação da Unidade de Internação bloco 2 em relação às demais unidades, Em contrapartida, a Unidade de Internação Bloco 4 possui a menor adequação, apresentando uma taxa média de 57,74% de infusão em relação aos 100% prescritos.

### Adequação entre calorias prescritas e infundidas e diagnóstico nutricional

O gráfico de funil demonstra uma maior adequação de infusão em pacientes que apresentam risco nutricional, porém, pacientes com diagnóstico de desnutrição grau I apresentam uma média de adequação de 40,69%.

### Adequação de calorias de acordo com a dieta prescrita

A dieta enteral ultraproteica hipercalórica representa a menor adequação em relação as demais prescritas, dicando na contramão da dieta normoproteica normocalórica, que apresenta uma taxa de adequação de 49,25%.

# Pontos relevantes encontrados na análise 

## Absenteísmo de colaboradores

A maior taxa de absenteísmo encontra-se na equipe de copeiras do turno da tarde com tempo de contratação inferior a um ano. Alguns fatores podem influenciar estes dados, como treinamento insuficiente da equipe, problemas de relacionamento ou atividades relacionadas a esta função que influenciam no estabelecimento de doenças ocupacionais. 

## Percentual de Infusão de Dietas

Os dados encontrados expõem pontos de preocupação relacionados às unidades internação que apresentam menores taxas de adequação. É relevante a utilização de mecanismos que investiguem e tracem planos de ação para compreender as causas da baixa taxa de adequação das dietas administradas em pacientes que já possuem diagnóstico de desnutrição e os pacientes eutróficos, a fim de prevenir a desnutrição intrahospitalar e mitigar os riscos de mortalidade. 
