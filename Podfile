source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

target 'Wakup' do

    # Background image load and cache
    pod 'SDWebImage', '~> 3.7'

    # An easy-to-plug-in Contextual Menu for iOS inspired by Pinterest.
    pod 'iOSContextualMenu', '~> 1.1'

    # A drop-in superclass category for showing empty datasets whenever the view has no content to display.
    pod 'DZNEmptyDataSet', '~> 1.7'

    # SwiftyJSON makes it easy to deal with JSON data in Swift
    pod 'SwiftyJSON', '~> 2.3'

    # Elegant HTTP Networking in Swift
    pod 'Alamofire', '~> 3.1'

    # Delightful on-disk cache
    pod 'AwesomeCache', '~> 2.0'

    # The waterfall (i.e., Pinterest-like) layout for UICollectionView.
    pod 'CHTCollectionViewWaterfallLayout', '~> 0.9'

    # Simple and highly customizable tag list view
    pod 'TagListView', '~> 1.0'

end

# Workaround until https://github.com/CocoaPods/CocoaPods/issues/5334 is fixed
post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CONFIGURATION_BUILD_DIR'] = '$PODS_CONFIGURATION_BUILD_DIR'
        end
    end
end