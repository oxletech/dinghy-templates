This repository contains Armory.io Dinghy modules that are used by pipelines.

| refID | Module | Description |
|--|--|--|
| 1 | determine_deployed_app_version.stage.module | Determine version of application currently deployed |
| 2 | confirm_deployment.stage.module | Confirm that deploy should continue |
| 3 | lookup_base_ami_id.stage.module | Lookup AMI ID for Base AMI |
| 4 | bake_ami.stage.module | Bake AMI |
| 5 | deploy-aws-dev.stage.module | Deploy application to AWS |
| 6 | publish_deploy_events_graphite.stage.module | Publish deploy events to Graphite |
| 7 | publish_deploy_events_rollbar.stage.module | Publish deploy events to Rollbar |

