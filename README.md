# Reinforcement-Learning-MPs
 Reinforcement Learning-UIUC-CS course projects

## Project 1: Cart Pole
This environment corresponds to the version of the cart-pole problem described by Barto, Sutton, and Anderson in "Neuronlike Adaptive Elements That Can Solve Difficult Learning Control Problem". A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The pendulum is placed upright on the cart and the goal is to balance the pole by applying forces in the left and right direction on the cart.

[Cart Pole](https://www.gymlibrary.dev/environments/classic_control/cart_pole/)

 *  **MDP & Bellman Equation**: Collect trajectory from simulator, set up MDP, compute infinite-horizon value function.

 *  **Random Search Learner**: randomly generate policies, evaluate by sampling trajectory as baseline.
 
 *  **Policy Gradient**: Softmax parametrization of policy, update theta directly with bootstrap target gradient ascent.

 *  **Actor-Critic**: Critic - Value Prediction Model on every state. Actor - Optimizing policy using policy gradient ascent.
  
## Project 2: Taxi
The Taxi domain was introduced in the paper "The MAXQ Method for Hierarchical Reinforcement Learning" by Thomas G. Dietterich in ICML 1998.

![taxi](https://github.com/QiLong25/Reinforcement-Learning-MPs/assets/143149589/308d2bbb-11bc-4c78-a944-5036291e453e)

[Taxi](https://pdfs.semanticscholar.org/fdc7/c1e10d935e4b648a32938f13368906864ab3.pdf)

 *  **Value Iteration Algorithm**.

 *  **Policy Evaluation Algorithm**.

## Disclaimer

THIS PROJECT IS INTENDED FOR WORK DISPLAY AND SHARING PURPOSES ONLY. THE CODE AND MATERIALS PROVIDED HERE SHOULD NOT BE SUBMITTED AS YOUR OWN WORK IN ANY FORM. USE OF THIS CODE FOR ACADEMIC ASSIGNMENTS OR EXAMS WITHOUT PROPER ATTRIBUTION OR PERMISSION MAY CONSTITUTE ACADEMIC MISCONDUCT INCLUDING PLAGIARISM. THE AUTHOR OF THIS PROJECT IS NOT RESPONSIBLE FOR ANY CONSEQUENCES ARISING FROM THE IMPROPER USE OF THIS CODE.

 *  **Policy Iteration Algorithm**: use policy evaluation as sub-routine.

 *  **TD(0)**: one-step bootstrap estimating value function of a policy.

 *  **Q-Learning**: one-step bootstrap target optimizing policy.

 *  **Function Approximation**: Linear approximation with Fourier basis.

![Q-Learning](https://github.com/QiLong25/Reinforcement-Learning-MPs/assets/143149589/0152f2ba-3e78-4417-bc66-cfb5f23efd67)






