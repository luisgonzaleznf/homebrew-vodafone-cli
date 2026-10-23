# homebrew-vodafone-cli

Homebrew tap for [vodafone-cli](https://github.com/luisgonzaleznf/vodafone-cli), a JSON-first CLI
for your own Mi Vodafone (Vodafone España) account.

```bash
brew install luisgonzaleznf/vodafone-cli/vodafone
```

Then sign in with `vodafone auth login`. To keep the session alive with a daily refresh, run
`brew services start luisgonzaleznf/vodafone-cli/vodafone`.

The formula is maintained in the vodafone-cli repository and copied here at each release. Report
issues and send changes there. Not affiliated with or endorsed by Vodafone.
