# TTS dataset creation guidelines

1. Introduction
2. Creation process
2.1. requirements
2.2. Selection of sentences
2.3. Notes for recordings
3. Conclusion
4. Resources

## 1. Introduction

Text-to-speech systems in screen readers allow us to easily navigate devices, as long as the system being used, and its voices are truly optimal for this task. One of them include response speed and good voice performance (interpretation of punctuation, appropriate intonations, prosody, etc.). To build a TTS voice under these conditions, it's important to highlight the points below:

## 2. Creation process

### 2.1. Requirements

It's recommended that recordings be of the best quality possible and be made in a quiet environment. In addition, you must take into account how you're going to interpret your voice in the recordings. That is, create your speaking style. Otherwise, the results, regardless of the TTS system in which the voice is built, the voice will come to sound monotonous as a consequence.

### 2.2. Selection of sentences

It's important to choose a set of sentences that have all the possible phonemes of the language. To do this, you can make this choice using fragments of books of your choice (or record the entire book if you like), since the greater the variability, whether in prosody, body of voice or phonemes, the more efficient the results can be. A minimum of 1 to 2 hours of data is required under these conditions.

### 2.3. Notes for recordings

* Try to maintain good vocalization while you speak.
* If the target text has punctuation marks, Apply the appropriate intonations and pauses according to the punctuation, EX.: In the comma, the rise in tone is applied to the last syllable and a short pause. If you interpret a pause where the text doesn't have one, try to reflect it in the text. This helps the text and audio align correctly when building the voice.

If these requirements aren't met, you can make as many takes of the recording as you want until you reach the desired result.

## 3. Conclusion

Having this set of recordings ready, it's time to build the corpus. This can have as many formats as possible. Some of these formats may be [LJSpeech](https://keithito.com/LJ-Speech-Dataset/) or `ssml`. The audio format must be uncompressed, the most commonly used is wav in a single channel (mono). The transcript can be created according to the format you have chosen.

## Resources

* [Piper recording studio](https://github.com/rhasspy/piper-recording-studio): Text prompts in many languages.
