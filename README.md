# Complex-Systems-Challenge
Marasigan, Ng

As the number of total agents increase, there is less money for each individual in the high and low pools as the chances of getting money each round lowers, as shown in Figures 1, 2, 3(5) and 4(6).

![Figure 1. Average money earned by each agent type with tau = 0.5 and population = 100](fig1.png?raw=true)
*Figure 1. Average money earned by each agent type with tau = 0.5 and population = 100*

![Figure 2. Average money earned by each agent type with tau = 1 and population = 100](fig2.png?raw=true)
*Figure 2. Average money earned by each agent type with tau = 1 and population = 100*

![Figure 3. Average money earned by each agent type with tau = 0.5 and population = 50](fig5.png?raw=true)
*Figure 3. Average money earned by each agent type with tau = 0.5 and population = 50*

![Figure 4. Average money earned by each agent type with tau = 0.5 and population = 50](fig6.png?raw=true)
*Figure 4. Average money earned by each agent type with tau = 1 and population = 50*

A higher tau value means that strategies that switch between pools a lot don’t gain as much of an advantage over the other strategies because of the costs incurred by switching in each round.

Safe agents perform better if the value of tau is higher, as they do not incur movement costs throughout the simulation, compared to the other strategies. Their wealth always increases at a steady pace.

Risky random agents generally performed the best out of all the other agents employing a different strategy, because they only switch between the low and high pools, leading to higher gains than the other agents whenever they get money in a single round.

Greedy agents perform better initially, but are beaten by risky random agents later on in the simulation. Figure 5(4) shows that greedy agents performed the best at the start but as time passes, they do not earn as much as they begin to compete amongst themselves. Another limiting factor is if the population grows, they would choose to stay in the stable pool because of their tendency not to go to the high or low pools if there are more than twenty agents occupying each.

![Figure 5. Average money earned by each agent type with tau = 1 and population = 10](fig4.png?raw=true)
*Figure 5. Average money earned by each agent type with tau = 1 and population = 10*

Although we initially thought that greedy would always win since they base their decisions based on the number of other agents that occupied the high and low pools, we found out that agents that employ a high-risk but high-reward strategy beat out all the other strategies in the long run.
