# java-read-webhooks

This sample will show you to read webhooks using the Nylas Kotlin/Java SDK.

## Setup

You need a web server capable of running Java code. [Qoddi](https://app.qoddi.com/login.php) is a great option.

### System dependencies

Handled by the web server.

### Gather environment variables

You'll need to create the following environment values:

```text
V3_TOKEN
BASE_URL
GRANT_ID
CALENDAR_ID
CLIENT_SECRET
```

### Install dependencies

Everything is on the POM.xml file, but here they are:

```bash
org.slf4j / slf4j-simple / 2.0.7
org.slf4j / slf4j-api / 2.0.7
com.nylas.sdk / nylas / 2.0.0-beta.1
com.sparkjava / spark-kotlin / 1.0.0-alpha
com.sparkjava / spark-template-mustache / 2.7.1
com.github.spullara.mustache.java / compiler / 0.9.4
com.fasterxml.jackson.core / jackson-databind / 2.15.2
org.apache.maven.plugins / maven-assembly-plugin / 3.6.0
commons-codec / commons-codec / 1.15
```

# Compilation

Clone this repo and use it as the source for your web server compilation

## Usage

Run the generated web page.

If successful, you will start to see all your incoming webhooks
