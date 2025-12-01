# Read Me

## Notebooks Folder
Contains several Jupyter notebooks. Each notebook varies only one hyperparameter while keeping the others constant. The hyperparameter value that achieves the best performance metrics is then fixed in the following notebook.

* **A_rgb:** uses only the RGB tiles.  
* **B_ndvi:** adds the NDVI channel along with the red, green, and blue channels.  
* **C_loss:** experiments with different model loss types.  
* **D_class_weights:** experiments with class weighting strategies.  
* **E_aug_strength:** experiments with different augmentation strengths.  
* **F_patch_size:** experiments with the model patch size.  
* **G_depth_level:** experiments with the model depth level.  
* **H_base_filters:** experiments with the model’s base (initial) number of filters.  
* **I_dropout:** experiments with the model dropout parameter.  
* **J_batch_norm:** experiments with enabling and disabling batch normalisation.  
* **K_learning_rate:** experiments with the model learning rate.  
* **L_epoch:** experiments with the number of training epochs.  
* **M_final_predictions:** configures the model with the final selection of hyperparameters. The model weights are exported and then reloaded to generate the final prediction tiles.  
* **N_slide_images:** generates output images for use in the web presentation.
* **artifacts**: this folder contains the model weights saved from its last run.