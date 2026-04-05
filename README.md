# Assignment 1 - Childcare Keyworker App (SwiftUI)

This repository contains the MADD Assignment 1 iOS application built with SwiftUI. The app models a childcare keyworker workflow, including attendance, daily diary updates, incident reporting, messaging, notifications, and profile/settings flows.

## Project Overview

- Platform: iOS (SwiftUI)
- Architecture: MVVM-style separation using Models, Services, ViewModels, and Views
- Persistence/Data Source: Local in-app data/service managers for assignment scope
- UX Scope: Splash, onboarding, dashboard, daily operations, and communication features

## Main Features

- Attendance tracking screen
- Daily diary and end-of-day checklist workflow
- Incident recording with body map support
- Message inbox and message detail flow
- Notification center sheet
- Child profile and settings pages
- Reusable custom SwiftUI components (cards, badges, progress ring, toast, tab bar)

## Folder Structure

- `Assignment1/Models` - domain data models
- `Assignment1/Services` - app service managers
- `Assignment1/ViewModels` - screen/business logic
- `Assignment1/Views` - feature views by module
- `Assignment1/Components` - reusable UI components
- `Assignment1/Utilities` - app constants, validators, theme/haptics, extensions
- `Assignment1/SampleData` - sample seed data

## How To Run

1. Open `Assignment1.xcodeproj` in Xcode.
2. Select an iOS Simulator target.
3. Build and run the `Assignment1` scheme.

## Notes

- This repository was committed in step-by-step progress to reflect weekly development milestones for academic review.
- `.gitignore` is configured for Xcode/macOS artifacts.
