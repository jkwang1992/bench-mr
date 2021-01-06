---
layout: default
title:  "Frontend"
date:   2021-01-04 13:20:59 +0100
has_children: true
nav_order: 2
---

# Python Frontend

The MPB instance is created via the following constructor:

```py
mpb = MPB(config_file = os.path.join(MPB_BINARY_DIR, 'benchmark_template.json'),
          output_path = '')
```

| Argument        | Description        |
|:----------------|:-------------------|
| config_file           | Path name of the configuration JSON file this experiment is based on |
| output_path           | Path where the resulting log files are stored from this experiment   |

