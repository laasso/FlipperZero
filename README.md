# FlipperZero Payloads Repository

![FlipperZero Logo](images/flipperzero.jpg)

Welcome to the FlipperZero Payloads Repository! This repository contains a collection of payloads designed to be exported and executed on the Flipper Zero device across various operating systems and platforms.

## About Flipper Zero

Flipper Zero is a versatile multi-tool device designed for security professionals, hackers, and enthusiasts. It features a wide range of capabilities, including RFID emulation, NFC cloning, Bluetooth sniffing, infrared control, and more. With its open-source architecture, Flipper Zero allows users to customize and extend its functionality through custom payloads and firmware.

## Xtreme-Firmware

For an enhanced Flipper Zero experience, we recommend using Xtreme-Firmware. Xtreme-Firmware is a custom firmware for Flipper Zero that unlocks additional features and optimizations, providing users with greater flexibility and control over their devices. You can find more information and download the latest version of Xtreme-Firmware from the [official website](https://flipper-xtre.me/update/).

## Repository Summary

This repository is organized into folders based on different payload categories and supported platforms. Here's a brief summary:

- **BadUSB**: Payloads for USB-based attacks on various platforms.
- **NFC**: Payloads and tools related to NFC technology, such as Amiibo manipulation.
- **RFID**: Payloads and tools for RFID-based attacks and emulation.

<details>
  <summary>Click to Expand Repository Structure</summary>


- **BadUSB**
  - **GNU-Linux**
    - **Execution**
      - [ChangeGitRemoteLink](badUsb/GNU-Linux/Execution/ChangeGitRemoteLink)
      - [ChangeMacAddress_Linux](badUsb/GNU-Linux/Execution/ChangeMacAddress_Linux)
      - [ChangeNetworkConfiguration_Linux](badUsb/GNU-Linux/Execution/ChangeNetworkConfiguration_Linux)
      - [Defend_yourself_against_AtlasVPN_bugdoor](badUsb/GNU-Linux/Execution/Defend_yourself_against_AtlasVPN_bugdoor)
      - [Edit_The_Default_Real_App_With_An_Arbitrary](badUsb/GNU-Linux/Execution/Edit_The_Default_Real_App_With_An_Arbitrary)
      - [EncryptAllDocuments_Linux](badUsb/GNU-Linux/Execution/EncryptAllDocuments_Linux)
      - [ExploitingAnExecutableFile](badUsb/GNU-Linux/Execution/ExploitingAnExecutableFile)
      - [Persistent_Keylogger-Telegram_Based](badUsb/GNU-Linux/Execution/Persistent_Keylogger-Telegram_Based)
      - [SendEmailThroughThunderbird](badUsb/GNU-Linux/Execution/SendEmailThroughThunderbird)
      - [Set_An_Arbitrary_And_Persistent_Tor_Circuit](badUsb/GNU-Linux/Execution/Set_An_Arbitrary_And_Persistent_Tor_Circuit)
        - [assets](badUsb/GNU-Linux/Execution/Set_An_Arbitrary_And_Persistent_Tor_Circuit/assets)
      - [SetArbitraryVPN_Linux](badUsb/GNU-Linux/Execution/SetArbitraryVPN_Linux)
      - [Telegram_Persistent_Connection_Linux](badUsb/GNU-Linux/Execution/Telegram_Persistent_Connection_Linux)
      - [Telegram_Persistent_Reverse_Shell_Linux](badUsb/GNU-Linux/Execution/Telegram_Persistent_Reverse_Shell_Linux)
    - **Exfiltration**
      - [ExfiltrateDocumentsFolder_Linux](badUsb/GNU-Linux/Exfiltration/ExfiltrateDocumentsFolder_Linux)
      - [ExfiltrateEmailAndPasswordByPhising_Linux](badUsb/GNU-Linux/Exfiltration/ExfiltrateEmailAndPasswordByPhising_Linux)
      - [ExfiltrateLogFiles_Linux](badUsb/GNU-Linux/Exfiltration/ExfiltrateLogFiles_Linux)
      - [ExfiltrateNetworkConfiguration_Linux](badUsb/GNU-Linux/Exfiltration/ExfiltrateNetworkConfiguration_Linux)
      - [ExfiltrateNetworkTraffic_Linux](badUsb/GNU-Linux/Exfiltration/ExfiltrateNetworkTraffic_Linux)
      - [ExfiltratePhotosThroughShell](badUsb/GNU-Linux/Exfiltration/ExfiltratePhotosThroughShell)
      - [ExfiltrateProcessInfo_Linux](badUsb/GNU-Linux/Exfiltration/ExfiltrateProcessInfo_Linux)
      - [ExfiltrateSudoPasswordByPhising_Linux](badUsb/GNU-Linux/Exfiltration/ExfiltrateSudoPasswordByPhising_Linux)
      - [ExfiltrateWiFiPasswords_Linux](badUsb/GNU-Linux/Exfiltration/ExfiltrateWiFiPasswords_Linux)
    - **Incident_Response**
      - [Auto-Check_Cisco_IOS_XE_Backdoor_based_on_CVE-2023-20198_and_CVE](badUsb/GNU-Linux/Incident_Response/Auto-Check_Cisco_IOS_XE_Backdoor_based_on_CVE-2023-20198_and_CVE)
        - [assets](badUsb/GNU-Linux/Incident_Response/Auto-Check_Cisco_IOS_XE_Backdoor_based_on_CVE-2023-20198_and_CVE/assets)
      - [Exploit_Citrix_NetScaler_ADC_and_Gateway_through_CVE-2023-4966](badUsb/GNU-Linux/Incident_Response/Exploit_Citrix_NetScaler_ADC_and_Gateway_through_CVE-2023-4966)
        - [assets](badUsb/GNU-Linux/Incident_Response/Exploit_Citrix_NetScaler_ADC_and_Gateway_through_CVE-2023-4966/assets)
    - **Phishing**
      - [StandardPhishingAttack_Linux](badUsb/GNU-Linux/Phishing/StandardPhishingAttack_Linux)
      - [StandardPhishingPayloadUsingKdialog_Linux](badUsb/GNU-Linux/Phishing/StandardPhishingPayloadUsingKdialog_Linux)
    - **Prank**
      - [ChangeDesktopWallpaper_LinuxKDE](badUsb/GNU-Linux/Prank/ChangeDesktopWallpaper_LinuxKDE)
      - [Change_The_App_That_Will_Be_Runned](badUsb/GNU-Linux/Prank/Change_The_App_That_Will_Be_Runned)
      - [SendTelegramMessages_Linux](badUsb/GNU-Linux/Prank/SendTelegramMessages_Linux)
      - [This_damn_shell_doesn_t_work___so_sad!-KALI](badUsb/GNU-Linux/Prank/This_damn_shell_doesn_t_work___so_sad!-KALI)
      - [This_damn_shell_doesn_t_work___so_sad!-LINUX](badUsb/GNU-Linux/Prank/This_damn_shell_doesn_t_work___so_sad!-LINUX)
  - **Mobile**
    - **Android**
      - **Bruteforce**
    - **iOS**
      - **BruteForce**
      - **Prank**
        - [Call_Someone_With_An_iPhone](badUsb/Mobile/iOS/Prank/Call_Someone_With_An_iPhone)
        - [Delete_A_Reminder_With_An_iPhone](badUsb/Mobile/iOS/Prank/Delete_A_Reminder_With_An_iPhone)
        - [Edit_A_Reminder_With_An_iPhone](badUsb/Mobile/iOS/Prank/Edit_A_Reminder_With_An_iPhone)
        - [Play_A_Song_With_An_iPhone](badUsb/Mobile/iOS/Prank/Play_A_Song_With_An_iPhone)
  - **Windows**
    - **AppMngt**
      - [Add_An_Excepiton_To_Avast_Antivirus](badUsb/Windows/AppMngt/Add_An_Excepiton_To_Avast_Antivirus)
      - [ChangeGitRemoteLink](badUsb/Windows/AppMngt/ChangeGitRemoteLink)
      - [CloseAllApplications_Windows](badUsb/Windows/AppMngt/CloseAllApplications_Windows)
      - [Install_And_Run_Any_Arbitrary_Executable-No_Internet_And_Root_Needed](badUsb/Windows/AppMngt/Install_And_Run_Any_Arbitrary_Executable-No_Internet_And_Root_Needed)
        - [assets](badUsb/Windows/AppMngt/Install_And_Run_Any_Arbitrary_Executable-No_Internet_And_Root_Needed/assets)
      - [Stop_A_Single_Process_In_Windows](badUsb/Windows/AppMngt/Stop_A_Single_Process_In_Windows)
      - [Uninstall_A_Specific_App_On_Windows_Through_Control_Panel](badUsb/Windows/AppMngt/Uninstall_A_Specific_App_On_Windows_Through_Control_Panel)
    - **Exfiltration**
      - [Create_And_Exfiltrate_A_Webhook_Of_Discord](badUsb/Windows/Exfiltration/Create_And_Exfiltrate_A_Webhook_Of_Discord)
      - [ExfiltrateComputerScreenshots](badUsb/Windows/Exfiltration/ExfiltrateComputerScreenshots)
      - [ExfiltrateProcessInfo_Windows](badUsb/Windows/Exfiltration/ExfiltrateProcessInfo_Windows)
      - [Exfiltrates_the_entire_database_of_the_Notion_client](badUsb/Windows/Exfiltration/Exfiltrates_the_entire_database_of_the_Notion_client)
      - [Exfiltrate_Windows_Product_Key](badUsb/Windows/Exfiltration/Exfiltrate_Windows_Product_Key)
        - [assets](badUsb/Windows/Exfiltration/Exfiltrate_Windows_Product_Key/assets)
      - [Export_all_saved_certificates_with_Adobe_Reader](badUsb/Windows/Exfiltration/Export_all_saved_certificates_with_Adobe_Reader)
      - [Export_Cookies_From_Firefox](badUsb/Windows/Exfiltration/Export_Cookies_From_Firefox)
      - [Exports_all_the_links_of_the_downloads](badUsb/Windows/Exfiltration/Exports_all_the_links_of_the_downloads)
      - [Netstat_Windows](badUsb/Windows/Exfiltration/Netstat_Windows)
      - [ProtonVPNConfigFile_Windows](badUsb/Windows/Exfiltration/ProtonVPNConfigFile_Windows)
      - [Tree_structure_of_the_operating_system](badUsb/Windows/Exfiltration/Tree_structure_of_the_operating_system)
    - **Misc**
      - [ChangeGitRemoteLink](badUsb/Windows/Misc/ChangeGitRemoteLink)
      - [CloseAllApplications_Windows](badUsb/Windows/Misc/CloseAllApplications_Windows)
      - [Make_Windows_performant_(but_ugly_and_boring)](badUsb/Windows/Misc/Make_Windows_performant_(but_ugly_and_boring))
      - [SendEmailThroughThunderbird](badUsb/Windows/Misc/SendEmailThroughThunderbird)
      - [Set_An_Arbitrary_And_Persistent_Tor_Circuit](badUsb/Windows/Misc/Set_An_Arbitrary_And_Persistent_Tor_Circuit)
        - [assets](badUsb/Windows/Misc/Set_An_Arbitrary_And_Persistent_Tor_Circuit/assets)
      - [Starting_a_PowerShell_with_administrator_permissions_in_Windows](badUsb/Windows/Misc/Starting_a_PowerShell_with_administrator_permissions_in_Windows)
        - [docs](badUsb/Windows/Misc/Starting_a_PowerShell_with_administrator_permissions_in_Windows/docs)
      - [UninstallSignal](badUsb/Windows/Misc/UninstallSignal)
    - **Passwords**
      - [Change_Windows_User_Name](badUsb/Windows/Passwords/Change_Windows_User_Name)
      - [ShowSavedPSW](badUsb/Windows/Passwords/ShowSavedPSW)
      - [userPSWchange](badUsb/Windows/Passwords/userPSWchange)
    - **Prank**
      - [AlienMessageFromComputer](badUsb/Windows/Prank/AlienMessageFromComputer)
      - [Change_Github_Profile_Settings](badUsb/Windows/Prank/Change_Github_Profile_Settings)
      - [ChangeWallpaperWithScreenshot](badUsb/Windows/Prank/ChangeWallpaperWithScreenshot)
      - [ContinuousPrintInTerminal](badUsb/Windows/Prank/ContinuousPrintInTerminal)
      - [Follow_Someone_On_Instagram](badUsb/Windows/Prank/Follow_Someone_On_Instagram)
      - [Full-ScreenBannerJoke](badUsb/Windows/Prank/Full-ScreenBannerJoke)
      - [NeverGonnaGiveYouUp_Windows](badUsb/Windows/Prank/NeverGonnaGiveYouUp_Windows)
      - [PlayASongThroughSpotify](badUsb/Windows/Prank/PlayASongThroughSpotify)
      - [Pranh(ex)](badUsb/Windows/Prank/Pranh(ex))
        - [assets](badUsb/Windows/Prank/Pranh(ex)/assets)
          - [transformation](badUsb/Windows/Prank/Pranh(ex)/assets/transformation)
            - [build](badUsb/Windows/Prank/Pranh(ex)/assets/transformation/build)
              - [pranh(ex)](badUsb/Windows/Prank/Pranh(ex)/assets/transformation/build/pranh(ex))
                - [localpycs](badUsb/Windows/Prank/Pranh(ex)/assets/transformation/build/pranh(ex)/localpycs)
            - [dist](badUsb/Windows/Prank/Pranh(ex)/assets/transformation/dist)
      - [SendMessagesInTeams](badUsb/Windows/Prank/SendMessagesInTeams)
      - [SendSignalMessages_Windows](badUsb/Windows/Prank/SendSignalMessages_Windows)
      - [The_Mouse_Moves_By_Itself](badUsb/Windows/Prank/The_Mouse_Moves_By_Itself)
      - [Try_To_Catch_Me](badUsb/Windows/Prank/Try_To_Catch_Me)
    - **WifiPassword**
      - [WifiPass](badUsb/Windows/WifiPassword/WifiPass)
      - [WiFiPasswords_Windows](badUsb/Windows/WifiPassword/WiFiPasswords_Windows)
</details>

## How to Contribute

Contributions to this repository are welcome! Here are some ways you can contribute:

- **Fork the repository**: Create your own copy of the repository to work on.
- **Make changes**: Add new payloads, improve existing ones, or fix bugs.
- **Submit pull requests**: Propose your changes to be reviewed and merged into the main repository.

## GitHub Best Practices

- **Create descriptive pull requests**: Clearly explain the purpose and changes made in your pull requests.
- **Follow coding conventions**: Maintain consistency with existing code and adhere to any guidelines specified in the repository.
- **Communicate effectively**: Use clear and respectful language in discussions and comments.
- **Review others' code**: Help ensure the quality of contributions by reviewing pull requests from other contributors.
- **Be open to feedback**: Welcome feedback on your contributions and be willing to make adjustments as needed.

## Special Thanks

A big thank you to [aleff-github](https://github.com/aleff-github) for sharing their payloads with us!

![Aleff's Profile Photo](https://avatars.githubusercontent.com/u/60389659?v=4)

We appreciate Aleff's generosity in sharing their payloads with the community. Their contributions have helped enhance our repository and provide more value to Flipper Zero users.

Feel free to explore the repository and contribute to make Flipper Zero even more powerful and versatile!

