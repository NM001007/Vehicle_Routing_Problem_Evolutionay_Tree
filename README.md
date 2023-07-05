# Vehicle_Routing_Problem_Evolutionay_Tree

This an implementation of the paper proposed by Niu et al. in 2021, entitled "An improved learnable evolution model for solving multi-objective vehicle routing problem with stochastic demand".

Briefly speaking, the paper uses evolution algorithm along with decision tree classifier to solve the vehicle routing problem in which the clients have stochastic demands. Moreover, several objectives have been considered in this algorithm including the distance, total time spent, and the number of sub-routes which is also referred to as the number of vehicles.

The implemented algorithm is then tested on Solomon dataset and the results are reported.

## Simulation Results

### Total Route Distance
The following figure illustrates the toatl distance values of the routes found by IMOLEM method, applied on various problem instances of the Solomon vehicle routing dataset.

![IMOLEM_Distance_2550100](https://github.com/NM001007/Vehicle_Routing_Problem_Evolutionay_Tree/assets/131379171/7aed2f58-a3db-4b4f-b1ed-a91b4940b20d)

### Number of Sub-Routes
The figure below shows various number of sub-routes for the routes found by IMOLEM method, applied on various problem instances of the Solomon vehicle routing dataset.
![IMOLEM_Number of subroutes_2550100](https://github.com/NM001007/Vehicle_Routing_Problem_Evolutionay_Tree/assets/131379171/95ee8eea-2aad-4186-8f07-8cf39b5a0bbe)


## Reference
@article{niu2021improved,
  title={An improved learnable evolution model for solving multi-objective vehicle routing problem with stochastic demand},
  author={Niu, Yunyun and Kong, Detian and Wen, Rong and Cao, Zhiguang and Xiao, Jianhua},
  journal={Knowledge-Based Systems},
  volume={230},
  pages={107378},
  year={2021},
  publisher={Elsevier}
  }
