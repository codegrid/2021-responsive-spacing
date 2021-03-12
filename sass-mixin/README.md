# responsive-spacing.scss

幅に合わせて伸び縮みする空白を出力するSassのmixinです。

## 利用例

```scss
section + section {
  @include responsiveSpacing(
    "margin-top",
    $bpLower: 360px, $bpUpper: 1024px,
    $spMin: 52px, $spMax: 136px
  );
}
```

## ライセンス

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.ja)