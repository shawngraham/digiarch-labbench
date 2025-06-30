# Historical Cemetery Network Dataset

I'll give you some information I cooked up regarding a small family cemetery. Your goal is to create a new python or R notebook where you load the data in and do some analyzes.

1. take this data, and make a new text file in the workbench. Represent the data provided to you below as an 'edgelist' where you list out the relationships. You need to have at least a 'source' and 'target' column, eg:
```
source,target
alice,bob
```
You might want to have more columns. When you save the txt file, CHANGE THE FILE EXTENSION to end with .csv, eg: `graveyard_net.csv`. 

Then,

2. make a new python or R notebook
3. load the data in
4. visualize the data
5. determine one or two metrics for the data.

**Hint**
In python, you can load the data with pandas: ```edges_df = pd.read_csv('edges.csv')```

In R, you can load it in with igraph: ```links <- read.csv("edges.csv", header=T, as.is=T)```


### Thompson Family
| Person | Birth Year | Death Year | Notes |
|--------|------------|------------|-------|
| John Thompson | 1820 | 1889 | Patriarch, miller |
| Mary Thompson | 1823 | 1891 | Wife of John |
| Sarah Thompson | 1847 | 1923 | Eldest daughter |
| Robert Thompson | 1849 | 1901 | Son, took over mill |
| James Thompson | 1851 | 1934 | Youngest son |
| Alice Thompson | 1872 | 1945 | Robert's wife |

### Hayes Family
| Person | Birth Year | Death Year | Notes |
|--------|------------|------------|-------|
| William Hayes | 1825 | 1895 | Blacksmith, business partner to John |
| Elizabeth Hayes | 1828 | 1901 | Wife of William |
| Thomas Hayes | 1850 | 1918 | Son, continued blacksmithing |
| Margaret Hayes | 1852 | 1925 | Daughter, schoolteacher |
| Catherine Hayes | 1875 | 1942 | Thomas's wife |
| David Hayes | 1877 | 1950 | Thomas's son |

### Miller Family
| Person | Birth Year | Death Year | Notes |
|--------|------------|------------|-------|
| Samuel Miller | 1815 | 1882 | Town doctor |
| Ruth Miller | 1818 | 1885 | Wife of Samuel |
| Benjamin Miller | 1845 | 1920 | Son, also doctor |
| Hannah Miller | 1848 | 1929 | Daughter, midwife |
| Edward Miller | 1870 | 1935 | Benjamin's son |
| Grace Miller | 1873 | 1940 | Benjamin's wife |

### Clark Family
| Person | Birth Year | Death Year | Notes |
|--------|------------|------------|-------|
| Charles Clark | 1830 | 1905 | Store owner |
| Emma Clark | 1833 | 1908 | Wife of Charles |
| Frank Clark | 1855 | 1930 | Son, inherited store |
| Lucy Clark | 1857 | 1932 | Daughter |
| Henry Clark | 1880 | 1955 | Frank's son |
| Rose Clark | 1882 | 1960 | Frank's wife |

### Wilson Family
| Person | Birth Year | Death Year | Notes |
|--------|------------|------------|-------|
| George Wilson | 1822 | 1890 | Farmer |
| Martha Wilson | 1825 | 1893 | Wife of George |
| Joseph Wilson | 1848 | 1915 | Son, farmer |
| Mary Wilson | 1850 | 1928 | Daughter |
| Peter Wilson | 1875 | 1940 | Joseph's son |
| Anna Wilson | 1878 | 1945 | Joseph's wife |
