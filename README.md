
# nodejs_test Step
Run test use `npm test`

### INPUTS
* `FLOW_ENABLE_FAILURE` - 

## EXAMPLE 

```yml
steps:
  - name: nodejs_test
    enable: true
    failure: true
    plugin:
      name: nodejs_test
      inputs:
        - FLOW_ENABLE_FAILURE=$FLOW_ENABLE_FAILURE
```
