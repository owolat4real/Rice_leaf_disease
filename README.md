Rice Leaf Disease Classification – Project Summary

This project identifies three types of rice leaf diseases — Leaf Blast, Bacterial Blight, and Brown Spot — using image classification. The dataset contained 120 images (40 per class), which were resized and normalized for consistency. To improve learning from the small dataset, data augmentation (flips, rotations, zooms, and brightness changes) was applied.

Two models were tested: a custom CNN, which achieved 68% accuracy, and a MobileNetV2 model using transfer learning, which reached 86% accuracy. MobileNetV2 performed better because it used pretrained ImageNet features, allowing it to recognize disease patterns even with limited data.

Challenges included installation issues, incorrect dataset structure, and low initial performance. These were solved through proper setup, data organization, and model fine-tuning.

In the end, MobileNetV2 was selected as the best model for deployment due to its higher accuracy, strong generalization, and stability when classifying rice leaf diseases.
