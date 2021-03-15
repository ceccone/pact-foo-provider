# pact-foo-provider

Repo to show the problem with `@IgnoreNoPactsToVerify` for [Pact-JVM Issue #1324](https://github.com/pact-foundation/pact-jvm/issues/1324)

## How to reproduce the problem
* an empty pact-broker running at `http://localhost`
* run `gradle check`