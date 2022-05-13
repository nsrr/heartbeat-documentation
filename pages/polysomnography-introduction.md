# Polysomnography introduction

Enrolled subjects underwent home sleep testing with the Embletta Gold portable monitor (Embla Systems, Broomfield, CO) to determine the presence of obstructive sleep apnea. Randomized subjects had the study repeated after 12 weeks of intervention while using the assigned therapy. Subjects wore the device for a single night in their own homes and returned the device by express mail or courier service. The montage collected included airflow measured by both a nasal cannula-pressure transducer system and a thermal sensor, thoracic and abdominal movement by inductance plethysmography, finger pulse oximetry, body position, and a 3-lead electrocardiogram. Data were downloaded at the local sites and transferred to a central Sleep Reading Center at Brigham and Women's Hospital for scoring by a single certified scorer. For the baseline examination, respiratory events were scored in accordance with American Academy of Sleep Medicine guidelines.

Apneas were defined as a >90% decrease from baseline in flow as measured by the thermal sensor, lasting at least 10 seconds, and were classified as central if there was no respiratory effort noted on plethysmography bands, and as obstructive if respiratory effort was present during the apnea. Hypopneas were defined as a >50% decrease from baseline in flow as measured by the nasal cannula-pressure transducer or thermal sensor, associated with at least a 3% fall in oxyhemoglobin saturation. The nasal cannula-pressure transducer system was used as the primary signal for identification of hypopneas, with the thermal sensor as an alternative sensor if the nasal cannula signal was missing.

As of May 13, 2022, we have replaced the AHI in NSRR with the AHI used to determine eligibility (referred to as [ahi_screening](https://sleepdata.org/datasets/heartbeat/variables/ahi_screening)). Scoring was based on an adaptation of the AASM 2007 alternative hypopnea criteria which included all apneas plus hypopneas with >= 50% reduction in amplitude in the nasal pressure or sum respiratory inductance channel.  Prior to this change, the variable ([aphypi](https://sleepdata.org/datasets/heartbeat/variables/aphypi)) was derived from a second pass of scoring done specifically to allow a comparison of the total number of respiratory events identified in those studies before and after study intervention. Since one arm of the trial included oxygen, the post-treatment studies for those participants would have been performed on oxygen and without a nasal cannula. Therefore, second pass studies did not distinguish apneas from hypopneas (all defaulted to hypopneas) and included two types of hypopneas, each with a 50% or more reduction in effort by respiratory bands: one with the a >= 3% desaturation and one without. In essence, this AHI reflects the Chicago 1999 criteria, but was done to identify events where oxygen desaturation may be blunted with use of oxygen. The summary metric ([aphypi](https://sleepdata.org/datasets/heartbeat/variables/aphypi)) of these combined events is labeled Respiratory Event Index. See the [HeartBEAT HSAT Scoring Manual](:files_path:/documentation/HeartBEAT_HSAT_Scoring_Manual.pdf) for details.

Notes:

- [Montage and Sampling Rate Information](:pages_path:/equipment/montage-and-sampling-rate-information.md)
- [HeartBEAT HSAT Scoring Manual](:files_path:/documentation/HeartBEAT_HSAT_Scoring_Manual.pdf)

## Signal and annotation files

[Raw polysomnography data](:files_path:/) is available for 317 randomized participants at baseline and 274 at followup. Each recording has a signal file (.EDF).

1. **[EDF](:files_path:/polysomnography/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from RemLogic.

## Known issues

- Subset of physical dimensions use invalid ASCII character (°) (traces back to source data from device download)
- Four (4) EDF files are invalid based on a filesize inconsistency (traces back to source data from device download)
  - `baseline`: 700205, 700266, 200288
  - `followup`: 700111

## History / changelog

*May 13, 2022*
- Removed XML event annotation files to avoid confusion with modified HeartBEAT scoring rules (see paragraph in introduction above)

*December 7, 2016*
- EDF recording dates changed from "00.00.00" to "01.01.85"

*August 2014*
- Polysomnography data uploaded to sleepdata.org

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
