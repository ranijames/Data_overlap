# Data_overlap

The Data Overlap has been developed to identify common elements between columns of a given dataframe. The columns of the dataframe may contain either string or numerical values. Data Overlap can compute intersections of categorical or string lists (e.g., genes) as well as numerical values. To use the Data Overlap tool, one should input a dataframe where the columns represent the lists to be compared for their intersection. Any number of columns can be included in the input. 

# Installation

Data_overlap can be installed directly using pip:

```pip install Data-overlap ```

# Useage

```
from list_overlap import Overlaps

```
Where ```df``` is a dataframe with columns to compare.
For example:

```
data_n = {'A':[1,2,3],'B': [1,2,3,4],'C':[5,2],'D': [2,8,9],'E': [2,11,5,9]}
df = pd.DataFrame.from_dict(data_n, orient='index').T
df.head()
A	B	C	D	E
0	1.0	1.0	5.0	2.0	2.0
1	2.0	2.0	2.0	8.0	11.0
2	3.0	3.0	NaN	9.0	5.0
3	NaN	4.0	NaN	NaN	9.0

```
### To view the output

```overlaps.get_the_overlaps(df)```

