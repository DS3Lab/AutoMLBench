# Benchmarking Machine Learning Clouds

We conduct a benchmark over several popular machine learning cloud platforms,
including Google, Amazon AWS, Azure and Oracle.
For reproducibility, we make all datasets and code public in this repo.
Our benchmark contains two snapshots, *mlbench* and *automlbanch*.


## mlbench

*mlbench* was conducted during 2016-2017 when Amazon and Azure provide ML training services.
- [Dataset](dataset.md)
- Configurations.
    - Amazon. Previous configurations have expired due to platform upgrades. Refer to the latest [confugiration](config/aws_config.md).
    - [Azure](https://gallery.azure.ai/Home/Author?authorId=69E57FAD37E93DF10A65AD63A0E8194944E8B9BC8D7BF222F3A1D0493B9A7661). 
    We share training workflows in this link. An Azure ML studio account is required.

## automlbench

*automlbench* was conducted during 2020-2022 when many machine learning clouds provide automatic machine learning training.
Our goal is to evaluate their AutoML functionalities.

- [Dataset](dataset.md)
- Code. We provide jupyter scripts for three platforms.
    - Google. Google does training and inference without any code.
    - [AWS](code/aws_sagemaker). We provide scripts for inference.
    - [Azure](code/azure). We provide scripts for inference.
    - [Oracle](code/oracle_datascience). We provide scripts for training and inference.
- Configurations. We show screenshots of how we configure each platform.
    - [Google](config/google_config.md)
    - [AWS](config/aws_config.md)
    - [Azure](config/azure_config.md)
    - [Oracle](config/oracle_config.md)
