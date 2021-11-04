# cfn-nag-action-example

This serves as an example for using the [cfn-nag-sarif-action](https://github.com/stelligent/cfn-nag-sarif-action) Action to scan cloudformation templates.

## Templates

The sample cloudformation templates in `templates` include intential errors that cfn_nag will detect.

## Action Workflows

One workflow, `cfn-nag` scans all of the cloudformation templates and uploads them to Github Code Scanning