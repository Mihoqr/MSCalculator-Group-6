# Milestone Calculator
- Anos, Shanne
- Atienza, Trisha Mei
- Quesada, Michelle Joi
- Layaguin, Darin

## About the Application

This application is a GUI-based tool designed to calculate grades for milestones and terminal assessments based on a given grade and distribution. It is an enhancement of a Grade Calculator, now tailored specifically for milestone grading.

## Input

1. **Milestone 1 Grade:** The grade achieved for Milestone 1, ranging from 0 to 25 points.
2. **Milestone 2 Grade:** The grade achieved for Milestone 2, ranging from 0 to 40 points.
3. **Terminal Assessment Grade:** The grade achieved for the Terminal Assessment, ranging from 0 to 35 points.

## Output

- **Total Grade:** The total grade computed based on the given grades and their respective weights.

## Exception Handling

- The program will not accept values lower than 0 or higher than the maximum points per milestone. If these exceptions occur, a dialog box will prompt the user indicating the exception.

## Calculation

- **Milestone 1:** Weighted at 25% of the total grade.
- **Milestone 2:** Weighted at 40% of the total grade.
- **Terminal Assessment:** Weighted at 35% of the total grade.

## Example

- If the user enters Milestone 1 Grade as 20, Milestone 2 Grade as 35, and Terminal Assessment Grade as 30, the Total Grade will be calculated as follows:

  - Milestone 1 Contribution: (20/25) * 25 = 20   
  - Milestone 2 Contribution: (35/40) * 40 = 35
  - Terminal Assessment Contribution: (30/35) * 25 = 30

  - Total Grade: 20 + 35 + 30 = 85

## How to Use

1. Enter the grades for Milestone 1, Milestone 2, and Terminal Assessment in their respective fields.
2. Click on the "Calculate" button to compute the Total Grade.
3. Or click "Clear all" to remove all the input.
4. If an exception occurs, a message will prompt you to correct the input.

## Future Enhancements

- Include a feature to save and load grades for different students or scenarios.
- Implement a visual representation of the grade distribution for better understanding.
