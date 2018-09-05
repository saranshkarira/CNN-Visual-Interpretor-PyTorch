# ConvNets Visualizer in PyTorch
Implementations of various CNN Visualization Techniques in PyTorch. These notebooks are implemented in Google Colaboratory.

## Requirements: 
You will need a Google Colaboratory Account, all rest dependencies are satisfied within the notebook itself.
**Note** : Select Runtime Environment as *Python3* and Hardware as *GPU* in Colaboratory

## Implemented:
- [x] Deep Dream
- [x] Layer Activations
- [x] Per Filter Activations
- [x] Weight/Feature Visualization
- [x] Occlusion
- [x] Saliency : Vanilla Backprop
- [x] Saliency : Guided Backprop
- [x] Smooth Grad
- [ ] Neural Texture Synthesis
- [ ] Neural Style Transfer
- [ ] Semantic Dictionaries
- [ ] GradCam
- [ ] Gradient Ascent

### Deep Dream
<img src="https://raw.githubusercontent.com/saranshkarira/cnn-visualizations-in-pytorch/master/src/test.gif" width="400" height="400" /><img src="https://raw.githubusercontent.com/saranshkarira/cnn-visualizations-in-pytorch/master/src/deep_dream/results/chame.jpg" width="400" height="400" />

### Total Activations of Each Layer
<img src="https://raw.githubusercontent.com/saranshkarira/cnn-visualizations-in-pytorch/master/src/total_activation_each_layer.png" width="500" height="800" />

### Per Filter Activations of a Selected Layer
<img src="https://raw.githubusercontent.com/saranshkarira/cnn-visualizations-in-pytorch/master/src/filter_wise_activation_of_a_chosen_layer.png" width="500" height="800" />

### Filters of a Selected Layer(Conv1)
<img src="https://raw.githubusercontent.com/saranshkarira/cnn-visualizations-in-pytorch/master/src/filters_of_a_chosen_layer.png" width="500" height="500" />

### HeatMap by Occlusion
<img src="https://raw.githubusercontent.com/saranshkarira/cnn-visualizations-in-pytorch/master/src/heatmap_by_occlusion.png" width="550" height="550" />

### Saliency by Vanilla Backprop
<img src="https://raw.githubusercontent.com/saranshkarira/cnn-visualizations-in-pytorch/master/src/saliency_by_simple_backprop.png" width="600" height="300" />

### Saliency by Guided Backprop
<img src="https://raw.githubusercontent.com/saranshkarira/cnn-visualizations-in-pytorch/master/src/saliency_by_guided_backprop.png" width="600" height="300" />

### Saliency by Smooth Grad
<img src="https://raw.githubusercontent.com/saranshkarira/cnn-visualizations-in-pytorch/master/src/saliency_by_smooth_grad.png" width="550" height="550" />
