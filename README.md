# National Library of New Zealand Tools Rosetta Dashboard Processor

Runs gradle tasks for the Rosetta pre-ingest dashboard.

## Synopsis

Tasks that directly interact with the Rosetta pre-ingest dashboard.

## Motivation

We want to manage the jobs coming into Rosetta through the use of a global dashboard.

## Important

At this time there is no important information to impart.

## Requirements

## Usage

See the *Parameters* section for explanations for the different parameters.

### Process the board

Processes the board as shown by the example:
```
gradle processBoard \
    -PboardUri=<board-uri> \
    -PboardUsername=<board-username> \
    -PboardPassword=<board-password> \
    --info --stacktrace
```

### Parameters

#### boardUri
The URL of the Wekan board. The default is `localhost`.

#### boardUsername
The username for the Wekan board. This parameter must be specified.

#### boardPassword
The password for the Wekan board. This parameter must be specified.

## Contributors

See git commits to see who contributors are. Issues are tracked through the git repository issue tracker.

## License

&copy; 2019 National Library of New Zealand. All rights reserved. MIT license.
