# Zeroth-Order Methods for Adversarial Attack

Optimization project for the University course: "Optimization for Data Science".

Authors: Mincato Emanuele and Caregari Alberto

The aim of this project is to implement and test three different variations of 
the vanilla Frank-Wolfe (FW) method in order to generate adversary attacks. 
The three algorithms are:

• Zeroth-order Stochastic Conditional Gradient Method (ZSCG)

• Faster Zeroth-Order Frank-Wolfe Methods (FZFW)

• Faster Zeroth-Order Conditional Gradient Method (FZCGS)

Frank-Wolfe algorithm is an efficient method
for optimizing non-convex constrained problems.
However, most of existing methods focus on
the first-order case. In real-world applications,
the gradient is not always available. To address
the problem of lacking gradient in many applications,
we implemented three different zeroth-order
Frank-Wolfe algorithms applying different gradient esetimator.
