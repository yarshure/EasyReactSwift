use_frameworks!
workspace 'EasyReactSwift'
project 'Example/Example'

target 'iOSDemo' do
    platform :ios, '8.0'
    pod 'EasyReactSwift', path: './'
    pod 'SwiftLint'
    
    target 'iOSDemoTests' do
      inherit! :search_paths
      pod 'Nimble', '~> 7.3.1'
    end
end


target 'macDemo' do
    platform :osx, '10.10'
    pod 'EasyReactSwift', path: './'
    pod 'SwiftLint'

    target 'macDemoTests' do
        inherit! :search_paths
        pod 'Nimble', '~> 7.3.1'
    end
end

install! 'cocoapods', disable_input_output_paths: true
