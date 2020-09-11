## 說明
直接建立專案docker image並上傳到registres的工具

[document](https://github.com/GoogleContainerTools/jib/tree/master/jib-maven-plugin#quickstart)
## 加入plugin於Ｍaven
``` xml
<plugin>
    <groupId>com.google.cloud.tools</groupId>
    <artifactId>jib-maven-plugin</artifactId>
    <version>0.9.6</version>
    <configuration>
        <from>
            <!--base image-->
            <image>openjdk:alpine</image>
        </from>
        <to>
            <!--<image>registry.cn-hangzhou.aliyuncs.com/m65536/jibtest</image>-->
            <!--目标镜像registry地址，为了方便测试，你需要换成自己的地址，如果你的网络不好，可以选用国内加速器，比如阿里云的-->
            <image>registry.hub.docker.com/moxingwang/jibtest</image>
        </to>
    </configuration>
    <executions>
        <execution>
            <phase>package</phase>
            <goals>
                <goal>build</goal>
            </goals>
        </execution>
    </executions>
</plugin>
```
## 建立映像檔並上傳
``` shell script
mvn clean compile jib:build
```
## 參數
- -Djib.to.auth.username:registry帳號
- -Djib.to.auth.password:registry密碼
