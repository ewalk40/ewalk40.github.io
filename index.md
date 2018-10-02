# Eric's Projects

### AR Quick Look Test Site
• This is a website for an AR Library! You can view it [here](Website.html)!

### Code Test
```Swift
let request = GADRequest()
request.testDevices = [kGADSimulatorID, "2a9a3dc602bc52708d00233d04e003be"]
bannerView.adUnitID = "ca-app-pub-6754636668034185/4286166234"
bannerView.rootViewController = self
bannerView.load(request)
        
settingsBtn.frame = CGRect(x: 0, y: 0, width: 25, height: 25)
settingsBtn.setImage(UIImage(named: "settings")?.withRenderingMode(.alwaysTemplate), for: .normal)
settingsBtn.addTarget(self, action: #selector(self.goToSettings), for: .touchUpInside)
settingsBtn.tintColor = UIColor.white
        
let settingsItem = UIBarButtonItem(customView: settingsBtn)
let width1 = settingsItem.customView?.widthAnchor.constraint(equalToConstant: 32)
width1?.isActive = true
let height1 = settingsItem.customView?.heightAnchor.constraint(equalToConstant: 32)
height1?.isActive = true
        
navigationItem.leftBarButtonItem = settingsItem
```
