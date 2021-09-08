## Indu Chinthakuntla\

I am fast learner and good at enjoying with friends. and today I am in maryville for higher stuides. They are not ready to send for masters as I am only child to them. But i have some goals to make my self happy and to feel my parents proud.

![MyPicture](C:\Users\s545151\Documents\GitHub\assignment2-Chinthakuntla\Picture)

***
## Recommendation for food

The table below describes the food and food availability location and the cost of food.
|Food/Drinks|Location|Cost|
|---|---|---|
|Chicken Biryani|Hyd Paradise|350|
|Fish Biryani|Hyd swagath|650|
|Ice-Cream|Hyd Mascati|150|
|KFC|Kukatpally|600|
|Oreo Milkshake|MOM's Hyd|200|

***
## Quote

>“Anyone can find the dirt in someone. Be the one that finds the gold.”
                                                ― *Gaur Gopal Das

>“Live your life in such a way that those who know you but don’t know God, will come to know God because they know you.”
                                                ― *Gaur Gopal Das

***
## Data Structure Algorithm
>For this type of queries, we want to find the sum of all values in a range. Therefore the natural definition of the function f is f(x,y)=x+y.
geeksforgeeks<https://www.geeksforgeeks.org/range-sum-queries-without-updates/>

```
long long st[MAXN][K + 1];

for (int i = 0; i < N; i++)
    st[i][0] = array[i];

for (int j = 1; j <= K; j++)
    for (int i = 0; i + (1 << j) <= N; i++)
        st[i][j] = st[i][j-1] + st[i + (1 << (j - 1))][j - 1];
```

code:<https://cp-algorithms.com/data_structures/sparse-table.html>