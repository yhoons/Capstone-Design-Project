# Capstone-Design-Project



#### Project Introduce

Advanced Blind Assistance System (It's ADAS applications mortif)

![image](https://user-images.githubusercontent.com/79200729/219953408-c5f88f30-6e93-4206-817a-d594714d1dd9.png)


### Project Software Architecture

---------------------

<img width="858" alt="image" src="https://user-images.githubusercontent.com/79200729/219953520-a60ec34d-3c52-4b29-a0ed-a278a3e82c3d.png">



### Requirements

------

```
Jetson nano - Ubuntu 20.04 (aarch64)
pytorch == 1.13.1
opencv == 4.3
conda ==
python == 3.8
```



### Process

-----

Data labeling -> Design DL model -> Setting loss function(celosss, L2 loss, iou loss, focal loss) & find optimal hyperparameters(lr, optimizer, loss weight) -> Evaluate mdel to satisfy KPI(Recall, Precision, PR curve) -> Model compression



