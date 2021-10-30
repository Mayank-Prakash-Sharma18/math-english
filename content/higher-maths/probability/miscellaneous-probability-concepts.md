---
title: Miscellaneous Probability Concepts
linktitle: Misc. Probability Concepts

toc: true
type: docs
date: "2021-10-25T00:00:00+01:00"
draft: false
menu:
  probability:
    parent: Probability
    weight: 30

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 30
---

##### Q. There are 5 letters and 5 directed envelopes. What is the probability that exactly one letter is placed in the wrong envelope?
(a) 0 <br>
(b) 1 <br>
(c) 0.2 <br>
(d) Cannot be determined

Explanation:<br>
<div class="Exp">

There is zero probability of this scenario as if one letter is placed in wrong envelope then it is obvious that one other letter would also be in wrong envelope.

To make it more clear, let’s say there are 5 envelopes A, B, C, D and E and five letters corresponding to these envelopes.

One letter, say belonging to A, is wrongly placed in the envelope B.

Now, there is no way for the letter belonging to B to be placed in the correct envelope (as the envelope belonging to B has already been used by A).

Therefore, exactly one letter can never be placed in the wrong envelope.

Answer: (a)
</div> <br>

##### Q. If there are 4 envelopes and 4 letters, then what is the probability that there is atleast one letter which is not in its right envelope?
<pre>(a) 1/24   (b) 4/10    (c) 23/24   (d) 6/10</pre>

Explanation:<br>
<div class="Exp">

Number of ways of putting all letters in their right envelopes = 1 <br>
Total number of ways of putting 4 letters in 4 envelopes = 4!

∴ Required probability that all letters are not in their correct envelopes = (4! - 1)/4! = 23/24

Answer: (c)
</div> <br>

