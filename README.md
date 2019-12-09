# autism
data used for the production of "Word up: experiential and neurocognitive evidence for associations between autistic symptomology and a preference for thinking in the form of words"

This readme outlines the variables used in the analysis (those which are not self-explanatory)

RIDNO: ID number used for the study.
QD_AQ_SOCIAL: social subscale of the autism quotient
QD_AQ_SWITCH: task switching subscale of the autism quotient
QD_AD_DETAIL: attention to detail subscale of the autism quotient
QD_AD_COMM: communication subscale of the autism quotient
QD_AD_IM: imagination subscale of the autism quotient

no_outliers versions have had outliers replaced with the median (see paper for details)

PC[1-4]_[0-1]: average scores for the PCA components in each task
the first number refers to the component, the second to the task
mean_PC[1-4]: average scores for the PCA components across both tasks
PC[1-4]_diff: difference between the two tasks (0-back - 1-back)
component 1: detailed thought
component 2: off-task thought
component 3: modality of thought
component 4: emotion of thought
task 0: 0-back
task 1: 1-back

outliers have been removed from these prior to this datasheet

MWQ_WM.ACC: accuracy in the 1-back
MWQ_WM.RT: reaction time in the 1-back
MWQ_CRT.ACC: accuracy in the 0-back
MWQ_CRT.RT: reaction time in the 0-back

inverse_efficiency_WM: IES (RT/accuracy) in the 1-back
inverse_efficiency_CRT: IES in the 0-back

AQ_total: total AQ score (sum of the five subscales)

AQ_total_cluster261068_connectivity: mean connectivity score from the model including the AQ total
from the seed in the lingual gyrus to the right motor cortex
AQ_total_cluster441038_connectivity: mean connectivity score from the model including the AQ total
from the seed in the lingual gyrus to the left motor cortex
mean_of_AQ_total_clusters: mean of these two scores

CT_SOCIAL_thickness_score: thickness of the lingual gyrus region identified as related to the
social subscale of the autism quotient 

AQ_social_seed_AQ_im_cluster_12_40_26_31_connectivity: mean connectivity score for the model
including the five subscales of the AQ for the region of vMPFC identified as related to the 
imagination subscale of the autism quotient
AQ_social_seed_AQ_im_cluster_12_32_54_31_connectivity: mean connectivity score for the model
including the five subscales of the AQ for the region of mSPL identified as related to the 
imagination subscale of the autism quotient

Zmean_PC3_[high/low]cluster441038: modality score for high and low connectivity groups 
calculated by median split using connectivity from left LG to left motor cortex

