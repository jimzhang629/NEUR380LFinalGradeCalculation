This notebook calculates each student's final average grade and average assignment category grades for the class NEUR380L, weighting each assignment within each assignment category (i.e., IRAs, TRAs, Clinical Case Sets) equally.

Steps:
1. Export the Canvas gradebook (Canvas course page -> Grades -> Export -> Export Entire Gradebook.)
2. In the first cell of the notebook, update the input filepath to point to where you saved the canvas gradebook, and update the output filepath to where you want to save the modified csv to.
3. In the second cell, update which assignments you want to exclude from each assignment category's average grade calculation. You can use the full name of the assignment as it is defined in the gradebook, or use a partial string that matches part of the name. Just be careful that your partial strings don't end up matching other assignment names that you do want to keep.
4. Run the entire notebook. This will produce a csv with grades for each assignment converted from points to percentages, as well as new columns for each student's final average grade and average grades for each assignment category. NOTE: Because the final exam and self-directed learning seminar assignment categories only have one assignment each, their average grade is the same as the grade for that single assignment.
