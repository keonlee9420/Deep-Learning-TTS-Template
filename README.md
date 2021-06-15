# Non-autoregressive Deep Learning-Based TTS Template

This is a template for the Non-autoregressive TTS model.
It contains
- Data Preprocessing Pipeline
- Data Loader
- Model / Trainer
- Logger, Postprocessing (logging, synthesizing, plotting, etc..)

# How to use it?
1. Clone the repository.
    ```
    git clone https://github.com/keonlee9420/Deep-Learning-TTS-Template
    cd Deep-Learning-TTS-Template
    ```
2. Replace all `MYMODEL` strings in this repo with your model name and also rename the file `model/MYMODEL.py`.
3. Build your model on `model/` and check `train.py` and `synthesize.py`.
3. Use `README_template.md` for the README.md file of your project.
4. Feel free to add `/img` for your model architecture and tensorboard examples. It would also be nice to show your model's output audio in `/demo`.
5. Don't forget to update `requirements.txt` and `/config` of your project.

# Citation

```
@misc{lee2021deep_learning_tts_template,
  author = {Lee, Keon},
  title = {Deep-Learning-TTS-Template},
  year = {2021},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/keonlee9420/Deep-Learning-TTS-Template}}
}
```

# References
- [ming024's FastSpeech2](https://github.com/ming024/FastSpeech2)
