# mac-keyboard-mapping

```
alias resetkeyboard="hidutil property --set '{\"UserKeyMapping\":[]}'"
alias reloadkeyboard="launchctl unload ~/Library/LaunchAgents/com.local.KeyRemapping.plist; launchctl load ~/Library/LaunchAgents/com.local.KeyRemapping.plist; echo Reloaded keyboard mapping"
```
