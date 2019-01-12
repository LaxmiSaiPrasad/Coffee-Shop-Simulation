# Coffee-Shop-Simulation
This code is written to perform simulation of Coffee Shop. Following are the features of the problem
1) The invenotry is assumed to be "infinity"
2) The capacity of the shop is assumed "infinity"
3) Inter-arrival time is considered to be exponential
3) Limitations have been implemented only in form of "Cashiers" and "Servers" employed in the coffee shop, where
3.a) "Cashiers" are those who take the order and process transaction
3.b) "Servers" are the ones who are responsible for realization of order
3.c) "Cashiers" and "Servers" roles are stictly differentiated, hence there is no interaction or transfer of personnels between 
the groups
4) Of all "Servers" and "Cashiers" available, only those with lowest index are engaged at any given point (essentially to replicate
simulation studies)
5) The ORDER TIME currently is FIXED, and is LINEAR FUNCTION of NUMBER OF UNIQUE ITEMS ORDERED of the menu
6) Customer will always order EQUAL TO or LESS THAN number of items sold by the coffee shop

The code is flexible with regards to following aspects:
1) Flexibility to choose number of items the simulator wants to sell
2) Assuming that the simulator also thinks like me, for every item in coffee shop menu to assign normal distribution 
to random variable that is representative of time it takes to make any item, the code is flexible in parameters that can
be assigned
3) The simulator has the flexibility in terms of fixing cost of the item

What we have no control over / is random?
The number of items that customer can order, and their quantities are random

What's the BIG PICTURE ?
Well, at coffee shop, the time of stay is affected by following:
1) Number of Cashiers
2) Number of Servers
3) Number of Machines
4) Orders given by the previous compatriots
We get an insight into:
1) Wait times
2) Number of personnels that sufficiently can run the coffee shop at expense of agreeable increase in wait time
3) Revenue generation time 
4) Value of business proposition when opening new coffee shop
Despite availibility of softwares like ARENA, SIMIO, FlexSim coding it offers flexibility to study greater variety of interactions. 

What more can be done ?
1) Fixing the capacity of coffee-shop
2) Maintaining Invenotry limits of the products in menu

Good luck !
Feel free to suggest more that can be done on this
