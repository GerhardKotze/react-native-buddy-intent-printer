# react-native-buddy-intent-printer

All creds to https://github.com/lucasferreira/react-native-buddy-intent-printer

# Usage

import SendBuddyIntentAndroid from "react-native-buddy-intent-printer"

var stringData = JSON.stringify(data);

//NOTE Print directly
SendBuddyIntentAndroid.print(stringData).then(wasOpened => {
    //TODO if true - show Print completed modal
});

//NOTE View Print
SendBuddyIntentAndroid.viewPrint(stringData).then(wasOpened => {
    //TODO if true - show Print completed modal
});

## License

MIT
