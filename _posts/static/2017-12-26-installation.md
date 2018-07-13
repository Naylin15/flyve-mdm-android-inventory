---
layout: post
howtos: true
published: true
title: Installation
permalink: howtos/installation
description: Get it now
category: user
date: 2017-12-29
---
There are three ways to install the Inventory Library for Android by downloading the latest JAR, grab via Maven, insert on `build.gradle` at app level or use Apache Ivy.

### Maven

```xml
<dependency>
  <groupId>org.flyve</groupId>
  <artifactId>inventory</artifactId>
  <version>1.0.0</version>
  <type>pom</type>
</dependency>
```

### Gradle

```groovy
compile 'org.flyve:inventory:1.0.0'
```

### Apache Ivy

```
<dependency org='org.flyve' name='inventory' rev='0.1.0'>
  <artifact name='inventory' ext='pom' ></artifact>
</dependency>
```

You can also find us on [**Bintray repository**](https://bintray.com/flyve-mdm/inventory/android-inventory-library).