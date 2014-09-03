# About

extJWNL WordNet 3.1 Data contains dictionary files
from Unix version of WordNet 3.1 augmented with
an extJWNL configuration file for an extremely easy
use of WordNet-like semantic resources in your project.

# Getting started

In the pom.xml:

```xml
<dependency>
    <groupId>net.sf.extjwnl</groupId>
    <artifactId>extjwnl</artifactId>
    <version>1.8.0</version>
</dependency>
<dependency>
    <groupId>net.sf.extjwnl</groupId>
    <artifactId>extjwnl-data-wn31</artifactId>
    <version>1.2</version>
</dependency>
```

In the code:

```java
Dictionary d = Dictionary.getDefaultResourceInstance();
```

# Notes
On checkout pay attention to your core.autocrlf git setting. The data files have unix line endings and they should remain so. The recommended way is to set core.autocrlf to false:
```cmd
git config core.autocrlf false
```
