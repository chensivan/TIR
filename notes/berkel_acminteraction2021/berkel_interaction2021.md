## What

This paper identifies three human-ai interaction paradigms: intermittent, continuous, and proactive. They also adavocate that there needs more efforts on exploring novel techniques to support end-users in non-intermittent ai interaction scenarios.

## Why

There's a growing focus on human-ai interaction design as of the rise in AI-drivent systems. However, current work in human-ai interaction is primarily defined by a focus on intermittent interaction scenarios, in which there's a clear line between the human initator of an interaction and an almost immediate system response. But, human-ai interaction goes beyond this pattern, and this paper defines it as the completion of a user's task with the help of ai support, which may manifest itself in non-intermittent scenarios.

## Detailed definition

1. intermittent human-ai: interaction as dialogue
   1. it's a turn-taking process. Norman introduced this action cycle. This is the same as the human-traditional system interaction.
      1. [Notes] gulfs of execution and evaluation are needed to be considered when designing the user experience
      2. [Examples]: intelligent digital assistants (e.g. hey google stop playing music)
2. continuous human-ai: interaction as commentary
   1. ai systems 'listen' to a stream of uninterrupted user input rather than individual instructions and can respond to this input throughout the duration of the interaction.
      1. [Notes] users are free to ignore the suggestions, and maintain their stream of input. when designing interactions for such systems, one needs to consider that users is typically focus on a task and distracting them from this activitivity is undesired. users but only respond when necessary or relevant.
      2. [Examples]: automatically indenting bullets in the text, checking and highlighting spelling mistakes.
3. Proactive human-ai: interaction as prescription
   1. systems do not wait for user input but actively initiate and complete tasks based on, e.g., sensor readings.
      1. [Notes]: The 'bridge of execution' is removed from the interaction, so the attention cycle is reduced to a 'reaction cycle', in which the user responds to the behavior of practive systems.
      2. [Examples]: user walks into the room and opens a book to read, the room light changes as it notices its dark outside and the need of light in the room

## opportunities

1. user's mental model of intermittent interaction is different from that of non-intermittent ones. additionally, users have desires to infer models on system operation, and this desire will continue to manifest itself in non-intermittent forms of interactions. the authors layout that we must assist users in constructing correct mental models to increase user understanding and prevent future errors.
2. with proactive systems, users' intention could be led by these systems w/o their consent and having a way of correcting errors.
3. embedding fairness, accountability and transparency into non-intermittent human-ai interactions is an open question. for instance, with proactive systems, the user group was not defined and involved when decisions were made or explained.

## other Notes

Stephen Payne:

> users of machines are eager to form explanatory models and will readily go beyond available data to infer models that are consistent with their experiences.

proactive systems will make this much faster but also harder to control if things go wrong.

## personal thoughts

- proactive ai scenairos remove the gulf of execution, so when designing systems, we won't follow Norman's design guidance on execution.
- semanticon sits in between intermittent and continuous human-ai interactions. in the beginning, the interaction is intermittent or manual, and when the system enters automation mode, it becomes continuous.
