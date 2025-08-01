# Anthro.id (Website) Changelog
For tech-savvy person only. All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 2.0.0-alpha.28 (2025-08-01)
### Added
- "Open image in new tab" on images inside the article for mobile device.

### Changed
- Minor CSS tweaks on user-owned tickets page.
- Minor CSS tweaks on event ticketing purchase session.
- Fix inability to scroll the event ticketing purchase session page for devices that are lower than 720 pixels in height. (Thanks to Bee2001!)

## 2.0.0-alpha.27 (2025-07-30)
### Changed
- Fix an error where the header buttons remains unchanged after redirection for authenticated users.

## 2.0.0-alpha.26 (2025-07-30)
### Added
- OpenGraph or metadata to individuals event page, so it's visible when embedding to Discord or Telegram.

### Changed
- Fix incorrect timezone conversion on Start / End Time of the event.
- Change box description (above "Buy Tickets" button) to "Tickets available soon" instead of "Starts from Rp 0,-"
- Minor tweaks on ticket list UI.
- Fix incorrect API path when trying to change a password.

### Removed
- Ticket pricing details on each ticket displayed on list if the event does not charge platform fees.

## 2.0.0-alpha.1 - 2.0.0-alpha.25 (2025-01 - 2025-07-30)
### Added
- User profile.
- Event ticketing.
- Legal page.

### Changed
- Enhanced website security.
- Revamp article page.
- Separate API routes from Next.js to Express.js.
- Updated several pages such as articles list, homepage, etc.
- Updated website components such as header, loading screen, footer, etc.

There's more.