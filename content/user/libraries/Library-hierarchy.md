<!--
title: "Library Hierarchy"
description: "View library dependencies hierarchy"
tags: "user library licenses hierarchy vulnerabilities sca"
-->

## How It Works

When an open source library is added to an application, all of the library's dependencies are also inherited. Some of these indirect dependencies may introduce vulnerable code into your applications. The [Contrast CLI](tools-cli.html#contrast-cli) identifies all open source libraries and sends the data to the Contrast UI, where you can visualize these libraries as a hierarchical dependency tree.

## Before You Start
 
To display library hierarchy for your application, Contrast must have to access your application code at pre-compile time - a different stage of the software development lifecycle (SDLC) than the Contrast agents collect. To do this, you must have installed and run the [Contrast CLI](tools-cli.html#contrast-cli) for your applications. 

## View Dependency Trees

To view your applications' library dependency trees, go to the **Applications** grid in the Contrast UI, and complete the following steps. 

* Select the application for which you want to view the library data.
* From the application's Overview page, navigate to the **Libraries** tab.  
* Select the dependency tree (graduated list) icon on the far right of the header to view the analysis of your application.  

In this view, Contrast displays the dependency tree for your application's libraries based on the data collected by the SCA tool. Within the tree, use the carets to expand sections for more information. 

<a href="assets/images/Library-hierarchy.png" rel="lightbox" title="View dependency trees"><img class="thumbnail" src="assets/images/Library-hierarchy.png"/></a>

<!-- What's the info displayed in the tree? Are these version numbers? Does it link to anything? --> 
