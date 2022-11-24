### Task: implement text-to-speech model
Implement [FastSpeech](https://arxiv.org/pdf/1905.09263.pdf). Dataset for model training: [LJSpeech](https://keithito.com/LJ-Speech-Dataset/)


--------------
### Requirements for format of your solution
* Brief report:
    * How to reproduce your model? (example: train 50 epochs with config train_1.json)
    * Attach training logs to show how fast your network trained
    * Description and result of each experiment
      * How did you train your final model?
      * What have you tried?
      * What worked and what didn't work?
      * What were the major challenges?
* Code
    * Code should be situated in a public github (or another platform) repository
    * Code should be divided into modules (models, data, scripts ...)
    * All the necessary packages should be mentioned in ./requirements.txt or in an installation guide section of README.md

--------------
### Evaluation

To evaluate the MOS, you must add a synthesis of the following sentences to the report:
* `Accept the things to which fate binds you, and love the people with whom fate brings you together, but do so with all your heart`
* `We suffer more often in imagination than in reality`
* `Wasserstein distance or Kantorovich Rubinstein metric is a distance function defined between probability distributions on a given metric space`

--------------
### Goal
* train the SOTA model by yourself
* understand the main practical implementation points of tasks with audio

--------------
### What will be assessed
* your ideas in experiments
* your understanding of the code
* your understanding of the model architecture 
* your understanding of training process
* code quality (reproducibility, readability, clearness)
