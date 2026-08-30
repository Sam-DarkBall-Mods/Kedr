# Kedr

[![CI](https://github.com/Sam-DarkBall-Mods/Kedr/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Kedr/actions/workflows/ci.yml)

Kedr is a shoulder fired anti-UAV launcher. It has its own missile, magazine,
infrared seeker settings, lock sounds and supply box.

## Requirements

- Arma 3 2.22 or newer

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The `kedr` path and the existing weapon and magazine class names are kept so
old loadouts continue to work.

## License

Code and configs use GPL-2.0-or-later. Original models, textures, animations
and sounds use APL-SA. See [LICENSES.md](LICENSES.md).
