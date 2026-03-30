## Figure 1. Decentralized Coupled HalfCheetah task with neither fully global nor fully local observations.

![Decentralized Coupled HalfCheetah task with neither fully global nor fully local observations.](nocoh_plot_nocoh_mas3ac_neighbour.png)

---

## Table 1: Non-cooperative Coupled HalfCheetah (Partially Observable)

| Algorithm | Agent 0 Reward       | Agent 0 Cost     | Agent 1 Reward       | Agent 1 Cost     | Agent 2 Reward       | Agent 2 Cost     |
| --------- | -------------------- | ---------------- | -------------------- | ---------------- | -------------------- | ---------------- |
| IPPO      | 902.29 ± 386.41      | 451.38 ± 305.37  | 904.99 ± 389.86      | 451.38 ± 305.37  | 905.91 ± 388.62      | 451.38 ± 305.37  |
| MAS³AC    | **2454.45 ± 161.17** | **5.07 ± 10.41** | **2461.52 ± 155.87** | **5.07 ± 10.41** | **2454.82 ± 159.71** | **5.07 ± 10.41** |

<br>

| Algorithm | Agent 3 Reward       | Agent 3 Cost     | Agent 4 Reward       | Agent 4 Cost     | Agent 5 Reward       | Agent 5 Cost     |
| --------- | -------------------- | ---------------- | -------------------- | ---------------- | -------------------- | ---------------- |
| IPPO      | 898.48 ± 395.57      | 432.92 ± 273.22  | 900.26 ± 397.68      | 432.92 ± 273.22  | 903.87 ± 397.26      | 432.92 ± 273.22  |
| MAS³AC    | **2427.87 ± 194.58** | **6.32 ± 12.78** | **2429.76 ± 199.06** | **6.32 ± 12.78** | **2427.75 ± 194.20** | **6.32 ± 12.78** |

---

## Figure 2. Reward and safety cost comparison when using only safety constraint, only stability constraint, and both safety and stability constraints.

![Reward and safety cost comparison when using only safety constraint, only stability constraint, and both safety and stability constraints.](safestable_plot_final_custom_steps.png)

---

## Figure 3. Reward and safety cost comparison for two tasks with different K values for learning rate design.

![Reward and safety cost comparison for two tasks with different K values for learning rate design.](differentK_plot_final_custom_steps.png)

---

## Table 2: Comparison with Different K Values

| Algorithm | Ant Reward          | Ant Cost        | Coupled Reward      | Coupled Cost    |
| --------- | ------------------- | --------------- | ------------------- | --------------- |
| HAPPO     | 41.29 ± 215.89      | 311.96 ± 67.96  | 2197.22 ± 112.77    | 230.28 ± 67.11  |
| K=1000    | 698.50 ± 181.70     | 4.27 ± 6.67     | 2567.26 ± 51.97     | 17.96 ± 32.99   |
| K=2500    | 970.57 ± 92.38      | **0.59 ± 1.45** | 2609.67 ± 49.43     | 0.80 ± 3.42     |
| K=5000    | **1064.21 ± 84.91** | 3.14 ± 11.29    | **2611.20 ± 92.02** | **0.19 ± 0.50** |
