---
aliases:
- /ko/serverless/serverless_integrations
- /ko/serverless/datadog_lambda_library/
- /ko/serverless/libraries_integrations/library/
kind: 설명서
title: 서버리스 라이브러리 및 통합
---

## 서버리스 개발 도구 통합

{{< whatsnext desc="Datadog은 널리 사용되는 서버리스 개발 도구와 통합되어 Datadog Lambda 확장 및 라이브러리를 애플리케이션에 자동으로 설치합니다." >}}
{{< nextlink href="/serverless/libraries_integrations/plugin/" >}}서버리스 프레임워크용 Datadog 플러그인{{< /nextlink >}}
{{< nextlink href="/serverless/libraries_integrations/cli/" >}}Datadog Lambda CLI{{< /nextlink >}}
{{< nextlink href="/serverless/libraries_integrations/cdk/" >}}AWS CDK에 대한 Datadog Construct{{< /nextlink >}}
{{< nextlink href="/serverless/libraries_integrations/macro/" >}}AWS SAM에 대한 Datadog Serverless Macro{{< /nextlink >}}
{{< /whatsnext >}}

## Datadog Lambda 확장 및 포워더(Forwarder)

{{< whatsnext desc="Lambda 함수에서 텔레메트리를 전송하려면 Lambda 확장 프로그램 또는 포워더가 필요합니다. 또한 AWS API 게이트웨이와 같은 비 Lambda 서버리스 리소스에 대한 로그를 수집하려면 포워더가 필요할 수도 있습니다." >}}
{{< nextlink href="/serverless/libraries_integrations/extension/" >}}Datadog Lambda Extension{{< /nextlink >}}
{{< nextlink href="https://github.com/DataDog/datadog-serverless-functions/tree/master/aws/logs_monitoring" >}}Datadog Forwarder Lambda Function{{< /nextlink >}}
{{< /whatsnext >}}

## Datadog Lambda 라이브러리

{{< whatsnext desc="특정 런타임에는 텔레메트리를 수집하기 위해 Datadog Lambda 확장 프로그램과 더불어 Datadog Lambda 라이브러리가 필요합니다." >}}
{{< nextlink href="https://github.com/DataDog/datadog-lambda-python" >}}Python용 Datadog Lambda 라이브러리{{< /nextlink >}}
{{< nextlink href="https://github.com/DataDog/datadog-lambda-js" >}}Node.js용 Datadog Lambda 라이브러리{{< /nextlink >}}
{{< nextlink href="https://github.com/DataDog/datadog-lambda-go" >}}Go용 Datadog Lambda 라이브러리{{< /nextlink >}}
{{< nextlink href="https://github.com/DataDog/datadog-lambda-rb" >}}Ruby용 Datadog Lambda 라이브러리{{< /nextlink >}}
{{< /whatsnext >}}

## Datadog AWS 통합

{{< whatsnext desc="Datadog은 Lambda 함수에서 직접 텔레메트리를 수집하는 것 외에도 서버리스 애플리케이션에서 사용하는 리소스에 대한 Datadog AWS 통합을 통해 텔레메트리를 수집할 수도 있습니다." >}}
{{< nextlink href="/integrations/amazon_lambda/" >}}AWS Lambda Integration{{< /nextlink >}}
{{< nextlink href="/integrations/amazon_step_functions/" >}}AWS Step Functions Integration{{< /nextlink >}}
{{< nextlink href="/integrations/amazon_appsync/" >}}AWS AppSync Integration{{< /nextlink >}}
{{< nextlink href="/integrations/amazon_api_gateway/" >}}AWS API Gateway Integration{{< /nextlink >}}
{{< nextlink href="/integrations/amazon_sqs/" >}}AWS SQS Integration{{< /nextlink >}}
{{< nextlink href="/integrations/amazon_sns/" >}}AWS SNS Integration{{< /nextlink >}}
{{< /whatsnext >}}