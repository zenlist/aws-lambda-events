## master

- No changes yet

## [[0.2.7] - 2020-04-02](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.2.7)

- Generate events from `aws-lambda-go` v1.16.
  Thanks @ewbankkit! [#16](https://github.com/LegNeato/aws-lambda-events/pull/16)

## [[0.2.6] - 2020-03-30](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.2.6)

- Generate events from `aws-lambda-go` v1.15.
  Thanks @ewbankkit! [#14](https://github.com/LegNeato/aws-lambda-events/pull/14)

## [[0.2.5] - 2019-10-19](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.2.5)

- `Deref` and `DerefMut` are now implemented for encoding tuple types. [#9](https://github.com/LegNeato/aws-lambda-events/pull/9)

## [[0.2.4] - 2019-03-18](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.2.4)

- Add `kinesis_analytics` events.
- Add `AppSyncIamIdentity` and `AppSyncCognitoIdentity` in `appsync`.
- Fix `dmarcPolicy` field for `SimpleEmailReceipt` in `ses`.

## [[0.2.3] - 2019-02-21](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.2.3)

- Add `ApiGatewayWebsocketProxyRequest` and `ApiGatewayWebsocketProxyRequestContext` in `apigw`.
- Add `customData` field for `CodeCommitRecord` in `code_commit`.
- Add `S3TestEvent` in `s3`.

## [[0.2.2] - 2019-02-01](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.2.2)

- Fix struct deserialization when the json key is not specified for a Go field
  and the field name does not match the generated Rust field name. [[#6](https://github.com/LegNeato/aws-lambda-events/pull/6)]

## [[0.2.1] - 2019-01-07](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.2.1)

- Add `multi_value_headers` field for `ApiGatewayProxyResponse`.

## [[0.2.0] - 2018-12-18](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.2.0)

- Add support for embedded fields, as seen in `cognito::CognitoEventUserPoolsPreSignup`. [[#4](https://github.com/LegNeato/aws-lambda-events/pull/4)]

## [[0.1.5] - 2018-12-17](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.1.5)

- Add `alb` events.

## [[0.1.4] - 2018-12-17](https://github.com/LegNeato/aws-lambda-events/releases/tag/v0.1.4)

- Inner fields of `Base64Data`, `MillisecondTimestamp`, `SecondTimestamp` are
  now public. [[#3](https://github.com/LegNeato/aws-lambda-events/pull/3)]
- Fields encoded as `serde_json::Value` may now optionally use a more-specific
  type. [[#1](https://github.com/LegNeato/aws-lambda-events/pull/1)]
