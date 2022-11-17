---
output: github_document
---

# An Explanation for This Repository's Name



[I got tired of the peer-review process](https://twitter.com/stevenvmiller/status/1229788167223398400) changing the names of my projects. When this happened, my repository names would no longer make sense. [I started creating nicknames for my projects](https://twitter.com/stevenvmiller/status/1229788168049676294) at the project's onset, using either the Ubuntu Name Generator or the Wu-Tang Name Generator. This led to the creation of an R package---[`{codename}`](https://github.com/svmiller/codename)---that would do this for me. This is what came out for this particular idea of mine.


```r
library(codename)

codename_message()
#> code name generated by {codename} v.0.4.9. R version 4.1.2 (2021-11-01).
variety_pack("Steve writes an EH/IR methods book")
#> Warning in char2seed(seed): probable complete loss of accuracy in modulus
#> [1] "safe test"
#> Warning in char2seed(seed): probable complete loss of accuracy in modulus
#> [1] "flaky sterculius"
#> Warning in char2seed(seed): probable complete loss of accuracy in modulus
#> [1] "lovely loon"
#> Warning in char2seed(seed): probable complete loss of accuracy in modulus
#> [1] "Pesty Criminal"
```

I liked "lovely loon" the best, so "lovely loon" it is.
