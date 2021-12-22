# ***alas de colibrí***

code for creating an animation of colbrí wing flapping. 46 landmarks were measured on nine frames of a single wing flap from the supplemental video 5 of Maeda et al. 2017, [Quantifying the dynamic wing morphing of hovering hummingbird](https://doi.org/10.1098/rsos.170307)

the landmarks were saved as the text file `wing_coords.txt`. a body outline was saved as the text file `body_coords.txt`. a template plot of the first and last frames was created onto which an animated flapping wing was projected. to create the animation, 100 steps across a third order polynomial was fitted for each of the 46 landmarks across the 9 empircal video frames. the code to create this animation is available in the jupyter notebook. the frames from which the landmarks were taken are also available in this repository.
