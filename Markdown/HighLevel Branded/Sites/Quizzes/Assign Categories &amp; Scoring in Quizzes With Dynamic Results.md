**Date Updated:** 2025-07-30T10:45:27.000Z

This feature in **quizzes** allows you to assign scores to answers and categorize them. This helps in generating useful quiz results, such as assessments, recommendations, or segmentation based on responses and now display personalized result messages based on scoring ranges. This is perfect for assessments, personality quizzes, onboarding surveys, and more.

---

**TABLE OF CONTENTS**

* [How to Add Scores in Quizzes](#How-to-Add-Scores-in-Quizzes)  
   * [Step 1: Create or Edit a Quiz](#Step-1%3A-Create-or-Edit-a-Quiz)  
   * [Step 2: Add Questions to the Quiz](#Step-2%3A-Add-Questions-to-the-Quiz)  
   * [Step 3: Assign Scores to Categories](#Step-3%3A-Assign-Scores-to-Categories)  
   * [Step 4: Save and Preview](#Step-4%3A-Save-and-Preview)[](#How-Quiz-Scoring-Works)  
   * [](#How-Quiz-Scoring-Works)[**How Quiz Scoring Works**](#How-Quiz-Scoring-Works)  
   * [Step 1: Set the Maximum Score for Each Question](#Step-1%3A-Set-the-Maximum-Score-for-Each-Question)  
   * [Step 2: Assign Scores to Answers](#Step-2%3A-Assign-Scores-to-Answers)  
   * [Step 3: Calculating the Final Score](#Step-3%3A-Calculating-the-Final-Score)  
   * [Key Takeaways About "Overall Only"](#Key-Takeaways-About-)
* [Add Dynamic Result Messages by Score Ranges](#Add-Dynamic-Result-Messages-by-Score-Ranges)
* [Best Practices & Troubleshooting](#Best-Practices-&-Troubleshooting)

---

# **How to Add Scores in Quizzes**

  
## Step 1: Create or Edit a Quiz

1. Log into your account.
2. Navigate to Sites > Quizzes.
3. Select an existing quiz or click + New Quiz to create a new one.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049005153/original/Glec9ZtQbZzu4KrQgDaNSJ0flyWbUSLmsQ.png?1751042063)

---

## Step 2: Add Questions to the Quiz

  
1. Click Add Question and choose a question type (Single Choice, Multiple Choice, Dropdown, etc.).
2. Enter the question and possible answer choices.
3. For each answer choice, assign a score value based on how much weight it carries.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049005260/original/OSmBr7KC7eIzXEetxYJmy7f_9KbDU1L_5w.png?1751042278)

---

## Step 3: Assign Scores to Categories

  
1. Create score categories (e.g., Category A, Category B, etc.).
2. Assign scores to each answer:  
   1. For Single Choice/Dropdown questions, assign a fixed score per answer.  
   2. For Multiple Choice/Multi Dropdown, assign a score per option that adds up if multiple choices are selected.
3. Assign each answer’s score to the relevant category.
4. If a question’s answer applies to multiple categories, select all that apply.  
    
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155049005294/original/kec9fRftzKKlqDz9xYjvv0RghxFC_Fs-RA.png?1751042314)

---

## Step 4: Save and Preview

1. Click Save Quiz once you’ve set up all questions and scoring.
2. Use the Preview option to test the quiz and check if scores are calculated correctly.

---

## **How Quiz Scoring Works**

## Step 1: Set the Maximum Score for Each Question

Every question has a maximum score, which depends on its type:

* Single Choice/Dropdown: Only one answer can be selected, so the max score is fixed.
* Multiple Choice/Multi Dropdown: Multiple answers can be selected, so the max score is higher. The max score is fixed and it is the sum of all the options in the dropdown/multiple choice.

#### Example:

* A Single Choice question might have a max score of 10.
* A Multiple Choice question might allow up to 50 points.

---

## Step 2: Assign Scores to Answers

  
When a quiz-taker selects an answer, it contributes to:

* Overall Score Only: Counts toward the total quiz score but not any specific category.
* Category-Specific Score: Counts toward both a specific category and the overall score.
* Multiple Categories: Affects more than one category at the same time.

Example:

* If a quiz has Category A, B, and C, and an answer is assigned to Category A, the score counts toward Category A and the Overall Score.

---

## Step 3: Calculating the Final Score

Once all answers are selected, the final score is calculated using this formula:

Final Score = (Selected Score / Max Score) \* 100

This is done separately for Overall Only and for each category.

#### **Example Calculation**

| Category   | Selected Score | Max Score | Final % | Final Score Formula                                                   |
| ---------- | -------------- | --------- | ------- | --------------------------------------------------------------------- |
| Overall    | 90             | 130       | 69.23%  | Selected Score for Overall / Maximum Possible Score for Overall       |
| Category A | 20             | 50        | 40.00%  | Selected Score for Category A / Maximum Possible Score for Category A |
| Category B | 20             | 50        | 40.00%  | Selected Score for Category B / Maximum Possible Score for Category B |
| Category C | 10             | 50        | 20.00%  | Selected Score for Category C / Maximum Possible Score for Category C |
  
  
In this example:  
  
* The quiz-taker scored 69.23% overall.
* For Category A, they scored 20 out of 50, resulting in 40%.

---

## Key Takeaways About "Overall Only"

  
1. "Overall Only" is a Consolidated Score  
   * If an answer is assigned only to "Overall Only," it doesn’t count towards any category.  
   * If an answer is assigned to both a category and "Overall Only," it is counted in both.
2. Categories Are Independent but Contribute to the Overall Score  
   * Each category's score is calculated separately, but the Overall Score is the sum of all category scores.
3. Formula Breakdown  
   * The Final Score Formula is calculated as:  
    Maximum Selected Score for X / Maximum possible score in each category  
   * This applies across Overall, Category A, Category B, etc. to derive the percentage scores.

---

# Add Dynamic Result Messages by Score Ranges

You can now display customized result messages based on the final score percentage (e.g., 0–40% = Low, 41–70% = Medium, 71–100% = High).  
  
#### 1\. Navigate to the Result Page

* Inside the quiz builder, scroll to the last section labeled “Result Page”

  
![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044791383/original/im0S_J27bG5YzDAG_sqy650r8htQTLhQyA.png?1744193847)  

####   

  
#### 2\. Define Score Ranges

* Locate the “Score Range Settings” under the Result Page.
* Define the thresholds:  
   * Low: 0% to 40%  
   * Medium: 41% to 70%  
   * High: 71% to 100%  
   * You can customize these ranges based on your quiz needs.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044791385/original/xJkMj_O3f5lKYyq_-LeC8qNpL_li84UiTA.png?1744193848)  

####   

####   

#### 3\. Personalize Messages for Each Range

* For each range (Low/Medium/High), add a custom message.
* Example:  
   * Low: “It looks like there’s room for improvement. Let's explore how we can help.”  
   * Medium: “You’re on the right track! Here’s how to optimize further.”  
   * High: “Awesome job! You’ve nailed this. Let’s talk about next steps.”  
         
   ![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/155044791384/original/j2vZcJo3MnYO_MU3atduOpmOZ4ygh6JifA.png?1744193848)

####   

#### 4\. Add a Call-to-Action (Optional)

* Include a CTA like:  
   * Subscribe  
   * Book a call  
   * Redirect to a funnel
* Customize it under the “CTA” box on the Result Page.

---

  
# **Best Practices & Troubleshooting**

* Clearly define max scores for each question to ensure consistency.
* Use categories effectively to segment quiz results.
* Ensure answer options are correctly mapped to their respective categories.
* Wrong final scores? Check if selected scores and category assignments are correct.
* Missing category scores? Make sure answer options are assigned to categories.
* Total not adding up? Remember that "Overall Only" does not count toward individual categories.

By following these steps, you can easily set up and manage calculated fields in quizzes for better assessments and insights!