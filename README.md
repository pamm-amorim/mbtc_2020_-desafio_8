# MBTC 2020 - DESAFIO 8 - GRUPO FCA

Desafio 8 (FCA) da Maratona Behind the Code 2020

https://github.com/maratonadev-br/desafio-8-2020

Neste repositório está o flow do Node-RED submetido para o desafio, seguindo as regras de negócios, de acordo com o github do desafio.

Minha colocação nesse desafio foi 67º lugar. https://maratona.dev/pt/ranking?c=8

# OBJETIVO

Como objetivo principal, espera-se ter um dispositivo inteligente que é capaz de compreender sugestões de um motorista que dirige um veículo Fiat ou Jeep. Esse dispositivo será capaz de analisar o contexto do que está sendo dito em linguagem natural por um motorista, realizar análise de sentimento, e ao final ser capaz de sugerir outros veículos para test-drive ou review, além de sintetizar informações valiosas para equipes de engenharia responsáveis por melhorias nos automóveis.

Neste desafio serão utilizados diversos serviços da IBM Cloud, como o Watson Speech to Text (STT) para a transcrição de áudio, e o Watson Natural Language Understanding (NLU) para extração de entidades textuais e análise de sentimento. As falas do motorista deverão ser processadas em áudio e texto, e as entidades textuais pertinentes a identificação de componentes, ou critérios de avaliação dos veículos, deverão ser anotadas por um modelo de IA. Esses serviços serão todos integrados por meio de um framework ou tecnologia de escolha livre pelo participante, que além do modelo treinado também entregará uma API REST como solução.

# RESUMO DAS TAREFAS

1. Baixar o conjunto de [amostras de texto fornecido](./doc/source/dataset) para treinamento do WKS.
2. Criar uma instância do Watson Knowledge Studio.
3. Criar uma instância do Natural Language Understanding.
4. Usar o WKS para criar um modelo de anotação textual especializado, utilizando o dataset disponibilizado.
5. Encapsular o modelo criado anteriormente com o Watson Natural Language Understanding.
6. Criar uma instância do serviço Watson Speech-to-Text (STT).
7. Construir uma API integrando o STT e o NLU, que seja capaz de receber audio ou texto como entrada, e devolver uma recomendação de veículo e as entidades textuais extraídas juntamente com o sentimento associado a cada uma delas.
8. Analisar e testar **bem** a sua solução com o conjunto de [amostras de texto](./doc/source/dataset) e [amostras de áudio](./doc/source/dataset) fornecidos.
9. Submeter sua solução em [https://fca.maratona.dev](https://fca.maratona.dev) - neste desafio você terá apenas 1 chance de submissão.
