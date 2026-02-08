# TehRobot Unraid Templates

Docker container templates for Unraid (6.10.0-rc1 and newer).

## Available Templates

| Container | Description |
|-----------|-------------|
| [docker-manager](https://github.com/TehRobot-Assistant/docker-manager) | Manage Docker containers remotely with secure login and user permissions |
| [media-optimizer](https://github.com/TehRobot-Assistant/media-optimizer) | Analyze Sonarr/Radarr libraries for space hogs and codec upgrades |

## Installation (Unraid 6.10+)

> **Note:** Template Repositories have been removed in Unraid 6.10.0-rc1. Use one of the methods below instead.

### Option A: Community Applications (Recommended)

1. Download the template XML file
2. Save to your flash drive:
   ```
   /boot/config/plugins/community.applications/private/<container-name>/<container-name>.xml
   ```
3. Go to **Apps** → find it under the **Private** category
4. Click **Install**

### Option B: Docker Tab

1. Download the template XML file
2. Save to your flash drive:
   ```
   /boot/config/plugins/dockerMan/templates-user/<container-name>.xml
   ```
3. Go to **Docker** → **Add Container**
4. Select the template from the dropdown

## Template Downloads

| Container | XML Template |
|-----------|--------------|
| docker-manager | [Download](https://raw.githubusercontent.com/TehRobot-Assistant/unraid-templates/main/docker-manager/docker-manager.xml) |
| media-optimizer | [Download](https://raw.githubusercontent.com/TehRobot-Assistant/unraid-templates/main/media-optimizer/media-optimizer.xml) |

## Support

For issues with specific containers, please use the GitHub Issues page for that container.
