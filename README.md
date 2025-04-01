# t-SNE Visualization
<p>
  <img src="https://github.com/nothingbutbut/ICML-t_SNE/blob/main/tsne_2Blocks_HalfCheetah-v4.png" alt="2 blocks" style="width:32%; float:left; margin-right:1%;">
  <img src="https://github.com/nothingbutbut/ICML-t_SNE/blob/main/tsne_4Blocks_HalfCheetah-v4.png" alt="4 blocks" style="width:32%; float:left; margin-left:1%;">
  <img src="https://github.com/nothingbutbut/ICML-t_SNE/blob/main/tsne_grow_HalfCheetah-v4.png" alt="Network Expansion" style="width:32%; float:left; margin-left:1%;">
</p>
<p style="clear:both; font-size:18px; margin-top:20px;">
  We analyze representations by sampling from the replay buffer, passing them through the critic network, and extracting features from the last layer for t-SNE visualization in 2D. We compare the settings with and without network expansion (using fixed 2/4 blocks). From left to right are the t-SNE results of 2 blocks, 4 blocks and expansion from 2 to 4 blocks.
  Results show that network expansion leads to clearer clustering, suggesting better-separated and more structured features.
</p>
