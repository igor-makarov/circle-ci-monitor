# CircleCI monitor based on [`wassup`](https://github.com/joshdholtz/wassup)

## Installation

1. Install wassup:  
   ```gem install wassup```
2. Set environment variables:
   * `WASSUP_CIRCLE_ORG_SLUG` - e.g. `gh/fastlane`
   * `WASSUP_CIRCLE_TOKEN` - personal token obtained from CircleCI

## Usage 

Poll several repos at once:

```
wassup Supfile <repo_name> [<repo_name>...] 
```

