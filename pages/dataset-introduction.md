# Dataset Introduction

The [HeartBEAT dataset](:files_path:/datasets) posted on the NSRR has gone through various post-processing steps in order to prepare the data for more widespread sharing. Changes and updates to the source data and have been coordinated in the [heartbeat-data-dictionary repository](https://github.com/sleepepi/heartbeat-data-dictionary).

**Disclaimer:** These data are not perfect. Known implausible or impossible values have been tracked and documented in our [KNOWNISSUES list](https://github.com/sleepepi/heartbeat-data-dictionary/blob/master/KNOWNISSUES.md). Please [submit issues](https://github.com/sleepepi/heartbeat-data-dictionary/issues) for any new problematic findings.

## Structure of the Dataset

The dataset is broken down into `baseline` and `final` (i.e. follow-up) files, containing 318 and 301 records, respectively. Participants who withdrew post-randomization (n=17) will not have a record in the `final` dataset.

## Explanation of treatment arms

Each HeartBEAT subject was randomized to one of three treatment arms. The assigned arm is represented by the [treatmentarm](https://sleepdata.org/datasets/heartbeat/variables/treatmentarm) variable. The meanings of the arms are as follows:

1. HLSE (Healthy Lifestyles and Sleep Education - control arm)
2. HLSE-O (Healthy Lifestyles and Sleep Education + (supplemental nocturnal) Oxygen - oxygen arm)
3. HLSE-P (Healthy Lifestyles and Sleep Education + Positive airway pressure treatment - CPAP arm)

If you have additional questions about the HeartBEAT dataset, please contact <a href="mailto:support@sleepdata.org">support@sleepdata.org</a>.
