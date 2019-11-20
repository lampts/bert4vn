# BERT for Vietnamese

"The brain doesn't have to model the world. The world is its own model." — Hubert Dreyfus (Berkeley Philosopher)

We published the BERT(Multilingual) finetuned for vietnamese as described here:

1. Initialized from BERT-Base, Multilingual Cased (New, recommended): 104 languages, 12-layer, 768-hidden, 12-heads, 110M parameters
2. Pretrained using 110K wordpiece vocab, on 500M+ words of vietnamese news (We don't release this dataset)
3. Fine tuned on Squad2 to get the given checkpoint (step 16289)

You can download it [here.](https://drive.google.com/open?id=169yKntAy8kqPKU0Crl1m5lLjQ3UZYwxZ) 

If it's helpful for you, please give it a star. We gonna release albert4vn ASAP. Keep in touch.

### Things to improve

- Train bert from scartch for vietnamese tokens
- Train albert from scratch for vietnamese tokens

### References

- https://github.com/google-research/bert/blob/master/multilingual.md
- https://www.tensorflow.org/tfrc
