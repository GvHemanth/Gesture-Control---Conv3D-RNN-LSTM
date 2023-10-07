# Gesture-Control---Conv3D-RNN-LSTM
## Smart TV Gesture Recognition

![Smart TV Gesture Recognition]([images/smart_tv.jpg](https://miro.medium.com/v2/resize:fit:609/1*_cO6HwEoNYLzTjIqDLUpJw.png))

## Problem Statement

Imagine revolutionizing TV control with gestures! I, as a data science team at a leading home electronics company, embarked on a journey to develop a feature for smart TVs that recognizes five different gestures. Users can control the TV seamlessly without a remote. 


Each gesture corresponds to a specific command:
- Thumbs up: Increase the volume
- Thumbs down: Decrease the volume
- Left swipe: 'Jump' backward 10 seconds
- Right swipe: 'Jump' forward 10 seconds
- Stop: Pause the movie

Our challenge? Continuous gesture monitoring through the TV's webcam and processing these gestures effectively.

## Architecture

To tackle this problem, we adopted a Conv3D CNN-RNN architecture stack, leveraging the power of Convolutional 3D layers and LSTM (Long Short-Term Memory) networks. This architecture excels at capturing both spatial and temporal information from the video sequences.

## Dataset

The dataset consists of video sequences, each containing 30 frames/images. These videos were recorded using regular webcams, simulating real interactions with smart TVs. Each gesture's frames are categorized into five classes (0-4), corresponding to the five gestures.

## Data Augmentation

To enhance model generalization, we employed an ImageDataGenerator for data augmentation, effectively increasing the dataset's diversity and robustness.

## Project Structure

- `data/`: Contains the dataset (not included in this repository due to size).
- `notebooks/`: Jupyter notebooks for data exploration, model development, and evaluation.
- `models/`: Saved model checkpoints.
- `README.md`: You're reading it!

## Usage

1. Download the dataset from here : https://drive.google.com/uc?id=1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL
2. Set up your Python environment with the necessary libraries.
3. Explore the provided Jupyter notebooks to understand the project.
4. Train the model and save checkpoints as needed.

## Contributions

Contributions are welcome! Feel free to open issues, provide feedback, or submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
