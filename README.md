# IndianVehicleNumberChecker

Here is a source code to check any Indian vehicle's public details available on govt site provided publically by government.

Refer the class IndianVehicleNumberChecker.java 

It uses 4 part of strings as parameters which are explained in comments next to it,

        //  Must be 2 letters and characters only (Union Territory / State code)
        String utOrState = "XX";
        
        //  Must be 2 letters and numbers only    (District serial number)
        String districtNumber = "00";
        
        //  optional and can be blank             (Optional code for additional sub-category needs)
        String additionalCode = "XX";
        
        //  Must be 4 letters and numbers only    (Vehicle serial number)
        String serialNumber = "0000";

Change the values with any vehicle number for which details are required.


To Run this java file few dependencies are requied which are given here for reference,

        <!-- https://mvnrepository.com/artifact/org.jsoup/jsoup -->
        <dependency>
            <groupId>org.jsoup</groupId>
            <artifactId>jsoup</artifactId>
            <version>1.11.3</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/org.apache.httpcomponents/httpclient -->
        <dependency>
            <groupId>org.apache.httpcomponents</groupId>
            <artifactId>httpclient</artifactId>
            <version>4.5.6</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/org.json/json -->
        <dependency>
            <groupId>org.json</groupId>
            <artifactId>json</artifactId>
            <version>20190722</version>
        </dependency>
