# Experimental Evaluation of BLE Beacon

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/YouQam/experimental-evaluation-ble-beacon/HEAD)

This repository contains data and code that reproduce published results in the paper:

Qamaz, Y., Schwering, A., Bistron, J. (2022). Experimental evaluation of using BLE beacon for outdoor positioning in GPS-denied environment. 

# Run this code

There are 3 main ways in which you can use this repository:

1. You can open 'Qamaz-etal-2022.md' by clicking it on the file list above. The file shows what code was used to achieve results from the paper.

2. You can click on the 'lunch binder' button above. This will open an interactive session of RStudio in your web browser. You are able to change the code there by selecting the file 'Qamaz-etal-2022.Rmd' and re-generating the analysis with the 'Knit' button. Rememeber any changes will be lost as soon as you close the browser window.

3. You can download the code and data and and try to run it locally. This is likely to fail in the future when software versions change. The analysis does work on the session listed below.



```
> sessionInfo()
R version 4.1.2 (2021-11-01)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 18.04.6 LTS

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/blas/libblas.so.3.7.1
LAPACK: /usr/lib/x86_64-linux-gnu/lapack/liblapack.so.3.7.1

locale:
 [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C               LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8    
 [5] LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8    LC_PAPER=en_US.UTF-8       LC_NAME=C                 
 [9] LC_ADDRESS=C               LC_TELEPHONE=C             LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

loaded via a namespace (and not attached):
 [1] compiler_4.1.2  fastmap_1.1.0   htmltools_0.5.2 tools_4.1.2     yaml_2.2.1      rmarkdown_2.14  knitr_1.37      xfun_0.30      
 [9] digest_0.6.29   rlang_0.4.12    evaluate_0.14   
```


# License
MIT
