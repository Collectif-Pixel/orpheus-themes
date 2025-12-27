# Orpheus Themes Registry

Official theme registry for [Orpheus](https://github.com/Collectif-Pixel/orpheus).

## Browse Themes

```bash
orpheus search
```

## Submit Your Theme

1. Create your theme repository with `theme.html` and `package.json`
2. Fork this repository
3. Add your theme to `registry.json`
4. Submit a Pull Request

### Registry Format

```json
{
  "name": "@username/theme-name",
  "displayName": "Theme Name",
  "description": "Short description",
  "author": "username",
  "tags": ["tag1", "tag2"]
}
```

## Guidelines

- Theme must have a valid `theme.html`
- Include a `package.json` with metadata
- Add a preview image in your repo (optional but recommended)
- Use descriptive tags
