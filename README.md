> **Note:** To access all shared projects, get information about environment setup, and view other guides, please visit [Explore-In-HMOS-Wearable Index](https://github.com/Explore-In-HMOS-Wearable/hmos-index).

# How To Make Timed-Random-Number

TimedRandomNumber is a demo app that generates time-based one-time passcodes (OTPs) for secure user authentication, refreshing every 30 seconds.

# Preview

<p align="left">
  <img src="screenshots/aa.png" width="25%">
</p>

# Tech Stack

Languages: ArkTS
Frameworks: HarmonyOS SDK 5.1.0(18)
Tools: DevEco Studio Vers 5.1.0.820
Libraries: `@kit.ArkUI`

# Use Cases

Password Authenticator lets users:
- Securely log in to applications and services using time-based one-time passcodes (OTPs).
- Protect their accounts from unauthorized access with codes that refresh every 30 seconds.

# Directory Structure

   ```
   entry/src/main/ets/
   |---entryability
   |   |---EntryAbility.ets
   |---entrybackupability
   |   |---EntryBackupAbility.ets
   |---pages
   |   |---Index.ets             // Generating and displaying a new 6-digit number every 30 seconds as an authenticator behavior                    
   ```


# Constraints and Restrictions
## Supported Devices
Huawei Watch 5

# LICENSE

BaristaRecipes is distributed under the terms of the MIT License.  
See the [LICENSE](/LICENSE) for more information.