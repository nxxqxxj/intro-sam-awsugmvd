# intro-sam-awsugmvd

Este proyecto contiene código y archivos de una app serverless y poder desplegarla con AWS-SAM-CLI. Incluye los siguientes archivos y carpetas:

- `src` - Código para laa funciones Lambda.
- `template.yaml` - SAM Template donde se definen los recursos de AWS de la aplicación.


## Desplegar la infra serverless

Para usar la CLI de AWS SAM:

* AWS SAM CLI - [AWS SAM CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html).
* Node.js - [Node.js](https://nodejs.org/en/), incluyendo npm.

Para buildear y desplegar la app por primera vez:

```bash
sam build
sam deploy
```

El endpoint de API Gateway se mostrará como output cuando se termine de desplegar la infra.

## Cleanup

Para eliminar la aplicación de ejemplo, se puede hacer con el siguiente comando:

```bash
sam delete
```

## Resources

Doc: https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html

Fork: https://github.com/aws/aws-sam-cli-app-templates/tree/master/nodejs20.x

Workshop: https://catalog.workshops.aws/complete-aws-sam/en-US
