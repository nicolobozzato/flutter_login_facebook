# Migration guides

## Upgrade to 1.3

Facebook SDK upgraded to 12.3 version.

### Android 

- Add `facebook_client_token` in `strings.xml` and `com.facebook.sdk.ClientToken` meta in `AndroidManifest.xml`.
- You can remove now:
    - `app_name` and `fb_login_protocol_scheme` from `string.xml`;
    - activities `com.facebook.FacebookActivity` and `com.facebook.CustomTabActivity` from `AndroidManifest.xml`.

See [Edit Your Resources and Manifest](README.md#edit-your-resources-and-manifest) in README.

### iOS

- You should run `pod update` in `/ios` directory for you project. That's for upgrading native dependencies. 
- Also `flutter clean` may be required.

## Upgrade to 1.2

Facebook SDK upgraded to 12 version.

### iOS

- Update minimum deployment target to iOS 10 if you have smaller version before.
- You should run `pod update` in `/ios` directory for you project. That's for upgrading native dependencies. 
- Also `flutter clean` may be required.

## Upgrade to 1.1

Facebook SDK upgraded to 11 version.

### iOS

You should run `pod update` in `/ios` directory for you project. That's for upgrading native dependencies.

Also `flutter clean` may be required.


## Upgrade to 0.5

Facebook SDK upgraded to 9.0.

### iOS

You should run `pod update` in `/ios` directory for you project. That's for upgrading native dependencies.

Also `flutter clean` may be required.