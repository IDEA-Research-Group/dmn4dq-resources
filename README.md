# DMN4DQ Resources

* datasets: `filtered-aws-ec2-data.csv` (can be downloaded from http://tiny.cc/filtered-aws-ec2-data) is a dataset from https://www.kaggle.com/akashsarda/aws-ec2-pricing-data/version/1 containing data about AWS Pricing Data. `aws-mini.csv` and `aws-mini.json`  are small chunks from that dataset.
* models:
  * `dmn4dq-v7.dmn` is a DMN to evaluate the quality of the datasets `filtered-aws-ec2-data` or `aws-mini` by following the DMN4DQ methodology.
  * `setCorrectiveActions.json` is a JSON file containing the definition of a set of corrective actions in accordance to the DMN4DQ+ methodology. It is tied to the DMN model `dmn4dq-v7.dmn` and its related datasets.
  * `dmn4dq.bpm` is a BPM model intended to facilitate the evaluation and reparation of individual JSON data records.

