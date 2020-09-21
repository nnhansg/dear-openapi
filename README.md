# dear-openapi

An OpenAPI description of the DEAR API https://inventory.dearsystems.com

## Generate

### Ruby

``` bash
# For MacOS
export RUBY_POST_PROCESS_FILE="$HOME/.rbenv/shims/rubocop -a"

openapi-generator generate \
-t ./generator/resources/ruby \
-i ./specification/dear-inventory-apikey-ruby.yaml \
-g ruby \
-o ./generator/output/dear-inventory-ruby \
-c ./generator/config-options/ruby/dear-inventory-ruby-config.json
```
