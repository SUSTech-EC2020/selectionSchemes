# selectionSchemes

### Yu Wu
Geometic ranking vs roulette wheel parent selection
based on elitism (always copy 10% best ) + (μ,λ) selection ( λ = 2μ )
### alpha = 0.01
![arithmetic+gaussian2](./figures/geometic_vs_vanilla.png)
![log_arithmetic+gaussian](./figures/geometic_vs_vanilla_2.png)

### alpha = 0.1
![gvv2](./figures/g_vs_v_2.png)
![gvv](./figures/g_vs_v.png)

### Ouyang Yicheng

POPULATION_SIZE = 30

MAX_EVALUATION = 500000

DIMENSION = 30

MUTATE_RATE = 0.1

ALPHA = 0.4

LAMBDA = int(POPULATION_SIZE * 0.4)

![](./figures/oyyc.png)

### Chao Pan

Single arithmetic + Nonuniform using Cauchy   
MIN = -1.28       
MAX = 1.28      
N = 30    
POPULATION_SIZE = 30    
GAMMA = 0.1   
ALPHA = 0.4   
UNIFORM_MUTATION_RATE = 1 / N   
MAX_EVALUATION = 50000    
REPEAT_TIMES = 10   

CROSSOVER_RATE = 0.5    
MUTATION_RATE = 0.5   
![img](./figures/myplot.png)


### Hao Tan

Recombination operator: arithmetic\
Mutation operator: uniform\
ALPHA = 0.4\
CROSSOVER_RATE = 0.1\
MUTATION_RATE = 0.1

Record the best so far\
![img](./figures/tanhao.png)
