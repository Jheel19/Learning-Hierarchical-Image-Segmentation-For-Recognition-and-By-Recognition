## BYOP 
---


### Description 📝
---


An approach integrating hierarchical segmentation and recognition, CAST (<u>C</u>oncurrently learns segmentation and recognition using
<u>A</udaptive <u>S</uegment<u>T</uokens), is implemented in this paper: https://openreview.net/pdf?id=IRcv4yFX6z. 

The primary file implementing the code is Implementation_of_cast_and_vit.ipynb and Implementation_of_samh_and_samb.ipynb.

This study primarily focuses on enhancing segmentation and recognition by proposing a concurrent and consistent hierarchical visual parsing framework. It examines the following key objectives and experiments:

1.Explore the feasibility of integrating hierarchical segmentation within the recognition process, utilizing superpixels and graph pooling.

2. Evaluate the ability of the CAST model to discover and leverage part-to-whole relationships for enhanced segmentation and recognition performance.
   
3. Examine the benefits of concurrently learning segmentation and recognition compared to treating them as separate tasks.

4. Test adaptive superpixels versus fixed patches.
   
5. Experiment with graph pooling techniques for segment hierarchy creation.

6. Assess the trade-offs in accuracy, efficiency, and resource usage compared to baseline models like SAM and ViT.



### Download Links🔗
---

CAST Repository: https://github.com/twke18/CAST

Dataset link: 
PartImageNet_OOD: https://github.com/TACJu/PartImageNet   
PASCAL Context: http://host.robots.ox.ac.uk/pascal/VOC/voc2010/PASCALContext.tar.gz  
ADE20K: http://data.csail.mit.edu/places/ADEchallenge/ADEChallengeData2016.zip




The Python codes provided in this repository download and implement the model and the dataset in the code itself, and structure it too, as they are directly callable. There is no requirement of setting paths in the code or placing files in specifc folders.


For PartImageNet: Download PartImageNet_OOD zip file, extract and upload val.zip and val.json.



### Installation 🔧
---

Requirements:

Channels:

    pytorch
    nvidia

Dependencies:

    python=3.9 or higher
    pip
    numpy
    pytorch-cuda=11.6
    pytorch==1.13.1
    torchvision
    torchdata
    timm=0.4.12
    tqdm
    dgl=1.1.3cu12.1


Rest dependencies have been listed in the environment.yaml file provided in CAST repo.



### Documentation 📑
---

Report: https://docs.google.com/document/d/1YmJgOIew-I87bBxWu6zhq5QYt6NjNIR2INCzJLbtWbY/edit?tab=t.0

