# machineLearningMushroomsDataset
Mushroom Dataset and train Machine Learning Algorithms on it  

# Aim  
How can we decide that when we see a mushroom is edible or what? My
aim is to predict a mushroom is edible or poisonous. To do that I will use
mushroom dataset which I downloaded here: https://www.mldata.io/datasetdetails/mushroom/#customize_download. Since this is a 2 class problem and all
mushrooms in dataset already labeled as a poisonous and edible, I decided to use
classification.

Mushrooms Dataset and Features Descriptions:  
• Cap: the expanded, upper part of the mushroom; whose surface is the pileus
(dataset involves its shape, color etc.)  

• Cup (Volva): a cup-shaped structure at the base of the mushroom. The basal
cup is the remnant of the button (the rounded, undeveloped mushroom
before the fruiting body appears). Not all mushrooms have a cup.  

• Gills: a series of radially arranged (from the center) flat surfaces located on
the underside of the cap. Spores are made in the gills. (dataset involves its
shape, size etc.)  

• Ring: a skirt-like ring of tissue circling the stem of mature mushrooms. The
ring is the remnant of the veil (the veil is the tissue that connects the stem
and the cap before the gills are exposed and the fruiting body develops). Not
all mushrooms have a ring. (dataset involves its number and its type)  

• Scale: rough patches of tissue on the surface of the cap (scales are remnants
of the veil).  

• Stalk: the main support of the mushroom; it is topped by the cap. Not all
mushrooms have a stalk (dataset involves its shape, root, color, surface
above ring etc.)  

• Dataset also involves mushrooms habitat and population.    

I read the dataset with pandas library. Then I print it to observe. It has 8124
entries. And it wasn’t numpy array. All of the values have written in char
characters. So, I had to label encoding. Before that I observe that mushrooms have
22 features and its label which is “type” column. Type is stands for the mushroom 
is edible or poisonous. Before the label encoding, poisonous represents as “p” and
edible represented as “e”. And before label encoding, I switch all of the NaN
values with most common values.

