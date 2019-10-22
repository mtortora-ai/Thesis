# Bachelor's Thesis
This thesis presents a system to automatically detect relevant interventions of the Italian National Fire Corps (Corpo nazionale dei vigili del fuoco). This is the institutional agency for fire and rescue service and it is part of the Ministry of the Interior, Department of Firefighters, Public Rescue and Civil Protection (Dipartimento dei Vigili del Fuoco, del Soccorso Pubblico e della Difesa Civile). This system will be useful to firefighters to automatically report relevant interventions to competent authorities.
To this aim, the national firefighters Corps provided us with two databases. The first one contains a complete description of the operations that took place in the provinces of Milan, Naples, Rome and Turin during the 2016, and in the case of Rome’s province the dataset also has the interventions from January 2017 up to June 2017. The second dataset contains the SMS messages sent to report a relevant intervention. This information was used in the labelling process to mark the samples of the first database as relevant or not relevant. We built a new representation of our samples extracting several features, such as the number of updates and the overall duration of an operation, the statistical description of the geographic characteristics of the territory (from Istat databases) and information about the venue where the intervention took place. For this latter attribute we built a satellite image classifier able to distinguish between agricultural, industrial and urban area. This last feature was one of the most important descriptors selected by CBFS method, which computes the clearness of features expressing separability among classes in a feature. With this best set of descriptors, we trained different supervised Machine Learning algorithms to predict the label of the interventions, choosing the best suited for our problem. The results show that the proposed approach can detect relevant interventions, but the error rate achieved as well as the consequent results analysis suggest that the real nature of the problem and the categorical features engineered could affect the recognition rate. The results and the specific knowledge collected on the issues suggest that further investigations
can be directed towards models based on finite-state machines.
