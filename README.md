### gradle导入

```kotlin
repositories {
    maven {
        url = uri("https://maven.pkg.github.com/huayunliufeng/maven-repo")
        credentials {
            username = "3300358443@qq.com"
            password = "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"
        }
    }
}
```

```kotlin
implementation("priv.zq:hylf-common:0.0.1")
```

### maven导入

> settings.xml文件添加配置

```xml
<server>
    <id>github</id>
    <username>3300358443@qq.com</username>
    <password>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</password>
</server>
```

```xml
<dependency>
    <groupId>priv.zq</groupId>
    <artifactId>hylf-common</artifactId>
    <version>0.0.1</version>
</dependency>
```
