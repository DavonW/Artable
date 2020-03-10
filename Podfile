# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'
def shared_pods
  pod 'Firebase/Core'
  pod 'Firebase/Auth'
  pod 'Firebase/Firestore'
  pod 'Firebase/Storage'
  pod 'IQKeyboardManagerSwift'
  pod 'Kingfisher','~> 4.0'
  pod 'CodableFirebase'

end
target 'Artable' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  shared_pods
  pod 'Stripe'
  pod 'Alamofire'
end

target 'ArtableAdmin' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  shared_pods
  pod 'CropViewController'

end
