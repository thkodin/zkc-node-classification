# Classifying Nodes in Zachary's Karate Club Dataset
A simple notebook utilizing PyTorch-Geometric for node classification on Zachary's Karate Club dataset using GCN, GraphSAGE, and GAT based graph models.

Originally an assignment of a course, extended by self later on.

In the following video, the complete history of the node embeddings and labels (reduced to 2D after the fact) from each of the three model's training sessions are presented. The leftmost (History 1) corresponds to the model with GCNConv operations, the middle (History 2) to SAGEConv, and the rightmost (History 3) to GATConv with single head. This particular animation was @ 1000 epochs, 0.001 LR, CE loss, and ADAM optimizer.

These are the validation time embeddings (without dropout).

https://user-images.githubusercontent.com/94681976/235876036-f9c23d49-9bd3-4397-8eeb-0dc3f9cb2c54.mp4

These are the training embeddings (with dropout, so they jump around a lot as you can see). They are rendered at a much lower framerate of 10 so the viewer can keep up.

https://user-images.githubusercontent.com/94681976/235500451-db6e1259-5177-412a-b512-824b7b042b65.mp4
