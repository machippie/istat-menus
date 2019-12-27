
## Default Variables

### istat_menus_started

Start in background after install

#### Default value

```yaml
istat_menus_started: true
```

### istat_menus_user

User to run user-specific commands

#### Default value

```yaml
istat_menus_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
