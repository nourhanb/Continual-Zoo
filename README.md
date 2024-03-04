# Continual-Zoo
This is the official implementation of our recent submission "Continual-Zoo: Leveraging Zoo Models for Continual Classification of Medical Images", submitted to CLVision Workshop at CVPR 2024. 

The code and datasets will be made publicly available after paper acceptance.

## Abstract
(...). 

## File Description
- constructing zoo: decide on number and type of pretrained models. 
- stage1_training: Training algorithm of stage 1 model.
- stage2_training: Training algorithm of stage 2 model.
- util: Contains functions used throughout the project.
- prompts: Command promts to execute each training file. The examples inside are those used to train the final models.

## Requirements
All the necessary libraries are listed in the requirements.txt file. You will also need:
- Python == 3.10
- CUDA == 11.7
- Cudnn == 8.5
- Pytorch == 2.0.0

## Training and Evaluation
Here you can find the command prompts used to run each training stage. You can edit the hyperparameters here or inside the corresponding code file.

- stage_1: `python_stage1_training.py --batch_size 16 --learning_rate 0.001 --epochs 150 --trial 2`

Testing contrastive models
- `python model_test.py --method CE`
  
## References

## Citation
