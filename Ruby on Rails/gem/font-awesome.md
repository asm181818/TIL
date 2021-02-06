### rails5系にfont-awesomeを入れる

```
gem 'font-awesome-sass'
```

インストール後、app/assets/stylesheets/application.scssに下記を追記

```
@import 'font-awesome-sprockets';
@import "font-awesome";
```
必ずこの順で書く
