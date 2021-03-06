# Make Xcode Gr8 Again
Xcode + Plugins = 💙 

## About
A Mac App to reenable plugins on Xcode.

**Use at your own risk.** 
(More information on the risks [below](https://github.com/fpg1503/MakeXcodeGr8Again#should-i-use-it))

## Usage
Currently there are two modes of usage: regular and YOLO.

### Regular
Simply drag your Xcode 8 App into the window. A new Xcode app will be created allowing the use of plugins.

### YOLO
Toggle the YOLO mode and drag the Xcode 8 App. That simple. This mode is called YOLO because it overwrites your binary with the unsigned version, if by some reason the process fails and you don't have a backup you may have to re-download (and re-extract) Xcode.

# Should I use it?
To answer this question let's provide you with some background so you can decide for yourself.

## Why did plugins stop working?
Apple has allegedly disabled the use of plugins to avoid another incident like the [Xcode Ghost](https://en.wikipedia.org/wiki/XcodeGhost) :ghost:. In 2016's dub dub Apple announced their new [Source Editor extensions](https://developer.apple.com/videos/play/wwdc2016/414/).

## Did they provide any alternatives?
Yes, as I mentioned above Apple announced Source Editor extensions. I was one of the first people in line for the Xcode lab to know more about it. Unfortunately these extensions are still pretty limited, run completely isolated from the Xcode process and require user interaction to do anything. They may, however, solve your problem, and if they do just use them.

## What exactly are you trying to do?
The plugins I like the most work seamlessly (without any user interaction) like [Polychromatic](https://github.com/kolinkrewinkel/Polychromatic) and [OptionalOutlets](https://github.com/fpg1503/OptionalOutlets). I've filed a radar asking for semantic highlighting support ([rdar://27028207](http://openradar.appspot.com/radar?id=6715695387639808)) but it remains **Open**. I had a discussion about it with some Apple engineers and they told me I should *file a radar for the missing functionalities* (radar or GTFO).

## How can I help?
File radars. Period. This app is a *hack* and adds the vulnerability that allowed Xcode :ghost: to happen again, that said, it means you're exactly as safe as you were before. I wouldn't use a unsigned Xcode to upload a Build. I'd really like to disable app submissions on Xcode Gr8, there's an [issue](https://github.com/fpg1503/MakeXcodeGr8Again/issues/4) about it, feel free to help.

## Contributing and future improvements
Known issues and road map are [here](https://github.com/fpg1503/MakeXcodeGr8Again/issues). Feel free to open feature requests, issues and PRs.

:rocket: **Let's Make Xcode Great Again™**

## License
MIT

## Special thanks/credits
- [steakknife's unsign](https://github.com/steakknife/unsign)
- [marcelofabri](https://github.com/marcelofabri) for reminding me to warn people about the [risks involved](https://github.com/fpg1503/MakeXcodeGr8Again/issues/9).

