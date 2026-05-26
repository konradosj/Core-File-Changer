# xxx_konradosj

A Python utility for batch-copying a replacement file to multiple target locations, automatically converting the file extension to match the replacement file.

## What it does

Give it one replacement file and any number of target files. For each target, it copies the replacement into the same directory as the target, renaming it to match the target's base name but using the replacement's extension.

Directories containing `xxx` in their path are processed first.

The replacement file's name must start with `xxx`.

**Example:**

```
python xxx_konraodsj.py xxx_new_sound.wav mod_a/sound.ogg mod_b/sound.mp3
```

Result:
- `mod_a/sound.wav` — replacement file copied here
- `mod_b/sound.wav` — replacement file copied here

## Requirements

- Python 3.x
- No external dependencies (standard library only)

## License

[PolyForm Strict License 1.0.0](https://polyformproject.org/licenses/strict/1.0.0)
