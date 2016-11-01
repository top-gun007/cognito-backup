# cognito-backup 👫➡💾
Amazon doesn't have any way of backing up their AWS Cognito User Pools.
cognito-backup is a CLI for backing up the data. <b>Note: AWS has no way of extracting the passwords of your users so you need to store these separately 😵</b>

## Install
```
npm install -g cognito-backup
```

## Usage
```
cognito-backup backup-users <user-pool-id> <options>
```

## Examples
```
cognito-backup backup-users eu-west-1_1_12345
cognito-backup backup-users eu-west-1_1_12345 --region eu-west-1 --file mypool.json
```

## TODO
```
- Implement restore
```