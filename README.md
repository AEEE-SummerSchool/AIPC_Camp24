# AIPC_Camp24

This is a repository to deliver the 2024 AIPC Camp Training Material on July 23-25, 2024.
Please DO NOT distribute this document for any commercial purposes.

## [Ryzen AI Processor Specifications](https://www.amd.com/en/products/processors/consumer/ryzen-ai.html#tabs-8c217919cb-item-b0799dc4e6-tab)

## Agenda

| Date   | Time        | Activity                                                              |
| ------ | ----------- | --------------------------------------------------------------------- |
| 23-Jul | 9:30-10:30  | AMD AI solutions and AI PC Design Flow                                |
|        | 10:30-11:30 | Setup the Remote Lab and run the 1st MLP example                      |
|        | 14:00-15:00 | Deep Dive the Ryzen AI SW ONNX Design Flow                            |
|        | 15:00-16:00 | Run Machine Learning Inference on the NPU with PyTorch and ONNX       |
|        | 16:00-17:00 | Homework- Run FashionMinst lab                                        |
|        |             |                                                                       |
| 24-Jul | 9:30-10:30  | Homework Review & PyTorch and ONNX Flow for Training                  |
|        | 10:30-11:30 | Demo and Run the Yolov8 and LLM on AI PC and Radeon GPU               |
|        | 14:00-16:00 | Lab Time: Try the NPU Kernel Programming with Riallto Labs            |
|        | 16:00-17:00 | Homework - Improvement Yolov8 Notebook                                |
|        |             |                                                                       |
| 25-Jul | 9:30-10:30  | CCF-DAC challenge Winner Sharing, IC Design DRC acceleration on AI PC |
|        | 10:30-11:30 | Explore the Ryzen AI NPU architecture with Riallto                    |
|        | 14:00-16:00 | Lab Time: Try the NPU kernel programming with Riallto labs            |

## Remote Lab Setup

[Lab 1 and Lab2 Remote Lab: Windows RDP Usage](./Remote_Lab_for_onnx.md)

[Lab3 Remote Lab usage](./Remote_lab_for_riallto.md)

## Homework

### Lab1 Run FashionMinst lab:

1. Find the original MLP notebook in Remote Lab Riallto 5-0
2. First run the original 5-0 MLP notebook step by step

### Homework1: Try to run MLP on  FashionMNIST dataset.

Complete the FashionMNIST homework by training a neural network on the FashionMNIST dataset. The lab involves setting up the environment, loading the dataset, building a simple MLP (Multi-Layer Perceptron) model, and training it on the FashionMNIST dataset. Evaluate the model's performance and make necessary adjustments to improve accuracy. Document your process and results.

### Lab2 Try the NPU Kernel Programming with Riallto Labs

1. Use RDP to log in to remote lab
2. Open the Riallto on the desktop
3. Learn and run the notebooks in Riallto

### Homework2 Improvement Yolov8 Notebook:

1. Clone the original Yolov8 from our [Github Rpo](https://github.com/AEEE-SummerSchool/AIPC_Camp24/tree/main) under Lab2 to the remotelab
2. Run the original Yolov8 notebook in yolov8_e2e/implement/yolov8_notebook.ipynb
3. Review and enhance the existing Yolov8 notebook by improving the model's performance and efficiency. This includes optimizing the data preprocessing steps, experimenting with different hyperparameters, and implementing advanced techniques to boost the model's accuracy and speed. Test the improved model on a validation set and compare the results with the original notebook. Provide a detailed report on the changes made and their impact on the model's performance.

### Lab3 Try the NPU Kernel Programming with Riallto Labs

1. [Lab3 Remote Lab usage](./Remote_lab_for_riallto.md)
2. Learn and run the 4-2 notebooks in Riallto
3. Download the notebook with the your written kernel.

## Submission

* Deadline: 31th July
* Submission format:
  * Download the Jupyter Notebook and send the notebook file through e-mail.
* E-mail Notification: aeee-sc@qq.com
  * Name, School, Cell Phone number should be provided in the e-mail.

## Addition meterial

1. [RyzenAI SW](https://github.com/amd/RyzenAI-SW)
2. [Riallto](https://riallto.ai/)
3. [YOLOv8 exmaple](https://github.com/amd/RyzenAI-SW/tree/main/example/yolov8)
