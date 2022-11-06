# KWS
In this homework I implement KWS model and striaming variant. Moreover, I implement different ways to compress model: distillation, fp16, quantithation. All experiments can be found in 'seminar_my.ipynb'.
If you want test model, you shuld use 'is_train = False' in notebook and downloads base model files: 

1. 'full_model.pth'
2. 'best_model.pth'
3. 'best_model_new.pth'
4. 'best_model_new_model.pth'
5. 'distilation_model_new_fp16_model.pth'

Also I added:

6. 'stream_full_model.pth' -- scripted full model for streaing, but this model 
but this model is automatically saved when run the notebook if you download items 1-5.

7. 'stream_small_model.pth' -- scipted my final compressed model, but this model 
but this model is automatically saved when run the notebook if you download items 1-5.
