# ostracism

Repository related to the research on the detection of ostracism, from the point of view of computational linguistics. 


The file corpus.csv (14200 x 8) contains the full dataset. 
Here a brief explanation of each column:
- comm: text of the reaction addressed to the target moderator; 
- aut: author of the reaction;	
- date: date of composition (UTC);	
- score: score per each reaction;	
- is_mod: wether or not the author of the reaction is a moderator;	
- label: 0 for popular moderators, 1 for ostracised ones;	
- karma: Reddit karma per each comment;	
- is_gold: whether or not the author of the reaction has a gold account.
