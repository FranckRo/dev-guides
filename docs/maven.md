[Home](../README.md) - [NPM](../docs/npm.md) - [Unix](../docs/unix-commands.md) - [Windows](../docs/windows.md) - [Maven](../docs/maven.md)

| Command |    Description  |
| ------------- |: -------------: |
| <code>mvn versions:set -DnewVersion=1.0.3-SNAPSHOT </code> | Upgrade version of components (explore your directories to update referenced dependencies) |


## How to clean specifics files created by previous installations (.zip in this sample)
Add to your pom.xml, sections _<plugins>_
<code>
<plugin>
    <artifactId>maven-clean-plugin</artifactId>
    <configuration>
        <filesets>
            <fileset>
                <directory>./</directory>
                <includes>
                    <include>**/*.zip</include>
                </includes>
                <followSymlinks>false</followSymlinks>
            </fileset>
        </filesets>
    </configuration>
</plugin>
</code>
