# Reinforcement-Learning-MPs
 Reinforcement Learning-UIUC-CS course assignments

## MP1: Cartpole
This environment corresponds to the version of the cart-pole problem described by Barto, Sutton, and Anderson in "Neuronlike Adaptive Elements That Can Solve Difficult Learning Control Problem". A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The pendulum is placed upright on the cart and the goal is to balance the pole by applying forces in the left and right direction on the cart.

[OpenAI gym doc](https://www.gymlibrary.dev/environments/classic_control/cart_pole/)

 *  Collect Trajectory from Simulator: collect (state, action, reward) triples given policy.

 *  Markov Decision Process: setup has state, action, transition, reward, discount factor spaces.
 
 *  Bellman Equation: compute infinite-horizon value function.

 *  Random Search Learner: randomly generate policies, evaluate by sampling trajectory, output optimum.
  
## MP2: Taxi
The Taxi domain was introduced in the paper "The MAXQ Method for Hierarchical Reinforcement Learning" by Thomas G. Dietterich in ICML 1998.

[Taxi Setup](https://pdfs.semanticscholar.org/fdc7/c1e10d935e4b648a32938f13368906864ab3.pdf)
![taxi](https://github.com/QiLong25/Reinforcement-Learning-MPs/assets/143149589/308d2bbb-11bc-4c78-a944-5036291e453e)

 *  Value Iteration Algorithm.

 *  Policy Evaluation Algorithm.

 *  Policy Iteration Algorithm: use policy evaluation as sub-routine.
