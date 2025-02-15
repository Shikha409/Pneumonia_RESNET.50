# Pneumonia Detection using RESNET.50

## Description
This project utilizes RESNET.50 for the detection of pneumonia from chest X-ray images. The model aims to assist in the healthcare industry, particularly in the radiological department, by providing an automated tool for accurate and efficient pneumonia diagnosis.

## Installation
To run this project, you need to have Python installed along with the following libraries:
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib

You can install the necessary packages using:
```bash
!pip install tensorflow keras opencv-python numpy matplotlib
```

## Usage
1. Clone the repository:
    ```bash
    git clone <(https://github.com/Shikha409/Pneumonia_RESNET.50/)>
    ```
2. Navigate to the project directory:
    ```bash
    cd Pneumonia_RESNET.50
    ```
3. Run the Jupyter Notebook to train and test the model:
    ```bash
    jupyter notebook Pneumonia_RESNET.50.ipynb
    ```

## Results
The model's performance is evaluated using various metrics such as accuracy, precision, recall, and F1-score. Detailed results and visualizations can be found within the notebook.

# # RESULTS 
# # 1 Not Efected
If the detection result is negative, it means there is no effect in the X-rays. 
like this 
![detection result3__result](https://github.com/user-attachments/assets/3c44ef1b-fee9-4629-ac91-24ac3e199c35)

# #2 Efected By Pneumonia
If the detection result is positive, it means there is a pneumonia effect in the X-rays.
like this 
![detection result2__result](https://github.com/user-attachments/assets/e1660bf7-6a37-4e18-bd3e-2eb15deeffc1)


## Conclusion
This model can be deployed to X-ray machines in the radiological department to assist radiologists in predicting pneumonia from chest X-ray images accurately and efficiently.

