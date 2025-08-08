# Plankton-Generalized-Category-Discovery

Understanding plankton populations is critical for
ecological and environmental research, yet traditional methods
of plankton classification are labor-intensive and inefficient. This
paper proposes an approach for classifying plankton species
with Generalized Category Discovery (GCD) and deep learning.
The challenge in plankton classification lies in the incomplete
datasets, where many species are underrepresented. Approaching
this problem with GCD techniques addresses this by identifying
new categories within image datasets, even without predefined
labels. Our method employes a ResNet-18 backbone for feature
extraction, fine-tuned with semi-supervised contrastive repre-
sentation learning. We introduce a semi-supervised Expectation
Maximization (EM) clustering algorithm with a mixture of von
Mises-Fisher distributions suitable for high-dimensional spherical
data. Evaluations on the WHOI-Plankton dataset demonstrate
that our approach outperforms traditional clustering methods
for medium to large classes in recognizing both known and
novel plankton species. This work shows significant promise in
automating and scaling plankton classification, which would be
a valuable tool for ecological monitoring.

The manuscript for this project can be viewed [here](https://github.com/Rohan-Jagannathan/Plankton-Generalized-Category-Discovery/blob/master/Manuscript.pdf)
