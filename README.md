# ios-deepar-amazon-ivs-sample-integration

To run the example

1. Run `pod install`
2. Download the DeepAR iOS SDK from https://developer.deepar.ai/downloads and copy the DeepAR.framework into quickstart-ios-swift/Frameworks folder.
3. Go to https://developer.deepar.ai, sign up, create the project and the iOS app, copy the license key and paste it to ViewController.swift (instead of your_license_key_here string)
4. Follow the Amazon IVS User Guide at https://docs.aws.amazon.com/ivs/latest/userguide/getting-started.html and create a channel.
5. Copy Ingest server and Stream key into  ViewController.swift to `kIngestServer` and `kStreamKey` variables from the created channel in the Amazon IVS console.
6. Run the app. Watch the live stream in the Amazon IVS console.
