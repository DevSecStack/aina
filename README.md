# Action in Action

## Usage

```
  - name: Run Another Action with Pre and Post Steps
    uses: devsecstack/aina@latest
    with:
        pre: |
          echo "This is a pre step"
        action: actions/setup-node@v3
        post: |
          echo "This is a post step"
```

## Advantages

- **Automation**: Streamlines repetitive tasks, saving time and reducing errors.
- **Consistency**: Ensures tasks are performed the same way every time.
- **Efficiency**: Increases productivity by handling tasks quickly and accurately.
- **Scalability**: Easily scales to handle larger workloads without additional effort.
