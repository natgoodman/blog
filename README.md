Nat's Website
================
Nathan (Nat) Goodman
December 5, 2018

<!-- README.md is generated from README.Rmd. Please edit that file -->
Welcome to my incipient website! It's just a landing page with links to recent working papers and blog posts. Clicking on a title takes you to the latest released version of the article on GitHub Pages. For articles published on blogs elsewhere, there's also a link to the posting.

About Me
--------

I am a retired computer scientist. I spent the first half of my career doing mainstream CS and the second half in bioinformatics. I split my years pretty evenly between academia and industry. My academic positions included faculty spots at Harvard and Boston University, and research scientist positions at the Whitehead Institute Genome Center (led by Eric Lander), the Jackson Laboratory, and the Institute for Systems Biology (in Lee Hood's lab). In industry, I mostly worked in startups and other small companies with positions running the gamut from programmer to president. As a retiree, I'm working on an eclectic mix of projects that interest me, stopping from time-to-time to write papers and posts on aspects that might interest others. I'm also doing a little consulting for select clients developing innovative, important products.

Working Papers and Blog Posts
-----------------------------

-   [Measuring Replication Success](https://natgoodman.github.io/repwr/mesr.stable.html) <br/> by Nat, December 5, 2018<br/> *Statisticians have devised numerous statistical tests for deciding whether a replication passes or fails, thus validating of refuting the original result. I call these tests "measures". Elsewhere I report results from simulating these tests across a range of conditions. Here I describe the measures themselves and provide implementation details for ones that aren't obvious.*

-   [Noncentral d2t-Distribution Applied to Measures of Replication Success](https://natgoodman.github.io/repwr/stats.stable.html) <br/> by Nat, December 3, 2018<br/> *Statisticians have devised numerous statistical tests for deciding whether a replication passes or fails, thus validating of refuting the original result. The noncentral t-distribution underlies many of these tests. I developed software that repackages R's built-in functions for the noncentral t-distribution to operate on sample size (instead of degrees of freedom), population effect size (instead of the noncentrality parameter), and observed effect size (instead of the t-statistic). I call this the d2t-distribution.*

-   [Systematic Replication May Make Many Mistakes](https://natgoodman.github.io/repwr/resig.stable.html). Short version of [Systematic Replication Has Limited Power to Detect Bad Science](https://natgoodman.github.io/repwr/repwr.stable.html) below <br/> by Nat, September 23, 2018<br/> kindly posted by Bob Reed on [The Replication Network](https://replicationnetwork.com/2018/09/28/goodman-systematic-replication-may-make-many-mistakes/)<br/> *Replication seems a sensible way to assess whether a scientific result is right. The intuition is clear: if a result is right, you should get a significant result when repeating the work; if it it's wrong, the result should be non-significant. I test this intuition across a range of conditions using simulation. For exact replications, the intuition is dead on, but when replicas diverge from the original studies, error rates increase rapidly. Even for the exact case, false negative rates are high for small effects unless the samples are large. These results bode ill for large, systematic replication efforts, which typically prioritize uniformity over fidelity and limit sample sizes to run lots of studies at reasonable cost.*

-   [Supplementary Material](https://natgoodman.github.io/repwr/resigsupp.stable.html) for [Systematic Replication May Make Many Mistakes](https://natgoodman.github.io/repwr/resig.stable.html) above <br/> by Nat, November 7, 2018<br/> *Contains results that didn't fit in the blog post as published for reasons of space or pedagogy. It's not terribly coherent as a standalone document. Sorry.*

-   <a name="repwr"></a>[Systematic Replication Has Limited Power to Detect Bad Science](https://natgoodman.github.io/repwr/repwr.stable.html)<br/> by Nat, August 28, 2018<br/> *Replication seems a sensible way to assess whether a scientific result is right. The intuition is clear: if a result is right, you should get a similar answer when repeating the work; if it it's wrong, your answer should be quite different. Statisticians have devised numerous statistical tests for deciding whether a replication passes or fails thus validating of refuting the original result. I simulate many of these tests across a range of conditions. For exact replications, simple significance testing works fine as a validation test, but when replicas diverge from the original studies no test works well. Much of the replication literature focuses, perhaps unwittingly, on methods for testing whether the studies are similar; these tests work quite poorly under all conditions analyzed here. Many caveats apply, but if correct, my results bode ill for large, systematic replication efforts, which typically prioritize uniformity over fidelity to run lots of studies at reasonable cost.*

    -   version 1.00 [html](https://natgoodman.github.io/repwr/doc.nnn/repwr.1.00.html), [pdf](https://natgoodman.github.io/repwr/doc.nnn/repwr.1.00.pdf)
        <p/>
-   [Science-Wise False Discovery Rate Does Not Explain the Prevalence of Bad Science](https://natgoodman.github.io/swfdr/swfdr.stable.html)<br/> by Nat, October 16, 2017<br/> kindly posted by Daniel Lakens on [The 20% Statistician](http://daniellakens.blogspot.com/2017/10/science-wise-false-discovery-rate-does.html)<br/> *This article explores the statistical concept of science-wise false discovery rate (SWFDR). Some authors use SWFDR and its complement, positive predictive value, to argue that most (or, at least, many) published scientific results must be wrong unless most hypotheses are a priori true. I disagree. While SWFDR is valid statistically, the real cause of bad science is "Publish or Perish".*

Comments Please!
----------------

Please post comments using the [GitHub Issue Tracker](https://github.com/natgoodman/blog/issues).
