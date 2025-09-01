# LSTM Seq2seq model for German-English translation
About:

In this repo you will find a Jupyter notebook in which I have implemented an LSTM encoder/decoder model with and without attention from scratch. It uses the sentencepiece tokenizer and is trained on the Multi30K (https://arxiv.org/abs/1605.00459) dataset which contains English and German image captions from Flickr. I have also implemented both greedy search and beam search algorithms for inference. With attention, the model achieves a BLEU score of ~37-38.



Future work:

I am a massive language nerd and my future goal in the sphere of NMT is actually to develop a Finnish model since Finnish is morphologically much more complex than German (when compared to English). For this reason, Finnish models often achieve lower BLEU scores. Specifically, I think it would be interesting to develop a custom tokenizer that uses linguistic rules to convert noun stems into their root forms to ensure that more words are seen during validation. This would likely produce translations with worse grammar but I think the rough meanings would be preserved and thus increase the BLEU score. Stay tuned.
