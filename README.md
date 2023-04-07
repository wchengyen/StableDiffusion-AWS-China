# StableDiffusion-AWS-China

以AWS China region 资源运行stable diffusion. 
提供ipynb 作为 参考

建议配置如下
- EC2 机型 - G4dn.xlarge 
- EC2 AMI - Deep Learning AMI GPU PyTorch 1.13.1 (Ubuntu 20.04) 20230315 (ami-088232cd83858d48c )
- EC2 EBS - 建议配置GP3 150 GB 以上
- EC2 安全组 - 新增 Jupyter notebook 开放端口 8888, Stable diffusion 开放端口9000
