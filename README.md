# Beauty Classifier

## Overview

This project is designed to assess the beauty of images, specifically focusing on portraits, utilizing a pre-trained Xception model and a Sentence Transformer model. The Xception model is employed for image beauty prediction, while the Sentence Transformer model generates dynamic reasons explaining why the image with the highest score is considered the most beautiful.


## Model Setup

- The Xception model is fine-tuned on an aesthetic dataset and saved for later use.
- A Sentence Transformer model ('paraphrase-distilroberta-base-v1') is employed to generate dynamic reasons.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
   ```

2. **Run the Code:**
   - Open the provided Colab notebook.
   - Execute the code cells to load the models and predict aesthetic scores for input images.

3. **Input Images:**
   - Enter image paths when prompted.
   - Press Enter to finish entering images.

4. **Results:**
   - Aesthetic scores and images are displayed.
   - The best image is highlighted with a reason caption.

## Output Explanation

- Aesthetic scores are numerical values indicating the aesthetic quality of each input image.
- Images are shown along with their scores, and the best image is labeled accordingly.
- A dynamic reason caption is generated for the best image based on predefined reasons.

## Dependencies

- TensorFlow
- Keras
- Sentence Transformers
- Matplotlib
- NumPy

## Additional Notes

- Ensure that the required dependencies are installed before running the code.
- The provided Sentence Transformer model ('paraphrase-distilroberta-base-v1') can be replaced with other models as needed.

