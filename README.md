*************************************************
LLM Peers Data -- Overview
The LLM identified peers data is based on the firm pairwise peers identified by Cao, Chen, Tucker and Wan (2025). This uploaded dataset is based on the data processed using Gemini-2.0 flash model,
for sample period of Compustat firms from 1981 to 2023. Please refer to Cao et al. (2025) for an extensive discussion of the measure, and details of the process to generate the pairwise peer data. In this 

****** NOTE: Please read the technical descriptions below before using the data.  
THis dataset includes below variables:

gvkey1 -- focal firm's Compustat identifier
gvkey2 -- peer firm's Compustat identifier
year -- the years which gvkey1 and gvkey2 are identified as peers by the LLM
llmpeer -- number of peers for the focal firm-year
llmrank -- the rank of the peer provided by the LLM, captures the closeness of focal firm and its peer firm in the product market

********************************************** Citations *****************************************************
Please cite the following study when using the LLM peers data:

Cao, Yi, L. Chen, J. W. Tucker, and C. Wan. 2025. Can generative AI help identify peer firms? Review of Accounting Studies, Forthcoming. 
