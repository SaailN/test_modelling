## topic modelling using various approaches

### Data cleaning
Steps:
- Extract and Merge files column wise
- Ignore all columns except QP/Job Role Name and final_pc
- Created and save in csv file
- remove stop words

### Tested topic modelling using classical NLP approcah: LDA
LDA was not able to get proper skillsets as it lagged logical meaning to the topics found

### Tested with LLM models
- Locally hosted a huge LLM model on GPU cluster and did instruction fine tuning on LLM to obtain skills from the context

### To do:
- Iterate through all the final_pc with unique job role to get skills
- Testing with all the context of data
- Cluster skills
- Find matrix of skills and job role
- Plotting both skill sets and job role

### Conclusion:
LLM was able to give better result for finding skill sets

