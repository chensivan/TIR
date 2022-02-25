## what

This paper conducted a controled experiment to explore to what extent that visual explanations of a model are helpful for humans in an age guessing application.

## Motivation

One common assumption underlying much interpretable ML research is that more faithful and accurate explanation can help people trust the models more. But, most evaluation of explanations has focused on the intrinsic relation to model properties rather than their effect on human decision-making.

## Study design

Task: showing an image of a person and guess their age
condicitions:

- baseline:
  - human alone
  - ai only provides its prediction w.o. explanation
- visual explanation:
  - strong: saliency map to show where the model paid attention to
  - spurious: used a wrongly trained model to show the saliency map
  - random: a randomly generated saliency map
- designed explanation:
  - delayed the response: prior work show this increase people's accuracy
  - empathetic: personifies the ai as an AI named Pat
  - show top 3 range

## Findings:

1. empathetic, top3, and strong outperform humans alone
2. additional explanation didn't improve accuracy
3. quality of explanation had little effect on accuracy
4. faulty explanations didn't decrease the trust in model predictions
5. even if the predictions are way off (not on the face), people still claimed that explanations appeared to be reasonable.

## Takeaway:

- showing confidence scores in textual form has no improvement
- changing the stated accuracy can increase trust, but if the observed accuracy is low the trust will descrease
- displaying uncertainty might be potentially helpful
- design of explanation includes more than just the layout: incentives to use ML tool, level of human agency and interactivity and the unremarkability of the system.

## Where

![office](office.JPG)
