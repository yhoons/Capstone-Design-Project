# Capstone-Design-Project



#### Project Introduce

Advanced Blind Assistance System (It's ADAS applications mortif)

![image](https://user-images.githubusercontent.com/79200729/219953408-c5f88f30-6e93-4206-817a-d594714d1dd9.png)


### Project Software Architecture

---------------------

<img width="858" alt="image" src="<img width="858" alt="step drawio" src="https://user-images.githubusercontent.com/79200729/223771090-4d3304b6-d423-4106-84e3-f90e2f378ca3.png">">



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



