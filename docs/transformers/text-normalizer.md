<span style="float:right;"><a href="https://github.com/RubixML/RubixML/blob/master/src/Transformers/TextNormalizer.php">[source]</a></span>

# Text Normalizer
This transformer converts the characters in all strings to lowercase.

**Interfaces:** [Transformer](api.md#transformer)

**Data Type Compatibility:** Categorical

> **Note:** ⚠️ This transformer cannot handle multibyte strings such as emjois properly. For multibyte support, use the [MultibyteTextNormalizer](multibyte-text-normalizer.md).

## Parameters
This transformer does not have any parameters.

## Additional Methods
This transformer does not have any additional methods.

## Example
```php
use Rubix\ML\Transformers\TextNormalizer;

$transformer = new TextNormalizer();
```
