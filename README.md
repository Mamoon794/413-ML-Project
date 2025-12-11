# Genre Based Song Lyrics Generation with LSTM
A model that generates song lyrics based on an input genre and optional input prompt.

- `baseModelOutput.txt` Contains the lyric outputs that the baseline model generated.
- `finalModelOutput.txt` Contains the lyric outputs that the final, improved model generated.
- `final_lyrics_generation.ipynb` Contains the code that was used to clean data, define and train our model, and generate lyrics.

## models folder
- `baseModel.pt` is the model file for the base model.
- `finalModel.pt` is the model file for the final model (our improved model).
- `lyric_tokenizer.model` and `lyric_tokenizer.model` are our tokenizer files that are used when generating output or training.
