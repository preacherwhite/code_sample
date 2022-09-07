# code_sample
This is a code sample from my main research project in lab. The main function of this script is to utilize neuron-prediciting CNNs (already trained)
and systematically running other analyzing codes while aggregating the results into neat organized folders. a total of 6 V1 neuron sites are examined, and 10 trained networks
were analyzed for each site, varying based on the amount of training samples they used. The analysis mainly consists of plotting tuning curves, getting top response images out of the validation set, getting top response artificial images using the model, and visualiztion results for each neuron in each model.

The dependencies of the file can be checked in the full repository of the project https://github.com/leelabcnbc/CNN_Tang_project, under the scripts/ folder. 
However the code would not run, given that the data (gigabites of numpy files) is quite large and not stored on github. Nevertheless you can check the files used for training and data analysis in that repository
