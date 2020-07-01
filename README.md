# Jottivity Firebase Rules

Unit tests for Firestore rules for [Jottivity](https://github.com/chiubaca/jottivity).

## Prerequisite steps 🐣 

Ensure you have firebase tools and Java install globally.

```powershell
# on windows
npm install -g firebase-tools
winget install --id="Oracle.JavaRuntimeEnvironment" --exact 
```

```bash
# on mac...
🤷
```

## Running Unit Tests 🧪

1. Ensure Firestore emulator is running in a seperate shell.

`firebase emululator:start`

2. Then in another shell run.

`npm run test`

## Deploy Rules 🚀 

`firebase deploy`

This will deploy modified Firestore rules to the Jottivity account.

> You must be logged into the jottivity account. Use - `firebase login`.