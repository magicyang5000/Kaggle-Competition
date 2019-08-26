about titanic competition  
https://www.kaggle.com/c/titanic/overview   
  
20190826　　　　
test data也需要做预处理，但是在做age的中位数填充时，填充原则是：  
1. train 和 test 取各自独立的 中位数填充？  
2. train 和 test 数据合并后，取中位数  
3. train得到的中位数，直接填充至test中？　
