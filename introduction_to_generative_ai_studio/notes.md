# Notes

## About
- Agenda:
    - Explain what Generative AI Studio does
    - Describe Generative AI Studio options
    - Explore the Generative AI Studio language model
    - ![agenda](images/agenda.png)

## Google's part
- Google Cloud provides several easy-to-use tools that help you use generative AI in your projects with or without an AI and machine learning background.
- One such tool is Vertex AI.

## Vertex AI
- https://cloud.google.com/vertex-ai
- Vertex AI is an end-to-end ML development platform on Google Cloud that helps you build, deploy, and manage machine learning models
    - ![vertex_ai](images/vertex_ai.png)

## Model Garden
- If you are a data scientist or ML developer who wants to build and automate a generative AI model, you can start from Model Garden
- Model Garden lets you discover and interact with Google’s foundation and third-party open source models and has built-in MLOps tools to automate the ML pipeline.

## Generative AI Studio
- With Vertex AI, if you are an app developer or data scientist and want to build an application, you can use Generative AI Studio to quickly prototype and customize generative AI models with no code or low code
- Generative AI Studio supports language, vision, and speech.
    - ![genai_studio.png](images/genai_studio.png)
    - The list grows as you are learning this course :)
- What one can do with language tasks:
    - ![gen_ai_studio_language.png](images/gen_ai_studio_language.png)

## X-shot prompting
- Zero-shot prompting - is a method where the LLM is given no additional data on the specific task that it is being asked to perform. Instead, it is only given a prompt that describes the task.
- One-shot prompting - is a method where the LLM is given a single example of the task that it is being asked to perform.
- Few-shot prompting - is a method where the LLM is given a small number of examples of the task that it is being asked to perform.
- ![xxx_shot_prompting.png](images/xxx_shot_prompting.png)

## Prompting parameters
- ![model_parameters.png](images/model_parameters.png)
- ![p_temperature.png](images/p_temperature.png)
- ![top_k.png](images/top_k.png)
- ![top_p.png](images/top_p.png)

## Parameter-efficient tuning
- ![parameter_efficient_tuning.png](images/parameter_efficient_tuning.png)
- PET is available at Vertex AI!
    - ![create_tuned_model.png](images/create_tuned_model.png)
