# Machine Learning on Mushrooms Dataset
Mushroom Dataset and train Machine Learning Algorithms on it  

# Aim  
How can we decide that when we see a mushroom is edible or what? My
aim is to predict a mushroom is edible or poisonous. To do that I will use
mushroom dataset which I downloaded here: https://www.mldata.io/datasetdetails/mushroom/#customize_download. Since this is a 2 class problem and all
mushrooms in dataset already labeled as a poisonous and edible, I decided to use
classification.

I read the dataset with pandas library. Then I print it to observe. It has 8124
entries. And it wasn’t numpy array. All of the values have written in char
characters. So, I had to label encoding. Before that I observe that mushrooms have
22 features and its label which is “type” column. Type is stands for the mushroom 
is edible or poisonous. Before the label encoding, poisonous represents as “p” and
edible represented as “e”. And before label encoding, I switch all of the NaN
values with most common values.

# Results:  
![alt text](https://github.com/mamiaydin/machineLearningMushroomsDataset/blob/master/final_table.png?raw=true)

