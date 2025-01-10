# HiCeller

The latest advancements in single-cell technology have brought unprecedented opportunities to uncover the molecular complexity of complex biological systems, particularly those associated with human-specific diseases. However, these advancements have also introduced new challenges—how to efficiently annotate long-tail single-cell data related to disease conditions. To effectively address this challenge, we proposed Celler, a cutting-edge generative pre-training model specifically designed for single-cell data annotation. Celler incorporates two groundbreaking elements: First, we introduced the Gaussian Inflation (GInf) Loss function. By dynamically adjusting sample weights, GInf Loss significantly enhances the model’s ability to learn from rare categories while reducing the risk of overfitting for common categories. Second, we integrated a Hard Data Mining (HDM) strategy into the training process, substantially improving the model’s predictive accuracy. Additionally, to further advance research in this field, we have constructed a large-scale single-cell dataset: Celler-75, which encompasses 40 million cells distributed across 80 human tissues and 75 specific diseases. This dataset provides critical support for comprehensively exploring the potential of single-cell technology in disease research.

![image]([Pie charts showing the cell distribution in four typical tissues.](https://github.com/YaoGina/HiCeller/blob/main/4data.png))
<img src="[https://github.com/YaoGina/HiCeller/blob/main/4data.png](https://github.com/YaoGina/HiCeller/blob/main/4data.png)" alt="项目效果图">
