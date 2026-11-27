# Milkerbunga
A Jailed Toolbox Application For iOS 14.0-15.7.1 And 16.0-16.1.2 Using [CVE-2022-46689](https://support.apple.com/en-us/102807)

Enable Notifications And Set Location Services To Always To Keep The App Running In The Background, Keep The Dock And Folder Background Hidden, And Prevent Some Sound Effects From Reverting

Warning: Some Changes Are Permanent On iOS 14.0-14.8.1

IPA Available In The [Releases](https://github.com/eliyaabouei-cloud/Milkerbunga/releases/latest) Section

Features

    Running In The Background To Keep Some Changes From Reverting
        From Running Tests, Battery Loss Is Negligible (~1% Per Day On Frequent), But That May Vary

    Springboard
        Hide Dock
        Hide Home Bar
        Hide Folder Backgrounds
        Disable Library Pod Background
        Disable Folder Background Blur
        Disable App Switcher Blur
        Hide CC Module Backgrounds
        Hide Notification Banner Background
        Notification Banner Shadow

    App Icon Themes
        Importing Folders Of App Icons
        No WebClips!

    Audio
        Custom Sound Efects
        Upload Your Own Sounds (Nearly Every Audio Format Allowed!)
        Max Upload Audio Size Of 150 KB, But Will Not Apply For Audio If Too Big!

    Passcode
        Customize Passcode Keys
        Import Passcode Keys Files (.passthm) From TrollTools

    Locks
        Importing Locks From TrollLock
        Custom Number Of Frames + Custom Animation Speeds

    Explore
        Find And Download Themes For Passcodes, Locks, And App Icons!
      
    Status Bar
        Change Carrier Name
        Change Secondary Carrier Name
        Change Battery Display Detail
        Change Time Text
        Change Breadcrumb Text
        Show Numeric WiFi/Cellular Strength
        Hide Many Icons In The Status Bar

    Other Tools
        Custom Fonts
        Lock Screen Footnote
        Notification Badges Changer (iOS 14-15 ONLY)
        Springboard Colors
        Settings App Customizer
        Calculator Error Message

    Misc
        Disable Shortcut Banners
        Turn Shortcuts Into App Clips
        Supervise Device Warning: Use The Features Below At Your Own Risk!
        Enable iPhone X Gestures
        Enable Dynamic Island (iOS 16+)

    Extra Tools
        Lock Screen Footnote
        No Lock On Respring
        Disable Low Power Alert

Installing

You Can Install Through AltStore, Sideloadly Or TrollStore (If Your Device Supports It)

Creating Custom Lock Animations

Lock Animations Are Very Simple To make For The Frames, Each Image Must Be Named "trollformation" With A Number A Afterwards (ie. trollformation1.png, trollformation2.png, trollformation3.png...). You Can Use Up To 120 Frames, Though I Am Not Sure Of The Exact Size Limit, Which Is Probably Much Less If Your Animation Is Not Exactly 40 Frames Or You Want To Customize The Display Length Of Each Frame, You Need To Define The Animations This Is Very Simple To Do:

    Create A JSON File Named animations.json
    Define The Values Format: "Frame Number": Time Interval Example:

{
    "1": 0,
    "2": 0.025,
    "10": 0.01,
    "15": 0.025
}

Explanation: You Do Not Need To State The Length Of Each Frame The Only Time That Absolutely Needs To Be Defined Is The First Frame If you Did Not Set A Time For The Frame, Milkerbunga Will Use The Time From The Last Frame The Time Interval Is How Long The Frame Stays On The Screen For Important: The Frame Number Must Be A String (Meaning In Quotes) Because Of How JSON Decoding Works
