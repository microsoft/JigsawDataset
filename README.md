This zip file contains the two datasets described in our paper -- 

1.) PandasEval1 - This dataset was collected by authors of the paper and consists of 68 entries  
2.) PandasEval2 - This dataset was collected in the form of a hackathon user study across two sessions differentiating tasks. Within each session we also have multiple sets with minor variations in tasks such as scalar and constant differences. Some tasks might be semantically different

It has 21 unique tasks, and for every task at most 5 variations because of the sets and with all natural language variations comprises of 725 entries.

For both these jsons we follow the structure as described below. 

* The outer level contains key-value pairs with unique task id. 
* For each task, we have key-value pairs for the sets in the task. 
* For each set, we have 
    - a list of queries along with user-ids who wrote those queries 
    - one or more io examples. Each io example contains 
        + code for inputs
        + code for output 
        + corresponding names for inputs and outputs
    - one or more correct solutions

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
