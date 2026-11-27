# Patch Notes

## 0.5.8 — Direct Expedition Button Input

### Added
- Direct touch and click handlers on Deploy Exploration Drone and Review Mission Brief.

### Changed
- Touch activation is handled on the buttons themselves instead of relying on parent-level event delegation.
- The document-wide touch fallback no longer intercepts these two controls.
- Decorative hero artwork is explicitly kept behind the expedition controls.

### Removed
- The competing parent-level pointer-up handler for deployment.

### Fixed
- Reworked the two expedition buttons after the previous event-routing changes failed to activate reliably on mobile.

## 0.5.7 — Deployment Hit-Test Fix

### Added
- A clear touch-friendly hit area for expedition deployment.

### Changed
- Decorative artwork no longer receives pointer input.
- Deployment controls are layered above the artwork.

### Removed
- None.

### Fixed
- Prevented the decorative hero-panel circle from intercepting taps intended for Deploy Exploration Drone.

## 0.5.7 — Deployment Hit-Test Fix

### Added
- A clear touch-friendly hit area for expedition deployment.

### Changed
- Decorative artwork no longer receives pointer input.
- Deployment controls are layered above the artwork.

### Removed
- None.

### Fixed
- Prevented the decorative hero-panel circle from intercepting taps intended for Deploy Exploration Drone.

## 0.5.6 — Touch Deployment Hotfix

### Added
- Separate, reliable activation paths for touch and mouse/keyboard.

### Changed
- Touch uses pointerup directly; mouse and keyboard use click.

### Removed
- Shared touch/click deployment path.

### Fixed
- Restored direct touchscreen deployment activation while retaining duplicate-start protection.

## 0.5.5 — Deployment Input Refactor (superseded)

### Added
- A delegated click path and a general touchscreen activation fallback.

### Changed
- Direct touch pointer-up handling was removed in this release.

### Removed
- The dedicated touch deployment handler.

### Fixed
- None. This release was superseded by 0.5.6 after touchscreen deployment stopped responding.

## 0.5.4 — Mobile Viewport & Scroll Stability

### Added
- Stable small-viewport framing for the facility interface on phones.

### Changed
- Communications filters and message actions refresh only the relevant panels instead of rebuilding the entire page.
- Mobile form controls use a 16px text size to prevent iOS Safari auto-zoom.

### Removed
- Manual facility scroll-position restoration during Communications refreshes.

### Fixed
- Corrected the mobile viewport-height fallback order.
- Reduced focus loss and layout repositioning during message filtering and management.

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

## 0.5.2 — Mobile Scroll Stability Hotfix

### Added
- Stable small-viewport height handling for mobile facility scrolling.

### Changed
- Communications rerenders preserve the facility page scroll position too.

### Removed
- None.

### Fixed
- Adjusted the mobile facility viewport to reduce scroll jumps when browser UI changes screen height.

## 0.5.3 — Mobile Communications Scroll Redesign

### Added
- One vertical scroll surface for the Communications Center on mobile.

### Changed
- Message cards expand naturally in the facility page on phones.

### Removed
- Nested mobile message-list scrolling.

### Fixed
- Reduced competing vertical scroll containers that could cause page snapping or unexpected scroll movement.
