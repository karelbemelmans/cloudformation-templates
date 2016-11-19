# Daily EBS bacups with Retention policy

This CloudFormation template is an implementation of these 2 blog posts:

  - https://serverlesscode.com/post/lambda-schedule-ebs-snapshot-backups/
  - https://serverlesscode.com/post/lambda-schedule-ebs-snapshot-backups-2/

In short this template will:

  - Create 2 Lambda functions:
    - a snapshot creation function
    - a cleanup of snapshots that reached the retention date
  - A supporting IAM role
  - Two supporting Lambda permissions


