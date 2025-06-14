# AI框架和科学计算大作业

AMGNET的复现实验

基于ModelArts平台完成，使用镜像为pytorch1.10-cuda10.2-cudnn7-ubuntu18.04

除镜像已有内容，相关依赖如下

```
torch-cluster===1.5.9 
torch-geometric===2.0.2 
torch-scatter===2.0.9 
torch-sparse===0.6.12 
pyamg
```

### 注意

airfoil使用的min_nodes为2000

cylinder使用的min_nodes为20000