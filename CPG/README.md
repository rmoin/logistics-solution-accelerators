[image1]: ProductDelivery.gif "Trained Agent"

# Logistics and Supply Chain Solution

The Logistics and Supply Chain solution accelerators can help you manage logistics and supply chain systems and mitigate challenges using AI:

- Design and implement a sustainable and resilient supply chain
- Manage the bi-directional flow and storage of goods and services
- Track information between the point of origin and point of consumption
- Minimize operational cost and boost resource utilization
- Minimize supply-chain disruptions and adapt to changing customer demands

AI Agent has a unique ability to help you optimize competing factors for efficiency and efficacy.


![Trained Agent][image1]

Manufacturers optimize their delivery tactics to maximize profit and minimize product wait times. 

When networks of manufacturing facilities and distributors are spread across a large area, they sometimes struggle to manage deliveries. They use simulation models to explore cost-effective ways to adjust deliveries. In those simulations, reinforcement learning can surface the best possible routes and decisions quickly.

This will deploy a solution accelerator using a UI by clicking the button below:

![Deploy To Azure](https://aka.ms/deploytoazurebutton)

## Results
The results obtained were extremely good. The method produced a waiting time more than four times shorter than the Nearest Agent heuristic. The reason RL beat the other heuristics by so much difference is because it could account for the fact that sometimes factories get overloaded by demand. The main difference here is that RL policy learned to dynamically assign orders. When the nearest factory to a distribution center is about to reach capacity the RL agent places orders at factories further away. This helps match production capacity to demand. The other methods are static and cannot adapt to abrupt changes in demand.
