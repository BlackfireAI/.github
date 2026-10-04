# Contributing

Thanks for taking an interest in our work.

## Before opening a pull request

Open an issue first describing what you want to change, unless it is a typo or an obvious
bug fix. It saves you writing code we may have already tried.

## Reporting a model problem

Speech models fail in ways that are hard to reproduce from a description alone. A useful
report includes:

- the audio that triggered it, or a clip that reproduces it
- what the model output, and what you expected
- the model version, your transformers and torch versions, and whether you ran on CPU or GPU

If the audio cannot be shared, say so and describe it: length, speaker, recording
conditions, dialect, how much English it contains.

## Accuracy claims

We publish the evaluation script and the test manifest alongside each model, and the full
per-utterance output of our own runs. If you measure something different, send the command
you ran and we will look at it. If you are proposing a change that improves accuracy,
include before and after numbers from the same script on the same test set.

## Code

Match the style of the file you are editing. Keep comments for things that are not obvious
from the code.

## Languages and dialects

We work on Nepali and the other languages of Nepal. If you have data, transcripts or
evaluation sets for a language we do not cover yet, we would like to hear from you, whether
or not it comes with code.
