---
title: "Quantifying structure and diversity in film festival networks"

# event: 
# event_url: 

location: "NetSci 2023: International School and Conference on Network Science, Central European University & Complexity Science Hub Vienna, Austria"
# address:
#  street: Piazza Marina, 61
#  city: Palermo
#  region: PA
#  postcode: '90133'
#  country: Italy

summary: "A poster presentation unpacking the structure of the global film festival network"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-07-12T00:00:00Z"
# date_end: "2022-04-27T11:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2023-04-26T00:00:00Z"

authors: 
- Andres Karjus
- Vejune Zemaityte
- Ulrike Rohn
- Maximilian Schich
- Indrek Ibrus

tags:
- film festivals
- Cinando
- cultural data analytics
- network analysis

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
- Public Value
- CUDAN
---

### Abstract

The film festival circuit is an integral component in the global film industry, yet has remained relatively understudied from a big-picture quantitative perspective. This is partly due to the lack of available data, and the hitherto dominant qualitative focus of related academic disciplines. In the existing literature, however, the film festival circuit is often discussed as a network, even if not quantified as such (De Valck, 2007; Elsaesser, 2005; Loist, 2016). Here, we employ data from the widely-used industry platform Cinando of Marché du Film - Festival de Cannes (2009–2021; 618 festivals, 32,700 films). We model festival events as a network connected by shared films, revealing a (bi)ennial rhythm of connections characteristic of the circuit. We propose to quantify festival profiles using showcased films' metadata, but argue against using count distributions of discrete metadata categories (i.e., genre, production country), as they tend not to be equidistant. Instead, we embed them in continuous latent vector spaces. In some cases, these can be externally sourced: e.g. geographical coordinates can be used to constitute the space of production countries. In others, such as “genre”, the latent space can be directly inferred from co-occurrence statistics, analogously to word embeddings in NLP. We demonstrate how these “festival embeddings”, where festivals are mean vectors of their films, provide insight into the non-random degree distribution in the festival network. We also utilize festival embeddings to measure diversity and changes in festival programming. Our operationalization of film festival data holds promise for researchers to better understand industry and cultural dynamics, as well as for festival programmers,  industry actors and policymakers to make more informed decisions. While our methodological contribution focuses on the film industry, the approach described here could be applied to any ecosystem of related or connected events, festivals, or fairs.

Conference website: https://netsci2023.wixsite.com/netsci2023


#### References

De Valck, M. (2007) Film festivals: from European geopolitics to global Cinephilia. Amsterdam University Press, Amsterdam.

Elsaesser, T. (2005). Film Festival Networks: The New Topographies of Cinema in Europe. In Film Festival Networks: The New Topographies of Cinema in Europe (pp. 82–107). Amsterdam University Press. 

Loist, S. (2016). The film festival circuit: Networks, hierarchies, and circulation. In M. de Valck, B. Kredell, and S. Loist (Eds.), Film Festivals: History, Theory, Method, Practice (pp. 67-82). Routledge.