# Linear Regression

This project provides an implementation of **Linear Regression**, a fundamental supervised learning algorithm used for modeling relationships between variables. The project includes dataset generation, model training using **Gradient Descent**, performance evaluation, and visualization of results.

## Features

- **Dataset Generation:** Creates synthetic data for training.
- **Linear Regression Model:** Implements **Gradient Descent** for optimizing the regression line.
- **Mean Squared Error Tracking:** Compares model performance with different learning rates.
- **Visualization:** Displays regression results through static plots and animated training progress.
- **Saving Outputs:** Supports exporting animations as `.gif`.

---

## Installation

Ensure all dependencies are installed:

```bash
pip install -r requirements.txt
```

Dependencies are listed in `requirements.txt`

If saving as MP4, **FFmpeg** is required:

- **Windows:** Download from [ffmpeg.org](https://ffmpeg.org/download.html) and add it to PATH.
- **MacOS:** Install via Homebrew:
  ```bash
  brew install ffmpeg
  ```
- **Linux:** Install via apt:
  ```bash
  sudo apt install ffmpeg
  ```


---

## Outputs

### Regression Animation

![gif](https://github.com/Alveaenerle/linear-regression/blob/main/linear_regression_animation.gif)


### MSE Change for different learning rates
![image](https://github.com/user-attachments/assets/90a18bc8-81df-495b-87bb-4a5a6fc0808f)



---

## Notes

- **If animations don’t render**, try `HTML(anim.to_jshtml())`.
- **Adjust iterations, learning rates, and update intervals** to experiment with different behaviors.



