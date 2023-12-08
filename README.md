# My Portfolio 
## Power BI Dashboard Sample
<img src="https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/f52ddf9c-ff9d-41ee-8c17-ec0b5491c7a6" width="700" height="350">
<img src="https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/13c1d7a4-b6d8-4980-9a7d-b786c8313f6d" width="700" height="350">


## SQL querying
queries & joins
## Data Visualisation, Analysis, and Machine Learning.
This is my workflow, going from the raw data, to a confusion matrix that evaluates the effectiveness of the predictive model.
<img src="https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/8ea42d1c-5df3-4ccb-9433-a16ce97cd704" width="700" height="400">

Raw data recieved from the datasource.
<img src ="https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/189e34f1-1e2d-45ef-8767-3b5a55ebccdb" width="300" height="300">

Correlations from the dataset, showing variables and their R value with other variables.  Sorted from strong to weak correlations. 
<img src ="https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/1922cce3-4b5c-44fc-9efa-b2b6707dfc8d" width="300" height="300">

The decision tree, sorting customers by factors that determine the churn.
![image](https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/8f609363-c2ba-4cf2-b7d1-2f3c92f5e1af)

Confusion Matrix results that evaluate the model, showing false positives/negatives.
![image](https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/d249f7cc-ac71-4d8f-b0ff-fb9fe580d515)

________________________________________________________________________________________________________________________________________________

This scatterplot is from a college research project comparing square footage and the sale price of homes.  
![image](https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/591561b1-f79d-4a3d-9d30-08d22c134a39)

This is my workflow for cleaning data prior to analysis; selecting the relevant data, removing outliers, imputing missing data based on the most appropriate method (average or median)
![image](https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/6dbf6f19-7d9e-475b-844d-a90b90cb2b9a)


## Python (show stats, and a code block)
![image](https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/6a4de389-d41c-4500-9099-5248628009b5)
Code for this graph:
        print('_____________________________________')
        print("Datapoints per Month")
        print('_____________________________________')
        # create boxplot array
        bpdata = []
        
        # loop to populate boxplot array
        for i in range(1,13):
            num_month = denver_data[denver_data['Month'] == i]
            avg = num_month['AvgTemperature']
            bpdata.append(avg)
        
        num = 1
        for array in bpdata:
            print("Month " + str(num) + ": " + str(len(array)))
            num = num + 1
        
        # boxplot creation, using bpdata array
        plt.figure(2)
        outlier_marker = dict(marker='o', markerfacecolor='orange', markersize=6)
        plt.boxplot(bpdata, flierprops=outlier_marker)
        
        plt.title('Denver Temperature Boxplot')
        plt.xlabel('Month')
        plt.ylabel('Temperature (F)')
        
        
        #print boxplot
        plt.show()
        plt.show()


## Machine Learning (time series, grocery store or customer segmentation)
low priority link college capstone
