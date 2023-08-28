# neoTorToiSe
Redesigning TorToiSe

RWKV+Audio Codec+TorToiSe+Vocoder=SotA TTS?

The idea is to train RWKV on a TTS task (`[BOS]Text to translate[SEP]<audio tokens here>[EOS]`) and then train Vocos (a vocoder) on the last (or maybe another) layer of wkv like Tortoise did with the last hidden layer of its GPT2.
