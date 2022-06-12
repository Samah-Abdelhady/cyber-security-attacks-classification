# Static and dynamic attacks classification:
### The project is 2 parts:
* Binary classification between (attack or normal) data.
* Multi classification between (normal and 10 types of different attacks).
### The (binary and multi) classifications are done with 2 methods:
1- The static method: means that train the used model only once part of the data, then
use it to predict the test data (all data are already exist).

2- The dynamic method: means that train the model with the already exist data, and use
the model to predict another part of the coming data (flow of data from Kafka server).
After reading a specific number of the flow of data, replace the old train data with the
new once and retrain the model on them. And so on.

3- Finally, compare between the performances of the model in the both cases.

### You will find more details and the results in the report.pdf
