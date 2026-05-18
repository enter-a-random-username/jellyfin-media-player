# Jellyfin Desktop

Jellyfin desktop client built with Qt WebEngine and [libmpv](https://github.com/mpv-player/mpv). Supports audio passthrough, hardware decoding, and playback of more formats without transcoding.

![Screenshot of Jellyfin Desktop](screenshots/video_player.png)

### Development Builds
Built from the latest commit on `master`.

## Building
See [dev/](dev/) for platform-specific build instructions.

## File Locations
Data is stored per-profile in a `profiles/<profile-id>/` subdirectory. The main configuration file is `jellyfin-desktop.conf`. You can also add `mpv.conf` to configure MPV directly.

**Linux:**
- Config: `~/.local/share/jellyfin-desktop/profiles/<profile-id>/`
- Cache: `~/.cache/jellyfin-desktop/profiles/<profile-id>/`
- Logs: `~/.local/share/jellyfin-desktop/profiles/<profile-id>/logs/`
