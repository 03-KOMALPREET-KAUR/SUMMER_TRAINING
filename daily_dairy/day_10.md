**DAY 10(04/07/2025)**

Today, we explored the Pandas and Matplotlib library in detail.

1) **Pandas**: Pandas is an open-source Python library used for data manipulation and data analysis.

   i. **Pandas DataFrame:** A DataFrame in Pandas is a 2D labeled data structure. It has rows and columns with labels, which makes data handling easy.

   ii. **Creating a Pandas DataFrame:** We loaded a Boston House price dataset using the syntax - from sklearn.datasets import load_boston and stored it in boston_df variable. Then we created the dataframe using syntax - boston_df = pd.DataFrame(boston_dataset.data, columns = boston_dataset.feature_names).

   iii. **File access using Pandas:** To load data from a excel file to a Pandas DataFrame, we use pd.read_excel('file_path') and similarly to read a csv file, we use pd.read_csv('file_path').

   iv. **Exporting the Pandas DataFrame to a file:** For exporting the pandas dataframe to excel file, we use df.to_excel('filename') and for csv file, we use df.to_csv('file_name').

   v. **Creating a DataFrame with random values**: We use pd.DataFrame(np.random.rand(20,10)) to create a dataframe with 20 rows and 10 columns filled with random float values between 0.0 and 1.0.

   vi. **Inspecting the DataFrame:**

    **.head()** gives the first 5 rows of DataFrame.

    **.tail()** gives the last 5 rows of DataFrame.
   
    **.info()** gives a concise summary of the DataFrame including number of rows and columns, data types of the values, missing values, memory usage etc.
   
    **.shape** give the dimensions (rows, columns).
   
    **.isnull().sum()** is used to check for missing values.

   vii. **Statistical Measures:**

    **.mean()** – Returns the average value of each column.
   
   
    **.std()** – Returns the standard deviation of values in each column.


    **.min()** – Returns the minimum value in each column.


    **.max()** – Returns the maximum value in each column.


    **.count()** – Returns the number of non-null entries in each column.


    **.describe()** – Returns a summary of descriptive statistics (count, mean, std, min, 25%, 50%, 75%, max) for the columns. 

 viii. **Manipulating DataFrames**: We learnt how to add a new column, drop a column, drop a row, access specific rows by index using .loc[index] and access specific columns using .iloc[:,index].

 ix. **Correlation**: We used .corr() to find relationships between columns. There are two types of correlation- **Positive Correlation:** Two variables increase together and **Negative Correlation:** One increases while the other decreases.

 x. Some important functions of Pandas:- 

    a) It provides a fast and efficient way to manage and explore data which makes it suitable for data science.

    b) Missing data is easily and efficiently handled.

    c) Columns can be easily inserted, modified and deleted from DataFrame.

    d) It provides support for cleaning of data needed for processing.

    e) It provides support for reshaping, merging and joining various datasets.

2) **Matplotlib:** Matplotlib is a powerful data visualization library in Python used to create a wide range of plots.
   
   i. a) **plt.plot()** is used to plot a	Line graph.
   
      b) **plt.bar()** is used to plot a	Bar chart.
   
      c) **plt.hist()** is used to plot a Histogram.
   
      d) **plt.scatter()** is used to plot a Scatter plot.
   
      e) **plt.pie()** is used to plot a Pie chart.
   
   ii. **Customizing Plots**
   
      a) **Title**: plt.title("Title")

      b) **Labels**: plt.xlabel("x"), plt.ylabel("y")
   
      c) **Colors and markers**: plt.plot(x, y, color='red', marker='o')
   



   
