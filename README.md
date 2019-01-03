# introduction
this repository is an example which is Xcodegen.

## the purpose of this repository
To understand how to write xcodegen yaml

## how to define environment
## how to write environment's value

```
configs:
   Debug: debug
   Beta: release
   AppStore: release

settings:
      configs:
        Debug:
          CODE_SIGN_IDENTITY: iPhone Developer
          BUNDLE_ID: hiratsuka-test.debug
          PRODUCT_NAME: debug-hiratsuka
          OTHER_SWIFT_FLAGS: -D DEBUG -Xfrontend -debug-time-function-bodies
        Beta:
          CODE_SIGN_IDENTITY: iPhone Distribution
          BUNDLE_ID: hiratsuka-test.beta
          PRODUCT_NAME: beta-hiratsuka
          OTHER_SWIFT_FLAGS: -Xfrontend -debug-time-function-bodies
        AppStore:
          CODE_SIGN_IDENTITY: iPhone Distribution
          BUNDLE_ID: hiratsuka-test.prod
          PRODUCT_NAME: prod-hiratsuka
          OTHER_SWIFT_FLAGS: -Xfrontend -debug-time-function-bodies

```


```

```
