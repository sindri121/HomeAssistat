# HomeAssistat

My Home Assistant configuration repository.

## Structure

| File / Directory | Description |
|---|---|
| `configuration.yaml` | Main Home Assistant configuration |
| `automations.yaml` | Automation rules |
| `scripts.yaml` | Scripts |
| `scenes.yaml` | Scenes |
| `sensors.yaml` | Sensor definitions |
| `secrets.yaml.example` | Template for `secrets.yaml` (copy and fill in values) |
| `themes/` | Custom UI themes |

## Setup

1. Copy `secrets.yaml.example` to `secrets.yaml` and fill in your values.
   `secrets.yaml` is listed in `.gitignore` and will **not** be committed.
2. Place your Home Assistant configuration files here.
3. Restart Home Assistant to apply changes.

## Resources

- [Home Assistant Documentation](https://www.home-assistant.io/docs/)
- [Configuration basics](https://www.home-assistant.io/docs/configuration/)
