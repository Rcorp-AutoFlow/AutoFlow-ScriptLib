# AutoFlow Script Library

Ready-to-use AutoFlow scripts for supported games and workflows.

Current library focus: **Clash of Clans** automation scripts.

## Requirements

Before using these scripts, make sure you have:

1. **AutoFlow v2.4 or newer**
2. **AutoFlow Pro**
   - Required because these scripts use more than 20 steps.
   - Required for background window mode.
   - Required for advanced features such as OCR/AI OCR when used by a script.
3. **Clash of Clans installed and running**
   - Supported targets include BlueStacks and Google Play Games on PC.
4. **A stable emulator/game window size**
   - Recommended: enable `Sync window size with script` in AutoFlow.
   - This helps the script match the screen size it was created for.
5. **Correct game language**
   - Some scripts detect text or images from the game screen.
   - If a script says it requires Indonesian/English game language, use that language.
6. **All related scripts imported together**
   - Some scripts are made to work as a group.
   - Import the full library folder instead of only one file unless the post says otherwise.

## How To Install Scripts

1. Download the `.json` script file or the full `Scripts` folder.
2. Open AutoFlow.
3. Open **Settings** and check your **Scripts Folder** path.
4. Copy the `.json` files into that Scripts Folder.
5. Restart AutoFlow or refresh/reopen the script list.
6. Select the script from the left script panel.

Default scripts folder is usually:

```text
Documents\AutoFlow\Scripts
```

If you changed the folder in AutoFlow Settings, use your custom folder instead.

## Recommended Setup

Use this setup for best results:

1. Open the emulator first.
2. Open Clash of Clans and wait until the village or attack screen is fully loaded.
3. In AutoFlow, enable **Background Window**.
4. Select the correct game/emulator window.
5. Enable **Sync window size with script** if available.
6. Run a small test script first, such as reconnect/check/home type scripts.
7. Only run farming scripts after the small test works correctly.

## Important Notes

- Do not resize the emulator while a script is running.
- Do not move the game UI layout during a script run.
- If the script clicks the wrong place, stop it and check:
  - correct background window selected
  - correct emulator selected
  - game screen is in the expected page
  - `Sync window size with script` is enabled
  - game language matches the script requirement
- If image/OCR checks fail, redraw or update the affected image/OCR steps for your screen.
- If you rename scripts, make sure any script that references another script is updated too.

## Included Scripts

| Script | Purpose |
| --- | --- |
| `COC - Farming Main Village` | Main farming flow for main village. |
| `COC - Farming Main Village (Dragon)` | Main village farming variant using dragon setup. |
| `COC - Farming Night Village (Elixir)` | Builder/night village elixir farming flow. |
| `COC - Farming Main` | Farming helper/main flow. |
| `COC - Deploy` | Deployment helper script. |
| `COC - Check Raid Result` | Checks raid result conditions. |
| `COC - Reconnect` | Reconnect/reload helper. |
| `COC - Treasure` | Treasure/check helper. |
| `COC - Beranda` | Home/base screen helper. |

## Troubleshooting

**Script is not visible in AutoFlow**

Make sure the `.json` file is inside the same Scripts Folder configured in AutoFlow Settings.

**Script runs but does not click correctly**

Enable Background Window, choose the correct emulator/game window, then enable Sync window size with script.

**Script works on one PC but not another**

The emulator size, game language, UI position, or target window may be different. Use Sync window size first, then adjust image/OCR/click steps if needed.

**AutoFlow says Pro is required**

These scripts are designed for Pro because they use background mode and many action steps.

## Safe Usage

Always test a script slowly before long farming runs. Watch the first full run, confirm the clicks are correct, then use it normally.

