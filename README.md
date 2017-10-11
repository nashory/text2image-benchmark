# text2image-benchmark
Performance comparison of existing GAN based Text To Image algorithms. (GAN-CLS, StackGAN, TAC-GAN)  
__Note: The codes in algorithms folder is brought from the respective author's repo, not written by me.__


## Bug fixed.
+ StackGAN:  
    + modified requirements.txt to avoid environemnt conflict.
    + used tensorflow 1.0.1 version instead of 0.12.0, to avoid `tf.zeros_initializer()` error. 
    + change the argument order of tf.concat to avoid type mismatch error. [[see here]](https://github.com/google/prettytensor/issues/48)
    + added folder/file creation code to automatically create Data/birds/example_captions.txt file.
    (please add example sentences to example_captions.txt file, otherwise there will be error.)


