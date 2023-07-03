# Notes

## About
- Lector: Takumi Ohyama, Machine Learning Engineer, Advanced Solutions Lab, Google Cloud
- Contents of the course:
    - explain what kind of technology has walking behind generative AIs
    - how to actually create a very simple generative model, image captioning model, by using a technologies like encoder-decoder, attention mechanism, and a bit transformers

## Image captioning task
- Task: having a pairs of images and text data, build and train a model that can generate these kind of takes captions based on images
- ![image_captioning.png](images/image_captioning.png)

## Architecture for solution
- ![image_captioning_architecture.png](images/image_captioning_architecture.png)
- It is kind of encoder decoder model
- But in this case, encode and decoder handle different modality of data, which is image and text

## Encoder part
- ![encoder_part.png](images/encoder_part.png)

## Decoder part
- ![decoder_part.png](images/decoder_part.png)
- ![decoder_design.png](images/decoder_design.png)

## Inference loop
- ![inference_loop.png](images/inference_loop.png)
    - ![inference_loop_step1.png](images/inference_loop_step1.png)
    - ![inference_loop_step2.png](images/inference_loop_step2.png)
    - ![inference_loop_step3.png](images/inference_loop_step3.png)
