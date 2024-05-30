# fm23-machine-learning
Criação de um algoritmo para auxiliar na jogabilidade do jogo "Football Manager 2023" a partir de machine learning e análise de dados. Este é um projeto para tentar criar um auxílio, e dessa forma, não há nenhuma certeza de que irá ser criada uma ferramenta com sucesso!

# Exportação dos dados
Para aprender a exportar os dados do Football Manager para um arquivo .csv para conseguir utilizar esse algoritmo, acesse o arquivo "tutorial.md" ([clique aqui](https://github.com/JoaoPedroMoro/fm23-machine-learning/blob/main/tutorial.md)) que lá está o passo a passo de como fazer isso.

# Buscar o(s) jogador(es) indicado(s)
Da mesma forma que foi ensinado no tutorial a como colocar filtros, você deve selecionar o filtro de ID único, conforme mostrado na imagem a seguir.
![imagem](images/19.png)
Após feito isso, coloque o ID, do jogador que você quer ver e ele aparecerá na tela.

# Posições
O código possui (por enquanto) algumas posições do jogo e seus atributos recomendados para a posição, assim, para buscar jogadores para uma determinada posição, se ela estiver disponível nas posições existentes, o usuário deve utilizara parte do código "Busca de jogador para posição".

# Busca de jogador para posição
Nesse trecho do código, aparecerá para o usuário a lista de posições disponíveis e ele deve digitar CORRETAMENTE, igual a que foi listada para ele, e selecionar o valor base dos atributos. Após feito isso, o programa irá buscar na base de dados disponível todos os jogadores que possuem pelo menos o valor informado para os atributos recomendados da posição informada. Se forem encontrados jogadores, será disponibilizado um arquivo .csv, com o nome "resultados.csv", com o ID Único, a Nacionalidade, o Valor estimado e a idade. Caso não forem encontrados jogadores na base de dados, será informado na saída.