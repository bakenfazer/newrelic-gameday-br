+++
title = "Ch-Cheque isso"
chapter = true
weight = 8
pre = "<b>8. </b>"
+++

### Co Co Con Confira o serviço de caixa

# Issue:

![Through the Roof Tweet](/images/through-the-roof.png)

# Desafio

Felizmente, nossa equipe de desenvolvimento registra um 'custom event' toda vez que um pedido é feito. Descubra quantos pedidos foram feitos nos últimos 30 dias e crie um gráfico que você pode compartilhar com sua equipe de liderança.

# Dica grátis

O código para o Custom Event que os desenvolvedores adicionaram é:
    app.RecordCustomEvent("OrderPlaced", map[string]interface{}{
         "OrderId": orderID.String(),
     })