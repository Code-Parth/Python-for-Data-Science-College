# Python-for-Data-Science-College

<p><a href="https://colab.research.google.com/github/Code-Parth/Python-for-Data-Science-GTU/blob/master/Python_for_Data_Science.ipynb" target="_parent"><img alt="Open In Colab" src="https://colab.research.google.com/assets/colab-badge.svg"/></a></p>

https://code-parth.github.io/Python-for-Data-Science-GTU/

# **Practical 01**

**Programs to understand the control structures of python.**
1. Python program to print &quot;Hello Python&quot;
2. Python program to find the area of a triangle
3. Python Program to Check Leap Year
4. Python Program to Find the Sum of Natural Numbers
5. Python Program to Print all Prime Numbers between an Interval

-----

# **Practical 02**

**Develop Programs to learn different data-types (string “ ”, set { }, list [ ],
dictionary { : }, tuple ( )) in python.**

1. Python Program to Remove Punctuation from a String
2. Python Program to Illustrate Different Set Operations – Union, Intersection, Difference, Symmetric Difference
3. Python Program to demonstrate list slicing
4. Python Program to compare two lists
5. Python Program to Check If a List is Empty
6. Python Program Concatenate Two Lists
7. Python Program to Merge Two Dictionaries
8. Python Program to Iterate Over Dictionaries Using for Loop
9. Python Program to Sort a Dictionary by Value
10. Python Program to Find the size of a Tuple
11. Python Program to find Sum of Tuple’s elements (numbers)
12. Python Program to Count the Number of Each Vowel

-----

#  **Practical 03**

**Develop Programs to learn concept of functions scoping, recursion and list mutability**

1. Python Program to demonstrate use of local, nonlocal &amp; global variable
2. Python Program to Make a Simple Calculator
3. Python Program to Find Factorial of Number Using Recursion
4. Python Program to Display Fibonacci Sequence Using Recursion

-----

# **Practical 04**

**Develop Programs to understand working of exception handling and assertions.**

1. Program Program to depict else clause with try-expect
2. Python Program to demonstrate finally
3. Python Program to depict Raising Exception
4. Python Program using assertions

-----

# **Practical 05**

**Develop programs to demonstrate use of NumPy**

Refer : https://numpy.org/doc/stable/user/quickstart.html

1. Print Numpy version and configuration information.
2. Create a numpy array with numbers ranging from 50 to 100.Also print attributes of created object.
3. Create a null vector of size 10.
4. Create a vector of size 10 initialized with random integers with a seed equal to last four digits of your enrolment number.
5. Create a matrix of size 5x5 initialized with random integers with a seed equal to last four digits of your enrolment number.
6. Create an identity matrix of size 5x5.
7. Do the following
    * Create a numpy array mat1 of size 5x2 with numbers ranging from 1 to 10.
    * Create another numpy array mat2 of size 2x5 with floating point numbers between 10 to 20.
    * Calculate the matrix product of mat1 and mat2.
    * Print vector containing minimum and maximum in each row of mat1.
    * Print vector containing mean and standard deviation in each column of mat2.
    * Perform vstack and hstack on mat1 and mat2.
    * Split mat1 horizontal into 2 and split mat2 vertical into 2 parts.
8. Create a vector vec of size 20 initialized with double numbers ranging from 20 to 40 and do the following.
    * Reshape it to a 5x4 matrix mat.
    * Print every 4th element of vec.
    * Print elements of vec less than or equal to 25.
    * In vec assign every number at even location to 1.
    * In vec assign from start position to 10th position every second element to 0.
    * Reverse elements of vec.
    * In mat print each row in the second column and print each column in the second row.
    * Apply some universal functions such as sin,sqrt,cos,exp on vec.
    * Print transpose and inverse of mat.
9. Demonstrate shallow copy and deep copy.

-----

# **Practical 06**

**Python File Handling to load text &amp; image data**
1. Create File with two columns X1 and Y1. Generate 20 rows with random data for values of X1 and Y1.
2. Demonstrate concept of streaming and sampling using above generated file. Fetch every even record from file and Fetch any 5 random records from file to demonstrate sampling.
3. Download and load image data from the following URL. https://unsplash.com/photos/pypeCEaJeZY

-----

# **Practical 07**

**Develop Programs to demonstrate use of Pandas for Conditioning Your Data**

URL for `test.xml` file.
https://drive.google.com/file/d/1FqOWhY2XNYkHwCBYOjhAILCzVUo9QEp6

URL for `indian_food.csv` file.
https://drive.google.com/file/d/1CNAdqFZ-Amji8kOMd4GovivK8UKVLQ-p

1.  Read the xml file `test.xml` and create a dataframe from it and do the following.
    *   Find and print duplicate records.
    *   Remove duplicates and save data in other dataframe.
2.  Read the csv file `indian_food.csv`. Consider value -1 for missing or NA values.(Replace -1 with NaN when reading a csv file.)
    *   Print the first and last 10 records of dataframe, also print column names and summary of data. Print information about data such as data types of each column.
    *   Convert columns with name course,diet,flavor_profile,state,region to categorical data type &amp; print data type for dataframe using info function.
    *   Categories are defined as follows.
          > Course ['dessert' 'main course' 'starter' 'snack']
          > 
          > Flavor_profile ['sweet' 'spicy' 'bitter' 'sour']
          > 
          > State ['West Bengal' 'Rajasthan' 'Punjab' 'Uttar Pradesh' 'Odisha' 'Maharashtra' 'Uttarakhand' 'Assam' 'Bihar' 'Andhra Pradesh' 'Karnataka' 'Telangana' 'Kerala' 'Tamil Nadu' 'Gujarat' 'Tripura' 'Manipur' 'Nagaland' 'NCT of Delhi' 'Jammu & Kashmir' 'Chhattisgarh' 'Haryana' 'MadhyaPradesh' 'Goa']
          > 
          > Region ['East' 'West' 'North' nan 'North East' 'South' 'Central']
    *   Print name of items with course as dessert.
    *   Print count of items with flavor_profile with sweet type.
    *   Print name of items with cooking_time < prep_time.
    *   Print summary of data grouped by diet column.
    *   Print average cooking_time & prep_time for vegetarian diet type.
    *   Insert a new column with column name as total_time which contains sum of cooking_time & prep_time into existing dataframe.
    *   Print name,cooking_time,prep_time,total_time of items with total_time >=500
    *   Print count of items with various flavour_profile per region.
    *   Find & print records with missing data in the state column.
    *   Fill missing data in the state column with -.
3.    Write regular expression, 
      > To extract phone numbers (+dd-dddd-dddd) from the following text
      >
      > “Hey my number is +01-555-1212 & his number is +01-770-1410”
      > 
      > To extract email addresses from the following text.
      > 
      > “You can contact to abcd@gmail.co.in or to xyzw@yahoo.in”
4.  Demonstrate stemming & stop word removal using nltk library for content given below
      >   Most of the world will make decisions by either guessing or using their gut. They will beeither lucky or wrong.
      >
      >   The goal is to turn data into information and information into insight.
5.  Using a 20 newsgroup dataset, create and demonstrate a bag of words model.Also convert theraw newsgroup documents into a matrix of TF-IDF feature.

-----

# **Practical 08**

**Develop Programs to visualize the data using matplotlib**

1.  Line Plot
2.  Scatter Plot
3.  Bar Chart
4.  Histogram
5.  Pie Chart

-----

# **Practical 09**

**Demonstration of Scikit-learn and other machine learning libraries such as keras, tensorflow etc.**

1.  Scikit-Learn for Classification (e.g., Iris dataset)
2.  Using Keras for Neural Networks

-----
