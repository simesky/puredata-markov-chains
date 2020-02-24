# Pure Data - Markov Chains
Abstraction for easier, hopefully more instuitive implementation of Markov chains in Pure Data

Based on the Markov Chain help file, the goal of this abstraction is to simplify the configuration of a Markov chain by visually representing the transition matrix. You can input the probabilities directly in the abstraction (always in sequence within a row) for quick experimentations. Note that only the first 2 probabilities of a row are necessary, as the third one is given automatically (remember that the sum of a row has to be 1 or 100%). 

# Attention: 
if you want to save the configuration with your patch, use the dedicated inlets! This is better anyway, since the clip objects will prevent you from having incorrect probabilities sums per row.

