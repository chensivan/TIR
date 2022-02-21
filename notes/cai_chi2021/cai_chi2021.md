## What

This is a case study on the development of human-ai onboarding materials for a DL medical AI assistant to aid in the grading of prostate cancer. One important takeaway is that onboarding materials can be served as a useful boundary object for cross-function teams. They are helpful both for improving model evaluation and designing easy to use interfaces.

## Important onboarding materials for medical ai assistants

- instructions on how to use the interface
- information descriptions on:
  - the amount of and type of training data used to train the model, and the input data
  - who annotated the training data
  - the strength and weakness of the AI assistant (e.g., accuracy in different cases)
  - strategies for using the system in light of its known strenths and weakness

## User requests vs impact on the user-developer interactions

1. User needs: actionable strategy for when to rely on ai and when to rely on their own judgement
   - users' own capability can be unclear (e.g., pathologists aren't sure the types of cases that they are less likely to grade accurately)
     - impact: expand the comparative analysis of users vs model performance, resulting data insights and strategies (e.g., how likely the AI systems will overgrade users)
2. user needs: strength/weakness on subtypes or edge cases
   - once the model is trained, it's more cost efficient to re-label based on the model performance, specificially on the edge cases. this would lead to more transparent system's limitation and scope, also improve future upstream data collection and model training
     - impact: re-label data with subtypes (e.g., sub-patterns of cancer grade 5)
3. user needs: system's failure cases
   - sometimes the prediction can be really off (i.e., non-human), and users need to know when those cases will occur
     - impact: prompt the knowledge distribution among the engineering teams about the model's idiosyncrasies; educate the users about these AI limitations
4. user need: easy to act on the model output
   - translating the metrics, graphs to human-digestable Takeaways
     - impact: prompt engineering teams to re-frame model proptiers with respect to the user's theory of mind; co-creation of this material between engineers, PMs, and UX is necessary.
5. user need: match their needs
   - mismatches between needs and objectives, e.g., tradeoffs between sensitivity and specificity, cost of error types, ability to compensate for common errors, etc
     - jointly defining model objectives, augment data annotation to provide those that deemed tricky to users

## Other takeaways

- developing onboarding materials early in the design and development process
- better codifying the onboarding creation process
- transforming model performance to detailed, human-actionable strategies.
