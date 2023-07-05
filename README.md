<repositories>
 <repository>
 <id>Moncash-sdk-java</id>
 <url>https://github.com/ecelestin/Moncash-sdk-java</url>
 <snapshots>
 <enabled>true</enabled>
 <updatePolicy>always</updatePolicy>
 </snapshots>
 </repository>
</repositories>
<dependencies>
 <dependency>
 ...
 
 <groupId>com.digicelgroup.moncash</groupId>
 <artifactId>sdk-moncash-api</artifactId>
 <version>1.0-SNAPSHOT</version>
 </dependency>
</dependencies>
  

import com.digicelgroup.moncash.APIContext;

import com.digicelgroup.moncash.http.Constants;

import com.digicelgroup.moncash.payments.Payment;

import com.digicelgroup.moncash.payments.PaymentCapture;

import com.digicelgroup.moncash.payments.PaymentCreator;

import com.digicelgroup.moncash.payments.TransactionId;

import org.apache.http.HttpStatus;

<!---
fsaintilma/fsaintilma is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
