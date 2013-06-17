
Enables interoperability between JVM languages
----------------------------------------------

Plugin page: [http://artifacts.griffon-framework.org/plugin/lang-bridge](http://artifacts.griffon-framework.org/plugin/lang-bridge)


The LangBridge plugin enables compiling commons Java/Groovy sources ahead of every other source available
on a Griffon application. This allows other JVM lang plugins (like [Clojure][1], [Scala][2] for example)
to implement/reference a common interface or POJO.

Usage
-----
Upon installation the plugin will generate a directory at `$appdir/src/commons`, you can place the common
code there. Compilation of that code is guaranteed to be done before any other compilation happens. However
you may compile that code manually by invoking

    griffon compile-commons

[1]: /plugin/clojure
[2]: /plugin/scala

