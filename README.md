Current behavior
Renovate is configured to manage Dockerfile and Tekton pipeline file updates, as well as specific environment files. However, it’s not merging open pull requests for the env file updates just merging for dockerfile and tekton. The expected behavior is that Renovate should auto-merge pull requests for dependency updates according to the defined rules.

Expected behavior
Renovate should automatically merge PRa for updates in Dockerfiles, Tekton pipeline files, and .env files in the config/params.env path. The updates should be merged automatically according to the configuration settings.

Link to the Renovate issue or Discussion
https://github.com/renovatebot/renovate/discussions/31276 
