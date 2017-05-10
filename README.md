# Hands On Azure - Palestra Azure App Service
O que é o Azure App Service? Demonstração do serviço Logic Apps!
Apresentação: https://goo.gl/HUa3Pw

# Exemplo com o Logic Apps
O objetivo desse exemplo é procurar no twitter o texto _#HandsOnAzure_ e enviar um email contendo o nome, o texto e a localização da pessoa que fez o _tweet_.

## Requisitos
* Uma conta no Azure
* Uma conta no Twitter
* Uma conta de email Google

## Criando o exemplo
1. Crie um Logic App no portal do Azure

![alt text][tutorial1]

2. Crie uma Logic App em branco
3. Clique no campo _Search all services and triggers_ e procure por _Twitter_ e o escolha.
4. Entre com sua conta do _Twitter_
5. No bloco do Twitter, digite o texto _#HandsOnAzure_ em _Search Text_ e altere _Frequency_ e _Interval_ para _Second_ e 15, respectivamente
6. Crie uma nova ação e procure por _send email_ e escolha _Gmail - Send email_
7. Entre com sua conta do Gmail
8. No bloco do Gmail, digite o email que receberá as menssagens em _to_. No _subject_ (assunto) e no _body_ escolha os dados que deseja receber do Twitterd
9. Clique em _Save_ e em _Run_, o _Azure deverá mostrar uma menssagem de sucesso
10. Em _Overview_ é possível ver o histórico de acionamento (_trigger_) do Logic App e quais canceladas (_Skipped_) e quais foram bem sucedidas (_Success_)

[step1]:  "Passo 1"