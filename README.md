# GraphQL plugin for SublimeText

GraphQL language definition for TextMate and SublimeText. This builds on the language files commonly used and adds more fine grained matching.

## Installation and Use

If you haven't already, [install Package Control](https://sublime.wbond.net/installation), then select `GraphQL` from the `Package Control: Install Package` dropdown list in the Command Palette.

To set this as your default GraphQL syntax, open a .graphql file, then select `View -> Syntax -> Open all with current extension as... -> GraphQL`.


## Todo

The plan is have the same capabilities as `GraphiQL`. For this propose, we need:

* Autocompletion based on a JSON or pretty-printed schema.
* Enable querying against the schema
* Validation

*All those are easy achievable using the `graphql-core` implementation, as Sublime Text uses Python under the hood for the plugins*.


## Contributing

Edit the yaml files with the `YAML-XXX` extensions, convert them to plist xml files, and send in a pull request. 
The easiest way to do this is by using [SublimeText Package Dev](https://github.com/SublimeText/PackageDev). You can do all of the above without leaving sublime text.

YAML is used since it's a lot more compact and easier to edit than xml.