# sms_spam_detector
A class project for refactoring code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. 

```bash
echo '\nDeactivating all active conda environments\n\n'
conda deactivate 2>/dev/null || true
echo '\nRemoving "sms_spam_detector" environment\n\n'
conda remove --name sms_spam_detector --all -y
echo '\nRecreate "sms_spam_detector" environment\n\n'
conda env create -f environment.yml -y
echo '\nActivate "sms_spam_detector" environment\n\n'
conda activate sms_spam_detector
```