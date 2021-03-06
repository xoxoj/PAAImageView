# PAAImageView
============

**Rounded async imageview downloader based on AFNetworking 2 and lightly cached**

[Swift version here](https://github.com/abiaad/PASImageView)

## Snapshot

![Snapshop PASwitch](https://raw.github.com/abiaad/paaimageview/master/snapshot.gif)

## Usage

```objective-c
PAAImageView *avatarView = [[PAAImageView alloc] initWithFrame:aFrame backgroundProgressColor:[UIColor whiteColor] progressColor:[UIColor lightGrayColor]];
[self.view addSubview:avatarView];
// Later
[avatarView setImageURL:URL];
```

## Update

1. You can load image using resources or another source (for example contact image);

You need use next method for load from resource
[avatarView setImage:[UIImage imageNamed:"test.png"]];

2. You can set width for background circle
[avatarView setBackgroundWidth:10.f];

**That's all**

## Contact

[Pierre Abi-aad](http://github.com/abiaad)
[@abiaad](https://twitter.com/abiaad)

## License

PAImageView is available under the MIT license.
