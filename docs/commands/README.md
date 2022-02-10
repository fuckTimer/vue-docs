# Commands

| Command                     | Callback                            | Description |
|-----------------------------|-------------------------------------|-------------|
| sm_invalidkey               | Command_InvalidKeyPref              | Choose your prefered option on invalid key input |
| sm_main                     | Command_Main                        | Teleports you to the main path |
| sm_start                    | Command_Start                       | Teleports you to the start zone of the current path |
| sm_stop                     | Command_Stop                        | Stops the timer |
| sm_end                      | Command_End                         | Teleports you to the end zone of the current path, timer will be stopped(!) |
| sm_r                        | Command_Restart                     | Same as sm_start, teleports you back to the start zone |
| sm_restart                  | Command_Restart                     | Same as sm_start, teleports you back to the start zone |
| sm_goback                   | Command_GoBack                      | Teleports you back to the previous stage/bonus or to the start zone |
| sm_rs                       | Command_RestartStage                | Teleports you back to the stage (start) zone |
| sm_back                     | Command_RestartStage                | Teleports you back to the stage (start) zone |
| sm_restartstage             | Command_RestartStage                | Teleports you back to the stage (start) zone |
| sm_bonuses                  | Command_BonusList                   | List all bonuses of the current map (main will also included) |
| sm_stages                   | Command_StageList                   | List all stages of the current map (level will disabled if no stage exists) |
| sm_b                        | Command_Bonus                       | Teleports you to the bonus start zone. |
| sm_bonus                    | Command_Bonus                       | Teleports you to the bonus start zone. |
| sm_s                        | Command_Stage                       | Teleports you to the stage zone. |
| sm_stage                    | Command_Stage                       | Teleports you to the stage zone. |
| sm_style                    | Command_Styles                      | Lists you all available styles, which you can switch to. |
| sm_styles                   | Command_Styles                      | Lists you all available styles, which you can switch to. |
| sm_tier                     | Command_Tier                        | Prints list of all maps into your chat with tier. |
| sm_hud                      | Command_HUD                         | List all HUD related commands as menu |
| sm_hudmove                  | Command_HUDMove                     | Move/Swap keys to another positions |
| sm_hudenable                | Command_HUDEnable                   | Enable/Disable the HUD entirely |
| sm_hudpreset                | Command_HUDPreset                   | Replace HUD with a predefined preset |
| sm_hudseparator             | Command_HUDSeparator                | Replace tabs against vertical bars or vice versa |
| sm_hudscale                 | Command_HUDScale                    | Change the HUD font size |
| sm_hudlength                | Command_HUDLength                   | Adjust the HUD with incorrect formatting |
| sm_hudspeedunit             | Command_HUDShowSpeedUnit            | Show 'u/s' behind speed or not |
| sm_hudspeed                 | Command_HUDSpeed                    | Change the hud speed calculation based of different axis |
| sm_hudtime                  | Command_HUDTime                     | Show times in different formats |
| sm_hud0hours                | Command_HUDShow0Hours               | Shows the leading 0(0): in time or not |
| sm_huddeadhud               | Command_HUDDeadHud                  | Shows as spectator the players hud in 1st- and 3rd person |
| sm_hudcomparelocation       | Command_HUDCompareLocation          | Enable/Disable HUD Time/Speed comparison with position option |
| sm_hudcompareagainst        | Command_HUDCompareAgainst           | Compare your time/speed against PR, SR or both (requires chat as location) |
| sm_hudcomparemode           | Command_HUDCompareMode              | Show full time/speed or the difference of the record |
| sm_hudcomparetime           | Command_HUDCompareTime              | How long the comparison should be shown in HUD |
| sm_hudcenterspeedposition   | Command_HUDCenterSpeedPosition      | Specify the position of the X- and Y-Axis for the speed (center) hud |
| sm_hudcenterspeedcolor      | Command_HUDCenterSpeedColor         | Specify the color of the X- and Y-Axis for the speed (center) hud |
