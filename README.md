# QSARs
Mechanistic QSAR models for key human health endpoints<br>
Notes for Dow’s Cheminformatics Models for Cholinergic (mAChR, nAChR, AChE) and Mitochondrial Interactions<br>
16 December 2022

Dow’s computational models are built using publicly available data and KNIME workflows.  There is an associated QSAR Model Reporting Format (QMRF) document for each the four model (muscarinic and nicotinic acetylcholine receptors, acetylcholinesterase and mitochondrial membrane potential inhibitors), which outlines model performance statistics.  The QMRF report includes title, general information about model development, the endpoint(s) evaluated, data used, the model algorithm, the applicability domain, internal and external validations and model interpretation.  Additional information is available in peer-reviewed, published papers (cited in QMRFs).  We are freely sharing these models with other users in hopes that we will receive feedback on model performance and that users will share updated versions of the models as ‘open source’ when improvements are made. <br><br>

Note: The KNIME workflows were developed in KNIME 4.6.1. <br><br>

We would like to make potential users aware of some of the properties of our models:<br>
  •	The models were built to favor specificity over sensitivity.  While we try to achieve high accuracy, there are likely to be ‘false positive’ predictions.<br>
  •	We are not responsible for erroneous model predictions.<br>
  •	The raw data on which the models were built are publicly available as supplemental information for peer-reviewed publications cited in the QMRF reports.<br>
  •	The models are a “snapshot” in time and the models will change as more data become available and as KNIME nodes change.
