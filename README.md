# Hildie Leyser

I'm a computational neuroscientist based in London and I'm looking for data science roles.

I started out in history at Oxford before moving into neuroscience. For my graduate research at McGill and RIKEN I studied how macaques explore and exploit rewards, both alone and in groups. I then joined Netholabs as its second employee and became Head of Research for the human programme, where I worked out how to record EEG and fNIRS in sync with eye tracking and motion capture.

The question I keep coming back to is what a model has actually learned. At Netholabs I evaluated VQ-VAE models of mouse behaviour, and one of them looked very convincing until I saw that its codebook perplexity tracked motion energy at ρ = 0.827. Perhaps it was mostly telling us how much the mouse was moving. That is a very different thing from finding behaviour, and I now go looking for this kind of shortcut in everything I build.

## Some things I've made

- [physiological-stress-detection](https://github.com/hildieleyser/physiological-stress-detection) detects stress from wearable signals in the 15 people of the WESAD study. Split at random, the model scores a macro F1 of 0.999. On people it has never seen that falls to 0.898, and for one person it can be as low as 0.61. Most of the gap is presumably the model recognising individuals.
- [site-signature-audit](https://github.com/hildieleyser/site-signature-audit) asks whether frozen pathology embeddings give away which site a slide came from. If they do, a model could be learning the hospital rather than the biology. The examples use synthetic data.
- [success-claim-audit](https://github.com/hildieleyser/success-claim-audit) compares what a robot policy says it achieved with what an independent observer saw. The examples use synthetic data here too.
- [stop-semantics](https://github.com/hildieleyser/stop-semantics) tests what actually happens when you hit the emergency stop on a physical AI system. The examples come from simulation.
- [social-exploration-primates](https://github.com/hildieleyser/social-exploration-primates) holds my hierarchical Bayesian models of how social context changes exploration in six Japanese macaques.

I work mostly in Python and R, with PyTorch for deep learning and brms for Bayesian modelling. I trained in data science at Le Wagon and I also teach Python for scientific computing, including a workshop for NHS staff at Imperial College London.

You can find me at [hildieleyser.com](https://hildieleyser.com) or on [LinkedIn](https://www.linkedin.com/in/hildelith-leyser-382564206/).
