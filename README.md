# Patchkit-Actions

GitHub Action to wrap [Patchkit CLI tools](https://github.com/patchkit-net/patchkit-tools).

# Usage
```yaml
  - uses: Battle-Nations/Patchkit-Actions@main
    with:
        # Patchkit Application secret
        secret: ''

        # Patchkit User API key
        api-key: ''

        # Version label
        label: ''

        # Path to version files directory
        files: ''

        # Should draft version be overwritten if it already exists
        # Default: 'false'
        overwrite-draft: ''
```
