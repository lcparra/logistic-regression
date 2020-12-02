# Logistic regression with regularization 

This matlab code implements classical linear logistic regression, but adds a regularization
term that prevents the transition from one class to another to be too sharp, i.e. it
penalizes the slope of the transition. As we explain in Appendinx B of the paper cited blow, 
this approximates support vectors when the classes are well separated. If classes do have 
some overlap, logistic regression assumes a smooth transition between the two classes, 
wheras support vectors, do not make much sense in that case. In a way this code implements 
the best of both worlds. 


[Lucas C. Parra, Clay D. Spence, Adam D. Gerson, Paul Sajda, "Recipes for the Linear Analysis of EEG", Neuroimage, vol. 28, no. 2, pp. 326-341, November 2005.](https://www.parralab.org/publications/ParraSpenceGersonSajda2005.pdf)


