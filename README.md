# pubmed searches for mutltisensory research

Used the following queries on [pubmed](https://pubmed.ncbi.nlm.nih.gov/) to get the results for the timeline.

Pubmed allows you to download the results as a csv file.

## non vision query

```
((sensory[Title/Abstract]) AND ( processing[Title/Abstract]) AND ( (auditory[Title/Abstract]) OR (touch[Title/Abstract]) OR (olfaction[Title/Abstract]) OR (multisensory[Title/Abstract]) OR (proprioception[Title/Abstract]) ) ) NOT (vision[Title/Abstract])
```

resulting csv: PubMed_Timeline_Results_by_Year-non_vision.csv

## vision query

```
(sensory[Title/Abstract]) AND ( processing[Title/Abstract]) AND (vision[Title/Abstract]) 
```