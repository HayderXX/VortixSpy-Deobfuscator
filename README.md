<p align="center">
  <br/>
  ____ ____ __ .__ _________<br/>
  \ \ / /___________/ |_|__|__ ___ / _____/_____ ___.__.<br/>
   \ Y / _ \_ __ \ __\ \ \/ / \_____ \\____ < | |<br/>
    \ ( <_> ) | \/| | | |> < / \ |_> >___ |<br/>
     \___/ \____/|__| |__| |__/__/\_ \/_______ / __// ____|<br/>
                                      \/ \/|__| \/<br/>
  <br/>
  <h1>VortixSpy</h1>
  <strong>.NET Deobfuscator - No mercy edition</strong>
</p>

Just drag & drop your protected .NET assembly onto `VortixSpy.exe`

### What it currently kills
• Compressors                (they all fall)
• Anti-tamper                (irrelevant now)
• Anti-dumper                (memory? what memory)
• Anti-debugger              (cry about it)
• Encrypted / junk resources (gone)
• Constant encryption        (numbers exposed)
• Proxy calls / indirection  (methods naked)

### In development / planned / Soon
- Advanced string decryptors
- Control flow deobfuscation
- Virtualization unpacking (etc, KoiVM...)
- Better symbol & type renaming

### Usage
1. Download latest release → [Releases page](https://github.com/HayderXX/VortixSpy-Deobfuscator/releases)
2. Drag & drop the obfuscated .dll / .exe onto `VortixSpy.exe`
3. Drag and drop the file(s) onto VortixSpy.exe and wait a few seconds.
4. Warning: Sometimes the obfuscated assembly and all its dependencies are loaded into memory for execution.
Even if the current version of VortixSpy doesn't load a certain assembly into memory for execution, a future version might.
5. other options: Start VortixSpy without any arguments and it will shows all.
### Credits / respect:
• 0xd4d             - dnlib legend
• yck1509           - some code
• Alcatraz3222      - supporter
• TheRealhayder     - created VortixSpy the Founder
