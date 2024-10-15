Following the steps of the notorious Andrej Karpathy in the following video-tutorial: https://www.youtube.com/watch?v=kCc8FmEb1nY&t=1492s, in this notebook we implement a Language Model based on the Transformer architecture "from scratch" that generates sequences of words that may fool someone into thinking that they were written by Miguel de Cervantes on the mother of the novel genre: "El Quijote de la Mancha". The goal is to understand the fundamentals behind Natural Language Processing and the Transformer architecture. Being more technical, we implement and "pre-train" a Decoder-Only Transfomer to generate text using "El Quijote de la Mancha".

NOTE: The validation process and the batch creation is simplified.
- Batch creation randomly selects samples, does not take into account samples reapeated samples (within and/or outside the batch).
- Validation method: Hold Out. No Cross-validation.
