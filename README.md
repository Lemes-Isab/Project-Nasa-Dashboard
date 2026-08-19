# Project-Nasa-Dashboard
🪐 Asteroid Dashboard — Análise de Asteroides Próximos à Terra

Um dashboard interativo desenvolvido para explorar, analisar e visualizar dados de asteroides próximos à Terra (Near-Earth Asteroids — NEAs), utilizando Python, Pandas, Plotly e Streamlit.

O projeto transforma um conjunto de dados astronômicos em uma aplicação visual e interativa, permitindo analisar características físicas e orbitais dos asteroides, identificar objetos potencialmente perigosos e explorar diferentes padrões presentes nos dados.

📌 Sobre o Projeto

Este projeto foi desenvolvido como parte de um trabalho acadêmico durante minha formação em Ciência de Dados para Negócios.

O principal objetivo foi aplicar, na prática, conceitos de:

📊 Análise exploratória de dados
🧹 Limpeza e tratamento de dados
🐍 Programação em Python
📈 Visualização de dados
🌐 Desenvolvimento de dashboards interativos
🔎 Identificação de padrões e informações relevantes

A aplicação utiliza dados reais de asteroides e apresenta as informações de maneira mais acessível, permitindo que o usuário explore o conjunto de dados por meio de filtros e visualizações interativas.

🚀 Funcionalidades

O dashboard permite:

🔎 Explorar informações sobre asteroides próximos à Terra
🎛️ Filtrar os dados de forma interativa
☄️ Identificar Asteroides Potencialmente Perigosos (PHA)
📏 Analisar o tamanho e o diâmetro dos asteroides
🌎 Visualizar a distância mínima de interseção orbital com a Terra (MOID)
🛰️ Analisar características das órbitas
📈 Comparar diferentes classes orbitais
💡 Obter insights automaticamente de acordo com os filtros selecionados
📊 Visualizar os dados por meio de diferentes gráficos interativos
🎛️ Filtros

O usuário pode explorar o conjunto de dados utilizando filtros como:

Classe orbital
Status PHA (Potentially Hazardous Asteroid)
Diâmetro
Magnitude absoluta (H)

As visualizações e indicadores são atualizados de acordo com os filtros selecionados.

📊 Visualizações do Dashboard
🔢 Indicadores Principais

O dashboard apresenta indicadores (KPIs) para fornecer uma visão geral dos dados selecionados.

Entre eles estão:

Total de asteroides analisados
Quantidade e percentual de asteroides potencialmente perigosos
Asteroides com MOID inferior a 0,05 AU
Asteroides com período orbital inferior a 2 anos
Asteroides com diâmetro superior a 1 km

Esses indicadores permitem compreender rapidamente as principais características do conjunto filtrado.

📊 Resumo dos Asteroides

Uma visualização em barras apresenta a proporção de objetos que atendem a diferentes critérios, permitindo comparar características como:

Objetos com nome registrado
Asteroides potencialmente perigosos
Objetos próximos da Terra
Asteroides com órbitas mais rápidas
Objetos de maior luminosidade
Alta excentricidade orbital
Alto albedo
Diâmetro estimado
Asteroides de grande porte
🛰️ Distribuição por Classe Orbital

Um gráfico de rosca apresenta a distribuição das classes orbitais mais frequentes no conjunto de dados.

Essa visualização permite observar quais tipos de órbita possuem maior representatividade entre os asteroides analisados.

📏 Distribuição por Tamanho

Os asteroides são agrupados de acordo com seu diâmetro:

Categoria	Diâmetro
🟢 Pequenos	< 100 m
🟡 Médios	100 m – 1 km
🔴 Grandes	> 1 km

Essa classificação facilita a comparação entre os diferentes tamanhos encontrados no conjunto de dados.

🌎 MOID × Diâmetro

O gráfico de dispersão relaciona:

Eixo X: Minimum Orbit Intersection Distance (MOID)
Eixo Y: Diâmetro do asteroide

Os pontos são diferenciados de acordo com o status de PHA, permitindo observar a relação entre o tamanho dos objetos e sua distância orbital mínima em relação à Terra.

Uma referência de 0,05 AU é utilizada para destacar a região de monitoramento considerada relevante para a análise.

💡 Magnitude Absoluta × Diâmetro

Esta visualização explora a relação entre a magnitude absoluta (H) e o tamanho estimado dos asteroides.

Os pontos são diferenciados por classe orbital, permitindo observar como características de luminosidade e tamanho se relacionam entre diferentes grupos de asteroides.

📦 Excentricidade Orbital por Classe

Um boxplot permite comparar a distribuição da excentricidade orbital entre as classes orbitais mais frequentes.

Essa visualização ajuda a identificar diferenças no comportamento das órbitas e a observar a dispersão dos valores dentro de cada classe.

💡 Insights Automáticos

Além das visualizações, o dashboard apresenta observações baseadas nos dados atualmente filtrados.

Entre os insights gerados estão:

Percentual de asteroides potencialmente perigosos
Quantidade de objetos dentro da região de monitoramento
Classe orbital predominante
Presença de asteroides de grande porte
Mediana da magnitude absoluta (H)
Características relevantes encontradas após a aplicação dos filtros

Dessa forma, o usuário não precisa interpretar cada gráfico isoladamente para encontrar informações importantes.

🛠️ Tecnologias Utilizadas
Linguagem
🐍 Python
Análise e tratamento de dados
Pandas
Visualização
Plotly
Desenvolvimento do Dashboard
Streamlit
Interface
HTML/CSS
Google Fonts

O projeto utiliza uma identidade visual inspirada no universo espacial para tornar a experiência de exploração dos dados mais intuitiva e envolvente.

📂 Estrutura do Projeto
📁 Asteroid-Dashboard
│
├── 📄 nasanovoc_comentado.py
├── 📄 README.md
├── 📄 requirements.txt
│
├── 📁 data
│   └── 📄 asteroides.csv
│
└── 📁 imagens
    └── 🖼️ screenshots do dashboard

A estrutura pode variar de acordo com a versão utilizada do projeto.

⚙️ Como Executar
1. Clone o repositório
git clone URL_DO_SEU_REPOSITORIO
2. Acesse a pasta do projeto
cd Asteroid-Dashboard
3. Instale as dependências
pip install -r requirements.txt

Caso o arquivo requirements.txt não esteja disponível, instale manualmente:

pip install streamlit pandas plotly
4. Execute o dashboard
streamlit run nasanovoc_comentado.py

Depois, o Streamlit disponibilizará o endereço local para acessar a aplicação pelo navegador.

📊 Dados

O projeto utiliza um conjunto de dados de asteroides próximos à Terra contendo informações físicas e orbitais dos objetos.

Entre as variáveis utilizadas estão:

Nome e identificação do asteroide
Diâmetro
Magnitude absoluta (H)
Albedo
Excentricidade orbital
Período orbital
Classe orbital
MOID
Distância orbital
Status de potencialmente perigoso (PHA)
Fonte dos dados

NASA JPL — Small-Body Database

O catálogo da NASA/JPL reúne informações sobre pequenos corpos do Sistema Solar, incluindo asteroides e outros objetos.

🎓 Objetivo Acadêmico

Este projeto foi desenvolvido com o objetivo de colocar em prática conhecimentos adquiridos durante a formação em Ciência de Dados para Negócios, utilizando um conjunto de dados científico real como base para análise.

Mais do que apresentar informações sobre asteroides, o projeto busca demonstrar como dados brutos podem ser transformados em informações visuais e insights, facilitando a interpretação e a tomada de decisões a partir dos dados.

🌟 Aprendizados

Durante o desenvolvimento do projeto, foram trabalhados conceitos relacionados a:

Manipulação de dados com Pandas
Tratamento e organização de dados
Criação de visualizações com Plotly
Desenvolvimento de aplicações com Streamlit
Construção de filtros interativos
Criação de indicadores e métricas
Análise exploratória de dados
Organização de um projeto de análise de dados
Apresentação de informações por meio de dashboards
👩🏻‍💻 Desenvolvido por

Isabela Lemes

Estudante de Ciência de Dados para Negócios

📊 Dados • Tecnologia • Inteligência Artificial • Negócios
