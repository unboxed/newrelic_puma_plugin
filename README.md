### Instructions for running the Puma agent

1. Go to <a href="https://github.com/unboxed/newrelic_puma_plugin/tags" target="_blank">the tags list</a> and find the latest archive.
2. Download and extract the source
3. Run `bundle install`
4. Copy `config/template_newrelic_plugin.yml` and rename file `config/newrelic_plugin.yml`
5. Replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key
6. Set the location of the puma state file in `config/newrelic_plugin.yml` (Note: your puma control has to bind to tcp)
7. Execute `./newrelic_puma_agent`
8. Go back to the Plugins list, and after a brief period you will see an entry for the Puma plugin