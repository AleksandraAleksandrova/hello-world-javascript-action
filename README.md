# hello-world-javascript-action

This action prints "Hello" + the name of a person to greet to the log. If no name is provided, the default greeting is set to "Hello World".

## Inputs

### who-to-greet

**Required** The name of the person to greet. Default value is set to "World" in the action metadata file.

## Outputs

### time 

This is the time the greeting was made.

## Example usage in workflow     
If you want to use the latest release, use this:
```yaml
uses: AleksandraAleksandrova/hello-world-javascript-action@v1.0
with:
  who-to-greet: 'Anna Karenina'
```
     
If you want to use the latest version possible, use this:
```yaml
uses: AleksandraAleksandrova/hello-world-javascript-action@main
with:
  who-to-greet: 'Evelyn Hugo'
```
     
This action was created to GitHub documentation examples!   
[Create Javascript Action](https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action)