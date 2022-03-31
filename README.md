# IssuesFromGitHub
GitHubから収集したIssueのリポジトリです。
GitHub上にあるOrganizationに登録されているリポジトリからIssueを収集しSRGMを適用できるフォーマットにしたものです。
## Organization
収集したOrganizaionと対応するリポジトリは以下の通りです。
|Organizaion|Repository|URL|
|--|--|--|
|google|guava||
|google|dagger||
|google|closure-compiler||
|google|error-prone||
|google|tink||
|google|glog||
|microsoft|azure-pipelines-agent||
|microsoft|CBL-Mariner||
|microsoft|charticulator||
|microsoft|fluentui-react-native||
|microsoft|Microsoft365DSC||
|microsoft|kiota||
|microsoft|msquic||
|microsoft|Recognizers-Text||
|microsoft|TypeScript-Website||
## Data
収集したデータは以下のディレクトリにあります。
``` sh
IssuesFromGitHub
├── README.md
└── data
    ├── google
    │   ├── closure-compiler.csv
    │   ├── dagger.csv
    │   ├── error-prone.csv
    │   ├── glog.csv
    │   ├── guava.csv
    │   └── tink.csv
    └── microsoft
        ├── CBL-Mariner.csv
        ├── Microsoft365DSC.csv
        ├── Recognizers-Text.csv
        ├── TypeScript-Website.csv
        ├── azure-pipelines-agent.csv
        ├── charticulator.csv
        ├── fluentui-react-native.csv
        ├── kiota.csv
        ├── msquic.csv
        ├── vscode.csv
        └── vstest.csv
```