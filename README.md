# Data Scientist

#### Technical Skills: Python, SQL, C++, Tensorflow ML


## Education
- Statistics and Data Science, BS | University of California Santa Barbara (_June 2024_)

### Work Experience
**Data Automation Specialist - California Resources Corporation (_March 2023 - March 2024_)**
-	Lead the data analysis on company screw compressor systems, saving predictive maintenance costs upwards of $100,000 per compressor, per maintenance shutdown.
-	Industrial research in process control using LSTM inverse modeling/ parameter optimization.
-	Design and engineer databases for equipment network, populating reoccurring data sourced compressors that range in the hundreds.
-	Perform SQL querying for data projects and overall use, efficiently connecting to data visualization displays.
-	Build automation scripts using Python to maintain organizational efficiency.
-	Clean and manipulate raw data to automate freshwater reports for 4 plant sites across California.
-	Establish scalable automated processes to develop, validate and implement machine learning models with a validation loss around 1e-12 in prediction.
-	Backend SQL Data Integration for database consolidation companywide: business, field, and accounting data, along with the intermediary database conglomerate. 
-	Responsible for displaying industrial research findings to our data automation team for further actionable insight.

## Projects
### Screw Compressor Predictive Maintenance - Machine Learning Inverse Modeling Optimization
[Notebook](FULLPROJECT.ipynb)

Used **Python** to train an LSTM Deep Learning Machine Learning model on hourly time-series dependent Screw Compressor data in order to identify causation and correlation of machine decay via the values of the internal vibrations, measured by the vibrations of the bearings inside the compressor. Utilizing the trained model, I ran it through an optimization algorithm to attempt **Inverse Modeling** in order to find optimal values within the system of the compressor to minimize the compressor vibrations, prolonging the health and efficiency of the machinery. The inverse modeling technique takes into account the base threshold of production from the compressor, in order to weigh the pros and cons of operating capacity. This was a project in which I tackled alone in technical execution, however the project matter was given to me from our maintenance engineers, in which I proposed this technique of solving their problem. The model's prediction accuracy of the system was of RMSE:  5.363805283501357e-06 as well as MAE:  7.1338842932800275e-06. The optimization algorithm is still in the works of finalization.

![Time Series Comparison](/assets/ts_comparison.png)

