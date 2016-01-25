# CDispatch

Linux Swift System Library for libdispatch aka GCD. This is NOT required for
OSX Swift.

To use it, make the `Package.swift` of your Swift Linux package look like this:

    import PackageDescription
    
    let package = Package(
      dependencies: [
        .Package(url: "https://github.com/AlwaysRightInstitute/CDispatch.git", 
                 majorVersion:0)
      ]
    )

###Contact

[@helje5](http://twitter.com/helje5) | helge@alwaysrightinstitute.com

![](http://www.alwaysrightinstitute.com/images/ARI-symbol-logo.png)
