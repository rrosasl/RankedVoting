# Context
This code is to use a survey from Google Forms for rank-voting
The concept is that people can put their preferences as a ranking, and through various rounds, if their prefered candidate is not chosen, their vote goes to their next alternative

**Input**: Google spreadsheet generated by Google Chrome

**Process**: Iterative process (loop), in each round:
+ A candidate is eliminated 
+ Their vote goes to their next preference
+ Repeat

**Output**:
+ DataFrame with vote evolution
+ Sankey Diagram showing election

