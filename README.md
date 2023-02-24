# link-jira-action

Github Action to link a JIRA issue to the PR based on PR title


## Example Usage

```yaml
- uses: jackpocket/link-jira-action@v1
        with:
          jira-base-url: https://FAKE.atlassian.net
          jira-email: secrets.FAKE_JIRA_EMAIL
          jira-token: secrets.FAKE_JIRA_TOKEN
```


Uses the PR Title (not the branch) for searching for JIRA issue to ensure that we have consistent PR titles.