---
title       : The Standardized Vocabularies
description : Understand the standardized vocabularies

--- type:VideoExercise lang:sql xp:50 skills:1 key:909e0deb29
## Setting up the data connection

*** =projector_key
f983958a7580558ae552bf6b8f3af012


--- type:PureMultipleChoiceExercise lang:sql xp:50 skills:1 key:6087d6f53d
## Introduction
![alt text][logo]

[logo]: https://github.com/PRijnbeek/VocabularyCourse/raw/master/img/vocabulary-cdm.png "Vocabulary Table Structure"

In the figure above you see the table structure of the Standardized Vocabulary section in the CDM.In each table you see a number of 'keys' in in each table. A 'red' key means that this is a so-called 'primary key', i.e. each value is unique and is used to reference the data. A 'green' key is a 'foreigh key' which means it links to a primary key in another table, e.g. the vocabulary_id in the concept table. The 'blue' keys represent primary keys that consists of multiple fields, i.e. the combination of these fields is unique and use to lookup data in the table.

In the upcoming questions we will explore the following most important tables:

CONCEPT: all concepts of all vocabularies

CONCEPT_RELATIONSHIP: all hierarchical relationships among concepts

CONCEPT_ANCESTOR: Multi-step hierarchical relationships pre-processed to make traversing the vocabulary easier

We will ask you to run a number of simple queries to train you in using these tables.

Let's start very simple. Try to find the the concept_name of concept_id = 313217 using the query below.

```
SELECT * 
FROM concept 
WHERE concept_id = 313217;
```

What is the correct answer?


*** =possible_answers

- Asthma
- [Atrial Fibrillation]
- Stroke
- Death

*** =hint

*** =feedbacks

- Check your query
- You did you first query against the Vocabulary!
- Check your query
- Check your query

