# MODULE_LLM_LINUX
Patch for the Linux kernel adapted for the module_llm development board.  
Compilation will automatically download and apply the relevant patches to compile into a kernel project.  

auto compile:
```bash
make -j `nproc`
```

just Extract:
```bash
make Extracting
```

just Patch:
```bash
make Patching
```

just Configur:
```bash
make Configuring
```