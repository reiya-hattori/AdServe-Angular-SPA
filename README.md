![](https://img.shields.io/badge/11.2.14-Angular-DD0031.svg?logo=angular&style=plastic)
![](https://img.shields.io/badge/14.21.3-Node.js-339933.svg?logo=node.js&style=plastic)
# adserve-angular-spa

## ディレクトリ構造
```
adserve-angular-spa
├── README.md
├── angular.json
├── e2e
│   ├── protractor.conf.js
│   ├── src
│   │   ├── app.e2e-spec.ts
│   │   └── app.po.ts
│   └── tsconfig.json
├── karma.conf.js
├── package-lock.json
├── package.json
├── src
│   ├── app
│   │   ├── about
│   │   │   ├── about.component.css
│   │   │   ├── about.component.html
│   │   │   ├── about.component.spec.ts
│   │   │   └── about.component.ts
│   │   ├── app-routing.module.ts
│   │   ├── app.component.css
│   │   ├── app.component.html
│   │   ├── app.component.spec.ts
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   ├── article
│   │   │   ├── article.component.css
│   │   │   ├── article.component.html
│   │   │   ├── article.component.spec.ts
│   │   │   └── article.component.ts
│   │   ├── content
│   │   │   ├── content.component.css
│   │   │   ├── content.component.html
│   │   │   ├── content.component.spec.ts
│   │   │   └── content.component.ts
│   │   └── home
│   │       ├── home.component.css
│   │       ├── home.component.html
│   │       ├── home.component.spec.ts
│   │       └── home.component.ts
│   ├── assets
│   ├── environments
│   │   ├── environment.prod.ts
│   │   └── environment.ts
│   ├── favicon.ico
│   ├── index.html
│   ├── main.ts
│   ├── polyfills.ts
│   ├── styles.css
│   └── test.ts
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.spec.json
└── tslint.json
```

## これはなにか
SPAでインターステシャル広告を配信するためのサンプルアプリです。

## なぜこれが必要なのか

## ローカルへのインストール
```
git clone https://github.com/reiya-hattori/adserve-angular-spa.git
npm install
```

### 起動
```
npm start
OR
ng serve -o
```

#### 注意点
Angular：version 11.2.14 の場合 Nodeのバージョンが14.Xでないと動作しない

## 本番にリリースされるファイルに制約はあるか

## mainへの権限

### mainの保護

## 注意点

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.14.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
