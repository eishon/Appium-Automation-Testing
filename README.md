## Appium Automation Testing

This is BoilerPlate project for Appium Automation Testing

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources. Where you will paste the testing code.
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Sample Session Script
### Android

    {
        "deviceName": "device_name",
        "platformName": "android",
        "appPackage": "build_identifier",
        "appActivity": "launcher_activity",
        "noReset": true
    }

### iOS

    {
        "deviceName": "device_name/udid",
        "platformName": "iOS",
        "platformVersion": "iOS",
        "app": "location of the .app file",
        "noReset": true,
        "automationName": "XCUITest" ,
    }