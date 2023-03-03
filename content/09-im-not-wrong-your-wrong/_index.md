+++
title = "Eu não estou errado, você está errado"
chapter = true
weight = 9
pre = "<b>9. </b>"
+++

### Algo está quebrado, você conserta

# Issue:

![Grumpy Cat](/images/grumpy-cat.png)

Os clientes estão relatando que você parou de fazer recomendações! Como eles saberão o que comprar!
O DevOps identificou que o serviço de recomendação está sendo eliminado regularmente no Kubernetes com um status de: Out of Memory (OOM). Eles querem que você investigue.

# Desafio

Começando com a Infrastructure UI, identifique os processos que estão fazendo com que o pod: 'out of memory'.

# Dica grátis

Na maioria das circunstâncias, a regra geral é um único processo por contêiner.