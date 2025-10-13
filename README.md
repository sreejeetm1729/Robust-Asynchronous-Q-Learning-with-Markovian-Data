# Robust Asynchronous Q Learning with Markovian Data

We study the problem of learning the optimal policy in a discounted, infinite-horizon reinforcement learning (RL) setting in the presence of adversarially corrupted rewards. To address this problem, we develop a novel robust variant of the Q-learning algorithm and analyze it under the challenging asynchronous sampling model with time-correlated data. Despite corruption, we prove that the finite-time guarantees of our approach match existing bounds, up to an additive term that scales with the fraction of corrupted samples. We also establish an information-theoretic lower bound, revealing that our guarantees are near-optimal. Notably, our algorithm is agnostic to the underlying reward distribution and provides the first finite-time robustness guarantees for asynchronous Q-learning. A key element of our analysis is a refined Azuma-Hoeffding inequality for almost-martingales, which may have broader applicability in the study of RL algorithms.

## Figures
<table>
<tr>
  <td>
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-with-Markovian-Data/blob/main/Figures%20and%20Tables/arxiv_10.png" style="width:380px">
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-with-Markovian-Data/blob/main/Figures%20and%20Tables/arxiv_3.png" style="width:380px">
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-with-Markovian-Data/blob/main/Figures%20and%20Tables/arxiv_12.png" style="width:380px">
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-with-Markovian-Data/blob/main/Figures%20and%20Tables/arxiv_13.png" style="width:380px">
  </td>
</tr>
