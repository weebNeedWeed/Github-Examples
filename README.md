# Github-Examples
A repo containing GitHub for programmatic examples
 
## Webhook
https://kontent.ai/blog/how-to-trigger-github-action-using-webhook-with-no-code/

## how to solve "Nested mappings are not allowed in compact mappings at line 28"
### NOTE: this is because the colon(:) sign in the string
```yaml
run: echo "Issue labels: ${{ join(github.event.issue.labels.*.name, ', ') }}"
```
https://github.com/github/vscode-github-actions/issues/205 