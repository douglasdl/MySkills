
Create a Blank (TypeScript) project and set the app name to '.' to create iin the current folder using the folder name as the app name:
```sh
npx create-expo-app@latest --template
```

Start the project:
```sh
npx expo start
```

Create "eas.json" (Choose Y, All):
```sh
eas build:configure
```

Check if the project is OK to build:
```sh
npx expo-doctor
```

Generate the preview Local Builds:

- Android
```sh
npx eas build -p android --profile preview --local
```

- iOS
```sh
npx eas build -p ios --profile preview --local
```

Generate the preview Remote Builds

- Android
```sh
npx eas build -p android --profile preview
```

- iOS
```sh
npx eas build -p ios --profile preview
```

- Android and iOS
```sh
npx eas build -p all --profile preview
```

Generate the production Local Builds:

- Android
```sh
npx eas build -p android --profile production --local
```

- iOS
```sh
npx eas build -p ios --profile production --local
```

Generate the production Remote Builds

- Android
```sh
npx eas build -p android --profile production
```

- iOS
```sh
npx eas build -p ios --profile production
```

- Android and iOS
```sh
npx eas build -p all --profile production
```
