
# BendersDOMP repository

## Benders Decomposition for the Discrete Ordered Median Problem

The following Github repository contains the data instances tested in the computational study section and the full version of the results in table format. 

### Models description

Model description in the results dataset.

- **0**: $DOMP_{r0}$
- **1**: $DOMP_{\theta}$
- **2**: $DOMP_{\theta1}$
- **3**: $DOMP_{\theta1a}$

### Result dataset description

Columns description in the results dataset.

**Files**: `Beasley_results.csv`, `Random_results.csv`

- `lamb`: represents the $\lambda$-vector tested
- `ins` (*only for* `Beasley`): represent the number of the instance tested
- `N`: instance size
- `p`: number of facilities to locate
- `cpu_0`: cpu time values for $DOMP_{r0}$
- `gap_0`: gap left at termination values for $DOMP_{r0}$
- `cpu_1`: cpu time values for $DOMP_{\theta}$
- `gap_1`: gap left at termination values for $DOMP_{\theta}$
- `cpu_2`: cpu time values for $DOMP_{\theta1}$
- `gap_2`: gap left at termination values for $DOMP_{\theta1}$
- `clazy_2`: number of integer or lazy cuts added in the model $DOMP_{\theta1}$ 
- `cuser_2`: number of fractional or user cuts added in the model $DOMP_{\theta1}$ 
- `cpu_3`: cpu time values for $DOMP_{\theta1a}$
- `gap_3`: gap left at termination values for $DOMP_{\theta1a}$
- `clazy_3`: number of integer or lazy cuts added in the model $DOMP_{\theta1a}$ 
- `cuser_3`: number of fractional or user cuts added in the model $DOMP_{\theta1a}$ 

