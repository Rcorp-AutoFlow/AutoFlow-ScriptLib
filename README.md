# AutoFlow Script Library

Ready-to-use AutoFlow scripts for supported games and workflows.

## Requirements

Before using these scripts, make sure you have:

1. **AutoFlow v2.5 or newer**
2. **AutoFlow Pro**
   - Required because these scripts use more than 20 steps.
   - Required for background window mode.
   - Required for advanced features such as OCR/AI OCR when used by a script.
3. **A stable emulator/game window size**
   - Recommended: enable `Sync window size with script` in AutoFlow.
   - This helps the script match the screen size it was created for.
4. **Correct game language**
   - Some scripts detect text or images from the game screen.
   - If a script says it requires Indonesian/English game language, use that language.
5. **All related scripts imported together**
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
2. In AutoFlow, enable **Background Window**.
3. Select the correct game/emulator window.
4. Enable **Sync window size with script** if available.
5. Run a small test script first.

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

