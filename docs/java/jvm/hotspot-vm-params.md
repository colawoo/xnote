
### 1 选项分类
Hotspot JVM提供以下三大类选项
- 标准选项：这类选项的功能是很稳定的，在后续版本中也不太会发生变化。运行java或者java -help可以看到所有的标准选项。所有的标准选项都是以-开头，比如-version， -server等。
- X选项：比如-Xms。这类选项都是以-X开头，可能由于这个原因它们被称为X选项。运行java -X命令可以看到所有的X选项。这类选项的功能还是很稳定，但官方的说法是它们的行为可能会在后续版本中改变，也有可能不在后续版本中提供了。
- XX选项：这类选项是属于实验性，主要是给JVM开发者用于开发和调试JVM的，在后续的版本中行为有可能会变化。

### 2 XX选项的语法
- 布尔类型选项，格式为-XX:+flag或者-XX:-flag，分别表示开启和关闭该选项。
- 非布尔类型选项，格式为-XX:flag=value

