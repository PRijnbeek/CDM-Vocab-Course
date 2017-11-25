---
title       : The Standardized Vocabularies
description : Understand the background of the OMOP-CDM
---
## Connecting to the demo CDM

```yaml
type: PureMultipleChoiceExercise
key: 6924ed57f3
lang: sql
xp: 50
skills: 1
```

![alt text][logo]

[logo]: https://github.com/PRijnbeek/VocabularyCourse/raw/master/img/omop-cdm.png "OMOP-CDM V5.2"

Let's first have a look at the OMOP-CDM and the role of the Standardized Vocabularies.

As you can see the OMOP-CDM is divided in multiple sections. Clinical Data is stored in the Standardized Clinical Data section on the left (light blue). The Standardized Vocabulary tables are group in the orange box on the right.

Which of the following statements is true?

`@possible_answers`
- This type of model is called an informatics model
- The clinical data tables contain clinical concepts in human readible form
- [This is a patient centric model]
- The model is now final and will be used as is in the future

`@hint`

`@feedbacks`
- A blend of a conceptual model and a data model is called an information model
- Only concept\_ids are stored in the clinical data tables, e.g. 8507 = male
- Correct Answer. All the clinical data tables have a link to the person table
- The model is evolving over time. This is driven by new use cases and input by the active OHDSI community



--- type:VideoExercise lang:sql xp:50 skills:1 key:909e0deb29
## <<<New Exercise>>>

*** =projector_key
f983958a7580558ae552bf6b8f3af012
