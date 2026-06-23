# SM Scope Tracker Releases

Public desktop installer releases and update feed for SM Scope Tracker.

The application source stays private. This repository only hosts installer
assets and static JSON used by the desktop updater.

Update feed files:

- `latest.json` is the primary public feed used by current desktop builds.
- `api/updates/desktop/latest` mirrors the old cloud update response shape so
  the same JSON can be served from the legacy `api.svmrc.co` path if needed.

