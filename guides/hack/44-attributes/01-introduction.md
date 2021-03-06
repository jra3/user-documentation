Attributes are a holder of metadata for any [reflectable](http://php.net/manual/en/intro.reflection.php) piece of code. This includes functions, classes, interfaces, traits, etc. 

Except for a few [special attributes](special.md), attributes are a purely syntactic entity. They lend themselves to tooling to accomplish tasks. For example, you can have documentation-based attributes, the contents of which are extracted by reflection.

@@ introduction-examples/simple.php @@

## Special Attributes

Some attributes have special meaning to both the Hack typechecker and HHVM. Here are the most common and useful ones:

- [`__Override`](special.md#__override)
- [`__ConsistentConstruct`](special.md#__consistentconstruct)
- [`__Memoize`](special.md#__memoize)
- [`__Deprecated`](special.md#__deprecated)

There are a few [much less common special attributes](special.md#uncommon) as well.
