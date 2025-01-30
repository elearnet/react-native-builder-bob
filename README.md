## npx locally in case for some occasion issues

usages

npx pathToThePackage options  
npx ../../libs/react-native-builder-bob/packages/react-native-builder-bob --version  
npx ../libs/react-native-builder-bob/packages/create-react-native-library --help

## for https://github.com/callstack/react-native-builder-bob/issues/755

npx ../libs/react-native-builder-bob/packages/create-react-native-library nm-for-test  
replace "react-native-builder-bob": with "react-native-builder-bob-fix"  
yarn install  
then run bob build
