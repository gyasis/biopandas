---
name: Bug report
about: Report and reproduce a bug
title: ''
labels: 'Bug'
assignees: ''

---

<!-- 
If this is your first Issue submitted to the BioPandas Issue Tracker, please review
the code of conduct, which is available at http://rasbt.github.io/biopandas/Code-of-Conduct/. 
-->


<!--
Before submitting a bug, please check the recent Changelog entries at 
https://github.com/rasbt/biopandas/blob/master/docs/sources/CHANGELOG.md
and do a quick search in the Issue Tracker (https://github.com/rasbt/biopandas/issues)
to make sure the issue hasn't been already
addressed.
-->

#### Describe the bug

<!--
Briefly describe what the bug is.
-->

#### Steps/Code to Reproduce

<!--


<!--
Please add a minimal example that can help understand and reproduce the bug.
Ideally, this should be a self-contained code example that can be run
on our computer with easily accessible datasets (ideally, datasets contained
in scikit-learn or BioPandas itself).


Example:

```python
import numpy as np
from biopandas.evaluate import bootstrap


rng = np.random.RandomState(123)
x = rng.normal(loc=5., size=100)
original, std_err, ci_bounds = bootstrap(x, num_rounds=1000, func=np.mean, ci=0.95, seed=123)
print('Mean: %.2f, SE: +/- %.2f, CI95: [%.2f, %.2f]' % (original, 
                                                        std_err, 
                                                        ci_bounds[0],
                                                        ci_bounds[1]))
```

If the code is too long, feel free to put it in a public gist and link
it in the issue: https://gist.github.com
-->

```python
Insert your example code here.
```

#### Expected Results

<!-- Please paste or describe the expected results.-->

#### Actual Results
<!-- Please paste or specifically describe the actual output or error traceback. -->

#### Versions

<!--
Please run the following snippet and paste the output below.
import biopandas; print("biopandas", biopandas.__version__)
import platform; print(platform.platform())
import sys; print("Python", sys.version)
import sklearn; print("Scikit-learn", sklearn.__version__)
import numpy; print("NumPy", numpy.__version__)
import scipy; print("SciPy", scipy.__version__)
-->


<!-- Thanks for contributing! -->