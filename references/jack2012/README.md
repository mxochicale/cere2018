@article {Jack7241,
	author = {Jack, Rachael E. and Garrod, Oliver G. B. and Yu, Hui and Caldara, Roberto and Schyns, Philippe G.},
	title = {Facial expressions of emotion are not culturally universal},
	volume = {109},
	number = {19},
	pages = {7241--7244},
	year = {2012},
	doi = {10.1073/pnas.1200155109},
	publisher = {National Academy of Sciences},
	abstract = {Since Darwin{\textquoteright}s seminal works, the universality of facial expressions of emotion has remained one 
of the longest standing debates in the biological and social sciences. Briefly stated, the universality hypothesis claims that 
all humans communicate six basic internal emotional states (happy, surprise, fear, disgust, anger, and sad) using the same facial movements 
by virtue of their biological and evolutionary origins [Susskind JM, et al. (2008) Nat Neurosci 11:843{\textendash}850]. 
Here, we refute this assumed universality. Using a unique computer graphics platform that combines generative grammars [Chomsky N (1965) MIT Press, Cambridge, MA] 
with visual perception, we accessed the mind{\textquoteright}s eye of 30 Western and Eastern culture individuals 
and reconstructed their mental representations of the six basic facial expressions of emotion. 
Cross-cultural comparisons of the mental representations challenge universality on two separate counts. 
First, whereas Westerners represent each of the six basic emotions with a distinct set of facial movements common to the group, 
Easterners do not. 
Second, Easterners represent emotional intensity with distinctive dynamic eye activity. 
By refuting the long-standing universality hypothesis, our data highlight the powerful influence of culture 
on shaping basic behaviors once considered biologically hardwired. 
Consequently, our data open a unique nature{\textendash}nurture debate across broad fields 
from evolutionary psychology and social neuroscience to social networking via digital avatars.},
	issn = {0027-8424},
	URL = {http://www.pnas.org/content/109/19/7241},
	eprint = {http://www.pnas.org/content/109/19/7241.full.pdf},
	journal = {Proceedings of the National Academy of Sciences}
}



# Face is a high dimensional dynamic information space

the face represents a high dimensional dynamic information space (see also Fernandez-Dols 2013). 
To illustrate, the face has numerous independent muscles (Drake, Vogl et al. 2010), 
which can be combined to produce intricate dynamic patterns (i.e., facial expressions). 

* Variations in facial morphology (i.e., shape and structure), 
* color (e.g., pigmentation, see Pathak, Jimbow et al. 1976), 
* texture (e.g., wrinkles, scarring), and 
* facial adornments (e.g., cosmetics/painting, tattooing, piercings/jewelry, hair) 
each provide further rich sources of variance (see Dimensions of Face Variance Movie below).

[Understanding the Face as a Dynamic Communication Tool](http://emotionresearcher.com/face-as-dynamic-communication-tool/)

(added:23march2018)





# Interesting sections in the paper

## Discussion

"
Are the six basic emotions universal? We show that six clusters
are optimal to characterize the Western Caucasian facial expression
models, thus supporting the view that human emotion is composed
of six basic categories (24, 31–33). However, our data show that this
organization of emotions does not extend to East Asians, ques-
tioning the notion that these six basic emotion categories are uni-
versal. Rather, our data reflect that the six basic emotions (i.e.,
happy, surprise, fear, disgust, anger, and sad) are inadequate to
accurately represent the conceptual space of emotions in East
Asian culture and likely neglect fundamental emotions such as
shame (34), pride (35), or guilt (36).
"

(added:23march2018)

## Stimuli


On each experimental trial, a 4D photorealistic facial animation gen-
erator (18) randomly selected, from 41 core action units (AUs) (37), a subsample
of AUs from a binomial distribution (n = 5, P = 0.6, median = 3). For each AU,
the generator selected random values for each of the six temporal parameters
(onset/peak/offset latency, peak amplitude, acceleration, and deceleration)
from a uniform distribution. We generated time courses for each AU using
a cubic Hermite spline interpolation (five control points, 30 time frames). To
generate unique identities on each trial, we first obtained eight neutral ex-
pression identities per race (white WC: four female, mean age 23 y, SD 4.1 y;
Chinese EA: four female, mean age 22.1 y, SD 0.99 y) under the same con-
ditions of illumination (2,600 lx) and recoding distance (143 cm; Dimensional
Imaging) (38). Before recording, posers removed any makeup, facial hair, vis-
ible jewelry, and/or glasses, and removed the visibility of head hair using a cap.
We then created, for each race of face, two independent “identity spaces”
for each sex using the correspondent subset of base identities and the shape
and Red-Green-Blue (RGB) texture alignment procedures (18). We defined all
points in the identity space by a [4 identities × 1] unit vector, where each entry
corresponded to the weights assigned to each individual identity in a linear
mixture. We then randomly selected each unit vector from a uniform distri-
bution and constructed the neutral base shape and RGB texture accordingly.
Finally, we retargeted the selected temporal dynamic parameters for each AU
onto the identity created and rendered all facial animations using 3ds Max.


18. Yu H, Garrod OGB, Schyns PG (2012) Perception-driven facial expression synthesis.
Comput Graph 36(3):152–162.


37. Ekman P, Friesen W (1978) Facial Action Coding System: A Technique for the Mea-
surement of Facial Movement (Consulting Psychologists Press, Washington, DC).

38. Urquhart CW, Green DS, Borland ED (2006) 4D Capture using passive stereo photo-
grammetry. Proceedings of the 3rd European Conference on Visual Media Production
(Institution of Electrical Engineers, Edison, NJ), p 196.



(added:23march2018)

