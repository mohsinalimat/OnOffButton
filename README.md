On & Off by Creativedash
===========

## About
This control is inspired on this Creative Dash dribbble:
![alt tag](https://d13yacurqjgara.cloudfront.net/users/107759/screenshots/1631598/onoff.gif)

## Implementation
You can found a more detail explanation on [this](http://ramosmachado.net/?p=14) blog post 

## Installation
For now, you need to copy the `OnOffButton.swift` into your project.

## Usage
After the installation, all you have to do is set your `UIButton` to use `OnOffButton`:

![alt tag](https://cloud.githubusercontent.com/assets/7672056/14966575/95d2de1e-1089-11e6-8e22-6beb549c806b.png)

Configure the properties as you want: 

![alt tag](https://cloud.githubusercontent.com/assets/7672056/14966574/95d082cc-1089-11e6-9ef7-8215e390bb19.png)

Create an `IBAction`:

```swift
@IBAction func changeButtonState(sender: OnOffButton) {
    sender.checked = !sender.checked
}
```


Profit ;)

## TODO
Make it available through Cocoapods and Carthage.

## License
Released under the MIT license. See the LICENSE file for more info.
