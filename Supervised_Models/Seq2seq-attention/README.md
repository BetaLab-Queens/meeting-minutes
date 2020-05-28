The AMI meeting data produces terrible results. This could be because:
- The MEETING DATA ONLY HAS 142 SAMPLES (likely the problem, see Seq2seq-attention-glove-embeddings-gigaword-142samples.ipynb)
- LSTM architecture only works with small input -> small output. A meeting is too long to handle. 

### For rouge, look at the bottom of gigaword for implementation details. 
