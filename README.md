# DeVo 

Audio samples 

## Abstract


## Organization

Audio files are organized using the following folder structure:
```
audio
└── model_name
      └── file_id.wav

 ```
#### `model_name`
Corresponds to the model name (or clean/noisy).
+ `clean` -> Clean speech without noise
+ `cpc` -> DeVo with Modified CPC Feature Encoder inputs, finetuned
+ `mel` -> DeVo with mel inputs
+ `demucs` -> Demucs-denoised 
+ `noisy` -> Noisy speech

## Perceptual Evaluation