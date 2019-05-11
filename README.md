# fargate-environment-variables
Available environment variables in AWS Fargate.

AWS does not publish such a list yet, so here you go:

## Platform version 1.3.0
_This was run on alpine in us-east-1_

```bash
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
HOSTNAME=ip-10-0-26-162.ec2.internal
AWS_DEFAULT_REGION=us-east-1
AWS_EXECUTION_ENV=AWS_ECS_FARGATE
AWS_REGION=us-east-1
AWS_CONTAINER_CREDENTIALS_RELATIVE_URI=/v2/credentials/423d5655-6866-471a-b10f-4f025d2aaaaa
ECS_CONTAINER_METADATA_URI=http://169.254.170.2/v3/d032fe3b-bb46-45af-8fb5-9cb4b69aaaaa
HOME=/root
```
