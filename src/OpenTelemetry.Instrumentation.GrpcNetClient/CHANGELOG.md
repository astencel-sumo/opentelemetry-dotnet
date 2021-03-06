# Changelog

## Unreleased

* The `grpc.method` and `grpc.status_code` attributes
  added by the library are removed from the span. The information from these
  attributes is contained in other attributes that follow the conventions of
  OpenTelemetry.
  ([#1260](https://github.com/open-telemetry/opentelemetry-dotnet/pull/1260)).

## 0.5.0-beta.2

Released 2020-08-28

* NuGet package renamed to OpenTelemetry.Instrumentation.GrpcNetClient to
  more clearly indicate that this package is specifically for gRPC client
  instrumentation. The package was previously named
  OpenTelemetry.Instrumentation.Grpc.
  ([#1136](https://github.com/open-telemetry/opentelemetry-dotnet/pull/1136))
* Grpc.Net.Client Instrumentation automatically populates HttpRequest in
  Activity custom property
  ([#1099](https://github.com/open-telemetry/opentelemetry-dotnet/pull/1099))
  ([#1128](https://github.com/open-telemetry/opentelemetry-dotnet/pull/1128))

## 0.4.0-beta.2

Released 2020-07-24

* First beta release

## 0.3.0-beta

Released 2020-07-23

* Initial release
