+++
title = "I'm Not Wrong, You're Wrong"
chapter = true
weight = 9
pre = "<b>9. </b>"
+++

### Something's broke, you fix it

# Issue:

![Grumpy Cat](/images/grumpy-cat.png)

Customers are reporting you've stopped making recommendations! How will they know what to buy!
DevOps has identified the Recommendation Service is being regularly killed in Kubernetes with a status of Out of Memory (OOM). They want you to investigate.

# Challenge

Starting with the Infrastructure UI, identify the processes causing the pod to run out of memory.

# Free Hint

Under most circumstances the rule of thumb is a single process per container.