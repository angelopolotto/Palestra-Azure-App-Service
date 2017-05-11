# __Hands On Azure - Palestra Azure App Service__
O que é o __Azure App Service__? Demonstração do serviço __Logic Apps__!

Apresentação: https://goo.gl/HUa3Pw

# Exemplo com o __Logic Apps__
O objetivo desse exemplo é procurar no __Twitter__ o texto __#HandsOnAzure__ e enviar um email contendo o nome, o texto e a localização da pessoa que fez o _tweet_.

## Requisitos
* Uma conta no __Azure__
* Uma conta no __Twitter__
* Uma conta de email __Google__

## Criando o exemplo
1. Crie um __Logic App__ no portal do __Azure__

![alt text][step11]

![alt text][step12]

2. Crie um __Logic App__ em branco

![alt text][step21]

3. Clique no campo _Search all services and triggers_ e procure por __Twitter__ e o escolha.

![alt text][step31]

![alt text][step33]

4. Entre com sua conta do __Twitter__

![alt text][step41]

![alt text][step42]

5. No bloco do __Twitter__, digite o texto __#HandsOnAzure__ em _Search Text_ e altere _Frequency_ e _Interval_ para _Second_ e 15, respectivamente

![alt text][step51]

6. Crie uma nova ação e procure por _send email_ e escolha _Gmail - Send email_

![alt text][step61]

![alt text][step62]

7. Entre com sua conta do Gmail

![alt text][step71]

![alt text][step72]

8. No bloco do Gmail, digite o email que receberá as menssagens em _to_. No _subject_ (assunto) e no _body_ escolha os dados que deseja receber do Twitter

![alt text][step81]

9. Clique em _Save_ e em _Run_, o __Azure__ deverá mostrar uma menssagem de sucesso

![alt text][step91]

![alt text][step92]

10. Execute alguns testes

![alt text][step101]

![alt text][step102]

11. Em _Overview_ é possível ver o histórico de acionamento (_trigger_) do Logic App e quais canceladas (_Skipped_) e quais foram bem sucedidas (_Success_)

![alt text][step111]

12. Vale ressaltar que a rotina buscará qualquer _tweet_ que contém o texto __#HandsOnAzure__ 

[step11]: https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2016.57.03.png?raw=true "Passo 1"

[step12]: https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2016.58.12.png?raw=true "Passo 1"

[step21]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2016.58.50.png?raw=true "Passo 2"

[step31]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2016.59.14.png?raw=true "Passo 3"

[step32]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2016.59.14.png?raw=true "Passo 3"

[step33]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.00.18.png?raw=true "Passo 3"

[step41]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.00.37.png?raw=true "Passo 4"

[step42]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.01.03.png?raw=true "Passo 4"

[step51]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.08.13.png?raw=true "Passo 5"

[step61]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.09.05.png?raw=true "Passo 6"

[step62]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.12.54.png?raw=true "Passo 6"

[step71]: https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.13.09.png?raw=true "Passo 7"

[step72]: https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.13.41.png?raw=true "Passo 7"

[step81]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.31.38.png?raw=true "Passo 8"

[step91]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.23.12.png?raw=true "Passo 9"

[step92]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.23.34.png?raw=true "Passo 9"

[step101]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.35.54.png?raw=true "Passo 10"

[step102]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.37.04.png?raw=true "Passo 10"

[step111]:
https://github.com/angelopolotto/Palestra-Azure-App-Service/blob/master/images/Screen%20Shot%202017-05-09%20at%2017.39.26.png?raw=true "Passo 10"