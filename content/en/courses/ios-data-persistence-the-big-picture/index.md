---
title: "iOS Data Persistence: The Big Picture"
weight: 4
pluralsight_url: "https://www.pluralsight.com/courses/ios-data-persistence-big-picture"
resources:
    - src: ios-data-persistence-big-picture.png
      params:
          weight: -100
---

We've all been there. Do a search on the topic of "saving data in iOS" and you'll get *dozens* of search results mentioning at least six different frameworks and platforms, and a month's worth of reading.

Wouldn't it be nice to distill the possibilities down into *just what you need* in order to start down a path for persisting data in your app?

[iOS Data Persistence: The Big Picture](https://www.pluralsight.com/courses/ios-data-persistence-big-picture) will be worth the hour of your time.

<i class="fas fa-video"></i> [Watch iOS Data Persistence: The Big Picture on Pluralsight](https://www.pluralsight.com/courses/ios-data-persistence-big-picture)


## Course Outline

During this one hour course, you will learn the *reasons* for saving data to help ground you as you begin to traverse the data persistence landscape.

You will discover how to use technologies like **User Defaults** and **Property Lists**, and I will guide you on how to work with Swift's **Encodable** and **Decodable** protocols.

You will understand what you're getting into if you choose to work with **SQLite**, **Core Data**, or **Realm Database** for local data persistence. You will know how it feels to reach for a remote data storage option like **CloudKit**, **Realm Platform**, or **Firebase**.

Finally, you will see a clear picture of what it's like to design a **document-based application** and integrate your app's data with the **iOS Files app**.

When you're finished with this course, you will have the skills and knowledge you need to make an informed decision about putting a reliable data storage plan for your iOS app into action.

### Establishing the Data Persistence Landscape

To start you off on the right footing, this module establishes the data persistence possibilities and focuses in on the *reasons* for saving data so that you're persisting with a purpose.

- You will be introduced to a player profile matrix to help you analyze your data persistence options from a number of angles.
- You will get the feel for working with the Swift `Encodable` and `Decodable` protocols.

### Saving Settings and Configuration

Users are picky, aren't they? Everybody has preferences, so it's no wonder that you as a developer are often tasked with letting your users customize their experience within your app.

- You will learn how to manage user preferences with the `UserDefaults` system that's built in to iOS.
- Next, you will explore synchronizing settings with iCloud Key-Value Store.
- Finally, you will understand how to ship configuration for your app with Property Lists included in your application bundle.

### Saving Objects and Object Graphs

What if you only wanted to load a subset of the data into memory instead of being locked in to an all-or-nothing situation with `UserDefaults` or Property Lists? What if you needed to save a more complex data model that includes relationships?

Six technologies and frameworks are featured in this module: SQLite, Core Data, Realm Database, CloudKit, Realm Platform, and Firebase.

The goal is to help you answer two questions:

- "What am I getting myself into if I pick one persistence technology over another?"
- "How does it feel to work with this persistence technology in code?"

You will answer these questions by surveying the setup process for each technology, exploring the data modeling process, and getting the feel for creating, updating, deleting, querying, and observing data.

### Saving Data as Documents and Files

What if you need to encapsulate chunks of content together and save it all as a packaged-up file, as a single unit with a custom file extension? For that, you need to know about saving data as documents and files.

- You will explore the use case for building a document-based application.
- You will walk through designing a document as a subclass of `UIDocument`.
- You will learn to create and load documents from a Document Browser and customize your app's file extension.
- Finally, you will answer the question, "How do I get my app's files to show up in the iOS Files app?"

## Feedback Welcome!

My goal is to help you filter the noise: to distill an overwhelming amount of information down into the big picture possibilities so that you can make an informed decision about a reliable data storage plan for your iOS app.

I welcome feedback on this course, and on other iOS development courses you might be interested in seeing in the Pluralsight library. Happy learning!
