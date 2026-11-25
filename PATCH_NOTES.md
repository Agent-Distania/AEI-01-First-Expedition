# Patch Notes

## 0.4.0 — Infrastructure & Exploration Update

### Added
- Restricted service wing connected to the Utility Room.
- Power Distribution Chamber.
- Service-wing access console.
- Optional discovery to scan.
- Messages for newly charted areas.

### Changed
- Expanded map to accommodate the new wing.
- Access to the new wing requires completing the main survey and recovering the maintenance index.
- Progression now includes investigation-based access.

### Removed
- None.

### Fixed
- Save migration for the new access system.
- Passage clearance issue in the new service wing.

## 0.4.1 — Deployment Hotfix

### Added
- Direct touchscreen activation for the Deploy Exploration Drone button.

### Changed
- Deployment ignores duplicate activation while the field view is already open.

### Removed
- None.

### Fixed
- Improved mobile deployment activation to address the drone not launching from the facility screen.

## 0.4.2 — Mobile Layout Hotfix

### Added
- Responsive short-screen layout rules for phones, with a compact field header and status bar.

### Changed
- The field viewport uses the full available phone width when desktop side panels are hidden.

### Removed
- None.

### Fixed
- Corrected the short-screen grid rule that left a narrow game view and unused black space on mobile.
- Reduced overlap in the mobile game header and footer status bar.

## 0.5.0 — Main Menu Update

### Added
- Main menu title screen with New Game and Continue options.
- Continue is disabled when no saved expedition is detected.

### Changed
- Facility screen is entered from the main menu.

### Removed
- None.

### Fixed
- New Game resets expedition progress to the initial state; an existing save is protected by a confirmation prompt.

## 0.5.1 — Communications Scrolling Hotfix

### Added
- Improved mobile touch scrolling behavior for the communications message list.

### Changed
- Communications list rerenders preserve the list scroll position.

### Removed
- None.

### Fixed
- Reduced scroll bounce and gesture interruption in the mobile communications list.
