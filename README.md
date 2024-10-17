Denna guide innehåller instruktioner för att köra AWS CloudFormation-stack.

## Förutsättningar

1. AWS CLI installerat och konfigurerat.
2. CloudFormation-filen redo (`examstack.yaml`).
3. SSH-nyckelpar (`MantisWeb`) tillgängligt i AWS.
4. Grundläggande förståelse för AWS-tjänster som EC2, VPC, Load Balancer, osv.

Kör följande kommando för att deploya stacken:

```bash
aws cloudformation deploy --template-file examstack.yml --stack-name examstack
