# Java Barcode and QR Code Reader: Command Line, GUI and Web

The repository contains three samples (command line, GUI, and web), showing how to implement Java barcode and QR code reader using [ZXing](https://github.com/zxing/zxing) and [Dynamsoft Barcode Reader](https://www.dynamsoft.com/barcode-reader/sdk-desktop-server/).

## Install ZXing and Dynamsoft Barcode Reader
Configure `pom.xml` file in Maven project:

```xml
<repositories>
<repository>
    <id>dbr</id>
    <url>https://download2.dynamsoft.com/maven/dbr/jar</url>
</repository>
</repositories>
<dependencies>
<dependency>
    <groupId>com.dynamsoft</groupId>
    <artifactId>dbr</artifactId>
    <version>9.0.0</version>
</dependency>
<dependency>
    <groupId>com.google.zxing</groupId>
    <artifactId>core</artifactId>
    <version>3.4.0</version>
</dependency>
```

## License Activation
Get a valid [license key](https://www.dynamsoft.com/customer/license/trialLicense?product=dbr) of Dynamsoft Barcode Reader and update the following Java code:

```java
BarcodeReader.initLicense("LICENSE-KEY");
BarcodeReader br = new BarcodeReader();
```

## Usage
- [Command Line](command-line/README.md)
- [GUI](gui/README.md)
- [Web](web/README.md)

## Blog
[How to Integrate Java Barcode SDK to Command-Line, GUI and Web Apps](https://www.codepool.biz/java-barcode-command-line-gui-web.html)
