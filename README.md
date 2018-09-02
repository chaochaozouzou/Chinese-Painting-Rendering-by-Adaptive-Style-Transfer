# Chinese-Painting-Rendering-by-Adaptive-Style-Transfer

Chinese painting is distinct from other art in that the painting elements are exhibited by complex water-and-ink diffusion and shows gray, white and black visual effect. Rendering such a water-and-ink painting with polychrome style is a challenging problem. In this project, we propose a novel style transfer method for Chinese painting. We firstly decompose the Chinese painting with adaptive patches based on its structure, and locally colorize the painting. Then, the colorized image is used for guiding the process of texture transfer that is modeled in Markov Random Field (MRF). More precisely, we improve the classic texture transfer algorithm by modifying the compatibility functions for searching the optimal match, with the chromatism information. The experiment results show that proposed adaptive patches can well preserve the original content while matching the example style. The main contributions of this work are summarized as follows:
1.	We adaptively divide target Chinese painting into patches based on its local similarity for texture synthesis, in stead of using patches of constant size, so as to achieve a realistic reconstruction of the original image while present most noticeable example style;
2.	Constraints are modified in the process of texture synthesis, where color is considered as a relevant factor guiding local texture transfer. It may guarantee the validity in transfer process, where the futile texture is prevented.

Results
 
 
 
 



