---
title: Welcome
description: Meet NativeScript - an open-source framework for the cross-platform development of truly native apps.
position: 10
publish: false
slug: introduction
previous_url: /index
---

{% nativescript %}
# Welcome to NativeScript

NativeScript is how you build cross-platform, native iOS and Android apps without web views. Use Angular, TypeScript or modern JavaScript to get truly native UI and performance while reusing the skills and the code from your web projects. Get 100% access to native APIs via JavaScript and reuse of packages from npm, CocoaPods and Gradle. Open source and backed by Progress.
{% endnativescript %}

{% angular %}
# NativeScript with Angular

NativeScript doesn’t require Angular, but it’s even better when you use it. You can fully reuse skills and code from the web to build beautiful, high performance native mobile apps without web views. NativeScript features deep integration with Angular, the latest and greatest (and fastest) JavaScript framework. Open source and backed by Progress.
{% endangular %}

New to NativeScript? [Try out NativeScript on your phone](https://www.nativescript.org/nativescript-example-application?utm_medium=referral&utm_source=documentation&utm_campaign=getting-started) to see what a truly native app feels like.

## Get Started

Ready to get started developing with NativeScript? We offer a set of comprehensive tutorials that walk you through installing NativeScript, and building a real-world iOS and Android app from scratch.

<div id="start-button-container">
  <a href="https://play.nativescript.org/?template=groceries-ng&tutorial=groceries-ng" class="ns-button -action" id="ng-start-button">Get Started with TypeScript & Angular</a>
  <a href="https://play.nativescript.org/?template=groceries-js&tutorial=groceries-js" class="ns-button -action" id="js-start-button">Get Started with JavaScript</a>
</div>

<script type="text/javascript">
  // Quick script to randomize the tutorial button order
  var container = document.getElementById("start-button-container");
  var ngButton = document.getElementById("ng-start-button");
  var jsButton = document.getElementById("js-start-button");

  if (Math.floor(Math.random() * 2) == 0) {
    container.insertBefore(jsButton, ngButton);
  }
</script>

> **NOTE**: NativeScript also lets you use TypeScript _without_ Angular. If you’re interested in this approach, start with [our JavaScript tutorial](https://play.nativescript.org/?template=groceries-js&tutorial=groceries-js) to familiarize yourself with the basic NativeScript concepts, and then refer to [our TypeScript documentation](https://www.nativescript.org/using-typescript-with-nativescript-when-developing-mobile-apps) for your next steps.

## Join the NativeScript Community

We have a vibrant, engaged community and are here to help. You can find us on [Twitter](https://twitter.com/nativescript) and our [community forum](http://forum.nativescript.org/).

