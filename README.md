# AIChatBot1
I made this following a tutorial however it doesn;t work for me. 
It has the following error when running. 
ValueError: Exception encountered when calling layer "sequential" (type Sequential).
    
    Input 0 of layer "dense" is incompatible with the layer: expected min_ndim=2, found ndim=1. Full shape received: (None,)
    
    Call arguments received by layer "sequential" (type Sequential):
      • inputs=tf.Tensor(shape=(None,), dtype=int64)
      • training=False
      • mask=None

The input shape is known and is not 0. It just cannot be called when prediciting. The model has a 0.9142% approxima accuracy. 

I also don't like how it is so hard coded, but that is my opnion. 
