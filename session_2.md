# Brain Foundation Models

## Learning Outcomes. By the end of the session, you:
- Are able to articulate what the term "Brain Foundation Model" means, and why it can be worthwhile to create BFMs.
- Can outline and discuss the various use cases for foundation models of neural activity: feature extraction, downstream adaptation, brain response modeling, stimulation optimization, alignment of brains in latent space, etc.
- Know the self-supervised learning techniques that can be used in building brain decoding models.
- Are oriented in the current state of BFM research, and active research groups in the space.

Year is 2025, everyone is very enthusiastic about the idea of the foundation models for all kinds of things.
Large language models have proven a massive success. 
Large models trained on a lot of data have also been a success in the fields of science, like biology. - CITE AlphaFold

Let's face it: brain foundation models are freaking cool.
But that is not good enough.
We need to think: why do we want to do this, what do we do, and how does it lead to improvement in the goals we want to achieve.


What is a brain foundation model?
- This is essentially a feature extractor.
- Kind of like in the LLM world, you first train a network to learn the statistics of language as it appears in the world. We are trying to compress a lot of data into small weights of the model. And compression is intelligence. To compress the internet effectively, large language models have to learn really useful features from the trillions of tokens of text. What you get is a raw, non-fine-tuned large language model that is actually quite useless on its own. The benefit unlocked with ChatGPT came from fine-tuning it on instruction following to take advantage of the features that the model has learned by compressing the internet and putting them to use to respond to the user queries and do what the user would like.
- This is what we are pursuing with Brain Foundation Models. (SHOW here the slide of unlabeled data challenge)

What are the usecases for brain foundation models?

- Improve decoding capability Every individual person by pre-training on a lot of unlabeled data.
- Uncover relationships between sensory stimuli and neural data to be able to optimize the sensory stimuli to achieve the desired effect in the brain. (multimodal BFM)
- Create models of how the brain responds to direct electric stimulation from the electrodes and then optimize the stimulation parameters to achieve the desired effects in the brain. For example, you might have a patient that suffers from depression, and let's say you have complete access to their brain. What you want to do is to help them with their depression. But unfortunately you don't have a knob that says, "turn depression down." Instead, you have knobs which say "deliver a current of 0.3 mA to those precise coordinates in the brain at this moment on this frequency." And how is it going to affect the brain? I believe at this moment, in January 2026, it is fair to say that we don't really know, besides some small number of exceptions. (i.e. move the person away from a seizure)
- Align different people in the same latent space to do cross-subject decoding.

So if those terabytes of data that we've been collecting from hundreds of patients over the years can somehow help us with that, that will be a real game changer!



Potential guest speakers
JJD
Greta Tuckute


What are the techniques for training brain foundation models?
- Masked modeling
- AR
- Contrastive learning
- maybe,  diffusion models?