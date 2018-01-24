# slack-files-purge
Ruby script to purge files from Slack in order to free up file space.

Fill in the token field with your generated [legacy token](https://api.slack.com/custom-integrations/legacy-tokens).

The API key you generate is tied to your username and your username's permissions. This means you can only "see" files in public channels, and in private channels and Direct Messages you are a part of.

There are a lot of files uploaded by someone else to Direct Messages or private channels you aren't in. Either get access to those channels, or have the other users generate API keys and run this script.
