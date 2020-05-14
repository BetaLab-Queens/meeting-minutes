# The models that don't work are the bi-directional models, the rest of the models work. 
## The glove embedded models should be designed to work well on generalizing new summaries since they won't be overfit to the specifics of the training data, so would be used over the trainable embedding model.  
The code above is an example of the working models, not fully trained. I didn't fully train each model since it takes 20+ hours to do so. The models can be further trained to produce more accurate summarization representations using 
- A) a larger dataset
- B) early stopping used with the epoch training
- C) 500+ hidden units, my computer crashes with anything over 400 hidden units (aka latent_dim)
