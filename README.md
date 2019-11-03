LitJSON for Unity Package Manager (UPM)
=======================================

A *.Net* library to handle conversions from and to JSON (JavaScript Object Notation) strings, modified for the Unity3D engine's Package Manager format. The goal of this fork is to create an easily-updatable version of LitJSON which includes various Unity-specific additions / fixes.

> _It's quick and lean, without external dependencies.
> Just a few classes so easily embeddable in your own code or a very small assembly to ship with your code.
> The code is highly portable, which in general makes it easy to adapt for new platforms._

## Deltas from Source
* Removed all tests, benchmarks, and so on - see the original for these files.

## Requirements

LitJSON currently targets and supports
* .NET Standard 2.0
* .NET Standard 1.5
* .NET Framework 4.5 and above
* .NET Framework 4.0
* .NET Framework 3.5 (including SQLCLR, for which [WCOMAB/SqlServerSlackAPI](https://github.com/WCOMAB/SqlServerSlackAPI) is an example of)
* .NET Framework 2.0
* Mono 4.4.2 and above

LitJSON for Unity Package Manager currently targets and supports (initial list for testing)
* Unity 2019.1.14f1

## License

[Unlicense][unlicense] (public domain).

[litjson]: [unlicense](http://unlicense.org/
[unlicense]: http://unlicense.org/
