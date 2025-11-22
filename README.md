
# AWS KMS Policy for Multi-Account Architecture
This document outlines a sample AWS Key Management Service (KMS) policy designed for a multi-account architecture. The policy allows specific AWS accounts to use and manage KMS keys while ensuring security and compliance.

log archive account: xxxxxxxxxxxx \
security account: xxxxxxxxxxxx

In security account, we have security services like CloudTrail, Config, SecurityHub, GuardDuty etc.

In log archive account, we have S3 buckets to store logs from various accounts.
