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

Luckily our dev team records a custom event every time an order is placed. Find out how many orders have been placed over the past 30 days and create a chart that you can share with your leadership team.

Felizmente, nossa equipe de desenvolvimento registra um evento personalizado toda vez que um pedido é feito. Descubra quantos pedidos foram feitos nos últimos 30 dias e crie um gráfico que você pode compartilhar com sua equipe de liderança.

# Dica grátis

The code for the custom event that the devs added is:
	app.RecordCustomEvent("OrderPlaced", map[string]interface{}{
        "OrderId":  orderID.String(),
    })

O código para o Custom Event que os desenvolvedores adicionaram é:
    app.RecordCustomEvent("OrderPlaced", map[string]interface{}{
         "OrderId": orderID.String(),
     })