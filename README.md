Image based diagnosis of pneumonia.

This mini-project concerns diagnozing pneumonia from chest XRay images. To learn more, see: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/home

Data: https://data.mendeley.com/datasets/rscbjbr9sj/2

Context: https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

The most common way of approaching task like medical image diagnosis is to use transfer learning, i.e. take one of the deep networks trained on dataset like ImageNet and tune them to specific classification task (for a good example of this using this dataset check https://www.kaggle.com/aakashnain/beating-everything-with-depthwise-convolution). However, I wanted to check if it is possible with custom model learned from scratch only on available data. 

The main code is located in pneumonia_datalab_version.ipynb. The experiment was run in the Google Cloud Datalab instance, so some code is specific to this environment. Notebook is written in the way that it can also serve as an experiment report.
