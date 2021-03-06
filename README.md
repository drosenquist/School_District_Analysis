# School_District_Analysis
## Purpose
Py City school board has asked that standarized test score for each school be analzyed due to suspicion that a high school in the district, Thomas High School, reported alerted test scores for its 9th grade class. Scores for Thomas' 9th grade were replaced with NaNs while keeping the rest of the data intact. The previous distrct wide analysis was recreated to see if the outcomes for the 9th grade scores differed between the two analysises.

## Results
### How is the district summary affected?
Original District Summary
<img width="933" alt="Screen Shot 2022-04-23 at 3 09 31 PM" src="https://user-images.githubusercontent.com/101379969/164947557-123cfa59-3c2f-4a97-8b85-475a961fe3b9.png">

Updated District Summary
<img width="941" alt="Screen Shot 2022-04-23 at 3 08 07 PM" src="https://user-images.githubusercontent.com/101379969/164947545-9b280234-3d91-44dc-bd25-4fa61d51b117.png">

The district results were nearly identical to each other. Changes in the reported numbers only differ to slight rounding differences in the results.

### How is the school summary affected?
Original School Summary
<img width="998" alt="Screen Shot 2022-04-23 at 3 17 22 PM" src="https://user-images.githubusercontent.com/101379969/164947812-7eebc235-715d-4e54-8649-d97e850697ed.png">

Updated School Summary 
<img width="987" alt="Screen Shot 2022-04-23 at 3 19 32 PM" src="https://user-images.githubusercontent.com/101379969/164947854-7940b79f-7bd4-466e-beb9-38e76332d287.png">

Removing the 9th grade scores for Thomas High School showed that the average test score for the school stayed the same.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
By replacing the 9th graders' math and reading scoores Thomas High School's performance relative to the otherrs drop from 2nd place to 8th place.

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
  Math and reading scores were unaffected other than scores fror Thomas High School's 9th grade (since they were changed to "Nan").
  
  Original Math Score Summary by School and Grade
  
  <img width="306" alt="Screen Shot 2022-04-23 at 3 58 03 PM" src="https://user-images.githubusercontent.com/101379969/164948831-d5afa7a9-a791-4baf-9c2f-4df771ebeadc.png">
  
  Original Reading Score Summary by School and Grade
  
  <img width="306" alt="Screen Shot 2022-04-23 at 3 58 03 PM" src="https://user-images.githubusercontent.com/101379969/164948790-b90cdedf-81d1-4e13-a651-ceefb7d2da8e.png">

  Updated Math Score Summary by School and Grade
  
  <img width="308" alt="Screen Shot 2022-04-23 at 3 57 56 PM" src="https://user-images.githubusercontent.com/101379969/164948736-8d9eb80d-b586-4f32-82d7-4534645eedc8.png">
  
  Updated Reading Score Summary by School and Grade
  
  <img width="306" alt="Screen Shot 2022-04-23 at 3 58 03 PM" src="https://user-images.githubusercontent.com/101379969/164948740-712bc835-7655-4b39-aae2-740b624a1d0f.png">

#### Scores by school spending

  There was no affect on scores by spending.
  
  Original Summary
  
   <img width="823" alt="Screen Shot 2022-04-23 at 3 41 20 PM" src="https://user-images.githubusercontent.com/101379969/164948357-b34d929a-63d7-474b-9767-edc876002440.png">
  
  Updated summary
  
   <img width="826" alt="Screen Shot 2022-04-23 at 3 41 57 PM" src="https://user-images.githubusercontent.com/101379969/164948387-b17deffa-d71a-494b-a0c7-96863b37e6b8.png">

#### Scores by school size
 
   There was no affect on scores by school size.

  Original Summary
  
  <img width="762" alt="Screen Shot 2022-04-23 at 3 46 35 PM" src="https://user-images.githubusercontent.com/101379969/164948631-90ea1219-4eb2-44dc-8ce4-a3aeccc82081.png">

  
  Updated summary
  
   <img width="763" alt="Screen Shot 2022-04-23 at 3 54 29 PM" src="https://user-images.githubusercontent.com/101379969/164948673-d9e803a9-3900-4b76-8830-531cd92f3128.png">

#### Scores by school type
  
  There was no affect on scores by school type.
  
  Original Summary
  
  <img width="725" alt="Screen Shot 2022-04-23 at 3 49 40 PM" src="https://user-images.githubusercontent.com/101379969/164948603-fd40b986-1742-46c4-83d4-7b253119bf0e.png">
  
  
  Updated summary
  
  <img width="722" alt="Screen Shot 2022-04-23 at 3 49 50 PM" src="https://user-images.githubusercontent.com/101379969/164948587-757749fc-e40d-4a91-a5e6-d3dcf3537f59.png">
  
## Summary
Removal on the 9th grade scores for Thomas High school had minimal impact on the analysis. There were no changes to scores by school, spending, size and type. The percentage of students passing reading and math for Thomas High School droped dramactially as changing the scores to "Nan" treated the 9th grade students as if they had failed. There were changes in the average math and reading score, but these changes were minimal indicating the reported test results were consitent with the other grades levels.
