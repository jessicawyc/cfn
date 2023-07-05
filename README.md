# cfn

## Blog 
### Translate All: Automating multiple file type batch translation with AWS CloudFormation
https://aws.amazon.com/blogs/machine-learning/translate-all-automating-multiple-file-type-batch-translation-with-aws-cloudformation/
The template is updated for nodejs version, 18 is failed because of the code is not compatible, so need to change to nodejs16, use [here](translateall_updated.yml)

Trigger Code sample
```
{
  "JobName": "testing",
  "InputBucket": "translateall-inputbucket-1nmk3eanpwrki",
  "InputS3Uri": "",
  "OutputBucket": "translateall-outputbucket-16c6eozc79yr2",
  "SourceLanguageCode": "ja",
  "TargetLanguageCodes": [
    "en"
  ]
}
```
```
```

InputS3Uri is not URi only the prefix of the documents you upload, if just in the S3, leave it blank.

language code check here, must be Array
https://docs.aws.amazon.com/translate/latest/dg/what-is-languages.html
