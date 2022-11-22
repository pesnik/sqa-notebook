+++
title = "Cucumber Documentation Summary"
author = ["R_Hasan"]
description = "Cucumber Documentation Summary"
date = 2022-11-21T14:21:00+06:00
draft = false
+++

## Anti Pattern {#anti-pattern}

There are several anti-patterns, we should avoid them. The described patterns are

1.  Feature-coupled step definations
2.  Conjunction steps


### Feature-coupled step definations {#feature-coupled-step-definations}

...those steps that can't be reused across feature or scenarios.


#### How to decouple steps &amp; step definations {#how-to-decouple-steps-and-step-definations}

-   organize steps by domain concept
-   use domain-related names for steps and step definations


### Conjunction steps {#conjunction-steps}

...those steps which combines a bunch of different things. Cucumber has \`And\`, \`But\` for a reason. For composition and reuse we can create related helper methods as another step can't be called from inside a step in step definations file.

> You want to strive to keep your steps atomic as much as possible.


### Thoughts on cucumber anti-pattern blog {#thoughts-on-cucumber-anti-pattern-blog}

...read the blog yourself [here](http://www.thinkcode.se/blog/2016/06/22/cucumber-antipatternsi)
