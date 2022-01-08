Checkout repository to specified dir (even if destination dir is not empty)

# Usage

<!-- start usage -->
```yaml
- uses: Coderslab-core/checkout-and-move@v2
  with: 
    # Repository name with owner. For example, Coderslab-core/shared-actions
    # Required: yes
    repository:
    
    # Repository content target path. For example .github/actions (repository content will be merged with given path)
    # Required: yes
    dest-path:
    
    # Personal access token (PAT)
    # Required: no
    # Default: ""
    token:

    # Temporary path to checkout repo before it's content will be moved to destination path
    # Required: no
    # Default: tmp-shared-actions
    tmp-path:
```
