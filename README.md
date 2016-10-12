# flossR
Should we floss?
Recent synthetic evidence suggests we do not need to do floss!

Data from:Sambunjak D, Nickerson JW, Poklepovic T, et al. Flossing for the management of periodontal diseases and dental caries in adults. Cochrane Database Syst Rev 2011(12):CD008829.

The effect sizes calculated by authors from primary research studies are provided in the 'effect.size' csv file.

The data from individual studies used provided in 'means' csv file.

Note: lower scores of GI and plaque are better (i.e. you have less gingivitis and less plaque). Thus, more negative values are positive, i.e. reductions in negative outcomes. Contrasts are structured around flossing + brushing versus brushing only.

Questions.
1. Does flossing reduce likelihood of gingivities or plaque build up?
2. Does number of participants within a given study influence the outcome/variation/strength of effect?
3. Is the length of study important?
4. Does how you floss influence outcomes?

Hint: Either use metafor package OR more interestingly using bootstrap/resampling to explore these questions.
