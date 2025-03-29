# DeepLense

optimizer = torch.optim.Adam(model.parameters(), lr=0.001)
scheduler = torch.optim.lr_scheduler.StepLR(optimizer, step_size=8, gamma=0.1)

Reach 58% accuracy at epoch 27
Train Loss: 0.8437, Train Accuracy: 59.21%
Val Loss: 0.8543, Val Accuracy: 58.63%


Add random rotation to train images
Train Loss: 0.9165, Train Accuracy: 54.76%
Val Loss: 0.9093, Val Accuracy: 54.91%

optimizer = torch.optim.Adam(model.parameters(), lr=1e-04)
scheduler = torch.optim.lr_scheduler.StepLR(optimizer, step_size=30, gamma=0.1)
after 79 epoch,
Train Loss: 0.2164, Train Accuracy: 91.38%
Val Loss: 0.2637, Val Accuracy: 89.29%