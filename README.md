# MADAM — Momentum Adaptive Directional Adam Mechanism

MADAM is an optimizer I designed by extending ideas from adaptive learning-rate and second-order moment optimization methods, particularly Adam.
The key motivation behind MADAM is to overcome one of Adam’s often-ignored limitations: the large variance introduced by the second-moment term in the initial iterations. MADAM incorporates a directional and adaptive momentum correction that significantly reduces this variance, leading to faster and more stable convergence.

While existing improvements like Rectified Adam (RAdam) have addressed some of Adam’s shortcomings, they can still exhibit oscillations or even become immobile when operating on high-dimensional or ill-conditioned optimization landscapes.
MADAM directly targets these challenges, offering a more reliable optimization trajectory with reduced jitter and improved conditioning response.

We evaluated MADAM on four standard benchmark optimization problems, and the results show consistent and successful performance improvements over baseline methods. 

In this repo  , you can find codes regarding the comparison plots between optimizers on benchmark problems . 

[Link to Research Paper]  (https://experts.illinois.edu/en/publications/on-the-variance-of-the-adaptive-learning-rate-and-beyond-2/#:~:text=Abstract,of%20the%20adaptive%20learning%20rate)
