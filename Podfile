platform :ios, '8.0'
plugin 'cocoapods-acknowledgements'

target 'Tropos' do
  pod 'HockeySDK', '~> 5.0', :inhibit_warnings => true
  pod 'Mixpanel', '~> 2.7', :inhibit_warnings => true

  target 'TroposTests' do
    inherit! :search_paths
    pod 'OCMock'
    pod 'OHHTTPStubs'
  end
end
