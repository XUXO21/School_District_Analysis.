# School_District_Analysis.

---

School_District_Analysis.

---

##Overview of the school district analysis

The purpose of this analysis is to help Maria a School District data scientist to analiza information from a variety of sources and formats in order to provide insights about, performance, trends and patterns. This insights will be used to have informed discussions and take statagic desitions by the schoolboard and super intendent regarding schools buget and priorities.

Never the less Maria has been informed about academic dishonesty on grades for Thomas High School, nine graders. For that reason information and insights are beeing recalcualted in order to understand impacts and take desitions. 

---

##Results

### How insights are affected:

* District summary: 
    - For average scores, only math had non significant variation 
    - % of Passing students for math reduced -0.2 p.p. and for reading -0.3 p.p. while % of Overall passing reduced -0.1 p.p.

Original:

![OrgDS](/Images/original_distircit_summary%20.png)

New:

![NewDS](/Images/new_distircit_summary%20.png)

* School summary:
  - 461 students are not beeing taken in count for math and reading grades
  - Total student count diminishes from 39,170 to 38,709
  - Impact on the percentage of total students grades in both math and reading is non significant (math: form 74.98 to 74.76, reading: from 58.80 to 85,65)
  - Overall passing percentage reduces form 65.17 to 64.85 -0.32 p.p.
  - Rest of the schools is not affected

* Thomas High School’s performance relative to the other schools
    - THS still mantains the number two position in school rank

Original:

![Org](/Images/original_top_five.png)

New:

![New](/Images/New_Top_Five.png)
    
### How does replacing the ninth-grade scores affect:

* Math and reading scores by grade
    - Both scores for both Math and Reading convert into "Nan" for Thomas HS in ninth-grade 

Original:

![Org](/Images/Original_math_by_grade.png)

New:

![New](/Images/New_math_by_grade.png)


* Scores by school spending
    - Impact can be seen on range from $631-645 range, but it is non significant

Original:

![Org](/Images/Original_school_%20Spending.png)

New:

![New](/Images/New_school_spending.png)


* Scores by school size
    - Impact can be seen on medium school range, but it is non significant

Original:

![Org](/Images/Original_school%20_size.png)

New:

![New](/Images/New_school_size.png)

* Scores by school type
    - Impact can be seen on charter school type, but it is non significant

Original:

![Org](/Images/Original_school_%20Spending.png)

New:

![New](/Images/Original_school_type.png)

---

## Summary:

On summary we can tell that we can see changes in the universe of students when changing ninth-gradraders for "Nan" and also some differences on math and reading percentage of students grades but they are non significant, while -0.3 reduction from overall average is seen. In terms of ranks among other schools or impact in scores by school type, size, spending or grade is non significant.
