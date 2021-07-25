# School_District_Analysis

## Graphics section - including graphics/images to be used in the report

Consolidating the files here so I can add to the full report later

This image shows a section of the school_data_complete_df dataframe after the Thomas HS 9th grade math and reading scores have been changed to null 

<a href=https://github.com/gcmastra/School_District_Analysis/blob/main/Resources/imge1_ths_math_scores_null.JPG">
![image](https://github.com/gcmastra/School_District_Analysis/blob/main/Resources/imge1_ths_math_scores_null.JPG)</a>


This graphic shows the summary data per scholl before the Thomas HS 9th grade data has been changed

![image](https://github.com/gcmastra/School_District_Analysis/blob/abb4811b52c9a6bb6ef347b870e4112619a364df/Resources/image2_section_of_per_school_summary_showing_THS_before_changes.JPG)


Making a change to the README so it will look to git like something changed and I can do a new pull to verify SSH is working 

## Technical Issues Encountered
Added on 20210723 - Dection 4.5.4 - during data cleanup of student test scores, in addition to unusual suffixes or prefixes, there could be other issues with the student names column, like misspellings or inaccurate keying of the name when read into the CSV.  My recommenation would be that they should have included a student ID # when taking the test so it could matched unambiguously against the main student record system.  If we could obtain a master list of student names and IDs, we could run a comparison that would spit out all the rows that do not find a match in the master database. 
