# stylistic-music-generation
Music Generation Finetuning notebook using the Meta's MusicGen model, modified from Hugging-face user ```ylacombe``` and trained on music from the Violet Evergarden: Automemories Soundtrack. 

### Tooling: 
 - [Musicgen](https://huggingface.co/facebook/musicgen-melody) (Checkpoint Model for Music Generation)
 - [aprilschen/VioletEvergardenAutomemories](https://huggingface.co/datasets/aprilschen/VioletEvergardenAutomemories) (dataset)
 - huggingface/transformers
 - Ipython (Audio displays)
 - demucs (Voice removal)
 - librosa (labelling: tempo and key)
 - CLAP (labelling: genre, instrument, mood)
 - Perameter-Efficient Fine-Tuning (Low-Rank Adaptation library)
