# XAIBio24
Exploring explainable AI (XAI) for genomic data analysis.

## What is Explainable AI (XAI)?

Explainable AI (XAI) is a set of methodologies, standards and techniques use
to help humans understand machine learning models' predictions.

Comparison with interpretability:

- Explainability refers to the level in which human can understand how the AI-based
system came up with a result.

- Interpretability refers to level of understanding how the underlying (AI) technology 
works.

Often in researching or studying ML, we sometimes come across the term "black box",
indicating that we do not understand what goes inside of a machine learning model.

## Why use XAI?

Problems such as hallucination - models that output seemingly correct grammar/syntax, 
but wrong results, or reasoning - where we don't fully comprehend the deduction 
of the models, how they led to the current decision are making our trust in the
models becoming harder and harder, as problems that require them to perform
are getting more complex

Imagine working for an important organization, such as gov, or a cancer research
institute. XAI helps in gate-keeping important decisions, where you don't wanna 
let an error slips through and fosters chaos. For example, hypothetically, a
patient is going through many different treatments for various diseases they have,
can a model reliably predict whether the treatments combined together will not
create any adverse effects on the patients?

## How XAI works?

We use XAI to understand and improve the user experience of a product or 
service by helping the end user the trust that AI is making good decisions.

### What are the techniques?

XAI contains 3 main methods: prediction accuracy, traceability and decision understanding

- Prediction accuracy is a comparison between running simulations and comparing
XAI output to the results in the training, prediction accuracy can be determined.

- Traceability limits the way decisions can be made and setting up a narrower 
scope for ML rules and features.

- Human factor, many people have a distrust in AI, and need to learn to trust it
in order to use it.

## Locally-intepretable model-agnostic explanations:

Let's break down the keywords:

- Locally-intepretable: referring to the subset/part of the inputs, and whether
the machine learning model can interpret this with confidence.

- Model-agnostic: referring to the applicability despite of the models' structures.
Meaning that you are safe to use LIME on any model.

- Explanations: can the model explain its decisions?

## Limitations of XAI:

- In terms of **model complexity**, LIME has been well used in many simple ML
models, such as linear regression, but its usage (XAI in general) has not been
well studied in more complex models (such as LLM).

- **Human biases** can play a big influence, since one of the key features of XAI
mentioned above involved human decisions and understandings.

- **Understanding is different from trusting**

## Materials to read:

1. Explainable artificial intelligence for breast cancer: A visual case-based
reasoning approach.[https://doi.org/10.1016/j.artmed.2019.01.001]

2. Explainable artificial intelligence in skin cancer recognition: A systematic 
review.[https://doi.org/10.1016/j.ejca.2022.02.025]

3. DeepXplainer: An interpretable deep learning based approach for lung cancer 
detection using explainable artificial intelligence.[https://doi.org/10.1016/j.cmpb.2023.107879]