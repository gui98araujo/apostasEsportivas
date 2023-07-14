# apostasEsportivas
Neste projeto pessoal, será desenvolvida uma análise aprofundada de dados relacionados ao mercado de apostas esportivas, com foco principal no mercado de futebol. Inicialmente, será analisado o mercado mais simples, que consiste em determinar o resultado de um jogo. Para essa análise, serão utilizados dados do site betexplorer e a linguagem Python juntamente com ferramentas como web scraping, a fim de obter dados sobre as odds esportivas das principais ligas de futebol em cada país.

Após obter um conjunto de dados por meio desse processo, será realizada a limpeza dos mesmos, excluindo valores nulos, jogos cancelados e jogos sem odds precificadas, entre outros critérios. Em seguida, uma análise abrangente dos dados será conduzida, gerando um relatório geral para cada resultado possível (vitória do time da casa, vitória do time visitante ou empate) utilizando a plataforma Power BI. Nessa análise, serão incluídos indicadores de lucratividade, quantidade de apostas e ROI (Return on Investment), permitindo a segmentação dos dados por país, liga, time e faixa de odds. O objetivo é obter insights que possam levar ao desenvolvimento de um método específico de aposta, com base em uma faixa de apostas na qual a casa de apostas não possa tirar vantagem dos clientes.

Posteriormente, será testada a criação de um modelo de redes neurais para calcular a probabilidade de cada evento ocorrer e, assim, precificar o valor esperado das odds. Para isso, serão criadas variáveis e verificada a importância delas para o modelo. Embora seja um modelo de classificação, não serão utilizadas métricas tradicionais de classificação, como acurácia, F1-score e precisão, para avaliar sua competência. Em vez disso, serão utilizadas métricas de dispersão, pois o objetivo é que as odds precificadas pelo modelo estejam o mais próximo possível das odds precificadas pelas casas de apostas.

Utilizando uma parte dos dados para teste, será possível verificar se é possível melhorar ainda mais a lucratividade com base nos insights obtidos. Serão observados pontos em que a aposta precificada esteja acima do valor estimado pelo modelo, buscando aumentar o volume de apostas. Vale ressaltar que o modelo selecionado foi gerado utilizando apenas ligas no formato de pontos corridos, já que em torneios de mata-mata muitos times não se enfrentam.
