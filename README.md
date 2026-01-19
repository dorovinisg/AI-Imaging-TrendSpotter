# AI Imaging TrendSpotter

Building AI course project

## Summary
AI system for medical imaging classification and detection that supports early identification of trends in lung diseases such as pneumonia and lung cancer. The project focuses on assisting clinicians and monitoring aggregated patterns over time.

## Background

Medical imaging is produced in huge volumes and early findings can be missed. The idea aims to:

* support faster diagnosis  
* reduce workload of radiologists  
* detect unusual increases of cases  
* improve patient outcomes  

The motivation is to create an assistant tool, not to replace doctors but to help them prioritize and recognize patterns earlier.

## How is it used?

The system would be used in hospitals:

1. Image (X-ray/CT) is analyzed  
2. Model returns probability and highlighted regions  
3. Doctor reviews result  
4. Aggregated results are monitored for trends

(https://upload.wikimedia.org/wikipedia/commons/3/3b/Chest_Xray_PA_3-8-2010.png)

## Data sources and AI methods

* Public chest X-ray / CT datasets  
* CNN or Vision Transformer models  
* Transfer learning  
* Classification and detection  
* Time-series monitoring


def analyze(image):
prediction = model(image)
return prediction



## Challenges

* Data quality and bias  
* False positives/negatives  
* Privacy and GDPR  
* Explainability  
* Not a medical diagnosis

## What next?

* Build prototype  
* Validate with experts  
* Add dashboard  
* Clinical pilot

## Acknowledgments

Building AI – University of Helsinki & Reaktor  
Open source AI libraries and public datasets


