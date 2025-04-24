# IOS101 Final Project - Elizabeth Kushelevsky

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

**Note Taker**: Scan notes from class, then upload them to send automatically.

### App Evaluation

[Evaluation of your app across the following attributes]
- **Category:** Education/productivity
- **Mobile:** Camera, push
- **Story:** My university's office of disability services coordinates students to share notes with their peers who request accommodations, and note-takers can get paid for their work. However, the filing process is often clunky, files can be too large to send over email on certain devices, and there is no good reminder system to actually send notes. This solutions streamlines the process of scanning and sending notes.
- **Market:** Student note-takers
- **Habit:** Weekly task
- **Scope:** A clearly defined project, with stretch features in using the camera and sending POST requests.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* As a student note-taker, I can fill in my information just once, scan my notes directly from my phone into the app, and have it sent off for me.
* As a Disability Services administrator, I can have a student's notes sent to me with all the correct information.

**Optional Nice-to-have Stories**

* As a student note-taker, I can receive push notifications at the end of a week if I still need to submit my notes.

### 2. Screen Archetypes

- [ ] Home screen
* User can select existing class for which to submit notes
* User can join a new class

- [ ] Join class screen
* User can fill in information for a new class and save it
* User can join a new class

- [ ] Upload screen
* User can scan a document into the app
* User can automatically send off their notes for an associated week of the class

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* none

**Flow Navigation** (Screen to Screen)

- [ ] Home
* Join class (upon completion of join class)
* Upload (upon completion of upload)

- [ ] Join class
* Home

- [ ] Upload
* Home

## Wireframes

![IMG_04406C379E1E-1](https://github.com/user-attachments/assets/0b6592bf-ebf0-4ce6-9440-c5182cd65c68)


## Schema 

- [ ] Sprint 1
* Set up frames' general appearance.

- [ ] Sprint 2
* Set up dynamic contents on home frame and make sure they are updated from join frame.

- [ ] Sprint 1
* Work on uploading and SMTP.

### Networking

- SMTP - for sending files and course info
