## Usage

Build

```
mvn clean install assembly:assembly -Dmaven.test.skip=true
```

Run

```
java -cp target/command-line-1.0-SNAPSHOT-jar-with-dependencies.jar com.java.barcode.App ..\images\AllSupportedBarcodeTypes.png
```

![Java barcode command line](http://www.codepool.biz/wp-content/uploads/2020/03/java-barcode-command-line.png)
