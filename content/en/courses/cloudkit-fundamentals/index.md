---
title: "CloudKit Fundamentals"
weight: 5
pluralsight_url: "https://www.pluralsight.com/courses/cloudkit-fundamentals"
resources:
    - src: cloudkit-fundamentals.png
      params:
          weight: -100
---

At the core of developing a seamless and collaborative data sharing experience for Apple's platforms is a thorough knowledge of CloudKit.

In this course, you'll learn to leverage Apple's flagship framework to achieve your app's remote data storage and data sharing requirements.

First, you'll learn how to configure CloudKit in your Xcode project and how to save, query, update, and delete data that your users store in iCloud. Next, you'll explore how to synchronize data across a user's devices. Finally, you'll discover how to handle CloudKit errors, test your app on physical devices, and deploy to production.

When you're finished with this course, you'll have a foundational knowledge of CloudKit that will help you provide a fluid, interactive data sharing experience.

<i class="fas fa-video"></i> [Watch CloudKit Fundamentals on Pluralsight](https://www.pluralsight.com/courses/cloudkit-fundamentals)


## Course Outline

### Module 1: Setting up CloudKit

The introduction to the course: the motivating factors for using CloudKit, course prerequisites, storyline overview, and a demo of the end product of the course.

The demo app for this course is a fun one! I put you in the scenario where we team up to build a hazard reporting app for our company's Safety Department. The final product will come complete with the ability to save, query, update, and delete text, images, and location information into iCloud using the CloudKit framework.

### Module 2: Modeling and Saving Data

Working with CloudKit begins with an understanding of the framework types that are used to model and save data. You'll learn about `CKRecord` and `CKAsset`, and save your first bits of data up to iCloud in this module.

### Module 3: Querying, Displaying, Updating, and Deleting Data

Once data has been saved into an iCloud database, the next logical step is to query it and display it within the app. I teach the `CKQuery` class for querying the CloudKit database for records and assets, so that data can be retrieved and displayed in the UI. And of course, once data is retrieved and displayed, it's fair game for updating and deleting.

### Module 4: Synchronizing Data Across Devices

The whole point of CloudKit is to make sure that data is accessible from more than one device. In this module, I teach how CloudKit uses subscriptions and push notifications to alert other users' devices to changes that have occurred in the CloudKit database, so that appropriate action can be taken in code to respond to those changes.

I also simulate hazard reports coming in from another user by adding data through the CloudKit Dashboard and watching the screen update with the new data in the iOS app.

### Module 5: Modeling Relationships Between Record Types

Modeling relationships between record types is important for many scenarios. In this module I teach how to work with `CKReference` in order to represent hierarchical relationships or ownership between model objects.

### Module 6: Planning for Production

Apple engineers repeatedly warn that CloudKit error handling isn't the difference between a good app and a bad app: it's the difference between a functional app and a non-functional app. To that end, I cover some of the most common CloudKit errors and how to handle them.

Once a version of the app is ready to put into users' hands, it's crucial to test it and move it to production. I discuss creating an ad-hoc deployment of the app and deploying the CloudKit database schema to production in preparation for the App Store.

## Course Resources

Demos of technology in action are *super* important to me. I packed as much demo content into the course as possible. You'll get to see the full array of dev-time experiences, not just the final "it works perfectly" outcomes.

The course also comes complete with working Xcode projects that gradually build you up to the final version of the app, one step at a time through each module.

## Feedback Welcome!

I welcome feedback on this course, and on other iOS development courses you might be interested in seeing in the Pluralsight library. Happy learning!
