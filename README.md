# Jigsaw Datasets
The datasets folder contains the two datasets described in our paper -

1.) PandasEval1 - This dataset was collected by authors of the paper and consists of 68 entries  
2.) PandasEval2 - This dataset was collected in the form of a hackathon user study across two sessions differentiating tasks. Within each session we also have multiple sets with minor variations in tasks such as scalar and constant differences. Some tasks might be semantically different

It has 21 unique tasks, and for every task at most 5 variations because of the sets and with all natural language variations comprises of 725 entries.

Both of these jsons follow the structure as described below. 

* The outermost level contains key-value pairs with the unique task id. 
* For each task, we have key-value pairs for the various sets in the task. 
* For each set, we have 
    - a list of queries along with user-ids who wrote those queries 
    - one or more io examples. Each io example is a dict containing 
        + code snippet for inputs
        + code snippet for output 
        + corresponding names for inputs and outputs
    - one or more correct solutions

In case you use these datasets please cite our work as
```
@inproceedings{Jigsaw,
 author = {Jain, Naman and Vaidyanath, Skanda and Iyer, Arun and Natarajan, Nagarajan and Parthasarathy, Suresh and Rajamani, Sriram and Sharma, Rahul},
 title = {Jigsaw: Large Language Models meet Program Synthesis},
 booktitle = {ICSE 2022},
 location = {Pittsburgh, Pennsylvania},
}  
```