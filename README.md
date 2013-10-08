Basic Maven Plugin
==============

It's a basic maven plugin. This project can be used as a template to create maven plugins.
To use this plugin in another project, just type the following code in pom.xml:

```html
<plugin>
  <groupId>br.com.caiosousa</groupId>
	<artifactId>basic-maven-plugin</artifactId>
	<version>1.0-SNAPSHOT</version>
	<executions>
	  <execution>
		  <goals>
			  <goal>basicplugin</goal>
			</goals>
		</execution>
	</executions>
</plugin>
```
