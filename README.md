# Patchkit-Actions

GitHub Action to wrap [Patchkit CLI tools](https://github.com/patchkit-net/patchkit-tools).

# Usage

## Upload a new version
```yaml
  - uses: Battle-Nations/Patchkit-Actions/upload@v2
    with:
        # Patchkit Application secret
        secret: ''

        # Patchkit User API key
        api-key: ''

        # Version label
        label: ''

        # Path to version files directory
        files: ''

        # Path to changelog file
        changelog-file: ''

        # Should draft version be overwritten if it already exists
        # Default: 'false'
        overwrite-draft: ''

        # Should draft version be published
        # Default: 'false'
        publish: ''
```

## Publish latest draft version
```yaml
  - uses: Battle-Nations/Patchkit-Actions/publish@v2
    with:
        # Patchkit Application secret
        secret: ''

        # Patchkit User API key
        api-key: ''
```
