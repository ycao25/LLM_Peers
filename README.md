*************************************************
LLM Peers Data -- Overview:
The LLM identified peers data are produced by Cao, Chen, Tucker and Wan (2025). There are two datasets in this project: llm_peers_bard_2025.7z is the zip file of the dataset based on Bard chat-bison-001 version and collected in July 2023. This is the main dataset for Cao, Chen, Tucker and Wan (2025). llm_peers_2025.7z is the zip file of the dataset based on Gemini-2.0 flash model, for sample period of Compustat firms from fiscal year 1981 to 2023. Please refer to Cao et al. (2025) for an extensive discussion of the measure, and details of the process to generate the pairwise peer data.  

****** NOTE: Please read the technical descriptions below before using the data.  
These datasets include below variables:

gvkey1 -- focal firm's Compustat identifier;
gvkey2 -- peer firm's Compustat identifier;
year -- the years for which gvkey1 and gvkey2 are identified as peers by the LLM;
llmpeer -- number of LLM peers for the focal firm-year;
llmrank -- the rank of the peer provided by the LLM, capturing the closeness of focal firm and its peer firm in the product market

********************************************** Citations *****************************************************
Please cite the following study when using the LLM peers data:

Cao, Yi, L. Chen, J. W. Tucker, and C. Wan. 2025. Can generative AI help identify peer firms? Review of Accounting Studies, Forthcoming. 
