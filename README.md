# Welcome to slack_cluster_manager 👋
![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000)
![Prerequisite](https://img.shields.io/badge/yarn-%3E%3D1.19.1-blue.svg)
![Prerequisite](https://img.shields.io/badge/node-%3E%3D12.11.1-blue.svg)
[![Documentation](https://img.shields.io/badge/documentation-yes-brightgreen.svg)](https://github.com/code4kit/slack-cluster-manager#readme)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/code4kit/slack-cluster-manager/graphs/commit-activity)
[![License: MIT](https://img.shields.io/github/license/code4kit/slack_cluster_manager)](https://github.com/code4kit/slack-cluster-manager/blob/master/LICENSE)

> This bot can manage cluster in slack. *Cluster is like group and list in slack.

### 🏠 [Homepage](https://github.com/code4kit/slack-cluster-manager#readme)

## Prerequisites

- yarn >=1.19.1
- node >=12.11.1

## Install

```sh
yarn
```

## Usage

```sh
yarn start
```

## Run tests

```sh
yarn test
```

## Usage Slack Command


#### 1. Create cluster
 + without specify

     :fries: ```create clusterName```
 
 + specify the cluster is the batch or vc
 
     :fries: ```create clusterName --batch```
 
     :fries: ```create clusterName --vc```
 
 #### 2. Delete cluster
:fries: ```delete the clustName```

+ Example
    :fries: ```delete c4k```
 
 #### 3. Update cluster(add member to cluster)
 + Add single member
 
 :fries: ```update @slackUserName```
 
 + Add multiple members
 
  :fries: ```update @slackUserName @slackUserName``` 
 
 + Add everyone in the channel
 
  :fries: ```update @here```
 
 :notebook: Only the Authorize user can use the first three command.
 
 #### 4. Mention every cluster members
 
 :fries: ```mention cluseterName message```
 
 + Example:
     :fries: ```mention c4k just do it```
     
#### 5. Invite every cluster members to channel

:fries: ```invite clustName```

+ Example:
    :fries: ```invite c4k```
#### 6. Kick every cluster member from channel

:fries: ```kick clusterName```

+ Example:

    :fries: ```kick c4k```
    
#### 7. List every cluster members (only DM)

+ List one cluster

    :fries: ```list clusterName ```

+ List all clusters members

    :fries: ```list```

## Author

👤 **code4kit**

* Website: https://code4kit.slack.com/signup
* Github: [@code4kit](https://github.com/code4kit)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](https://github.com/code4kit/slack_cluster_management/issues).

## Show your support

Give a ⭐️ if this project helped you!


## 📝 License

Copyright © 2019 [code4kit](https://github.com/code4kit).

This project is [MIT](https://github.com/code4kit/slack-cluster-manager/blob/master/LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
