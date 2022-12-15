# Surf’s Up Analysis	

This analysis was made to convince W.Avy and the rest to invest in Surf and Shake shop, a store that will cell surfboards and ice cream to locals and tourists. W.Avy wanted to go deeper into this analysis and the lack of research into weather caused him to lose his investment after closing the store.

W.Avy found the SQL database of the closest weather stations.
After we received the SQL database, we used Jupyter Notebook to retrieve the data, filter the data to create Data Frames and then save it with store it with SQLite that allowed us to show the info adding it to a local website with Flask.
Data was delivered in two parts :
•	Rain W.Avy was concerned about the amount of rain each day that last year brough to the city. Because that can directly affect sales in ice cream and surfing goods,a graph was created with such info .


![p](https://user-images.githubusercontent.com/114957364/207779889-2c1289c6-de05-48d1-965b-2de995beb502.png)

•	Temperature: Another important factor cause can affect directly the ice cream sales, also they can be prepared in a way that they don”t buys more than they should, causing waste of money and to be prepared for the high seasons . 



![g](https://user-images.githubusercontent.com/114957364/207779948-b295ae5e-6c2c-4c0c-8293-25d58502b11c.png)

## Results: 
1.	They may have higher sales in June due higher temp with an AVG of 75F and a max of 85F but also, they can expect more rain, summer vacations can bring more tourists increasing sales.

2.	December can be a better month for the store due a more constant temp and less rain during the hole month, they can expect AVG temps from 71 with a max 75.

3.	A deeper analysis of December may be needed because regardless that have 1 more day 
we’re missing 183,000.000 readings, may be caused by closed stations or weather emergencies. 


you can access to all of this info oppening the app.py with the command prompt

![Screenshot (94)](https://user-images.githubusercontent.com/114957364/207780888-2f231b3b-572e-4581-b1eb-c73c081155e2.png)
