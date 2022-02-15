## Javadoc example

> This was created using the java-17-openjdk.

![](/assets/output.png)

### Steps to reproduce

- #### Install a JDK
- #### Create a example class ([MyClass.java](./mypackage/MyClass.java)) (it can be inside a package)
- #### Comment out the code with the [javadoc syntax](https://www.oracle.com/mx/technical-resources/articles/java/javadoc-tool.html).
- #### Run javadoc
```bash
javadoc -d docs/ mypackage
```
- #### The doc should look like [this](https://tonycituk.github.io/javadoc-example/).