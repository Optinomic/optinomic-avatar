[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/optinomic/optinomic-avatar)

# \<optinomic-avatar\>

Avatar with initials. gender & age - colors.

For Documentation check the [component-page](https://optinomic.github.io/optinomic-avatar/components/optinomic-avatar/).


<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="optinomic-avatar.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<optinomic-avatar firstname="Sonja" lastname="Muster" gender="female" birthdate="1993-05-21T00:00:00.000000000000Z"></optinomic-avatar>

<optinomic-avatar firstname="Sonja" lastname="Muster" gender="female" small birthdate="1993-05-21T00:00:00.000000000000Z"></optinomic-avatar>
```


## Install

```
$ bower install optinomic/optinomic-avatar
```

## Dependencies

Make sure that you import the following Dependencies. These are not imported inside the element itself.

<link rel="import" href="../polymer/polymer.html">


## CDN

Optinomic - Elements are also available CDN:

### Version 0.0.3

```html
<link rel="import" href="https://cdn.rawgit.com/Optinomic/optinomic-avatar/57bcaa2f/optinomic-avatar.html">
```

### Inside Optinomic-App-Templates you simply could use this syntax to have always the latest version:
```html
<head>
    include(../lib/polymer/imports/optinomic-avatar.m4)
</head>
```
