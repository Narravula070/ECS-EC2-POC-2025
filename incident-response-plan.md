# Incident Response Plan

## Critical Service Failure

1. Identify the failing service through CloudWatch alarms.
2. Check ECS service logs for error messages.
3. If container issue, roll back to the previous task definition.
4. If instance issue, terminate and replace the problematic instance.
5. Update status page and notify stakeholders.
6. Conduct a post-mortem analysis and update documentation.
