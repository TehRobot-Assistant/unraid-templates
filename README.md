# TehRobot Unraid Templates

Docker container templates for Unraid Community Applications.

## Available Containers

| Container | Description | Docker Hub |
|-----------|-------------|------------|
| [docker-manager](https://github.com/TehRobot-Assistant/docker-manager) | Manage Docker containers remotely with secure login and user permissions | [tehrobot/docker-manager](https://hub.docker.com/r/tehrobot/docker-manager) |
| [media-optimizer](https://github.com/TehRobot-Assistant/media-optimizer) | Analyse Sonarr/Radarr libraries for space hogs and codec upgrades | [tehrobot/media-optimizer](https://hub.docker.com/r/tehrobot/media-optimizer) |
| [plex-dupefinder](https://github.com/TehRobot-Assistant/plex-dupefinder) | Find and remove duplicate media files using Plex and Sonarr/Radarr scoring | [tehrobot/plex-dupefinder](https://hub.docker.com/r/tehrobot/plex-dupefinder) |
| [restore-runner](https://github.com/TehRobot-Assistant/restore-runner) 🧪 beta | Automated backup restore rehearsal — proves your Restic / Borg / Kopia backup is still restorable | [tehrobot/restorerunner](https://hub.docker.com/r/tehrobot/restorerunner) |
| [patch-pulse](https://github.com/TehRobot-Assistant/patch-pulse) 🧪 beta | Release notes + CVE context for your Docker container updates | [tehrobot/patchpulse](https://hub.docker.com/r/tehrobot/patchpulse) |

## Installation

### Community Applications

Add this URL as a template repository in Unraid Community Applications:

```
https://github.com/TehRobot-Assistant/unraid-templates
```

### Manual Install

1. Download the template XML for the container you want
2. Save to your Unraid flash drive:
   ```
   /boot/config/plugins/dockerMan/templates-user/<container-name>.xml
   ```
3. Go to **Docker** > **Add Container** and select the template

## Template Downloads

| Container | XML Template |
|-----------|--------------|
| docker-manager | [Download](https://raw.githubusercontent.com/TehRobot-Assistant/unraid-templates/main/docker-manager/docker-manager.xml) |
| media-optimizer | [Download](https://raw.githubusercontent.com/TehRobot-Assistant/unraid-templates/main/media-optimizer/media-optimizer.xml) |
| plex-dupefinder | [Download](https://raw.githubusercontent.com/TehRobot-Assistant/unraid-templates/main/plex-dupefinder/plex-dupefinder.xml) |
| restore-runner (beta) | [Download](https://raw.githubusercontent.com/TehRobot-Assistant/unraid-templates/main/restore-runner/restore-runner.xml) |
| patch-pulse (beta) | [Download](https://raw.githubusercontent.com/TehRobot-Assistant/unraid-templates/main/patch-pulse/patch-pulse.xml) |

## Support

For issues with specific containers, use the GitHub Issues page for that container.
