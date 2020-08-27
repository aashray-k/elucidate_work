Notebook Guide:
	Stage 1- Feature creation and data cleaning. walks through our steps in creating features to capture 
		 transaction frequency, consistency, and size and to identify the presence of wage or salary
		 string in pattern; this also shows how we dealt with missing values
	
	Stage 2- Comparison of approaches and model selection. A comparison of the NLP only, NLP+ features, and
		 features only approaches to identify the best model and approach, followed by hyperparameter tuning
		 to obtain the final model.
	Stage 3- Final cross-validation and custom accuracy metric. A final cross validation applid to all of our
		 data using the best model after hyperparameter tuning to derive an estimate for our overall 
		 accuracy (per consumer, as defined by the client)
	Supplement- Visualizations. an interactive widget that shows the distributions of salaries across different
		    treatment and control conditions for each of our features using barplots.

Fasttext Modeling:
	- transactions_repmodel.bin: the fasttext model trained on the entire corpus of patterns

Note:
	CSV files mentioned in the data have been removed as per stipulations of the non-disclosure agreement