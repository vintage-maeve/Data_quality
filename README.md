# Cloud computing environments to support data science teaching in health - data quality assessment

Author: Ioana Dumitrescu

The purpose of this project is to establish the data quality of a given dataset and then to provide suggestions on how to improve it.

In order to start using the notebook, upload the data set using either of the 2 provided methods:
1. `Direct upload` - change the value of the `file_path` variable to the file path of the desired data set
1. `Use the upload widget` - select the file that you want to upload and then run the cell named `Validating data upload`, which extracts the content of the uploaded data set.

You can also visualize a preview of the data set as a confirmation that you have indeed uploaded the correct file. 

The following techniques are used for **assessing the quality of the data set**:
1. General data set metadata - shows some descriptive and structural metadata that offer users some general insights about the content of the data and its structure.

1. Values distribution for a specific column - select a column and visualize the distribution of its values

![ezgif com-gif-maker](https://user-images.githubusercontent.com/32450978/115015418-82716d80-9eab-11eb-8c46-9a11b4e55d1c.gif)

1. `Unique values for a specific column` - select a column and visualize a table of all the unique values in that column sorted descendingly according to their frequency

![ezgif com-gif-maker(1)](https://user-images.githubusercontent.com/32450978/115016070-805bde80-9eac-11eb-820e-2ad3851c1346.gif)

1. `Assessing the plausibility of the data set - column similarity` - visualizing a heatmap that informs the user about the relations between columns

![ezgif com-gif-maker(2)](https://user-images.githubusercontent.com/32450978/115016793-7a1a3200-9ead-11eb-8d65-0fc3b0cd9eb7.gif)

1. `Missing values analysis - customized missing values` - you can add different values for the missing items (for example, if in your data set -9 represents a missing value, you can add it in the text box and then click 'submit'); multiple values can be added but they must be separated by **commas** (e.g -9,NULL,hello i am a missing value)
![ezgif com-gif-maker(3)](https://user-images.githubusercontent.com/32450978/115017345-51466c80-9eae-11eb-8fa1-d4900df0b299.gif)

1. `Identify the missing values` - shows the number of missing values (NA, NULL, empty strings), together with the number of customized missing values
1. `Similarity between missing values indexes` and `Similarity heatmap for missing values indexes` - a correlation matrix and a heatmap which show the similarity between all columns with missing values (useful for visualizing what is the probability that if values are missing from column A, they will also be missing in column B)
![ezgif com-gif-maker(4)](https://user-images.githubusercontent.com/32450978/115018095-58ba4580-9eaf-11eb-8076-65cd76c8d89d.gif)


`Cleaning the data set` is in charge of performing the transformation functions for **improving the quality of the data set**:
![ezgif com-gif-maker(5)](https://user-images.githubusercontent.com/32450978/115018902-59071080-9eb0-11eb-8acd-4f19e9932ef8.gif)
