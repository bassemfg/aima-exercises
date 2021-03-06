[Exercise 17.12](ex_12/)

Consider an undiscounted MDP having three states, (1, 2, 3), with
rewards $-1$, $-2$, $0$, respectively. State 3 is a terminal state. In
states 1 and 2 there are two possible actions: $a$ and $b$. The
transition model is as follows:

-   In state 1, action $a$ moves the agent to state 2 with probability
    0.8 and makes the agent stay put with probability 0.2.

-   In state 2, action $a$ moves the agent to state 1 with probability
    0.8 and makes the agent stay put with probability 0.2.

-   In either state 1 or state 2, action $b$ moves the agent to state 3
    with probability 0.1 and makes the agent stay put with
    probability 0.9.

Answer the following questions:

1.  What can be determined *qualitatively* about the
    optimal policy in states 1 and 2?

2.  Apply policy iteration, showing each step in full, to determine the
    optimal policy and the values of states 1 and 2. Assume that the
    initial policy has action $b$ in both states.

3.  What happens to policy iteration if the initial policy has action
    $a$ in both states? Does discounting help? Does the optimal policy
    depend on the discount factor?
