# EchoSAM

Obtained data from Stanford’s EchoNet dataset, completed preprocessing work such as cleaning and resizing
Established a vision model that recognizes cardiac location in echocardiogram, fined-tuned Segment Anything Model (SAM) based on PyTorch, combined medical-specific modifications from Lightning-SAM, MedSAM, Medical-SAM-Adapter, finally improved IOU and Dice accuracy rate by 8-10% on original SAM (from 0.75, 0.81 to 0.82, 0.91)
