# Composer action

Uses the offical [composer docker image](https://hub.docker.com/_/composer)
With [hirak/prestissimo](https://github.com/hirak/prestissimo) installed

## Example usage

```yaml
steps:
  - name: Run composer
    uses: nick-zh/composer-php@master
    with:
      action: 'update'
      options: '-o'
```

