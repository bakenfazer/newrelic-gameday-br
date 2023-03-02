+++
title = "Ch Check it out"
chapter = true
weight = 8
pre = "<b>8. </b>"
+++

### Ch Cha Ch Check out the Checkout Service

# Issue:

![Through the Roof Tweet](/images/through-the-roof.png)

# Challenge

Luckily our dev team records a custom event every time an order is placed. Find out how many orders have been placed over the past 30 days and create a chart that you can share with your leadership team.

# Free Hint

The code for the custom event that the devs added is:
	app.RecordCustomEvent("OrderPlaced", map[string]interface{}{
        "OrderId":  orderID.String(),
    })