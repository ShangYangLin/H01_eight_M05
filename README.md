# H01_eight_M05
Using artificial intelligence and medical health big data to reverse the medical care and management of chronic diseases project (NSTC 110－2634－F－002－049), sub-plan8, model5

This model was built by Shang-Yang Lin and upload in August 4 2023 (Research Center of Sleep Medicine, TAIPEI MEDICAL UNIVERSITY)

Background: CPAP is the mainstay of medical treatment for OSA and involves the use of a pump to deliver air into the nose or mouth via a mask during sleep. However, poor compliance was a critical problem (reports shows only 30–60%.)

Objective: Built AI model by using HRV indexes derived from EKG signal of CPAP titration ongoning helps physicians and clinical health care personnels to identify patient with good compliance.

Methods: The good compliance patient was fulfill the criteria for “regular use” (defined as 4 hours use on 70% of days) for at least one year, while the poors was defined as refusing any treatment for at least 4 months after CPAP titration (both group were suffer by severe OSA). We derived the HRV indexes (RMSSD, SDNN, PNN50, HF, LF, VLF, LF/HF Ratio, VLF/Total Power) every five minutes. 

Results: The missing values of HRV data was imputed and then the whole dataset was standardized. A neural networks (deep learning) model shows 75% in accuracy after hyperparameter optimization. We humblely upload the framework of our model and weight of neurons, and looking forward all type of cooperation and feedback.

Keywords: Obstructive sleep apnea (OSA), Continuous Positive Airway Pressure (CPAP), Heart rate variability (HRV), Deep learning (DL),  Treatment compliance
