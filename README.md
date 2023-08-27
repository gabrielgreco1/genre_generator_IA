# genre_generator_IA

Este projeto utiliza Python e a API GPT-3 da OpenAI para categorizar filmes e séries da Netflix por gênero.
Ele começa lendo um CSV contendo detalhes sobre várias produções, incluindo uma coluna de descrições. 
Em seguida, inicializa a API GPT-3 com uma chave específica.
O script define uma função que toma uma descrição de filme ou série como entrada e consulta o modelo GPT-3 para determinar o gênero mais apropriado.
Esta função é então aplicada a cada linha do DataFrame para criar uma nova coluna contendo os gêneros inferidos. Finalmente, o DataFrame atualizado é exibido.
O dataset original do projeto contém 9.000 linhas, e como (ainda) não sou um milionário, tive que restringir a apenas 10 linhas, para não consumir tanto dos meus suados 5$ que tenho de crédito de token na openai.

Utilizei um dataset do Kaggle para realizar este projeto. URL do dataset completo:

https://www.kaggle.com/datasets/shivamb/netflix-shows
