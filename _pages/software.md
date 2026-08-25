---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}

`cbi_partitions`
------

`cbi_partitions` is a Python library implementing Conformalized Bayesian Inference (CBI) for clustering problems based on partition-valued Monte Carlo posterior samples. It provides point estimation of the data clustering, construction of a credible set of partitions with guaranteed posterior coverage using conformal prediction principles, and density-based clustering to explore posterior multimodality. The method is introduced in the paper ["Conformalized Bayesian Inference, with Applications to Random Partition Models"](https://arxiv.org/abs/2511.05746).

To install directly from GitHub:

```
pip install https://github.com/nbariletto/cbi_partitions/archive/main.zip
```

- [GitHub repository](https://github.com/nbariletto/cbi_partitions)
- [Tutorial](https://nbariletto.github.io/cbi_partitions_repo/)
