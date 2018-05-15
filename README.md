# CAp2018_competition

Axes d'amélioration:
- regarder comment faire pour ne pas perdre de mots/ponctuations avec word2vec
- ~~regarder si on peut résoudre ce problème comme un problème de régression (avec une seule sortie)~~ (pas d'améliorations)
- trouver une fonction proche de la fonction de coût de la compétition mais différentiable pour remplacer l'entropie croisée
- ~~dropout~~(amélioration)
- utiliser d'autres données pour mieux classer C1/C2 (des extraits d'articles de journaux par ex)
- ~~essayer plusieurs couches~~ (amélioration)
- ~~LSTM à la place de GRU~~ (stacked LSTM > stacked GRU sinon GRU > LSTM)
- augmented RNN: https://distill.pub/2016/augmented-rnns/ https://web.stanford.edu/class/cs224n/lectures/lecture12.pdf
- temporal convolution network: https://openreview.net/pdf?id=rk8wKk-R-
- ~~essayer d'autres techniques que word2vec~~ (ELMo: pas d'améliorations)
- ~~ELMO: http://allennlp.org/elmo~~ (pas d'améliorations)
- peephole et gradient clipping pour LSTM
