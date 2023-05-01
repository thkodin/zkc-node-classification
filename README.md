# zkc-node-classification
A simple notebook utilizing PyTorch-Geometric for node classification on Zachary's Karate Club dataset using GCN, GraphSAGE, and GAT based graph models.

Originally an assignment of a course, extended by self later on.

In the following video, the complete history of the node embeddings and labels (reduced to 2D after the fact) from each of the three model's training sessions are presented. The leftmost (History 1) corresponds to the model with GCNConv operations, the middle (History 2) to SAGEConv, and the rightmost (History 3) to GATConv with single head. This particular animation was @ 1000 epochs, 0.001 LR, CE loss, and ADAM optimizer.

<video src=outputs/1000-epochs_0.001-lr_CE-loss_ADAM-opt.mp4, alt="side-by-side-model-animations"></video>
