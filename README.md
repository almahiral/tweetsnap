# ThreadSnap

Anda ingin membaca thread Twitter lebih cepat? Ayo gunakan ThreadSnap!

![image](https://github.com/almahiral/threadsnap/assets/74372506/a7f75012-5493-4f7a-9bb9-ba5856cd6d43)

ThreadSnap adalah website yang dapat merangkum isi dari suatu thread Twitter dalam bahasa Indonesia.

ThreadSnap menggunakan teknologi Transformer language model, lebih tepatnya mt5 [https://huggingface.co/docs/transformers/model_doc/mt5](https://huggingface.co/google/mt5-base)https://huggingface.co/google/mt5-base yang di fine-tune menggunakan dataset XLSum Indonesian [https://huggingface.co/datasets/csebuetnlp/xlsum](https://huggingface.co/datasets/csebuetnlp/xlsum) untuk merangkum sebuah thread Twitter berbahasa Indonesia.

Adapun 2 metode pre-processing juga dilakukan, yaitu: 1) Semantic Search dan 2) Text Normalization. Kedua metode ini dilakukan untuk mengatasi bahasa sosial media yang sangat dinamis, tidak beraturan, dan mengandung Colloquial Lexicon [https://github.com/nasalsabila/kamus-alay/blob/master/colloquial-indonesian-lexicon.csv](https://github.com/nasalsabila/kamus-alay/blob/master/colloquial-indonesian-lexicon.csv) dan berbagai "slang" lainnya.
