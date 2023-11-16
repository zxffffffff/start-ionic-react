# start-ionic-react
 一个 Ionic React 脚手架项目，使用 TypeScript 开发

# react
参考：https://github.com/zxffffffff/start-web-react.git

# ionic
参考：https://ionicframework.com/docs/react

## 创建工程
```bash
# native-run 原生运行，cordova-res 启动页和打包图标
npm install -g @ionic/cli native-run cordova-res

# Tabs 初始模板，Capacitor 原生容器
ionic start start-ionic-react tabs --type=react --capacitor
cd start-ionic-react

# 添加原生功能
npm install @capacitor/camera @capacitor/preferences @capacitor/filesystem
# 添加 Web UI 库 (PWA=渐进式)
npm install @ionic/pwa-elements
```

## 运行
```bash
# 浏览器运行
ionic serve
ionic capacitor add # 原生
```
