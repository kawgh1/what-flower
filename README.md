# what-flower

![gif](https://raw.githubusercontent.com/kawgh1/what-flower/main/flower.gif)

Machine Learning App that uses a Flower Recognition Model to tell user what flower a picture is


## Dev Notes  

- ###  Install `Alamofire` and `SwiftyJSON` to app
  - In the root project folder, run `pod init`
  - open the podfile running `open Podfile -a Xcode`
  - keep `use_frameworks!`
  - add `pod 'Alamofire', '~> 4.4'`
  - add `pod SwiftyJSON`
  - close the pod file and go back to terminal root project folder
  - run `pod install` to install Alamofire and SwiftyJSON

- ### Install `SDWebImage` to app
  - add `pod 'SDWebImage'`
  - https://cocoapods.org/pods/SDWebImage
