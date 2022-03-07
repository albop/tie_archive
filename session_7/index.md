# AI & Behavioural Biases (quick intro)

### Pablo Winant, ESCP Business School


<style>
.container{
    display: flex;
}
.col{
    flex: 1;
}
</style>

----

### Overview


In [session 2](./session_2/../index.html), we have discussed several kinds of biases that apply to AI:
- biases from a quantitative/statistical approach
  - systematically wrong predictions of well-defined prediction algorithm
- the problem of preference misspecification
  - algorithm is correct, but the goal it must achieve is wrong
  - preference specification is subject to many problems (multiple contingencies, preference aggregation, multiple objectives)
- AI "behavioral" mistakes
  - AI replicates non rational human behavior (behavioural biases)
  - can be by immitation or otherwise

----

### Behavioural Economics

```Behavioral economics combines elements of economics and psychology to understand how and why people behave the way they do in the real world. It differs from neoclassical economics, which assumes that most people have well-defined preferences and make well-informed, self-interested decisions based on those preferences.``` ([intro from university of Chicago](https://news.uchicago.edu/explainer/what-is-behavioral-economics))

Behavioural economists:
- identify *actual* patterns in agent's decisions 
  - they are measured as deviations to idealized, rational, utility-maximizing economic behaviour
- develop theories that can, consistently predict these patterns
- patterns and theories are tested empirically in labs

----

### The Marshmallow Experiment

#### Instant Gratification

<iframe width="1120" height="630" src="https://www.youtube.com/embed/QX_oy9614HQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

----

### The lab

<img src=lab1.jpg width=30%> <img src=lab2.png width=30%>

Behavioural economists recruits participants for their experiments.

- they perform some specific tasks or play a game meant
- usually paid and incentivized (to have skin in the game)
- experiment tries to recreate conditions so as to expose specific features of human choices
- usually *one* determinant of choice is randomized so as to measure its effect cleanly
- more participants lead to more certain results (if representative)

----

### Example: Other-regarding preferences

The ultimatum game:
- two players negotiate over a fixed amount of money
- player 1 demands a proportion of the pie
- player 2 sees the size and player's 1 demand and either rejects or accepts it
  - accept: split is implemented
  - reject: both players get 0

----

### Example: Other-regarding preferences (2)

<img src=ultimatum.png width=60%>

- hundreds of papers since original one by Guth et al.
- consistent results: average offer is 40%, offers below 20% have high chances to be rejected, lots of 50-50
- note that the "rational choice" for both agents would be 99-1!

----

### Example: Other-regarding preferences (3)

What determines the split? What influences altruism?

![altruism](dilbert.gif)

There are many variants of the ultimatum game with small variations.
- Example: what is the effect of feeling shame towards the other player
  - for half of the candidates, exactly as before (control sample)
    - control group
  - for the other half, the two players, don't see each other don't have any contact. Only the demand from player one is communicated to player 2.
    - treatment group
  - -> players are less generous but the result holds

----

### GPT-3

- GPT-3: Generative Pre-trained Transformer
  - by OpenAI (now Microsoft
  - big deep-learning architecture, trained billions of texts
- produces completion on a prompt
  - the prompt can be used to explain the context...
  - ... but might influence the response
- can we use GPT-3 as our participant in the lab?
  - with which procedure? what would be the experimental biases?
- can we replicate experimental designs to test for behavioural biases?
- what does it even mean?

----

### GPT-3: example


----

### The Behavioural AI Project

TODO: review. Do we want an option to create a game?

- Next week: a game jam
  - several short starting ideas will be presented
  - choose one, work individually on it, then in group, present ideas
  - by the end of the session fill a very short project description
  - then one week to substantiate it a bit (not necessarily finish it)
- The Behavioural AI project
  - we want to know what is the behavior of AI, its biases
  - think about an experimental protocol, or a game-design, which exposes it
  - present it as if it was an actual project

----