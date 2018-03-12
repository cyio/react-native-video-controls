## 使用：

1. 添加子模块
```sh
git submodule add git@github.com:cyio/react-native-video-controls.git
yarn add ./react-native-video-controls
react-native link react-native-video
```

2. 在`package.json`中，手动添加依赖
```
"dependencies": {
  ...
	"react-native-video-controls": "file:./react-native-video-controls"
}
```

3. 子模块安装依赖
```sh
cd react-native-video-controls
yarn
```
