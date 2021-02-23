source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '12.0'
inhibit_all_warnings!

target 'TortugaDemo' do
    use_frameworks!
        
        pod 'RealmSwift'
        pod 'HandyJSON'
        pod 'SnapKit'
        pod 'SVProgressHUD'
        pod 'Toaster'
        pod 'EmptyDataSet-Swift'

target 'TortugaDemoTests' do
    inherit! :search_paths
    # Pods for testing
end

target 'TortugaDemoUITests' do
    inherit! :search_paths
    # Pods for testing
end

pre_install do |installer|
Pod::Installer::Xcode::TargetValidator.send(:define_method, :verify_no_static_framework_transitive_dependencies) {}
end

end
