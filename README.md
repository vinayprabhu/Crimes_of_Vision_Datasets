# 1: CelebA-HQ and Glow
## No! Models *amplifying biases* is not a hand-wavy shtick ethicists use. 

Exhibit-A: Difference between the prototypical aligned and averaged pixel space image v/s the model-concocted image:

![Exhibit-A](/img/glow_0.png)

## If this is *this* bad for the 'attractive' attribute (I don't condone the presence of such subjective garbage attributes in the first place), are the rest of them just filled with _caucasian-esque_ images?
![Exhibit-B](/img/glow_1.png)



Surely, it must be the data. No?

Nope.
### Just 3.39% of the dataset is tagged FEMALE, ATTRACTIVE and PALE-SKINNED
Even if we consider only 'attractive' images, barely 5.9% of these images (1017) are 'female' and 'pale_skinned'.

![Exhibit-C](/img/glow_3.png)
As seen, there *IS* diversity that is ignored by the model.

## Devil's advocate: What if there 3 attributes were unluckily evaluated wrongly?

Or, in other words, for Attractive, Male and Pale_skin, do the 'positive' and 'negative' directions both make sense visually?
![Exhibit-B](/img/glow_2.png)

Yep. They do!

# 2: Crimes_of_Tiny_Images
JFC! What a hot mess. *Scream into void*

Examples of offensive imagery in the datatset

![Exhibit-A](/img/unethical_1.png)
![Exhibit-B](/img/unethical_2.png)
![Exhibit-C](/img/unethical_3.png)
![Exhibit-D](/img/unethical_4.png)
