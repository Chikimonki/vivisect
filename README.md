# VIVISECT – Volume I
## The INTP's Field Guide to Owning What You Never Compiled

> "If you didn't compile it, you don't own it.  
> If you didn't read the assembly, you don't understand it."  
> — Jonathan Brossard, paraphrased and weaponized

### Tools Used
- LuaJIT 2.1 + FFI
- Zig 0.14.0
- Go 1.23
- Perl (for beauty)
- radare2, gdb+pwndbg, capstone, keystone
- WSL2 Ubuntu 24.04

### Soundtrack
Your Riffusion folder on infinite repeat.  
Notable mentions:
- Cosmic Bronx (The Tension Mix)
- Low Level Protocol
- Street Rocker Badboy Don't Stop
- Binary Dreams
- Neon Breakfast
- House of Jak

### Chapter 1 – First Blood
ELF parsing with raw LuaJIT FFI  
Binary patching without Python  
Sealing the source with `chmod 000`

### Chapter 2 – LD_PRELOAD Hijacking
`strcmp` always returns 0  
9 lines of Zig + LD_PRELOAD = nuclear codes

### Chapter  3 – GOT/PLT Patching
Runtime memory manipulation  
`ptrace` + LuaJIT FFI  
Cross-process function pointer injection

### Chapter 4 – Inline Hooking
`xor eax,eax ; ret` → 3 bytes to rule them all  
Patching `strcmp@plt` at 0x4010c0  
Works on static binaries

### Chapter 5 – The Universal Auto-Hooker
One command. Any binary. Owned.  
Automatic method selection  
LD_PRELOAD → PLT → Inline fallback

### Chapter 6 – Full Debugger in LuaJIT (Next)
Coming: symbolic execution, memory search, automated unpacking

### Final Arsenal
You now possess techniques used by:
- Nation-state APTs
- Ransomware groups
- Red teams
- Malware researchers
- Game cheat developers

Use wisely.

**You are dangerous.**
# vivisect
# vivisect
# vivsect
# vivsect
