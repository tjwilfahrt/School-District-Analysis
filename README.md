# School-District-Analysis
## Challenge 1 - Replace Ninth-Grade Reading and Math Scores using 'loc' method
#### Use loc method on the student_data_df to select all the reading scores from the 9th grade at Thomas High Schooland replace them with NaN (code and output included).

student_data_df.loc[(student_data_df["reading_score"] >= 70) & (student_data_df["math_score"] >= 70)]

student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") & (student_data_df["grade"] == "9th"), "reading_score"] = np.nan

student_data_df

  ![Screen Shot 2021-10-17 at 5 51 40 PM](https://user-images.githubusercontent.com/90878939/137647816-fb2dd5f7-3cfd-42c7-9fd6-b23b38829879.png)

#### Refactor the code in Step 2 to replace the math scores with NaN (code and output included).

student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") & (student_data_df["grade"] == "9th"), "math_score"] = np.nan

student_data_df

  ![Screen Shot 2021-10-17 at 5 51 50 PM](https://user-images.githubusercontent.com/90878939/137647820-b48b9e9c-290b-4ad4-926b-5997e8ae6e7b.png)

#### Check the student data for NaN's (code and output included). 
student_data_df.tail(10)

  ![Screen Shot 2021-10-17 at 5 31 43 PM](https://user-images.githubusercontent.com/90878939/137647260-ecc31a7b-49eb-4af7-b39f-05c011f9bcfd.png)



## Challenge 2 - School District Analysis (code included in PyCitySchools_Challenge file)

#### District summary dataFrame
  ![Screen Shot 2021-10-17 at 5 33 39 PM](https://user-images.githubusercontent.com/90878939/137647317-8593a442-4db7-4292-9d05-a7b78d83b37d.png)

#### School summary dataFrame
  ![Screen Shot 2021-10-17 at 5 34 25 PM](https://user-images.githubusercontent.com/90878939/137647338-2a72ca88-f7f8-4cd9-81f7-4117c7275e17.png)

#### Top 5 performing schools, based on the overall passing rate
  ![Screen Shot 2021-10-17 at 5 38 46 PM](https://user-images.githubusercontent.com/90878939/137647454-07e93a2a-9bcb-40fb-a605-9145988eeef5.png)

#### Bottom 5 performing schools, based on the overall passing rate
  ![Screen Shot 2021-10-17 at 5 39 18 PM](https://user-images.githubusercontent.com/90878939/137647483-2a196214-5f7f-4cd4-8993-d3f49ce1227a.png)

#### Average math score for each grade level from each school
  ![Screen Shot 2021-10-17 at 5 40 17 PM](https://user-images.githubusercontent.com/90878939/137647505-6713a069-c0b8-4cef-992c-e6bb7dfac9ff.png)

#### Average reading score for each grade level from each school
  ![Screen Shot 2021-10-17 at 5 40 54 PM](https://user-images.githubusercontent.com/90878939/137647527-84c3ab37-80f7-48c8-b7ce-77e5df6b7502.png)

#### Scores by school spending per student
  ![Screen Shot 2021-10-17 at 5 42 09 PM](https://user-images.githubusercontent.com/90878939/137647573-4b0223b7-6190-4141-be07-45162d13c648.png)

#### Average scores spending per student
  ![Screen Shot 2021-10-17 at 5 43 55 PM](https://user-images.githubusercontent.com/90878939/137647622-b99b630a-0fc7-4d38-ae4b-e260b8d40b7d.png)

#### Scores by school size
  ![Screen Shot 2021-10-17 at 5 45 04 PM](https://user-images.githubusercontent.com/90878939/137647637-751302e1-7469-4a05-9f31-dda7f3e17b8f.png)

#### Average scores by school size
  ![Screen Shot 2021-10-17 at 5 45 53 PM](https://user-images.githubusercontent.com/90878939/137647672-cbf9597b-438d-45b9-997f-076a87397049.png)

#### Average scores by school type
  ![Screen Shot 2021-10-17 at 5 48 58 PM](https://user-images.githubusercontent.com/90878939/137647753-0e451094-8d06-4d46-8723-a6d4961db3f2.png)
