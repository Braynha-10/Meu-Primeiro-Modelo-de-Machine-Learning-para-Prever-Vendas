⚡ Storytelling - Previsão de Vendas de Energéticos com Machine Learning
🎯 O Desafio
Imagine que você é o dono da TurboPower Drinks, uma rede de lojas especializadas em bebidas energéticas espalhadas por pontos estratégicos da cidade: perto de faculdades, academias, escritórios e centros comerciais.

Com o tempo, você percebe que as vendas de energéticos variam bastante durante o dia e ao longo da semana. Na segunda de manhã, o movimento é diferente da sexta à tarde. Você já percebeu padrões, mas não consegue traduzi-los em números consistentes para ajudar na tomada de decisão.

A pergunta é simples:

Como prever quantos energéticos serão vendidos em determinado horário e dia da semana?

Se você conseguir prever isso com precisão, poderá:

Organizar melhor o estoque,

Otimizar a produção e a logística,

Planejar promoções com base na demanda,

E, claro, aumentar seus lucros!

🤖 A Solução com Machine Learning
Para resolver esse problema, decidi aplicar Machine Learning, mais especificamente um modelo de regressão preditiva, para estimar a quantidade de energéticos vendidos com base em duas variáveis principais:

Dia da Semana (segunda a domingo)

Hora do Dia (0h às 23h)

Essas variáveis refletem diretamente o comportamento das pessoas — seja no ritmo de trabalho, nos estudos, no lazer ou nos treinos.

🔍 Como o Projeto Foi Feito
Geração dos Dados:
Criei um conjunto de dados simulando 200 registros com vendas reais de energéticos, respeitando padrões lógicos:

Mais vendas aos finais de semana e no fim do expediente.

Picos nas manhãs de segunda a sexta.

Horários de menor movimento durante a madrugada.

Exploração Visual:
Utilizei gráficos de dispersão para entender a correlação entre as variáveis. A visualização já mostrava uma tendência clara: certos horários e dias vendem mais.

Modelo Preditivo:

Apliquei o One-Hot Encoding para tratar os dias da semana.

Dividi os dados em treino e teste.

Treinei um modelo de Regressão Linear simples com a biblioteca scikit-learn.

Avaliação do Modelo:

Métricas como R² e MAE mostraram que o modelo teve uma boa performance.

Com ele, é possível fazer previsões rápidas, como:

Quantos energéticos devo esperar vender às 14h de um sábado?

🚀 Impacto Esperado
Com o modelo em funcionamento, a TurboPower Drinks ganha um superpoder: antecipar a demanda.
Isso significa menos desperdício, mais eficiência, mais vendas e um time de vendas preparado para o fluxo real de clientes.

E esse é só o começo: a mesma base pode ser ampliada futuramente com variáveis como clima, eventos na cidade, localização da loja, etc.
