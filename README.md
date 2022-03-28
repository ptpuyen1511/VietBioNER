# A Vietnamese Biomedical Named Entity Recognition Corpus

## Context

VietBioNER is constituted by biomedical grey literature specified for tuberculosis.
The corpus was annotated with five named entity categories of Organisation, Location, Date and Time, Symptom and Disease, and Diagnostic Procedure.

## Entity Category Examples

| Entity Category         | Examples                                                                                  |
|:-------------------------:|-------------------------------------------------------------------------------------------|
| `Symptom_and_Disease` | `lao đa kháng thuốc` (multidrug-resistant tuberculosis), `ho có đờm` (coughing up phlegm) |
| `DiagnosticProcedure` | `AFB (+)`, `GeneXpert`                                                                    |
| `Location`            | `phía Bắc Việt Nam` (North Vietnam), `Khu vực Đông Nam Á` (Southeast Asia)                |
| `DateTime`            | `mùa hè` (summer), `từ 1990-1992` (from 1990-1992) |
| `Organisation`        | `Bộ Y tế` (Ministry of Health), `Khoa Phổi Thận` (Lung and Kidney Department)             |
## Content

The corpus contains 1706 sentences with an average length of 31 tokens.
About 74% of sentences in the corpus contained annotated entities, whose distribution among the five categories is detailed in Fig.1.

<div align="center">

![distribution_ne](img/barchart.png)

*Figure 1: Distribution of each entity type in VietBioNER.*

</div>

The corpus is randomly split into three sets: training, validation, and test sets. These sets are constructed with an approximate ratio of 7:3:7. Specifically, the training set consists of 706 sentences, the validation set consists of 300 sentences, and the test set has 700 sentences.

The distribution of all entity categories is reported in Table 1.

|   Entity Category   | Train | Valid | Test |
|:-------------------:|:-----:|:-----:|:----:|
| Symptom_and_Disease |  838  |  378  |  810 |
| DiagnosticProcedure |  191  |   89  |  202 |
|       Location      |  162  |   78  |  106 |
|       DateTime      |  141  |   58  |  97  |
|     Organisation    |   77  |   36  |  71  |
*Table 1: Number of entities in each sets.*
