# ProjetoAnaliseDadosIncidenciaCovid
Este projeto foi desenvolvido com o intuito de, utilizando uma base de dados significativa, ser capaz de extrair informações necessárias e que foram julgadas pertinentes para o contexto.

# Instruções
O código foi construído com base no arquivo com os microdados da Covid-19. Assim, inicialmente, é preciso que você tenha este arquivo baixado. O link para acessá-lo e baixá-lo está aqui: 
https://www.saopaulo.sp.gov.br/wp-content/uploads/2023/08/20230808_Casos_e_obitos_ESP.zip
Após obter o arquivo, é necessário que você tenha o software jupyter instalado na sua máquina para que o arquivo consiga ser lido e rodado da melhor forma possível.
Assim, tendo os dois requisitos acima, basta acessar o arquivo script através do jupyter, alterar a variável path para se adequar ao seu diretório e rodar o código!

# Explicação
A necessidade de ter desenvolvido este código surgiu para responder as seguintes questões:
1- Existe diferença de incidência de covid entre homens e mulheres?
2- Faça um gráfico da mortalidade por faixas de idade
3- Qual a doença pré-existente mais provável de se encontrar numa pessoa com covid?
4- Baseado nesses dados, faça um modelo que estime a probabilidade da pessoa morrer, uma vez que está contaminada com covid, e considerando os inputs de idade, gênero e doenças pré-existentes

Cada item no arquivo script está demarcado e explicado, seja para facilitar a compreensão do código ou para apresentar a explicação dos dados. O item 4 é o mais complexo, entretanto, possui uma sintaxe bem simples. Eu utilizei um conceito básico de análise de dados que é a regressão linear; ele consiste em uma técnica que utiliza matemática para conseguir encontrar as relações entre dois fatores de dados. Em seguida, essa relação é usada para prever o valor de um desses fatores com base no outro. Dessa forma, fui capaz de, a partir do input do usuário para descrever uma pessoa, conseguir realizar uma previsão conforme a base de dados de Covid-19. 
