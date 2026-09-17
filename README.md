# Bijoy52 Bangla Typer (Obsidian plugin)

Type Bangla using the Bijoy52 keyboard layout directly inside Obsidian's
editor — no OS-level keyboard install, works in any note.

## Usage

1. Enable the plugin (Settings → Community plugins).
2. Open Settings → Hotkeys, search for **"Toggle Bijoy52 Bangla mode"**, and
   assign a hotkey (e.g. `Ctrl+Alt+B`).
3. Press that hotkey while editing a note. The status bar (bottom right)
   shows **বাংলা (Bijoy52)** when on, **EN** when off.
4. Type Bijoy52 keystrokes as usual; press the hotkey again to switch back to
   normal typing.

## How it works

A longest-match lookup engine over the authoritative Bijoy Classic → Unicode
rule set (`bn-bijoyUnicode.mim`, originally from Ananda Computers), handling
matra reordering, reph, conjuncts, and independent-vowel forms — the same
engine used in the companion browser and AutoHotkey versions of this tool.
No network calls, no telemetry, no external dependencies.

## License

MIT — see `LICENSE`.
