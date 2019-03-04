
# Steps to Reproduce build failure.

1. Create new Single View iOS App
2. `pod init`
3. add `pod 'OpenSSL-Universal', :git => 'https://github.com/krzyzanowskim/OpenSSL.git', :branch => :master` to the `Podfile`
4. `pod install`
5. open the workspace and hit `cmd-U` to run tests
6. Observe that tests do not build
