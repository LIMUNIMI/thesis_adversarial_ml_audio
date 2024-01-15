# A systematic evaluation of adversarial attacks against speech emotion recognition models

Source code for the paper "A systematic evaluation of adversarial attacks against speech emotion recognition models" [Submitted]

## Set up

Use conda and the environment file provided

## Description of notebooks

- **attacks.ipynb**: Run the attacks and the evaluation
- **correleations_analysis.ipynb**: Perform preliminary analysis on the datasets for identifying most correlated classes
- **datasets_preprocessing_phase1.ipynb**: Perform pre-processing (step 1)
- **datasets_preprocessing_phase2.ipynb**: Perform pre-processing (step 2), including data augmentation
- **datasets_sr_test.ipynb**:
- **data_visualization.ipynb**:
- **defenses-Copy1.ipynb**:
- **defenses.ipynb**:
- **hyperparameter_optimization-Copy1.ipynb**:
- **hyperparameter_optimization.ipynb**: Perform the hyper-parameter fine-tuning
- **image_specotrograms.ipynb**: Create images and audio of original and attacked samples
- **metadata_preparation.ipynb**:
- **model_CNN_LSTM.ipynb**: Create the models
- **preprocessing_comparison.ipynb**:
- **random_guess_dummy_classifier.ipynb**: Run a random guessing classifier on the data

## Demo

Here are some audio as examples of the original and attacked samples.

### EmoDB

- Male
  - Original: [audio](./audio_examples/d1OM.wav)
  - Attacked: [audio](./audio_examples/d1AM.wav)
  - Attacked without outliers: [audio](./audio_examples/d1AM_no_outlier.wav)
- Female
  - Original: [audio](./audio_examples/d1OF.wav)
  - Attacked: [audio](./audio_examples/d1AF.wav)
  - Attacked without outliers: [audio](./audio_examples/d1AF_no_outlier.wav)

### EMOVO

- Male
  - Original: [audio](./audio_examples/d2OM.wav)
  - Attacked: [audio](./audio_examples/d2AM.wav)
  - Attacked without outliers: [audio](./audio_examples/d2AM_no_outlier.wav)
- Female
  - Original: [audio](./audio_examples/d2OF.wav)
  - Attacked: [audio](./audio_examples/d2AF.wav)
  - Attacked without outliers: [audio](./audio_examples/d2AF_no_outlier.wav)

### Ravdess

- Male
  - Original: [audio](./audio_examples/d3OM.wav)
  - Attacked: [audio](./audio_examples/d3AM.wav)
  - Attacked without outliers: [audio](./audio_examples/d3AM_no_outlier.wav)
- Female
  - Original: [audio](./audio_examples/d3OF.wav)
  - Attacked: [audio](./audio_examples/d3AF.wav)
  - Attacked without outliers: [audio](./audio_examples/d3AF_no_outlier.wav)

## Cite us

[TODO]

