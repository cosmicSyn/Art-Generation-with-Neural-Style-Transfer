# Neural Style Transfer Project

## Aim
The goal of this project is to implement Neural Style Transfer (NST), a fascinating technique that combines the content of one image with the artistic style of another. This process results in a new image that retains the content structure of the original while adopting the stylistic elements of a chosen artwork.

## Approach
- **Packages**
  - Import necessary Python libraries, including TensorFlow, NumPy, and Matplotlib.

- **Problem Statement**
  - Define the objective of the project: applying Neural Style Transfer to generate visually appealing images.

- **Transfer Learning**
  - Utilize transfer learning with a pre-trained VGG19 model to efficiently extract content and style features from input images.

- **Neural Style Transfer (NST)**
  - **Computing the Content Cost**
    - **Make Generated Image G Match the Content of Image C**
    - **Content Cost Function  𝐽𝑐𝑜𝑛𝑡𝑒𝑛𝑡(𝐶,𝐺)**
      - Exercise 1: Implement the compute_content_cost function.

  - **Computing the Style Cost**
    - **Style Matrix**
      - Exercise 2: Implement the gram_matrix function.
    - **Style Cost**
      - Exercise 3: Implement the compute_layer_style_cost function.
    - **Style Weights**
      - Exercise 4: Implement the compute_style_cost function.

  - **Defining the Total Cost to Optimize**
    - Exercise 5: Implement the total_cost function.

- **Solving the Optimization Problem**
  - **Load the Content Image**
  - **Load the Style Image**
  - **Randomly Initialize the Image to be Generated**
  - **Load Pre-trained VGG19 Model**
  - **Compute Total Cost**
    - **Compute Content Cost**
    - **Compute Style Cost**
      - Exercise 6: Implement the train_step function.
  - **Train the Model**

# Implementation

For the implementation of the image segmentation project, the following libraries and tools were utilized:

- **Python:** The core programming language for implementing the image segmentation solution.

- **TensorFlow and Keras:** Leveraged the powerful combination of TensorFlow as the deep learning framework and Keras as the high-level neural networks API. These libraries facilitated the seamless implementation of the U-Net architecture for image segmentation.

- **Pandas and NumPy:** Utilized Pandas for data manipulation and NumPy for numerical operations, providing efficient handling and processing of dataset-related tasks.

- **Scikit-learn:** Employed Scikit-learn for various machine learning utilities, including metrics for model evaluation and preprocessing tools.

- **Matplotlib:** Used Matplotlib for creating visualizations, allowing for the exploration and analysis of the dataset, model training progress, and results.

## Results
The Neural Style Transfer model successfully generates visually appealing images by combining the content of one image with the artistic style of another. The project provides insights into the creative potential of deep learning techniques, allowing for the creation of unique and stylized visual content.

## License
This project is licensed under the [MIT License](LICENSE).

## Disclaimer

I recognize the time people spend on building intuition, understanding new concepts and debugging assignments. The solutions uploaded here are **only for reference**. They are meant to unblock you if you get stuck somewhere. Please do not copy any part of the code as-is (the programming assignments are fairly easy if you read the instructions carefully). Similarly, try out the quizzes yourself before you refer to the quiz solutions. This course is the most straight-forward deep learning course I have ever taken, with fabulous course content and structure. It's a treasure by the deeplearning.ai team.
