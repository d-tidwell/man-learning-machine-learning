# Lambda Data Darek Package

This is a simple data science helper package.
to install pip install -i https://test.pypi.org/simple/ lambdadata-darek==0.0.1
In python enviroment then from lambdadata import lambdadata_py

## Contains:

# DF CLEANING AND INFO

nullcheck(df)\
'''checks for nulls in a dataframe'''

whitespace(df)\
'''removes whitespace from dataframe'''

remove_percent(df)\
'''duh'''

# Statistics
 
find_outliers(list)\
'''it doesn't grant wishes'''
  
  
proba_givenb(probb_givena, proba, probb_givennota)\
  
  '''#Single Bayes Theorem Test A given B'''
 

one_samp_pval(conts):
  '''1sample PVALUE from list of continuous value columns
    from a list called conts'''

two_samp_pval:
  '''2 TWO SAMPLE test against means of subgroups within a population: beware: means
  comparison is valued differently then taking the mean against a 1samp
  left df in stats test will be the primary, takes list named conts'''
  
zscore(raw_score):
'''calculates z score'''

create_t_test_set(null_df, reject_df):
'''1 sample t test''

confidence_interval(data, confidence=.95):
'''Calculates Confidence Interval'''

support_ttest(feature, level):
  
  '''# Function takes a feature from the dataframe and a significance level and 
   returns a tuple with a boolean value (True if the pvalue < significance level) 
   and the pvalue.'''

print_ttests(index):  
  ''' Function takes a column value for the index, prints pvalues and whether or not
  null hypothesis should be rejected for all other features in the dataframe.'''
        
# PCA

get_pca(df,n):  
'''Gets the n number of principle components from a dataframe'''

get_redundant_pairs(df):
      '''Get diagonal and lower triangular pairs of correlation matrix'''

 def get_top_abs_correlations(df, n=5):
 '''gets n number of top absolute correlated pairs'''

