+++
title = "Cucumber Scenarion Class"
author = ["r_hasan"]
description = "short descriptions for io.cucumber.java.Scenario class methods, annotaions and others."
date = 2022-11-25T00:00:00+06:00
draft = false
+++

## Preface {#preface}

This class is under io.cucumber.java8 package. We can use this as parameter in before and after hook methods. It helps to write text and embedding media into reports and inspecting results. This class extends java.lang.Object class.

> Note: This class is not intended to be used to create reports. In that particular intention using \`io.cucumber.plugin.Plugin\` class would be
> more precise and this has much richer access.


## Methods and their usage {#methods-and-their-usage}


### attach {#attach}

-   description: Attach data to the report(s).
-   examples:
    ```java
     // Attach a screenshot. See your UI automation tool's docs for
     // details about how to take a screenshot.
     scenario.attach(pngBytes, "image/png", "Bartholomew and the Bytes of the Oobleck");
    ```


### getSourceTagNames {#getsourcetagnames}

-   description: returns tags of this scenario.


### getStatus {#getstatus}

-   description: returns the current status of this test case


### isFailed {#isfailed}

-   description: true if and only if getStatus() returns "failed"


### log {#log}

-   description: Outputs some text into the report.


### getName {#getname}

-   description: returns the name of the Scenario


### getId {#getid}

-   description: returns the id of the Scenario.


### getUri {#geturi}

-   description: returns the uri of the Scenario.


### getLine {#getline}

-   description: the line in the feature file of the Scenario. If this is a Scenario from Scenario Outlines this will return the line of the example row in the Scenario Outline.


## Inherited Methods (important ones) {#inherited-methods--important-ones}


### getClass {#getclass}

-   description: returns The Class object that represents the runtime class of this object.


## Assests {#assests}

-   [javadoc documentation](https://javadoc.io/static/io.cucumber/cucumber-java8/6.9.1/io/cucumber/java8/Scenario.html)
