# Build Dependencies Report
GitHub Action that fetches detailed information for a list of dependencies and builds a report document

This tool is designed to work against the CSV file that is output by [streeva/read-dependencies-go](https://github.com/streeva/read-dependencies-go) or [streeva/read-dependencies-action](https://github.com/streeva/read-dependencies-action).

An exclude list can be provided if there are private project dependencies you don't want included in the report.

# Usage

See [action.yml](action.yml)