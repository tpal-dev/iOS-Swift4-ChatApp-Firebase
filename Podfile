# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'ChatApp' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for ChatApp


pod 'Firebase'
pod 'Firebase/Auth'
pod 'Firebase/Analytics'
pod 'Firebase/Database'
pod 'Firebase/Storage'
pod 'SVProgressHUD'
pod 'ChameleonFramework'
pod 'SDWebImage'

end




post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
        end
    end
end



