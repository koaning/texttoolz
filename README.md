# texttoolz

> tools and tricks that are good to have around

### Text Filter Things

Flashtext text finder might be useful.

### Phrase Detection Things

We can do something "data driven" like described [here](https://arxiv.org/pdf/1310.4546.pdf).

$$ 
\operatorname{score}\left(w_i, w_j\right)=\frac{\operatorname{count}\left(w_i w_j\right)-\delta}{\operatorname{count}\left(w_i\right) \times \operatorname{count}\left(w_j\right)}
$$

Then there's spaCy's grammar tricks. 

And [Gensim](https://radimrehurek.com/gensim/models/phrases.html).
