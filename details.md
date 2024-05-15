---
title: Details
layout: home
nav_order: 3
---

## Details on architectures of submodels
### ResNet18

Details of 𝛾 of NeFL-D on ResNet18
<table>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th colspan="4">NeFL-D (ResNet18)</th>
    </tr>
    <tr>
      <th>Layer 1 (64)</th>
      <th>Layer 2 (128)</th>
      <th>Layer3 (256)</th>
      <th>Layer 4 (512)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.20</td><td>1</td><td>0.20</td><td>1,1</td><td>0,0</td><td>1,1</td><td>0,0</td></tr>
    <tr><td>2</td><td>0.38</td><td>1</td><td>0.38</td><td>1,0</td><td>0,0</td><td>1,0</td><td>1,0</td></tr>
    <tr><td>3</td><td>0.57</td><td>1</td><td>0.57</td><td>1,1</td><td>1,1</td><td>1,1</td><td>1,0</td></tr>
    <tr><td>4</td><td>0.81</td><td>1</td><td>0.81</td><td>1,0</td><td>1,1</td><td>0,0</td><td>1,1</td></tr>
    <tr><td>5</td><td>1</td><td>1</td><td>1</td><td>1,1</td><td>1,1</td><td>1,1</td><td>1,1</td></tr>
  </tbody>
</table>

Details of 𝛾 of NeFL-WD on ResNet18
<table>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th colspan="4">NeFL-WD (ResNet18)</th>
    </tr>
    <tr>
      <th>Layer 1 (64)</th>
      <th>Layer 2 (128)</th>
      <th>Layer3 (256)</th>
      <th>Layer 4 (512)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.20</td><td>0.34</td><td>0.58</td><td>1,1</td><td>1,1</td><td>1,1</td><td>1,0</td></tr>
    <tr><td>2</td><td>0.4</td><td>0.4</td><td>1</td><td>1,1</td><td>1,1</td><td>1,1</td><td>1,1</td></tr>
    <tr><td>3</td><td>0.6</td><td>0.6</td><td>1</td><td>1,1</td><td>1,1</td><td>1,1</td><td>1,1</td></tr>
    <tr><td>4</td><td>0.8</td><td>0.8</td><td>1</td><td>1,1</td><td>1,1</td><td>1,1</td><td>1,1</td></tr>
    <tr><td>5</td><td>1</td><td>1</td><td>1</td><td>1,1</td><td>1,1</td><td>1,1</td><td>1,1</td></tr>
  </tbody>
</table>

### ResNet34

Details of 𝛾 of NeFL-D on ResNet34
<table>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th colspan="4">NeFL-D (ResNet34)</th>
    </tr>
    <tr>
      <th>Layer 1 (64)</th>
      <th>Layer 2 (128)</th>
      <th>Layer 3 (256)</th>
      <th>Layer 4 (512)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.23</td><td>1</td><td>0.23</td><td>1,0,0</td><td>1,0,0,0</td><td>1,0,0,0,0,0</td><td>1,0,0</td></tr>
    <tr><td>2</td><td>0.39</td><td>1</td><td>0.39</td><td>1,1,1</td><td>1,1,1,1</td><td>1,1,0,0,0,1</td><td>1,0,0</td></tr>
    <tr><td>3</td><td>0.61</td><td>1</td><td>0.61</td><td>1,1,1</td><td>1,1,1,1</td><td>1,1,0,0,0,1</td><td>1,0,1</td></tr>
    <tr><td>4</td><td>0.81</td><td>1</td><td>0.81</td><td>1,1,1</td><td>1,0,0,1</td><td>1,1,0,0,0,1</td><td>1,1,1</td></tr>
    <tr><td>5</td><td>1</td><td>1</td><td>1</td><td>1,1,1</td><td>1,1,1,1</td><td>1,1,1,1,1,1</td><td>1,1,1</td></tr>
  </tbody>
</table>

Details of 𝛾 of NeFL-WD on ResNet34
<table>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th colspan="4">NeFL-WD (ResNet34)</th>
    </tr>
    <tr>
      <th>Layer 1 (64)</th>
      <th>Layer 2 (128)</th>
      <th>Layer 3 (256)</th>
      <th>Layer 4 (512)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.20</td><td>0.38</td><td>0.53</td><td>1,1,1</td><td>1,0,0,1</td><td>1,0,0,0,0,1</td><td>1,0,1</td></tr>
    <tr><td>2</td><td>0.40</td><td>0.63</td><td>0.64</td><td>1,1,1</td><td>1,0,0,1</td><td>1,1,1,0,0,1</td><td>1,0,1</td></tr>
    <tr><td>3</td><td>0.60</td><td>0.77</td><td>0.78</td><td>1,1,1</td><td>1,1,1,1</td><td>1,1,1,1,0,1</td><td>1,0,1</td></tr>
    <tr><td>4</td><td>0.80</td><td>0.90</td><td>0.89</td><td>1,1,1</td><td>1,1,1,1</td><td>1,1,1,0,0,1</td><td>1,1,1</td></tr>
    <tr><td>5</td><td>1</td><td>1</td><td>1</td><td>1,1,1</td><td>1,1,1,1</td><td>1,1,1,1,1,1</td><td>1,1,1</td></tr>
  </tbody>
</table>

### ResNet56

Details of 𝛾 of NeFL-D on ResNet56
<table>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th colspan="3">NeFL-D (ResNet56)</th>
    </tr>
    <tr>
      <th>Layer 1 (16)</th>
      <th>Layer 2 (32)</th>
      <th>Layer 3 (64)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.2</td><td>1</td><td>0.2</td><td>1, 1, 0, 0, 0, 0, 0, 0, 0</td><td>1, 1, 0, 0, 0, 0, 0, 0, 0</td><td>1, 1, 0, 0, 0, 0, 0, 0, 0</td></tr>
    <tr><td>2</td><td>0.4</td><td>1</td><td>0.4</td><td>1, 1, 1, 0, 0, 0, 0, 0, 0</td><td>1, 1, 1, 0, 0, 0, 0, 0, 0</td><td>1, 1, 1, 1, 0, 0, 0, 0, 0</td></tr>
    <tr><td>3</td><td>0.6</td><td>1</td><td>0.6</td><td>1, 1, 1, 1, 0, 0, 0, 0, 0</td><td>1, 1, 1, 1, 0, 0, 0, 0, 0</td><td>1, 1, 1, 1, 1, 1, 0, 0, 0</td></tr>
    <tr><td>4</td><td>0.8</td><td>1</td><td>0.8</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 0</td><td>1, 1, 1, 1, 1, 1, 1, 0, 0</td></tr>
    <tr><td>5</td><td>1</td><td>1</td><td>1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1</td></tr>    
  </tbody>
</table>

Details of 𝛾 of NeFL-WD on ResNet56
<table>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th colspan="3">NeFL-WD (ResNet56)</th>
    </tr>
    <tr>
      <th>Layer 1 (16)</th>
      <th>Layer 2 (32)</th>
      <th>Layer 3 (64)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.2</td><td>0.46</td><td>0.43</td><td>1, 1, 1, 1, 0, 0, 0, 0, 0</td><td>1, 1, 1, 1, 0, 0, 0, 0, 0</td><td>1, 1, 1, 1, 0, 0, 0, 0, 0</td></tr>
    <tr><td>2</td><td>0.4</td><td>0.61</td><td>0.66</td><td>1, 1, 1, 1, 1, 1, 0, 0, 0</td><td>1, 1, 1, 1, 1, 1, 0, 0, 0</td><td>1, 1, 1, 1, 1, 1, 0, 0, 0</td></tr>
    <tr><td>3</td><td>0.6</td><td>0.77</td><td>0.77</td><td>1, 1, 1, 1, 1, 1, 1, 0, 0</td><td>1, 1, 1, 1, 1, 1, 1, 0, 0</td><td>1, 1, 1, 1, 1, 1, 1, 0, 0</td></tr>
    <tr><td>4</td><td>0.8</td><td>0.90</td><td>89</td><td>1, 1, 1, 1, 1, 1, 1, 1, 0</td><td>1, 1, 1, 1, 1, 1, 1, 1, 0</td><td>1, 1, 1, 1, 1, 1, 1, 1, 0</td></tr>
    <tr><td>5</td><td>1</td><td>1</td><td>1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1</td></tr>
  </tbody>
</table>

### ReNet110

Details of 𝛾 of NeFL-D on ResNet110
<table>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th colspan="3">NeFL-D (ResNet110)</th>
    </tr>
    <tr>
      <th>Layer 1 (16)</th>
      <th>Layer 2 (32)</th>
      <th>Layer 3 (64)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.2</td><td>1</td><td>0.20</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0</td><td>1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0</td><td>1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0</td></tr>
    <tr><td>2</td><td>0.4</td><td>1</td><td>0.40</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0</td><td>1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0</td><td>1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0</td></tr>
    <tr><td>3</td><td>0.6</td><td>1</td><td>0.60</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0</td></tr>
    <tr><td>4</td><td>0.8</td><td>1</td><td>0.80</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0</td></tr>
    <tr><td>5</td><td>1</td><td>1</td><td>1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1</td></tr>
  </tbody>
</table>

Details of 𝛾 of NeFL-WD on ResNet110
<table>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>    
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th colspan="3">NeFL-WD (ResNet110)</th>
    </tr>
    <tr>
      <th>Layer 1 (16)</th>
      <th>Layer 2 (32)</th>
      <th>Layer 3 (64)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.2</td><td>0.46</td><td>0.44</td><td>1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1</td><td>1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1</td><td>1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1</td></tr>
    <tr><td>2</td><td>0.4</td><td>0.60</td><td>0.66</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 1</td></tr>
    <tr><td>3</td><td>0.6</td><td>0.77</td><td>0.77</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 1</td></tr>
    <tr><td>4</td><td>0.8</td><td>0.90</td><td>0.89</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 1</td></tr>
    <tr><td>5</td><td>1</td><td>1</td><td>1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1</td></tr>
  </tbody>
</table>

### Wide ResNet

Details of 𝛾 of NeFL on Wide ResNet101_2
<table>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th colspan="4">NeFL-D (Wide ResNet101_2)</th>
    </tr>
    <tr>
      <th>Layer 1 (128)</th>
      <th>Layer 2 (256)</th>
      <th>Layer 3 (512)</th>
      <th>Layer 4 (1024)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.5</td><td>1</td><td>0.51</td><td>1, 1, 1</td><td>1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0</td><td>1, 1, 0</td></tr>
    <tr><td>2</td><td>0.75</td><td>1</td><td>0.75</td><td>1, 1, 1</td><td>1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0</td><td>1, 1, 1</td></tr>
    <tr><td>3</td><td>1</td><td>1</td><td>1</td><td>1, 1, 1</td><td>1, 1, 1, 1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1</td><td>1, 1, 1</td></tr>
  </tbody>
</table>

### ViT-B/16

<table>
  <caption>Details of $\bm{\gamma}$ of NeFL-D and NeFL-W on ViT-B/16</caption>
  <thead>
    <tr>
      <th rowspan="2">Model<br>index</th>
      <th rowspan="2">Model size<br>𝛾</th>
      <th rowspan="2">𝛾<sub>W</sub></th>
      <th rowspan="2">𝛾<sub>D</sub></th>
      <th>NeFL-D (ViT-B/16)</th>
    </tr>
    <tr>
      <th>Block</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>0.5</td><td>1</td><td>0.50</td><td>1, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0, 0</td></tr>
    <tr><td>2</td><td>0.75</td><td>1</td><td>0.75</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 0, 0, 0</td></tr>
    <tr><td>3</td><td>1</td><td>1</td><td>1</td><td>1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1</td></tr>
  </tbody>
</table>


## Pre-trained models (trained on ImageNet-1k)
### ResNet18/34
- Trained by epochs of 90, batch size of 32
- Optimizer: SGD with learning rate of 0.1, momentum of 0.9, and weight decay of 0.0001
- Learning rate decreased by a factor of 0.1 every 30 epochs

### Wide ResNet101_2
- Trained by epochs of 90, batch size of 32
- Optimizer: SGD with learning rate of 0.1, momentum of 0.9, and weight decay of 0.0001
- Learning scheduler: Cosine learning rate with warming up restarts for 256 epochs

### ViT-B/16
- Trained by epochs of 300, batch size of 512
- Optimizer: AdamW with learning rate of 0.003 and weight decay of 0.3
- Learning scheduler: Cosine annealing after linear warmup method with decay of 0.033 for 30 epochs
- Augmentation:
  - Random augmentation
  - Random mixup with alpha=0.2
  - Cutmix with alpha=1
  - Repeated augmentation
  - Label smoothing of 0.11
  - Gradient norm clipping to 1
  - Model exponential moving average (EMA)