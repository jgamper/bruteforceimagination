---
layout: post
title: "The Last Polymath, a neural network"
date: 2020-08-19T19:34:30-04:00
description: Thoughts on how GPT would impact science
comments: true
---

> Good mathematicians see analogies between theorems; great mathematicians see analogies between analogies

This quote remark of S. Banach (quoted by S. Ulam 1957) caught my attention while reading 
[_Probability theory: the logic of science_](https://www.cambridge.org/core/books/probability-theory/9CA08E224FF30123304E6D8935CF1A99)
by E. T. Jaynes - took a note of it a few years ago, and.. I forgot about it..
 
To my own surprise, I got reminded of it after a recent GPT-3 twitter-storm (checkout a mid-July spike on
[Google Trends](https://trends.google.com/trends/explore?q=gpt-3) for related search queries). A release of another 
deep neural net is by far not an event of immediate importance to probability theory, but nonetheless.. 
As I was looking through the relevant literature, and [GPT-3 API](https://openai.com/blog/openai-api/) use-cases published on 
twitter (see [Gwern's overview](https://www.gwern.net/GPT-3#what-benchmarks-miss-demos)) -
it became self-evident that the likelihood of substantial medium-term consequences from Open AI's work is high! 

Question is what are these consequences going to be? Now, I dont have the resources to train such a model and test its
limits (I wish), but I do have a keyboard to write about! So here is my speculation.

Generative pre-training transformer (GPT), most certainly follows the steps of Alpha Go in teaching 
[Rich Sutton](http://www.incompleteideas.net/)'s 
[bitter lesson](http://www.incompleteideas.net/IncIdeas/BitterLesson.html) to the 
[skeptics](https://twitter.com/GaryMarcus/status/1297176789983272961?s=20). Yet the learning objective as well as the 
overall scaling is far simpler, and as Gwern's [post](https://www.gwern.net/newsletter/2020/05#gpt-3 ) points out 
cheaper, as compared to Alpha Go (and other projects alike).

> [AlphaGo seems to have totally original moves it creates itself.](https://www.latimes.com/world/asia/la-fg-korea-alphago-20160312-story.html)

Alpha Go [received](https://www.reuters.com/article/us-science-intelligence-go-idUSKCN0WH0XJ) a honorary 9-dan 
title for exhibiting creative skills and pushing forward the game's progress. It inspired multiple professional players
to reflect on their style and strategies, and learn new moves. If that has been the outcome of Alpha Go, then who and
how will be inspired by GPT like models?

When I am learning let's say a concept in linear algebra, and if I really want to understand it, I would refer 
to multiple different textbooks. First to
[_Linear Algebra and Its Applications_](https://www.goodreads.com/book/show/179699.Linear_Algebra_and_Its_Applications) 
By G. Strang, then [_Linear Algebra Done Right_](http://linear.axler.net/) by S. Axler, and then finally to 
Evan Chen's [_Napkin Project_](https://web.evanchen.cc/napkin.html). Then at some point, I see a concept of interest being
used in an applied research paper and it finally clicks!

What caught my attention, is that the data used to train GPT-3 includes very few books, textbooks, and scientific 
journal articles. If GPT-? model could be trained on anything from children's textbooks to graduate course
textbooks with a wide subjects variety, I suspect it would have a strong foundation in scientific reasoning. 

Moreover the data is mostly in English language. Scientific concepts are the
same in different languages, but those same concepts expressed in a different language would provide a stronger learning signal. 
Google, for example, [demonstrated](https://arxiv.org/abs/2007.01852) how BERT sentence embeddings improve 
across all languages when trained on low and high resource languages simultaneously. 

Finally, while textbooks would provide a strong foundation, there is just an enormous abundance of scientific papers 
published every year. As [Nature article](https://www.nature.com/articles/nj7612-457a) from 2016 puts it:

> Recent bibliometrics show that the number of published scientific papers has climbed by 8–9% each year over 
> the past several decades. In the biomedical field alone, more than 1 million papers pour into the PubMed 
> database each year — about two papers per minute.

There is an argument on the quality of all of the research or some of it even being wrong. But the overall trajectory 
of scientific progress has been up, and that is key. Which means that overall, the average use of statistical models, 
experimental, design, proofs and reasoning is correct within the scientific literature - the model trained on all of knowledge would likely pick that up,
as consistent use of the right scientific tools and reasoning will lead to the consistent reduction of the unsupervised loss. 

Henry Poincare seems to be often referred to as the last polymath within mathematics, a person who has excelled in all 
fields of mathematics that existed during his lifetime. How likely there to be a polymath in any field of studies given
the current rate of scientific outputs? Quite unlikely it seems, which is what precisely reminded me of the S. Banach's 
quote - we are missing out on analogies to be made to inspire solutions to the existing problems! 

Most certainly GPT like model will not be an AGI, but a model trained on all of the textual knowledge written by humans,
potentially with some supervised regularisation, will be a very useful. As [Shahine](https://fr.linkedin.com/in/shahine-bouabid) 
helped me to summarise: "Just as AlphaGo pushed the boundaries of human's knowledge in board games, where best players in Go, Chess and other games learn 
from neural network. So will GPT trained on all of scientific knowledge advance science by for example showing signs of inter-fields 
extrapolation of scientific methods".

Other resources:

1. Mitchell M. [_Can GPT-3 Make Analogies?_](https://medium.com/@melaniemitchell.me/can-gpt-3-make-analogies-16436605c446)
2. Ruder S. [_Why You Should Do NLP Beyond English_](https://ruder.io/nlp-beyond-english/)
3. [Philosophers On GPT-3](http://dailynous.com/2020/07/30/philosophers-gpt-3/) & Hardmaru's [tweet](https://twitter.com/hardmaru/status/1289015596646928387?s=20)
4. Roziere et al. [_Unsupervised Translation of Programming Languages_](https://arxiv.org/abs/2006.03511) & Lample's [theard](https://mobile.twitter.com/GuillaumeLample/status/1269982022413570048)
5. Clark J. [_Delegation Machines_](https://twitter.com/jackclarkSF/status/1288144405812019200?s=20)
6. Gwern [_on GPT-3_](https://www.gwern.net/newsletter/2020/05#gpt-3) & Gwern's [_GPT-3 Creative Fiction_](https://www.gwern.net/GPT-3#bpes)
7. Harvard nlp [_The Annotated Transformer_](https://nlp.seas.harvard.edu/2018/04/03/attention.html)
8. [Are we in an AI overhand?](https://www.lesswrong.com/posts/N6vZEnCn6A95Xn39p/are-we-in-an-ai-overhang)
9. Karpathy strikes again with [minGPT](https://github.com/karpathy/minGPT)

 

Cite as:

```
@article{gamper2020gpt-unsolved,
  title   = "The last polymath, a neural network",
  author  = "Gamper, Jevgenij",
  journal = "https://bruteforceimagination.com/",
  year    = "2020",
  url     = "https://bruteforceimagination.com/blog/2020/gpt-polymath/"
}
```
