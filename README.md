# Projeto_HardwarIA
Recomendação de Componentes para Computador usando IA

Este projeto visa recomendar configurações ideais de componentes de computador com base em um orçamento fornecido pelo usuário e seu objetivo de uso do computador. O sistema utiliza um algoritmo genético para encontrar a melhor combinação de componentes, levando em consideração os pesos atribuídos a cada categoria de peças e o limite de preço.

#Conjunto de Dados
O conjunto de dados contém informações sobre diferentes componentes de computador, incluindo placas-mãe, processadores, memórias RAM, placas de vídeo, fontes de alimentação, sistemas de resfriamento e opções de armazenamento. Cada componente tem um preço associado e uma pontuação que reflete sua qualidade ou desempenho.

#Algoritmo Genético
O algoritmo genético é utilizado para iterar por várias combinações possíveis de componentes e encontrar a configuração mais adequada dentro do orçamento fornecido. Ele realiza seleção de pais, crossover e mutação para gerar novas configurações e avalia cada configuração com base em seu custo total e pontuação.

#GEMINI AI
Além do algoritmo genético, o projeto incorpora a GEMINI AI para verificar a validade da configuração recomendada. A AI avalia a compatibilidade dos componentes, a eficiência do sistema de resfriamento, o consumo de energia e fornece feedback sobre se a configuração atende às necessidades do usuário.

#Como Usar
Execução do Algoritmo Genético: O algoritmo genético é executado para encontrar a melhor configuração dentro do orçamento.
Input de Dados: O usuário deve fornecer um orçamento e seu objetivo de uso do computador.
Execução da GEMINI AI: A configuração recomendada é verificada pela GEMINI AI para garantir sua validade e atendimento aos requisitos do usuário.
Saída de Resultados: A configuração recomendada, seu custo total e uma explicação sobre as escolhas feitas são exibidos ao usuário.
