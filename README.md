# genre_generator_IA

Este projeto utiliza Python e a API GPT-3 da OpenAI para categorizar filmes e séries da Netflix por gênero.
Ele começa lendo um CSV contendo detalhes sobre várias produções, incluindo uma coluna de descrições. 
Em seguida, inicializa a API GPT-3 com uma chave específica.
O script define uma função que toma uma descrição de filme ou série como entrada e consulta o modelo GPT-3 para determinar o gênero mais apropriado.
Esta função é então aplicada a cada linha do DataFrame para criar uma nova coluna contendo os gêneros inferidos. Finalmente, o DataFrame atualizado é exibido.
