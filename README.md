# dear-openapi

An OpenAPI description of the DEAR API https://inventory.dearsystems.com

## Generate

### Ruby

``` bash
openapi-generator generate \
-t ./generator/resources/ruby \
-i ./specification/dear-apikey-ruby.yaml \
-g ruby \
-o ./generator/output/dear-ruby \
-c ./generator/config-options/ruby/dear-ruby-config.json
```
