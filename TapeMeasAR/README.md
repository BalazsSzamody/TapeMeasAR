# SentiaCodingChallange

This project is my solution for the coding challange Sentia supplied as part of their recruitment process.

## Main tasks and implementations in the project

* **JSON parsing** - handled with the help of the built in Codable protocol
* **Data aquisition** - handled by Alamofire in NetworkManager
* **Content presentation** - the content is displayed in a UISplitViewController
* **Premium distinction** - the distinction between standard and premium content is implemented by ThemeAdjustable protocol with the help of 4 custom views
* **Cell layout** - handled by AutoLayout constraints
* **Architectural pattern** - "Model - View - View Model"
* **Styling and design pleasantries** - UIActivityIndicators implemented in Storyboard for both imageViews while the images are downloaded and programmaticaly while the TableView loads. The Navigationbar is hidden in the list view. Animated selection and highlighting in TableViewCell


## Built With

* [Carthage](https://github.com/Carthage/Carthage) - Decentralized dependency manager 
* [Alamofire](https://github.com/Alamofire/Alamofire/) - HTTP networking framework
* [AlamofireImage](https://github.com/Alamofire/AlamofireImage/) - Image component framework for Alamofire
* [AlamofireNetworkActivityIndicator](https://github.com/Alamofire/AlamofireNetworkActivityIndicator) - Network Activity Indicator handling framework for Alamofire


## Author

* **Zsolt Balazs Szamody** - [Fr3qu3ntFly3r](https://github.com/Fr3qu3ntFly3r)

