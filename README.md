# React Native WebRTC Kit CocoaPod Specs

React Native WebRTC Kit 用の CocoaPod Specs リポジトリです。

## About Shiguredo's open source software

We will not respond to PRs or issues that have not been discussed on Discord. Also, Discord is only available in Japanese.

Please read https://github.com/shiguredo/oss before use.

## 時雨堂のオープンソースソフトウェアについて

利用前に https://github.com/shiguredo/oss をお読みください。

## Spec リポジトリの準備

1. 本リポジトリをローカルの Spec リポジトリに登録します。

```
$ pod repo add rnkit-ios-sdk-specs https://github.com/react-native-webrtc-kit/webrtc-ios.git
```

2. Spec のリストを更新します。

```
$ pod repo update
```

## Podfile

Podfile の先頭に次の記述を追加することで、本リポジトリの Spec を利用可能になります。

```
source 'https://github.com/react-native-webrtc-kit/webrtc-ios.git'
source 'https://github.com/CocoaPods/Specs.git'
```

