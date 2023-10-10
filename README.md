# Etsy Product Category and Color Prediction

## About This Project

Welcome to my personal project, where I delve into the fascinating world of Etsy, a renowned online marketplace, to explore intriguing trends related to product categories and colors. Through the application of machine learning techniques, I set out to uncover the potential of predicting both the category and color of a product based on its title and image. The outcomes of this endeavor reveal that category prediction yields promising results, while predicting colors presents unique challenges due to the subjective nature of color perception. This project offers valuable insights into consumer interactions with diverse product categories and colors, all within the context of the thriving e-commerce landscape.

## Key Findings

In the course of this personal project, my primary goals were to predict the top and bottom categories of products listed on Etsy.com and determine their color using machine learning algorithms. To achieve this, I harnessed the power of Random Forest and K-Nearest Neighbour classification algorithms, resulting in impressive accuracy rates of over 85% for both category predictions. However, the accuracy of color prediction fell short of expectations.

For future exploration, I recommend experimenting with alternative deep learning models such as ResNet50, Inception, VGG, or MobileNet, to ascertain whether they can enhance color classification accuracy. Another intriguing avenue is the implementation of a multi-step approach, where object detection identifies objects within images, and a subsequent machine learning model extracts colors from object masks to potentially yield more precise predictions.

Furthermore, it's worth noting that the Random Forest and KNN models employed in this personal project were not fine-tuned. Fine-tuning these models may lead to enhanced results. This endeavor underscores the potential of machine learning in the analysis of e-commerce data, inviting further personal exploration and refinement of predictive models in this captivating domain.

## Technologies Used

- Machine Learning
- TensorFlow (for color prediction)
- Random Forest
- K-Nearest Neighbour
- Python

## Usage

1. Clone this repository.
2. Set up the necessary environment and dependencies as specified in the project files.
3. Run the provided scripts to train and evaluate the machine learning models.
4. Explore the project's code and data to gain insights into the methodology and results.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to dive into the code and results contained within this repository, as it represents my personal exploration of the intriguing world of Etsy, machine learning, and e-commerce trends. If you have any questions or suggestions, please don't hesitate to reach out.
