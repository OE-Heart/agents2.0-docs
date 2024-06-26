📈 Evaluation
=====================

Brief Introduction
------------------

The evaluation module is used to evaluate the performance of the model. It includes the following classes:

- Case: The Case class is used to store the information of a case, including the case ID, case name, task ID, task description, function IDs, KB ID, input, ground truth, result, trajectory, dataset evaluation, loss, and SOP suggestion.
- CaseLoss: The CaseLoss class is used to record the loss information of a case. It functions similarly to a dictionary, but is written as a class for convenience.
- DatasetEvaluation: The DatasetEvaluation class is used to record the evaluation results of a dataset. It functions similarly to a dictionary, but is written as a class for convenience.
- SOPSuggestion: The SOPSuggestion class is used to record the suggestion information for SOP. It functions similarly to a dictionary, but is written as a class for convenience.

.. toctree::

   case