# springboot-vue-gradle
Vue.js (Vue CLI 3 でプロジェクト作成) を含んだ Spring Boot のプロジェクトを gradle でビルドする場合のサンプルプロジェクト

## Spring Boot と Vue.js の両方のビルド等の処理実行方法
gradle の bootJar/bootRun タスク実行で Vue.js 部分の処理を実行するようにしている(build.gradle 参照)

## Vue.js 部分のみのビルド等の処理実行方法
### Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn run build
```

### Lints and fixes files
```
yarn run lint
```

### Vue.js のビルド設定
vue.config.js に、ビルドファイルの出力先設定と、ビルド対象ファイルの設定を記載した