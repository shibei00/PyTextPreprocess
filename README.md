# PyTextPreprocess
A package of preprocessing English text or Chinese text.

The preprocessing of English text includes:

1. Remove punctuations.
2. Tokenize sentences.
3. Remove stopwords.
4. Stem words.

The preprocessing of Chinese text includes:

1. Segment via Jieba package.
2. Remove punctuations.
3. Remove stopwords.

The function en_str_preprocess and ch_str_preprocess are vectorized for Numpy.