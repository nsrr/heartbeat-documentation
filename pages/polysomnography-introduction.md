# Polysomnography introduction

Enrolled subjects underwent home sleep testing with the Embletta Gold portable monitor (Embla Systems, Broomfield, CO) to determine the presence of obstructive sleep apnea. Randomized subjects had the study repeated after 12 weeks of intervention while using the assigned therapy. Subjects wore the device for a single night in their own homes and returned the device by express mail or courier service. The montage collected included airflow measured by both a nasal cannula-pressure transducer system and a thermal sensor, thoracic and abdominal movement by inductance plethysmography, finger pulse oximetry, body position, and a 3-lead electrocardiogram. Data were downloaded at the local sites and transferred to a central Sleep Reading Center at Brigham and Women's Hospital for scoring by a single certified scorer. For the baseline examination, respiratory events were scored in accordance with American Academy of Sleep Medicine guidelines.

Apneas were defined as a >90% decrease from baseline in flow as measured by the thermal sensor, lasting at least 10 seconds, and were classified as central if there was no respiratory effort noted on plethysmography bands, and as obstructive if respiratory effort was present during the apnea. Hypopneas were defined as a >50% decrease from baseline in flow as measured by the nasal cannula-pressure transducer or thermal sensor, associated with at least a 3% fall in oxyhemoglobin saturation. The nasal cannula-pressure transducer system was used as the primary signal for identification of hypopneas, with the thermal sensor as an alternative sensor if the nasal cannula signal was missing.

While home sleep testing is an accepted modality for diagnosis of obstructive sleep apnea, the lack of electroencephalographic measures of sleep and arousal will result in false-negative studies in individuals whose respiratory events are accompanied by arousal but not desaturation, or who spend a large portion of the recording awake (underestimating the frequency of events by including awake time in the denominator). Although this is of considerable clinical diagnostic importance, it does not affect the validity of the study results, since the resultant underestimation of sleep apnea severity will not lead to inclusion in the study of subjects without sleep apnea; however, some caution must be taken in extrapolating to individuals with obstructive sleep apnea whose hypopneas are not accompanied by desaturation. Moreover, the lack of sleep measures does limit our ability to evaluate potential mediation of the CPAP effect on blood pressure by changes in arousal frequency or other sleep quality measures. ([Source](http://www.nejm.org/doi/full/10.1056/NEJMoa1306766#t=article))

Notes:

- [Montage and Sampling Rate Information](:pages_path:/equipment/montage-and-sampling-rate-information.md)
- [Embletta Scoring Procedures](:pages_path:/manuals/embletta-scoring-procedures)

## Signal and annotation files

[Raw polysomnography data](:files_path:/) is available for 317 randomized participants at baseline and 274 at followup. Each recording has a signal file (.EDF) and event scoring (.XML).

1. **[EDF](:files_path:/polysomnography/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from RemLogic.
2. **[XML (NSRR)](:files_path:/polysomnography/annotations-events-nsrr)** - Annotation files processed in the [EDF Editor and Translator](https://www.sleepdata.org/tools/edf-editor-and-translator) tool.

NSRR XML files can be overlaid onto EDF signal files using the [EDF Viewer tool](https://sleepdata.org/community/tools/nsrr-edf-viewer). For more information about the XML translation (mapping) process, review the files available on the [EDF Editor and Translator Releases page](https://github.com/nsrr/edf-editor-translator/releases).

## Known issues

- Subset of physical dimensions use invalid ASCII character (°) (traces back to source data from device download)
- Four (4) EDF files are invalid based on a filesize inconsistency (traces back to source data from device download)
  - `baseline`: 700205, 700266, 200288
  - `followup`: 700111

## History / changelog

*December 7, 2016*
- EDF recording dates changed from "00.00.00" to "01.01.85"

*August 2014*
- Polysomnography data uploaded to sleepdata.org

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
