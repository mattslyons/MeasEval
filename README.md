### Welcome to MeasEval: Counts and Measurements!

Counts and measurements are an important part of scientific discourse. It is relatively easy to find measurements in text, but a bare measurement like 17 mg is not informative. However, relatively little attention has been given to parsing and extracting these important semantic relations. This is challenging because the way scientists write can be ambiguous and inconsistent, and the location of this information relative to the measurement can vary greatly.

MeasEval is a new entity and semantic relation extraction task focused on finding counts and measurements, attributes of these quantities, and additional information including measured entities, properties, and measurement contexts.

For more details and to participate, head over to our CodaLab pages:
[https://competitions.codalab.org/competitions/25770](https://competitions.codalab.org/competitions/25770)

### Summary

Abstract: SemEval 2021 Task 8: MeasEval: Counts and Measurements aimed to generate research on the contextual extraction of counts and measurements in order to introduce a system of measurement extraction that identified entities while preserving semantic relationships. MeasEval included five subtasks ranging from straightforward quantity extraction to more complicated qualifier extractions. Because these tasks primarily concern scientific texts, we completed several MeasEval tasks using base RoBERTa as our baseline, and cs_roberta_base and biomed_roberta_base as competitor models, hypothesizing that the domain-adapted pretrained (DAPT) RoBERTa models, especially the model trained on biomedical texts, would yield improved performance. We demonstrate that DAPT models offer improvement over non-DAPT models even when unique labeled training tokens are repeated as few as two or three times within a domain.

The primary code, including preprocessing, pipeline, and model building, are contained [here](https://github.com/sams-data/MeasEval/blob/main/baselines/batch_doc_pipeline.ipynb).

The final paper (ACL format) is located [here](https://github.com/sams-data/MeasEval/blob/main/Stephens%20Shen%20Lyons%20Final%20Paper%20DataSci%20266.pdf).
