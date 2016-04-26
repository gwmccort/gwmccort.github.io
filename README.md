# JBake Site - Groovy Template

http://jdmartinho.com/blog/blog/2015/2015-08-22-how-to-create-a-blog.html

http://coffeaelectronica.com/blog/2015/baking-with-groovy-and-github.html

https://github.com/jbake-org/jbake-gradle-plugin

https://bintray.com/calmdev/gradle-plugins/jbake-gradle-plugin/view

Your jBake content can be found in `src/jbake` and you can build the site using:

    ./gradlew jbake

Your site will be generated in `build/jbake`.

You can start a local server with your generated content using:

  groovy serve.groovy [port]

> There is an upcoming release of the `gradle-jbake-plugin` which will have serving support built-in, this is just a stop gap solution until then.

When you are ready to publish the site to your GitHub-Pages, run:

  ./gradlew publish
