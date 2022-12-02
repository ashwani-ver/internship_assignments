# internship_assignments
#Assignment -1 
  In the house prediction data, the reduntant columns is removed for final training.
  Data cleaning like outlier removal performed on need basis.
  Some graphs is pllotted for better visualization of the data.
  Scaling the data is required to bring the integers on the same scale.
  Three models are used for training the data namely Linear , lasso and Randomforest regressor.
  Randomforest regressor outperformed other models so that we can use it
  
  
  
  
  
  
  
  
  
  
  
#Assignment - 2 .Matching the similar product.
  Two datasets are given from flipkart and amazon products.
  We are given different information about the products.
  We have to use ML algorithms to match the product from two datasets.
  So first , converting all strings of flipkart to lower case to avoid upper case and lower case error in alphabets and same thing for amazon data.
  Using np.where function to match the product names and assigning matched columns to '1' amd ummatched columns to  '0'.
  19851 rows of products completely matched the product names.So, these data are filtered out first. Then, some of the data were different because they had different words. 
  So we can use 'IN' function to find the substrings between two columns. in that 96 rows again matched. These data were filtered from the dataframe and later used concat function to add all the data.
 Thanking you.
  
