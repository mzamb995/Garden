---
{"dg-publish":true,"permalink":"/systematic-search-workshop/"}
---

#Busqueda #INCAN

[[Digital Guide to Reviews\|Digital Guide to Reviews]]

To carry out a systematic search in a comprehensive fashion we can think about the following blocks.


1. [[Search Modes\|Search Modes]]
2. [[Search Terms\|Search Terms]]
3. [[Search Operators\|Search Operators]]
4. [[Field Searches\|Field Searches]]
5. [[Special Operators\|Special Operators]] 
6. [[Search Filters\|Search Filters]]

These are our main tools that we can utilize to craft our systematic search strategy

The overall structure and checklist that we can utilize to do this is as follows: 

1. Concentrate on essential concepts
2. Compile [[Search Terms\|search terms]]
3. Divide the search
4. Capture different word forms
5. Connect similar terms
6. Define logical sets
7. Indicate phrases 
8. Indicate field searches
9. Bundle results and find the overlap
	1. Add a search filter (optional)
10. Review search results and revise strategy
#  Understanding Your Ideas

1. First, establish if you already have a pre-existing research question or you are trying to generate a specific question from a broad question (i.e. For patients with a history of heart attacks, is aspirin more effective than other antiplatelet aggregators in preventing further heart attacks?)
2. Once you have arrived at your research question it can help to break it down into concepts, typically you want 2 or 3 (not many more) distinct essential concepts.
	1. Problem (Heart Attacks)
	2. Patient 
	3. Intervention (Aspirin)
3. For each concept collect different terminology ( this can be from experts, by using other articles, from databases and many more)
	1. Including regular text words
	2. Controlled vocabulary (MeSH)

| Concept              | Text Words   | Controlled Vocabulary |
| -------------------- | ------------ | --------------------- |
| ==Problem==:Heart attack | `Heart attack`<br>`Heart attacks`<br>`myocardial infarct`<br>`myocardial infarcts`<br>`myocardial infarction`<br>`myocardial infarctions`<br>`MI`<br>`AMI`<br>`heart infarct`<br>`heart infarcts`<br>`heart infarction`<br>`heart infarctions`<br> | `myocardial infarction`                      |
| ==Intervention==: Aspirin                     | `aspirin`<br>`acetylsalicylic acid`<br>`acetyl salicylic acid`<br>`ASA`             | `aspirin`                      |

4. After we have our basic concepts and associated terms we need to develop a search structure using [[Search Operators\|boolean operators]]. 
	1. Continuous search statement
		1. (heart attack OR MI) AND (aspirin OR ASA)
	2. Divide the same continuous statement into smaller chunks
		1. heart attack OR MI
		2. aspirin OR ASA
		3. #1 AND #2
	3. The divided search is less convenient to use, but it is easier to revise, organize and to detect errors.
We can design a template strategy to help us carry this out in a systematic fashion
	1. Problem text word search
	2. Problem controlled vocabulary search
	3. Intervention text word search
	4. Intervention controlled vocabulary search
	5. Bundle the problem search results
	6. Bundle the intervention search results
	7. Find the overlap between the Problem and Intervention Results

In table format 

| #   | Terms                                                                                                                                                                                                                                          | Step                                          |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| 1   | `Heart attack`<br>`Heart attacks`<br>`myocardial infarct`<br>`myocardial infarcts`<br>`myocardial infarction`<br>`myocardial infarctions`<br>`MI`<br>`AMI`<br>`heart infarct`<br>`heart infarcts`<br>`heart infarction`<br>`heart infarctions` | Problem text word search                      |
| 2   | myocardial infarction                                                                                                                                                                                                                          | Problem controlled vocabulary search          |
| 3   | `aspirin`<br>`acetylsalicylic acid`<br>`acetyl salicylic acid`<br>`ASA`                                                                                                                                                                        | Intervention text word search                 |
| 4   | aspirin                                                                                                                                                                                                                                        | Intervention controlled vocabulary search     |
| 5   |                                                                                                                                                                                                                                                | Bundle problem search results                 |
| 6   |                                                                                                                                                                                                                                                | Bundle Intervention search results            |
| 7   |                                                                                                                                                                                                                                                | Find overlap between Problem and Intervention |


So far so good, we now have our template.
5. Now we can carry out a truncation search to see if we have missed anything or can simply our terms in our example search.
	1. we search: myocardial infarct* (in PubMed)
		1. myocardial infarct
		2. myocardial infarct**s**
		3. myocardial infarct**ion**
		4. myocardial infarct**ions**
		We have some terms in our original search strategy that be replaced with truncation, this is also benefical because it may include terms that we haven't 

| #   | Terms                                                                                     | Step                                          |
| --- | ----------------------------------------------------------------------------------------- | --------------------------------------------- |
| 1   | ==`Heart attack*`==<br>==`myocardial infarct*`==<br>`MI`<br>`AMI`<br>==`heart infarct`*== | Problem text word search                      |
| 2   | myocardial infarction                                                                     | Problem controlled vocabulary search          |
| 3   | `aspirin`<br>`acetylsalicylic acid`<br>`acetyl salicylic acid`<br>`ASA`                   | Intervention text word search                 |
| 4   | aspirin                                                                                   | Intervention controlled vocabulary search     |
| 5   |                                                                                           | Bundle problem search results                 |
| 6   |                                                                                           | Bundle Intervention search results            |
| 7   |                                                                                           | Find overlap between Problem and Intervention |

6. Now we want to connect similar terrms using the OR operator

| #   | Terms                                                                                                                                                                                                                                          | Step                     |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| 1   | `Heart attack*` ==OR==<br>`myocardial infarct*` ==OR==<br>`MI` ==OR==<br>`AMI` ==OR==<br>`heart infarct`* | Problem text word search |
| 2   | myocardial infarction                                                                                                                                                                                                                          | Problem controlled vocabulary search                         |
| 3   | `aspirin` ==OR==<br>`acetylsalicylic acid` ==OR==<br>`acetyl salicylic acid` ==OR==<br>`ASA`                                                                                                                                                                                                                                               | Intervention text word search                         |
| 4   | aspirin                                                                                                                                                                                                                                               | Intervention controlled vocabulary search                         |
| 5   |                                                                                                                                                                                                                                                | Bundle problem search results                         |
| 6   |                                                                                                                                                                                                                                                | Bundle Intervention search results                         |
| 7   |                                                                                                                                                                                                                                                | Find overlap between Problem and Intervention                         |

7. We would look for logical sets and enclose them in parentheses, since our search is simple and every single step is a distinct concept we do not need to to this, but here is an example of what could happen.

| #   | Terms                                                                                                                                                                                                                                          | Step                     |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| 1   | `Heart attack*` OR<br>`myocardial infarct*` OR<br>`MI` OR<br>`AMI` OR<br>`heart infarct`* ==OR (myocardium AND necrosis)==  | Problem text word search |
| 2   | myocardial infarction                                                                                                                                                                                                                          | Problem controlled vocabulary search                         |
| 3   | `aspirin` OR<br>`acetylsalicylic acid` OR<br>`acetyl salicylic acid` OR<br>`ASA`                                                                                                                                                                                                                                               | Intervention text word search                         |
| 4   | aspirin                                                                                                                                                                                                                                               | Intervention controlled vocabulary search                         |
| 5   |                                                                                                                                                                                                                                                | Bundle problem search results                         |
| 6   |                                                                                                                                                                                                                                                | Bundle Intervention search results                         |
| 7   |                                                                                                                                                                                                                                                | Find overlap between Problem and Intervention                         |
I would have to enclose this in parenthesis as the concept of  necrosis is distinct from the other concepts in the same search box.  

8. Now we will indicate phrases by using quotation marks that we want to look up precisely and that represent an individual concept and where we don't expect a word to be put in between them. 
	1. Note: single phrase terms do not need quotations (such as aspirin)

| #   | Terms                                                                                                                                                                                                                                          | Step                     |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| 1   | =="==`Heart attack*`=="== OR<br>=="==`myocardial infarct*`=="== OR<br>`MI` OR<br>`AMI` OR<br>=="==`heart infarct`*=="== | Problem text word search |
| 2   | =="==myocardial infarction=="==                                                                                                                                                                                                                          | Problem controlled vocabulary search                         |
| 3   | `aspirin` OR<br>=="==`acetylsalicylic acid`=="== OR<br>=="==`acetyl salicylic acid`=="== OR<br>`ASA`                                                                                                                                                                                                                                               | Intervention text word search                         |
| 4   | aspirin                                                                                                                                                                                                                                               | Intervention controlled vocabulary search                         |
| 5   |                                                                                                                                                                                                                                                | Bundle problem search results                         |
| 6   |                                                                                                                                                                                                                                                | Bundle Intervention search results                         |
| 7   |                                                                                                                                                                                                                                                | Find overlap between Problem and Intervention                         |

9. Now we need to add in [[Field Searches\|field searches]] to allow our search to be reproducible, as if we don't establish this then it's possible that the database we are searching in will add in it's own codes and we won't be able to understand this. 
	1. There are two options for non controlled vocabulary on PubMed
		1. We can search all text words with the tag [tw] at the end of our search term which will look in the title, abstract, MeSH terms and other fields for the term you specified. This is great for a broad search.
			1. e.g. heart[tw]
		2. If we want to be more specific, we can just look in the title and abstract with the tag: [tiab] , this will run a narrower search
			1. e.g. heart[tiab]
	2. For controlled vocabulary there is only one option: [mh] 
		1. This will search the MeSH term field
			1. e.g heart[mh]

Let's see what this looks like in our example starting with a broad search


| #   | Terms                                                                                                                                                                                                                                          | Step                     |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| 1   | "`Heart attack*`"==[tw]== OR<br>"`myocardial infarct*`"==[tw]== OR<br>`MI`==[tw]== OR<br>`AMI`==[tw]== OR<br>"`heart infarct*`"==[tw]== | Problem text word search |
| 2   | "myocardial infarction"==[mh]==                                                                                                                                                                                                                          | Problem controlled vocabulary search                         |
| 3   | `aspirin`==[tw]== OR<br>"`acetylsalicylic acid`"==[tw]== OR<br>"`acetyl salicylic acid`" ==[tw]==OR<br>`ASA`==[tw]==                                                                                                                                                                                                                                               | Intervention text word search                         |
| 4   | aspirin==[mh]==                                                                                                                                                                                                                                               | Intervention controlled vocabulary search                         |
| 5   |                                                                                                                                                                                                                                                | Bundle problem search results                         |
| 6   |                                                                                                                                                                                                                                                | Bundle Intervention search results                         |
| 7   |                                                                                                                                                                                                                                                | Find overlap between Problem and Intervention                         |

10. We are almost there! Now we need to bundle results by concept
	1. First we will bundle the words for the problem (in our example, myocardial infarction)
	2. Then we will bundle the intervention search results
	3. Then we will look to find the overlap, or those publications that really interest us
Here is what looks like in a practical application, I promise it's not too bad

| # | Terms | Step |
| ---- | ---- | ---- |
| 1 | "`Heart attack*`"[tw] OR<br>"`myocardial infarct*`"[tw] OR<br>`MI`[tw] OR<br>`AMI`[tw] OR<br>"`heart infarct*`"[tw] | Problem text word search |
| 2 | "myocardial infarction"[mh] | Problem controlled vocabulary search |
| 3 | `aspirin`[tw] OR<br>"`acetylsalicylic acid`"[tw] OR<br>"`acetyl salicylic acid`" [tw]OR<br>`ASA`[tw] | Intervention text word search |
| 4 | aspirin[mh] | Intervention controlled vocabulary search |
| 5 | ==#1 OR #2== | Bundle problem search results |
| 6 | ==#3 OR #4== | Bundle Intervention search results |
| 7 | ==#5 AND #6== | Find overlap between Problem and Intervention |

This will work in PubMed, the # symbol can call upon our previous searches and combine them to give us our overlap easily.

11. This is an optional step, we can apply a [[Search Filters\|search filter]] sometimes this will not give us any new information, for the sake of this example we will utilize it 
	1. In this example we will use the Randomized controlled trial filter which can be found in this [[Search Filters\|note]] .
	What does this look like? Let's take a quick look! 
		NOTE: pt stands for publication type and sh for Subject heading! The original source is [here](https://sites.google.com/a/york.ac.uk/issg-search-filters-resource/home/rcts?authuser=0)


| # | Terms | Step |
| ---- | ---- | ---- |
| 1 | "`Heart attack*`"[tw] OR<br>"`myocardial infarct*`"[tw] OR<br>`MI`[tw] OR<br>`AMI`[tw] OR<br>"`heart infarct*`"[tw] | Problem text word search |
| 2 | "myocardial infarction"[mh] | Problem controlled vocabulary search |
| 3 | `aspirin`[tw] OR<br>"`acetylsalicylic acid`"[tw] OR<br>"`acetyl salicylic acid`" [tw]OR<br>`ASA`[tw] | Intervention text word search |
| 4 | aspirin[mh] | Intervention controlled vocabulary search |
| 5 | #1 OR #2 | Bundle problem search results |
| 6 | #3 OR #4 | Bundle Intervention search results |
| 7 | ==#5 AND #6== | Find overlap between Problem and Intervention |
| 8 | "randomized controlled trial"[pt] | Filter |
| 9 | "controlled clinical trial"[pt] | Filter |
| 10 | randomized[tiab] | Filter |
| 11 | placebo[tiab] | Filter |
| 12 | "drug therapy"[sh] | Filter |
| 13 | randomly[tiab] | Filter |
| 14 | trial[tiab] | Filter |
| 15 | groups[tiab] | Filter |
| 16 | #8 OR #9 OR #10 OR #11 OR #12 OR #13 OR #14 OR #15 | Filter |
| 17 | animals[mh] NOT humans[mh] | Filter |
| 18 | ==#16 NOT #17== | Filter |
| 19 | ==#7 AND #18== | Combining Filter with previous search |
We did it! We have developed a draft search strategy that will limit our search to RCTs

It is usually recommended that you first run the strategy without any filters, if there is a massive amount of literature that will prove unwieldy then a filter can be applied. 

12. Finally, we would run the search on the [Advanced search](https://pubmed.ncbi.nlm.nih.gov/advanced/) of the PubMed search engine line by line, and review and revise the search
	1. Are there any error messages? 
	2. Are we getting any terms that return 0 results?
	3. Is it too narrow or too broad?
		1. If it is too broad, we can use more specific terms, additional concepts or apply a filter
		2. If it is too narrow we need to find synonyms that are broader, remove words, remove filters.  
	4. If you already have a benchmark study that is relevant to your question, you should be able to find it with the search strategy, if not, then it should be modified until you are able to do so. 
	5. As with anything, peer reviewing the search strategy and revision of it is key to a healthy systematic review. 


[[Digital Guide to Reviews\|Back To Home]]