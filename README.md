# Quora-insincere-questions-classification
Given a question the model decides whether the question is sincere or insincere.
An insincere question is defined as a question intended to make a statement rather than look for helpful answers. Some characteristics that can signify that a question is insincere:

Has a non-neutral tone

Has an exaggerated tone to underscore a point about a group of people

Is rhetorical and meant to imply a statement about a group of people

Is disparaging or inflammatory

Suggests a discriminatory idea against a protected class of people, or seeks confirmation of a stereotype

Makes disparaging attacks/insults against a specific person or group of people

Based on an outlandish premise about a group of people

Disparages against a characteristic that is not fixable and not measurable

Isn't grounded in reality

Based on false information, or contains absurd assumptions

Uses sexual content (incest, bestiality, pedophilia) for shock value, and not to seek genuine answers

The training data includes the question that was asked, and whether it was identified as insincere (target = 1). The ground-truth labels contain some amount of noise: they are not guaranteed to be perfect.

