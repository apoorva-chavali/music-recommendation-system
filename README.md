Current recommendation systems often overlook emotional context and rely on historical listening
patterns or static mood tags. This project introduces a novel music recommendation framework employ-
ing a Wide and Deep Learning architecture that takes in real-time emotional states inferred directly from
natural language as inputs and recommends songs accordingly. The system captures emotional contexts
from user-provided textual descriptions by using transformer based embeddings which were finetuned
for predicting the valence-arousal emotional dimensions. The deep component of the architecture uti-
lizes these embeddings to generalize unseen emotional patterns, while the wide component effectively
memorizes user-emotion and emotion-genre associations through cross-product features. Experimental
results show that personalized music selections positively influence the user’s emotion and and significant
improvement in emotional relevance.

