# Anvil Aerospace – Home Assistant Theme

An authentic Star Citizen Anvil Aerospace MFD-inspired theme for Home Assistant.

The design uses deep blue-black cockpit surfaces, illuminated cyan display text, muted blue panel layers, and restrained lime status indicators.

## Preview palette

| Role | Color |
|---|---|
| Main background | `#0B202B` |
| Panel surface | `#123342` |
| Raised surface | `#194657` |
| Display cyan | `#39D5D8` |
| Bright cyan | `#63F0EA` |
| Status lime | `#B6D58B` |
| Warning | `#F2D34F` |
| Alert | `#FF4058` |

## Installation

### HACS (recommended)

1. Open **HACS** in Home Assistant.
2. Open the three-dot menu and select **Custom repositories**.
3. Add `anazario93/ha-anvil-aerospace` and select **Theme** as the category.
4. Select **Anvil Aerospace** and download it.
5. Restart Home Assistant if prompted.

### Manual

1. Copy the `themes/anvil-aerospace.yaml` file into your Home Assistant `config/themes/` directory.
2. Ensure themes are enabled in `configuration.yaml`:

   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```

3. Restart Home Assistant.

## Enable the theme

In your Home Assistant user profile, select **Anvil Aerospace** under **Theme**.

## Design notes

- Dark blue/teal cockpit backgrounds and layered panel surfaces.
- Cyan primary text, icons, controls, and active states.
- Lime-green selection and success accents.
- Yellow warnings and red alerts reserved for status feedback.
- Subtle borders; no excessive neon glow.

The theme styles Home Assistant's standard frontend variables. Individual custom cards may define their own colors and may need card-specific styling.

## License

MIT
