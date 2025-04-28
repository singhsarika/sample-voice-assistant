Testing with device using Google Assistant:
https://developer.android.com/develop/devices/assistant/test-tool

Using ADB:
1. adb shell am start -n com.sample.voiceassistantapp/.MainActivity -e "intent_name" "GET_FASTAG_BALANCE"
2. adb shell am start -W -a android.intent.action.VIEW -d "samplevoiceapp://openfeature" com.sample.voiceassistantapp
