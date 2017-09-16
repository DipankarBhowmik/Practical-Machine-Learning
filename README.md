# Practical-Machine-Learning
## Summary
By means of devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to assemble a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants.

Six young health participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: exactly according to the specification (Class A), throwing the elbows to the front (Class B), lifting the dumbbell only halfway (Class C), lowering the dumbbell only halfway (Class D) and throwing the hips to the front (Class E).

The training dataset was separated into two parts: tranining part (70%), testing part (20%)i.e. for the validations.

The training model developed using Random Forest was able to achieve over 99.73% accuracy, or less than 0.03% out-of-sample error, and was able to predict the 20 test cases with 100% accuracy.

The training data for this project are available [here](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv).

The test data are available [here](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv).

## Steps are as follows:-
1. Processing & Cleaning of data.
  a. Environment Preparation.
  b. Download & Reading of the Dataset.
  c. Create a partition with the training dataset
  d. Remove variables with Nearly Zero Variance.
  e. Remove variables that are mostly NA.
  f. Remove identification only variables.
2. Model Prediction
  -Decision Trees
      *model-fit
      *prediction - Test dataset
  -Boosted Model
      *model-fit
      *prediction - Test dataset
  -Random Forest
      *model-fit
      *prediction - Test dataset
  3. Testing Model
  4. Conclusion
  5. Reproducible-
  
      Session Information
        R version 3.4.0 (2017-04-21)
        Platform: x86_64-w64-mingw32/x64 (64-bit)
        Running under: Windows 7 x64 (build 7601) Service Pack 1
 
         Matrix products: default
 
         Locale:
         LC_COLLATE=English_India.1252  LC_CTYPE=English_India.1252   
         LC_MONETARY=English_India.1252 LC_NUMERIC=C                  
         LC_TIME=English_India.1252    
 
         Attached base packages:
         parallel  splines   stats     graphics  grDevices utils     datasets 
         methods   base     
 
         Other attached packages:
          plyr_1.8.4          gbm_2.1.3           survival_2.41-3    
          corrplot_0.77       randomForest_4.6-12 rattle_5.1.0       
          rpart.plot_2.1.2    rpart_4.1-11        caret_6.0-77       
         ggplot2_2.2.1       lattice_0.20-35     knitr_1.17         
 
         Loaded via a namespace (and not attached):
          reshape2_1.4.2     kernlab_0.9-25     purrr_0.2.3       
          colorspace_1.3-2   htmltools_0.3.6    stats4_3.4.0      
          prodlim_1.6.1      rlang_0.1.1        ModelMetrics_1.1.0
         glue_1.1.1         withr_2.0.0        bindrcpp_0.2      
         foreach_1.4.3      bindr_0.1          dimRed_0.1.0      
         lava_1.5           robustbase_0.92-7  stringr_1.2.0     
         timeDate_3012.100  munsell_0.4.3      gtable_0.2.0      
         recipes_0.1.0      codetools_0.2-15   evaluate_0.10.1   
         class_7.3-14       DEoptimR_1.0-8     Rcpp_0.12.11      
         scales_0.4.1       backports_1.1.0    ipred_0.9-6       
         CVST_0.2-1         digest_0.6.12      stringi_1.1.5     
         dplyr_0.7.2        RcppRoll_0.2.2     ddalpha_1.2.1     
         grid_3.4.0         rprojroot_1.2      RGtk2_2.20.33     
         tools_3.4.0        magrittr_1.5       lazyeval_0.2.0    
         tibble_1.3.3       DRR_0.0.2          pkgconfig_2.0.1   
         MASS_7.3-47        Matrix_1.2-9       lubridate_1.6.0   
         gower_0.1.2        assertthat_0.2.0   rmarkdown_1.6     
         iterators_1.0.8    R6_2.2.2           nnet_7.3-12       
         nlme_3.1-131       compiler_3.4.0
 
     
