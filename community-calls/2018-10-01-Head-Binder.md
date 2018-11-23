# Binder meets Library Carpentry

Tim Head, [@betatim](https://twitter.com/betatim)

---

# End Goal

Science works by building on the work of those who came before. You need to reuse. Before reuse comes: replicate, reproduce, etc. Today even these steps are massively expensive/time consuming.

End goal: make reuse as easy as possible.

---

# Code + Data is not enough

You need the environment in which the code was applied to the data to get the results in the paper.

---

# Environments: technically already possible

In practice very hard to do.

```
RUN apt-get update &amp;&amp; \
    apt-get install --yes --no-install-recommends \
       less &amp;&amp; \
    apt-get purge &amp;&amp; \
    apt-get clean &amp;&amp; \
    rm -rf /var/lib/apt/lists/*
```

---

# Binder demo

[PDF](https://arxiv.org/abs/1803.05268), [code](https://github.com/davidmascharka/tbd-nets), and

&lt;a href=&#34;https://mybinder.org/v2/gh/betatim/tbd-nets/binder?filepath=visualize-output.ipynb&#34; class=&#34;center width-50&#34;&gt;&lt;img src=&#34;https://mybinder.org/badge.svg&#34; alt=&#34;Binder&#34;&gt;&lt;/a&gt;

---

# How does it work?

Short explanation of how we build on standards and practices already used in the community. For example `requirements.txt` (for Python) or `DESCRIPTION` (for R).

---

# mybinder.org is open!

All software is BSD3 licensed. All configuration, incident reports and meetings about mybinder.org are open.

Everything you need to know about [how we deploy mybinder.org](https://github.com/jupyterhub/mybinder.org-deploy/)

---

# Three public BinderHubs!

1. https://mybinder.org
2. https://notebooks.gesis.org/binder/
3. http://binder.pangeo.io/

---

# Where to next?

Sustainable governance, federation, and doi2docker are things I am excited about working on.

---

# Project Binder and libraries?

* Very popular tool with educators (self-service!)
* Used for making publications easy to re-run
* Based on open-source tools with a team that is known for being good actors in the open-source world.
* Binder team currently has no experts in archival best practises
* How to best combine data, code, publishing, archiving and all that?

---

# Other use cases of Binder

* [open refine without installing it] (https://mybinder.org/v2/gh/betatim/openrefineder/master?urlpath=%2Fopenrefine)
* [Interactive textbook](https://eng.libretexts.org/Textbook_Maps/Computer_Science/Map%3A_Python_for_Everybody_(Severance)/4%3A_Functions/4.04%3A_Random_numbers)
* [More textbooks](https://www.inferentialthinking.com/chapters/03/2/Names)
