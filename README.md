# Reinforcement_Learning
 
In this repository, we include 3 different seminars where we cover Dynamic Programming, its approximate version and an specific Soft Policy Iteration algorithm. 

All folders containing the files are based on the same problem: comparing the performances of different policies when dealing with a queue of users, from 0 to 100: actions, costs and rewards are common throughout the folders.

To begin with, in Dyanmic Programming we will be computing the value functions associated to each policy type (lazy and agressive) and comparing the obtained results for each one of them. We are going to be implementing the two methods we have been proposed: power iteration and directly solving the Bellman equations. Furthermore, we will be obtaining the optimal policy using the two following methods: policy iteration and value iteration; we will be comparing the obtained optimal policy with both lazy and aggressive policies from the first part of the problem.

Then, in Approximate Dynamic Programming we will begin equally as before, but now implementing two other methods: temporal difference and least squares temporal difference. Moreover, we will be obtaining the optimal policy using an approximated policy iteratio and comparing the obtained optimal policy with the ones from the first problem folder, by means of: firstly, plotting the value functions of the approximated (with 10 and 100 iterations); secondly, showing the final policies obtained in each case, by computing the corresponding service rates and plotting them.

Finally, in Soft Policy Iteration we will be using the LSTD implementation from the previous problem set and implementing a soft policy iteration method, where the initial policy is set as a uniform policy and, at each iteration, we evaluate the policy with LSTD, compute the Q-function estimates for each action and set the new policy as instructed.
