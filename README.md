# Contax
A fully-featured mobile application to store contacts within your network and linking to various third-party social networks

![Design](https://i.imgur.com/b2EZcie.png)  

## Core Features:
* Login auth with Google or Apple
* When user creates an account, automatically generate the QR code linking to their Contax profile
* Allow the user to link social profiles through third-party authorization
* This allows automatically following their network on authorized applications when their QR code is scanned
* Allows user to browse their contact’s profiles directly from the app
* Allow users to upload contact card QR code from camera roll
* Automatically update local contact details if a contact updates their social profiles on their profile (automatically sync with backend db)
* Should be able to sync contacts to/from the camera roll, with the ability to import camera roll contacts with platform profiles

## Design Features
* Integrated QR code scanner
* FlatList used on contacts page to avoid rendering everything
* Customizable Themes with several oob themes
  * Primary color
  * Background color
  * Accent color
* Swipe to switch screens, following central carousel design

## Technical Architecture:
* Compatible with Web, IOS, and Android through React Native
* Firebase back end for highly flexible scaling
* Try to use as much serverless for backend APIs as possible
  * But also need to keep in mind that the more that can run locally, the better

