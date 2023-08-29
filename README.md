# neoTorToiSe
Redesigning TorToiSe

Llama+Audio Codec+TorToiSe+Vocoder=SotA TTS?

The idea is to train Llama on a TTS task (`[BOS]Text to translate[SEP]<audio tokens here>[EOS]`) and then train Vocos (a vocoder) on the last (or maybe another) hidden layer of the model like Tortoise did with the last hidden layer of its GPT2.
