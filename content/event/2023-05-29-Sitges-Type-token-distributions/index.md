---
title: "Type-token distributions beyond the Zipf law: a simple model with choice"

# event: 
# event_url: 

location: "XXVII Sitges Conference on Statistical Mechanics, Spain"
# address:
#  street: Piazza Marina, 61
#  city: Palermo
#  region: PA
#  postcode: '90133'
#  country: Italy

summary: "A presentation discussing a statistical model for describing the distributions of movies by popularityn"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-05-29T00:00:00Z"
# date_end: "2022-04-27T11:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2023-04-26T00:00:00Z"

authors: 
- Mikhail Tamm
- Paul Krapivsky 
- Vejune Zemaityte
- Ksenia Mukhina
- Maximilian Schich

tags:
- film popularity
- type-token distributions 

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 
  focal_point: Right

# links:
# - icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- CUDAN
---

### Abstract

Zipf law is one of the very few regularities believed to permeate quantitative social sciences. It describes distribution of tokens (objects) between a given set of types (classes), and states that if types are order in descending order of popularity (number of tokens in them), then the size of a type is proportional to its rank in some negative power. This law is well established in wealth distribution (Pareto law),[^1] city science (Zipf law for city sizes),[^2] linguistics (distribution of word frequencies).[^3] The same law is believed to hold for the distribution of demand for cultural objects like movies, books, singles, etc., which is supposed to lead to important consequences for marketing.[^4]

Using historical data for film industry we show here that it is not always the case. In fact, the distributions of movies by popularity is (apart from a small number of super-hits) well described by exponential rank-size distribution, i.e., size (popularity) decays exponentially with rank. 

In order to describe this behavior we construct a following simple statistical model. Consider a set of $m$ initially empty classes (types) and sequentially add $N$ tokens to these types according to the following procedure: first, choose a subset of a types at random, then determine which of the classes in this subset currently has the largest number of tokens (if there is a draw between two or more leaders, then choose one of them at random) and add an additional
token to this class.

In the limit of large number of classes $m → ∞$ and finite number of tokens per class $t = frac{N}{m}$ the model is described by the infinite set of differential equations
$$dCk/dt = Cka−1 − Cka$$
where Ck is the fraction of types with at most k tokens in them. We show that for large k and t the distribution Ck(t) converges to a scaling form C(x) where x = k/t, and C(x) satisfies
$$(aCa−1 − x)C′ = 0$$
with boundary conditions C(0) = 0, C(∞) = 1. This equation has a solution
$$C(x) = ( (1 for x/a)1/(a−1) for 0x > a < x < a$$
This means that the type-token distribution has a form of a travelling wave with growing average number of tokens per class, the leading class has approximately at tokens in it. Converting this limiting behavior into the form of rank-size distribution we show that for a ≫ 1 it converges to the exponential distribution akin to one observed in the data.

We discuss possible generalizations of this model, such as preferential choice of the subset of a classes.

Conference website: https://sites.google.com/fmc.ub.edu/sitges-conference

[^1]: W.J. Reed, Physica A, 319, 469 (2003).

[^2]: M. Barthelemy, The Structure and Dynamics of Cities: Urban Data Analysis and Theoretical Modeling, Cambridge University Press (2016).

[^3]: M. Gerlach, E.G. Altmann, New J. of Physics, 16, 113010 (2014).

[^4]: C. Anderson, The long tail: why the future of business Is selling less of more, Hyperion, New York, 2006.