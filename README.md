# School District Analysis

## Overview

The school board and superindentants require standardized test analysis, reporting, and presentation to provide insights about performance, trends, and patterns, which will be used to make informed decisions at the school and district levels. Student funding and standarized test scores will be analyzed using math and reading score data, and the data will be aggregated to show trends in school performance.

After the initial analysis, evidence showed academic dishonesty among the reading and math grades for Thomas High School ninth graders. The school board wants to uphold state-testing standards and requests that the ninth grade math and reading scores for Thomas High School be replaced. The analysis will be repeated and changes in the overall analysis will be described.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

* How is the district summary affected?

Initial district summary analysis:
<img width="1113" alt="PyCitySchools_district_summary_df" src="https://user-images.githubusercontent.com/106785377/183272812-fdb6f85f-ef63-425d-abf7-74fbcc051db7.png">

Repeated district summary analysis:
<img width="1117" alt="Challenge_district_summary_df" src="https://user-images.githubusercontent.com/106785377/183272816-b0fda4b2-295b-40d1-8a5d-975e9d68484e.png">

      The district summary is largely unaffected by removing the Thomas High School ninth grader reading and math scores from the analysis.

* How is the school summary affected?

      The only school in the school summary analysis that was affected by the changes is Thomas High School.

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Initial school summary analysis:
<img width="1178" alt="Initial_district_summary" src="https://user-images.githubusercontent.com/106785377/183273064-cf5e5526-be62-4999-81ea-6fae9e13f889.png">

Repeated school summary analysis:
<img width="1178" alt="Repeated_district_summary" src="https://user-images.githubusercontent.com/106785377/183273065-496f26bb-3f84-431f-ba15-f8e89b3a908e.png">

      The school summary for Thomas High School is largely unaffected by removing the ninth grader reading and math scores from the analysis.

* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade

Initial math scores by grade:

<img width="356" alt="Initial_MathScoresbyGrade" src="https://user-images.githubusercontent.com/106785377/183273734-d30f36b3-5c89-45db-8d81-2af6d1120ed6.png">

Initial reading scores by grade:

<img width="361" alt="Initial_ReadingScoresbyGrade" src="https://user-images.githubusercontent.com/106785377/183273738-09b89464-a925-41e1-ab3c-1a90c5157a49.png">

Repeated math scores by grade:

<img width="361" alt="Repeated_MathScoresbyGrade" src="https://user-images.githubusercontent.com/106785377/183273742-35be9025-322d-49a5-b037-ca18a6393d09.png">

Repeated reading scores by grade:

<img width="358" alt="Repeated_ReadingScoresbyGrade" src="https://user-images.githubusercontent.com/106785377/183273749-93baf675-031d-4051-8cd5-b9ba2ba77c32.png">

            Ninth grade scores are Nan for math and reading in the repeated analysis.

   * Scores by school spending

            The scores by school spending are not affected by the changes made in the repeated analysis.

   * Scores by school size

            The scores by school size are not affected by the changes made in the repeated analysis.

   * Scores by school type

            The scores by school type are not affected by the changes made in the repeated analysis.

## Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
