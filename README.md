# cfn

## Blog 
### Translate All: Automating multiple file type batch translation with AWS CloudFormation
https://aws.amazon.com/blogs/machine-learning/translate-all-automating-multiple-file-type-batch-translation-with-aws-cloudformation/
The template is updated for nodejs version, use [here](translateall_updated.yml)

Trigger Code sample
```
{
  "JobName": "testing",
  "InputBucket": "translateall-inputbucket-1nmk3eanpwrki",
  "InputS3Uri": "test",
  "OutputBucket": "translateall-outputbucket-16c6eozc79yr2",
  "SourceLanguageCode": "ja",
  "TargetLanguageCodes": [
    "en"
  ]
}
```
```
```

language code 在这里查
https://docs.aws.amazon.com/translate/latest/dg/what-is-languages.html
