# FemaleAgencyTamerTaming
Computational Linguistics to Assess Female Agency in The Taming of the Shrew and Tamer
Copy_of_BeccaCohen_2 contains code for creating the Tamer Tamed dataframe
Creatingtamingdatasetattempt 2 contains code for creating the Taming dataframe
powerframes contains the code for lemmatizing the dataframes, and iterating/matching verbs in the connotation frames to each line of the play to get the power and agency scores
TamerTamedlinecounts contains code for getting word counts,line counts, verb counts in order to normalize the data
TamerTamedAnalysisNormalized and TamerTamedAnalysisRawCounts contain the non-spacy original analytics
The above analytics for Tamer Tamed are included within analytics_for_taming_act_bd (act_bd refers to the addition of act breakdowns since they were not originally easy to incoporate and I went back and added them later)
tamingwpunc, TamerTamedwpunctuation and tamertamedwpunc2 contain code for adding punctuation back in to split up the text by sentences, since originally punctuation was removed, and sentences could not be seperated well enough to determine the subject of a single sentence\
SPACYwithsentences_Taming and SPACYwithsentencestamertamed contain the above analysis steps, but repeated with spacy to pull out the subjects per sentence instead of per speaker line (as it was earlier)
analytics_for_tamer_withSPACY and analytics_for_tamer_with_act_bd contain the final analytics, and some of the most important graphs used in the final thesis paper
