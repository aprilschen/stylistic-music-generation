# stylistic-music-generation
Music Generation Finetuning notebook using the Meta's MusicGen model, trained on music from the Violet Evergarden: Automemories Soundtrack. 

### Tooling: 
 - AWS Sagemaker (Compute/Jupyter Notebooks platform)
 - Weights & Biases (ML Observability)
 - [Musicgen](https://huggingface.co/facebook/musicgen-melody) (Checkpoint Model for Music Generation)
 - [aprilschen/VioletEvergardenAutomemories](https://huggingface.co/datasets/aprilschen/VioletEvergardenAutomemories) (dataset)
 - huggingface/transformers
 - Ipython (Audio displays)
 - demucs (Voice removal)
 - librosa (labelling: tempo and key)
 - CLAP (labelling: genre, instrument, mood)
 - Perameter-Efficient Fine-Tuning (Low-Rank Adaptation library)

   
Code is modified from Hugging-face user ```ylacombe``` to run on AWS Sagemaker & partially on M1 Apple Silicon (no GPU).
