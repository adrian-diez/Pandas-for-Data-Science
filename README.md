# Pandas-for-Data-Science

This project is an example of how to use Python and its library <b>Pandas</b> to visualize data.

In this case, the data comes from an Excel file, so we will use the library <b>xlrd</b> to extract the data into a Python variable.

Pandas is a library that divides 2D matrices into <em>Series</em>, tables of one column of data, and <em>DataFrames</em>, tables of more than one column.

Some examples of the usage of the Pandas library in this project are:
<ul>
  <li>
    Displaying the categories of data and the top 5 entries with <b>DataFrame.head()</b>.
  </li>
  <li>
    Accessing a column and assign it to a Series using <b>square brackets</b>, or a DataFrame using <b>double</b> square brackets.
  </li>
  <li>
    Creating and displaying a subtable with the necessary columns from the original data frame, including several columns in the process.
  </li>
  <li>
    Accessing specific values using the indices as pointers with <b>DataFrame.iloc[row, column]</b>.
  </li>
  <li>
    Accessing specific values using the names of the first column (generally, the number of entry) for rows and the name of the first row (generally, the title or category of the column) for columns with <b>DataFrame.loc[row, column]</b>.
  </li>
  <li>
    Combining the two prior processes to create a subsection of the table, accessing the index of first and last wanted rows and columns, like this: <b>DataFrame.iloc[row1:row2, column1:column2]</b>, or using DataFrame.loc with the names of the rows and columns, instead of their indices.
  </li>
</ul>
  
# Special thanks

<b>This course was found in <b>Coursera.org</b> as part of the IBM Data Analyst professional certificate.
