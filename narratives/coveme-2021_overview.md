---
title: Comparing SARS-CoV-2 outbreaks for coVEME 2021
authors: "James Hadfield"
authorLinks: "https://twitter.com/hamesjadfield"
affiliations: "Fred Hutch, Seattle, USA"
date: "2021-09-02"
dataset: "https://nextstrain.org/community/blab/coveme-2021/brazil?d=tree"
abstract:
    This narrative is intended as an overview of the datasets already explored during coVEME 2021.
    The main purpose is to showcase the ability to use narratives to convey scientific information.
---

# [Focusing on Minas Gerais](https://nextstrain.org/community/blab/coveme-2021/brazil?d=map)

We start by looking at the map, to convey the uneven subsampling, with a strong focus on Brazil.
Note that all our samples (Blue) which we downloaded from GISAID are from Brazil, as expected, but that very few other samples (Yellow), which we got from the GenBank dataset, are from Brazil.

Why might this be?

# [Our data](https://nextstrain.org/community/blab/coveme-2021/brazil?c=num_date&d=tree&f_mydata=yes)

This is the canonical tree coloured by sampling date, filtered to our data.

Notice how the Minas Girais data is concentrated into only 4 parts of the tree? We'll revisit this in a couple of slides time.


# [Spike mutation 417 in the Gamma clade](https://nextstrain.org/community/blab/coveme-2021/brazil?c=gt-S_417&d=tree&label=clade:20J%20%28Gamma,%20V3%29&p=full)

Zooming into the Gamma Clade, and colouring by Spike codon 417.

There's lots of homoplasy at this position - is this to be expected?

# [How are the clade frequencies changing over time?](https://nextstrain.org/community/blab/coveme-2021/brazil?branches=hide&c=clade_membership&d=tree&f_mydata=yes&l=scatter&p=full)

We now look at a scatterplot, with clade on the vertical axis and (sampling) time on the horizontal axis.

This data is subset to Minas Girais and coloured by clade. This represents all of the publicly available (GISAID) data for this area.

We see the birth and death of many clades - 20B, which dominated until March 2021, which was then replaced by Alpha and Gamma (also known as P.1). Alpha didn't last long, and now Gamma dominates.

We see the introduction of Delta recently, which is now circulating alongside Gamma.

Worldwide, we see Delta predominating, but not in Brazil. Why might this be?

Can we tell from this data if Delta will outcompete Gamma?


# [Let's change to look at a different dataset](https://nextstrain.org/community/blab/coveme-2021/nz?d=map)

The dataset has no changed -- Blue still represents "our data", but now we're focused on New Zealand.

Our contextual sequences come mainly from Australia, which is to be expected as until recently the majority of
travel to New Zealand came from Australia.

The outbreak in New Zealand has been different from Brazil. 
Our geographic isolation allowed our government to all but shut the borders, with very few international arrivals
coming into the country.
In addition, we have been pursuing an elimination strategy, with "hard and fast" lockdowns whenever a case is discovered
in the community.

These dynamics should be reflected in a different tree structure than the one we were looking at previously.

# [New Zealand samples are mostly small clusters with little onwards transmission](https://nextstrain.org/community/blab/coveme-2021/nz?c=country&d=tree&dmax=2021-08-05&f_country=New%20Zealand&p=full)

Looking at samples collected _before_ August 5th 2021, and filtering to New Zealand samples (coloured in teal) we see that there have been over one hundred cases, but they are mainly singletons or small clusters which don't transmit for long periods of time?

Why is this?


Second question: Why do we only see New Zealand samples (tips) after June 2021?
(Hint: It wasn't because there were no cases in New Zealand until then!)

# [Zooming in shows this in more detail](https://nextstrain.org/community/blab/coveme-2021/nz?c=country&d=tree&dmax=2021-08-05&f_country=New%20Zealand&label=clade:20C&p=full)

During most of this period there has been very little covid transmitting in the community within New Zealand. 
Each international arrival must quarantine in government facilities for two weeks upon arrival, with multiple PCR tests.
This means that while there is some transmission within these facilities, especially with a traveller's bubble, it doesn't jump into the community.

# [August 2021 outbreak](https://nextstrain.org/community/blab/coveme-2021/nz?c=country&d=tree&f_country=New%20Zealand&label=clade:21A%20%28Delta%29&p=full&dmin=2021-08-05)

Recently, New Zealand detected a case of Delta in the community.
The country went into complete lockdown the next day.

This is clearly seen as a clade entirely comprised of New Zealand samples, with very recent sampling times.

# [August 2021 outbreak has little diversity](https://nextstrain.org/community/blab/coveme-2021/nz?c=gt-nuc_21679&d=tree&f_country=New%20Zealand&label=clade:21A%20%28Delta%29&m=div&p=full)

Switching to a divergence view, we see very little 

As expected for a well sampled, recent outbreak, we see very little diversity within the outbreak, and it
is monophyletic. Nonetheless, we do see a few mutations, which we use here to colour the tree.

P.S. What could the big comb (lots of identical genomes) at the top, coloured in yellow, be a sign of?

P.P.S. How do we explain the New Zealand samples which are not part of this clade?
