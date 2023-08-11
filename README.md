# hello-world-javascript-action

This action prints "Hello" + the name of a person to greet to the log. If no name is provided, the default is "Hello World".

## Inputs

### who-to-greet

**Required** The name of the person to greet. Default value is set to "World" in the action metadata file.

## Outputs

### time 

This is the time the greeting was made.

## Example usage in workflow
```yaml
uses: AleksandraAleksandrova/hello-world-javascript-action@main
with:
  who-to-greet: 'Evelyn Hugo'
```

