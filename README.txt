                   POKÉAPI - ANÁLISE DE DADOS DE POKÉMON 

    Visão Geral: 

PokéAPI é uma aplicação interativa para explorar e analisar dados de Pokémon usando a PokéAPI. O projeto permite que os usuários selecionem Pokémon, visualizem suas estatísticas, habilidades, 
tipos e movimentos, além de receber sugestões de treinamento. Também inclui uma funcionalidade para exibir os cinco Pokémon mais fortes com base em uma análise comparativa.

    Funcionalidades: 

Busca de Pokémon: Obtém dados dos primeiros 10 Pokémon através da PokéAPI, incluindo suas estatísticas, habilidades, tipos e movimentos.
Sugestões de Treinamento: Recomendações personalizadas para aprimoramento de habilidades, com base nos status do Pokémon.
Comparação de Força: Identificação dos cinco Pokémon mais fortes entre os selecionados.
Visualização: Gráfico de pizza para visualizar as estatísticas de um Pokémon e uma tabela organizada com as informações detalhadas.

Para rodar o projeto localmente, siga as instruções abaixo: 

    Pré-requisitos:

* Python 3.x
* Jupyter Notebook (opcional, para análises interativas)
* Pandas para manipulação de dados
* Matplotlib para visualizações

    Como Usar: 

Após instalar as dependências, você pode explorar os dados executando os notebooks do repositório ou usando os scripts de análise.

Análises básicas: Use o notebook análise_basica.ipynb para explorar as estatísticas dos Pokémon, tipos, gerações e habilidades.
Análise Competitiva: O notebook analise_competitiva.ipynb traz informações sobre o uso de Pokémon em campeonatos, incluindo estatísticas de vitória e combinação de movimentos.
Visualizações: Gera gráficos comparativos, como distribuição de tipos e habilidades, principais Pokémon por geração e mais.

Distribuição de tipos: quais tipos são mais comuns ao longo das gerações?
Combinações eficazes: quais são as combinações de Pokémon que maximizam a cobertura de tipos em batalhas?
Desempenho em campeonatos uma análise dos Pokémon mais populares nas competições competitivas.

   Estrutura do Código: 

Função fetch_all_pokemon(): Busca dados de múltiplos Pokémon e organiza suas estatísticas.
Função suggest_training_with_llm(): Sugere estratégias de treinamento com base nos status do Pokémon.
Função fetch_pokemon_info(): Coleta informações detalhadas de um Pokémon e exibe em uma tabela e gráfico de pizza.
Função display_top_pokemon(): Compara as estatísticas e exibe os cinco Pokémon mais fortes.


