# Waste Classifier using Teachable Machine

-----------------------------------------------------------------------------------------------------------------------------------------

This project is a **waste classifier** built using [Google Teachable Machine](https://teachablemachine.withgoogle.com/). It uses machine learning to identify and sort different types of waste (like plastic, paper, glass, etc.) from images.  
No coding was required to build or train the model-everything was done using Teachable Machine’s easy-to-use interface!


## How It Works

1. **Data Collection:**  
   Images of different waste types (plastic, paper, glass, etc.) were collected and labeled in Teachable Machine.

2. **Model Training:**  
   The model was trained using Teachable Machine’s web interface to recognize each waste category.

3. **Export:**  
   The trained model was exported in TensorFlow.js format.

4. **Usage:**  
   The exported model files (`model.json`, `metadata.json`, etc.) can be used in web applications or other projects to classify waste images.

## Waste Categories

- Plastic
- Paper
- Glass
- Metal
- Cardboard
- Organic



## Files in This Repository

- `model.json` – The trained model architecture and weights.
- `metadata.json` – Information about the model and classes.
- `*.bin` – Binary files containing model weights.
- `README.md` – Project information (this file).

## How to Use

You can use this model in your own web projects or apps.  
For example, you can load the model in a JavaScript web app using [TensorFlow.js](https://www.tensorflow.org/js):

```js
const modelURL = 'path/to/model.json';
const model = await tmImage.load(modelURL, metadataURL);
// Use model.predict() on new images
```

For more details, see the [Teachable Machine export guide](https://teachablemachine.withgoogle.com/export).

## Credits

- Model trained and exported using [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)
- Project by Sahithi Cinchalapu  

