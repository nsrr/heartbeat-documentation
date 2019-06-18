# Dataset introduction

The [HeartBEAT dataset](:files_path:/datasets) posted on the NSRR has gone through various post-processing steps in order to prepare the data for more widespread sharing. Changes and updates to the source data and have been coordinated in the [heartbeat-data-dictionary repository](https://github.com/nsrr/heartbeat-data-dictionary).

**Disclaimer:** These data are not perfect. Known implausible or impossible values have been tracked and documented in our [KNOWNISSUES list](https://github.com/nsrr/heartbeat-data-dictionary/blob/master/KNOWNISSUES.md). Please [submit issues](https://github.com/nsrr/heartbeat-data-dictionary/issues) for any new problematic findings.

## Structure of the dataset

The dataset is broken down into `baseline` and `final` (i.e. follow-up) files, containing 318 and 301 records, respectively. Participants who withdrew post-randomization (n=17) will not have a record in the `final` dataset.

## Explanation of treatment arms

Each HeartBEAT subject was randomized to one of three treatment arms. The assigned arm is represented by the [treatmentarm](https://sleepdata.org/datasets/heartbeat/variables/treatmentarm) variable. The meanings of the arms are as follows:

1. HLSE (Healthy Lifestyles and Sleep Education - control arm)
2. HLSE-O (Healthy Lifestyles and Sleep Education + (supplemental nocturnal) Oxygen - oxygen arm)
3. HLSE-P (Healthy Lifestyles and Sleep Education + Positive airway pressure treatment - CPAP arm)

## Data collection forms

The NSRR provides [original data collection forms as PDFs](:files_path:/forms). Many [variables link to these forms](:datasets_path:/heartbeat/variables) to give users a better idea about the origins of the underlying data.

The forms are included here for historical purposes only and are not intended for use in prospective studies. If you wish to use these forms, please check existing copyrights and regulations beforehand.

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
