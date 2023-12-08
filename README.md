# My Portfolio 
## Power BI Dashboard Sample
![image](https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/f52ddf9c-ff9d-41ee-8c17-ec0b5491c7a6)
![image](https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/13c1d7a4-b6d8-4980-9a7d-b786c8313f6d)

## SQL querying
queries & joins
## Data Visualisation and Analysis (brad business problem)
![image](https://github.com/johnleonard512/johnleonard512.github.io/assets/140750487/591561b1-f79d-4a3d-9d30-08d22c134a39)
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
