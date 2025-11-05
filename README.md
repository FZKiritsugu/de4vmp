Description
===========

a fully static devirtualizer for vmp, works for versions 3.4, and early 3.5

<img width="1904" height="573" alt="image" src="https://github.com/user-attachments/assets/b87fd449-d8fc-45a5-9b4a-f55a668a57a8" />


Usage
===========

1. if target has anti-tamper, dump it via ks-dumper (https://github.com/EquiFox/KsDumper)
2. demutate with demutation (https://github.com/xlfj5211/DeMutation)
3. clean with de4dot to allow pattern detection
4. drag n drop into devirtualizer
5. clean junk code with de4dot

Common errors
===========

* if demutatiton fails, anti-tamper is propably still present
* if devirtualizer fails, its either new version or the file is corrupted

Disclaimer
===========

* I made it a long time ago, left no comments so don't ask me how it works, neither do I know
* thanks to washi and rtn community
