
platform :ios, '10.0'
use_frameworks!


target 'FreshFridge' do
  
  pod 'Kingfisher'
  pod 'SVProgressHUD'
  pod 'IQKeyboardManagerSwift'
  pod 'SnapKit', '~> 5.6.0'
  pod 'JXSegmentedView', '~> 1.3.0'
  
  pod 'FirebaseCore', :git => 'https://github.com/firebase/firebase-ios-sdk.git', :branch => 'master'
  pod 'FirebaseFirestore', :git => 'https://github.com/firebase/firebase-ios-sdk.git', :branch => 'master'
  pod 'FirebaseStorage', :git => 'https://github.com/firebase/firebase-ios-sdk.git', :branch => 'master'
  
  post_install do |installer|
      installer.pods_project.build_configurations.each do |config|

      config.build_settings["EXCLUDED_ARCHS[
      =iphonesimulator*]"] = "arm64"
    
        end
    end

  
end
