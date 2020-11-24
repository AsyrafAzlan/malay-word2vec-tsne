# malay-word2vec-tsne
Application of Malay Word2Vec and its visualization using t-SNE in 2D and 3D space.

Word2Vec is performed on Malay Wikipedia dump on 2020-03-01:
</br>[1] Wikimedia Foundation. ―mswiki dump progress on 20200301.‖ Wikimedia Downloads. https://dumps.wikimedia.org/mswiki/20200301/ (accessed March 09, 2020).
You may find the latest dumps on: https://dumps.wikimedia.org/mswiki

The Word2Vec output/results/collaterals can be obtained via:
</br>https://www.dropbox.com/s/pm9rrynspp16det/malay_word2vec.zip?dl=0

Word2Vec algorithm is based on:
</br>[2] Mikolov, Tomas, Kai Chen, Greg Corrado, and Jeffrey Dean. "Efficient estimation of word representations in vector space." arXiv preprint arXiv:1301.3781 (2013).

T-Distributed Stochastic Neighbor Embedding
</br>[3] Maaten, Laurens van der, and Geoffrey Hinton. "Visualizing data using t-SNE." Journal of machine learning research 9, no. Nov (2008): 2579-2605.

Interestingly, some super-clusters are observed as seen in bottom right part of the figure where Foods, Plants and Animals are close to each other. This may be considered accurate as plants and animals are parts of nature and can be considered as supplies within a food chain. 
</br>Another super cluster can be viewed at the bottom left section of the figure where Europe, Asia and Africa are closely placed as they are all countries or places within each continent. 
</br>Another inference that can be made is that Philosophy is in a higher coordinate from Professions while Space is on an even higher coordinate than Philosophy as it may be relatively interpreted that philosophers think of the stars in their vocation.
![ScreenShot](https://github.com/AsyrafAzlan/malay-word2vec-tsne/blob/main/word2vec_tsne2d.png)

3D visualization is slightly harder for the eye but you can still see the clusters are formed.
![ScreenShot](https://github.com/AsyrafAzlan/malay-word2vec-tsne/blob/main/word2vec_tsne3d.png)
