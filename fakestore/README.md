# microG FakeStore

This is the upstream microG FakeStore v0.2.1 package (`com.android.vending`),
included as a small compatibility stub. It does not provide Google Play Services
or a functioning Play Store.

- Upstream: https://github.com/microg/FakeStore/releases/tag/v0.2.1
- APK: `com.android.vending-83700037.apk`
- SHA-256: `ab3e5396956a80a1a3ebc7c1953da008d69f694f133bdd0cbc95e0e8e19ecda0`
- License: Apache-2.0

The device framework maps this package's declared fake signature to the
allowlisted Google certificate in every build variant. The mapping remains
restricted to the upstream microG signing certificate, the `com.android.vending`
and `com.google.android.gms` package names, and the one certificate embedded in
the framework; the APK must therefore remain presigned.
