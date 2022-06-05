# trabalho-js-2b
A ideia do projeto é gerar um iphone que liga ou desliga ao deslizar o mouse ou dar um click no botão da função desejada, e quebra ao dar dois clicks na imagem. 

Dentro do body foi aberta uma div e dentro da mesma a img, para conter a imagem do iphone desligada, logo foi aberto outra div para conter os botões de ligar e desligar, usando a tag button para tal. 

Terminado o HTML no CSS foi utilizado as tags flex direction para direção de coluna e o align-items para alinhar no centro tudo que estava no header, main, e a tag width para colocar os botões do mesmo tamanho. 

No Javascript foi aberto uma const para deixar o valor fixo da ação que eles executam, foi criado uma function para executar a ação de ligar, usando a tag .addEventListener para que após o click ele execute a função dita anteriormente, e o mesmo foi feito para a função de desligar, usando novamente o addEventListener para um comando que ao passar o mouse em cima da iphone ele ligue e ao tirar o mouse ele desligue, também foi criado uma function para que  que a imagem da iphone quebrado seja usada ao executar a função de dois clicks, e para que o iphone permaneça quebrado mesmo após passar o mouse em cima, foi utilizada a function e dentro da mesma a tag indexOff para procurar a palavra 'quebrada' usando > -1 para que a condição retorne verdadeira ou falsa, já que ele retorna um número maior que –1 quando se encontra a palavra desejada, e quando não encontrado retorna um númeromaior que -1 e mantenha o iphone quebrado, para isso foi usado o if como condição. 
