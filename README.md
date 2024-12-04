# aws-Rekognition-DIO-Nexa-Bootcamp
A example project created with JAVA to demonstrate the AWS rekognition functionality, based in DIO BOOTCAMP

## This output has used the samples provided by AWS for JAVA that can be found on [examples AWS](https://github.com/awsdocs/aws-doc-sdk-examples/blob/main/javav2/example_code/rekognition/src/main/java/com/example/rekognition/RecognizeCelebrities.java)


## Use Cases
Some of the use cases can be:

- PPE detection
 - PPE are mandatory in some areas, the PPE detection provided by the AWS rekognition can be used to generate alerts when people without PPE access these areas.

- Alert human presence: Using the 'Amazon Rekognition Streaming Video Events' an alert can be triggered when a person is detected in a specific camera fotage
## Details

This repo only contains the image processed and the output after execute the action RecognizeCelebrities, I've added the image path arg into the launch.json file.

```java
// Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.
// SPDX-License-Identifier: Apache-2.0
        {
            "type": "java",
            "name": "RecognizeCelebrities",
            "request": "launch",
            "mainClass": "com.example.rekognition.RecognizeCelebrities",
            "projectName": "RekognitionV2-RekognitionV2",
            "args": "C:\\Users\\GabrielAlves\\Desktop\\piratas-do-caribe.jpg"
        }
```