# AEI-01 — First Expedition

A browser-based exploration prototype about a research drone exploring an immense, ancient megastructure.

## Play
Open `index.html` in a modern browser. Keyboard and touchscreen controls are supported by the game build; device-specific behavior may vary by browser.

## Current version
**0.5.3 — Mobile Communications Scroll Redesign**

## Project notes
- This repository contains the current standalone HTML game build.
- The project is a work in progress. Areas, systems, and narrative details are subject to change.
- Mystery and setting canon are intentionally not fully explained in-game.

## Patch notes
See the in-game Patch Notes for version history. The current release's summary:

### 0.5.3 — Mobile Communications Scroll Redesign

**Added**
- One vertical scroll surface for the Communications Center on mobile.

**Changed**
- Message cards expand naturally in the facility page on phones.

**Removed**
- Nested mobile message-list scrolling.

**Fixed**
- Reduced competing vertical scroll containers that could cause page snapping or unexpected scroll movement.


### 0.5.1 — Communications Scrolling Hotfix

**Added**
- Improved mobile touch scrolling for the communications message list.

**Changed**
- Message list rerenders preserve the current scroll position.

**Removed**
- None.

**Fixed**
- Reduced scroll bounce and gesture interruption in mobile communications.

### 0.5.0 — Main Menu Update

**Added**
- Main menu title screen with New Game and Continue options.
- Continue is disabled if no save is detected.

**Changed**
- Facility screen is entered from the main menu.

**Removed**
- None.

**Fixed**
- New Game resets to initial state; existing progress is protected by a confirmation.

### 0.4.2 — Mobile Layout Hotfix

**Added**
- Responsive short-screen phone layout and compact field header/status bar.

**Changed**
- Field viewport now uses the full available phone width when desktop side panels are hidden.

**Removed**
- None.

**Fixed**
- Corrected the short-screen grid override that left the game view narrow and unused black space on mobile.
- Reduced mobile header and footer overlap.

### 0.4.1 — Deployment Hotfix

**Added**
- Direct touchscreen activation for Deploy Exploration Drone.

**Changed**
- Deployment ignores duplicate activation while field view is already open.

**Removed**
- None.

**Fixed**
- Improved mobile deployment activation.

### 0.4.0 — Infrastructure & Exploration Update

**Added**
- Restricted service wing connected to the Utility Room.
- Power Distribution Chamber with infrastructure details.
- Service-wing access console and optional scan discovery.
- Messages for newly charted areas.

**Changed**
- Map accommodates expanded area.
- Access requires completing the main survey and recovering the maintenance index.
- Progression uses investigation to access new areas.

**Removed**
- None.

**Fixed**
- Save migration for new access system.
- Service-wing passage clearance issue.
