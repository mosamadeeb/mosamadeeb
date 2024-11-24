## mosamadeeb

*(previously known as SutandoTsukai181)*

If only writing profile readmes was as fun as coding...

### 📚 Education
- BSc. w/ High Honors in Computer Engineering (read: CS in middle east). Attended 2 years at [Bilkent University](https://w3.bilkent.edu.tr/bilkent/) then transferred to [Middle East Technical University (NCC)](https://ncc.metu.edu.tr/).

- Some of the interesting courses I took:
  - **Database Management Systems**: query optimization, transaction management, concurrency control, crash recovery, security & authorization...
  
  - **Image Processing**: space and frequency domains, image enhancement, edge detection, segmentation, morphology, compression, pattern recognition... (all practiced in MATLAB)
  
  - **Cloud Computing**: parallel & distributed systems, scaling, virtualization, containers, AWS, architectures (REST, pub-sub, middleware), communication (RPC, messaging), coordination, election algorithms, fault tolerance...
  
  - **Computer Graphics**: [ray tracing](https://github.com/mosamadeeb/Raytracer), shading, texture mapping, data structures for graphics, [modelling & viewing transformations](https://github.com/mosamadeeb/Transformer), forward rendering pipeline, culling, clipping, rasterization, OpenGL, vertex & fragment shaders, shadows, curves, surfaces...

  - **Operating Systems, Data Communication & Networks, Embedded Systems**

- My capstone project was about [activity detection-based health monitoring](https://github.com/mosamadeeb/MultiSensorHardwareSetup) where I programmed MCUs in C++ and Pi's in Python to create a reliable and recoverable multi-sensor network that collects human motion data for activity detection on the edge.

### 🧠 Interests
**Backend development**, because I like designing and building systems, and I'm always excited about the latest open-source libraries that let me try out different approaches for solving a problem 👀.
- Completed courses about HTTP clients and [web servers](https://github.com/mosamadeeb/go-playground/tree/main/boot.dev/learn-web-servers) while learning Go on [Boot.dev](https://www.boot.dev).
- Build(ing) an API for a [workout tracker](https://github.com/mosamadeeb/go-workout-tracker) (idea from [roadmap.sh](https://roadmap.sh/projects/fitness-workout-tracker)) in Go so I can become familiar with modern backend practices in Go.
- Built some RESTful servers during my internships using .NET (C#). I later on realized how huge of a tech debt .NET had after I built a server in Go.

**Reverse engineering**, because I like going deep into the details of how something works.
- I RE'd a lot (and I mean a lot) of file formats and structures used in video games, and built tools for them, such as:
  - (Un)packers for archive formats

  - Conversion (or Blender import) scripts for 3D model, animation, and texture formats for games such as [Yakuza](https://github.com/mosamadeeb/yakuza-gmt-blender), [Kurohyou](https://github.com/mosamadeeb/kurohyo_elpk_blender), and [Naruto Storm/JoJo All Star Battle](https://github.com/mosamadeeb/cc2_xfbin_blender)

  - (De)serializers for general game data formats
- Used IDA Pro, Ghidra and x64dbg (disassemblers/debuggers) to figure out specific game behaviour which allowed me to:
  - RE some of the more complicated formats

  - Find out the compression algorithms or [encryption](https://github.com/mosamadeeb/yagami-decryption-agency) used for archives

  - Write function hooks that get injected into the game's process to modify the logic, and perform things such as *loading unpacked modifed files from other directories* (essentially a [mod loader](https://github.com/mosamadeeb/YakuzaParless))

### 💻 Programming languages
- Language I'm most comfortable with: **Python**, as I've been using it for +4 years for writing scripts and it just used to fill my (simple) programming needs.

- In addition to Python, I've written a lot of projects in **C++, C#, Java, and Rust**.

- Favourite programming language: ~~the right one for the job~~ **Go**, because it lets me write clean and simple, yet powerful and performant code. It also ticks all of my checkboxes for a user-friendly language (type inference, structs with methods, no OOP, no borrow checker, less brackets/semicolons).

- I still occasionally use C++ and Python, depending on the requirements of what I need to build.

### 👨‍💻 Projects
These are some of the projects I think are interesting, grouped by language.

<!-- https://github.com/gleich/profile_stack -->
<!-- START OF PROFILE STACK, DO NOT REMOVE -->
| 💻 **Language** | 🚀 **Projects** |
| - | - |
| [![Python](https://img.shields.io/static/v1?label=&message=Python&color=3776AB&logo=python&logoColor=FFFFFF)](https://github.com/mosamadeeb?tab=repositories&q=&type=&language=python&sort=) | [![ChatDB](https://img.shields.io/static/v1?label=&message=ChatDB&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/ChatDB) [![PyBinaryReader](https://img.shields.io/static/v1?label=&message=PyBinaryReader&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/PyBinaryReader) [![eboot_string_patcher](https://img.shields.io/static/v1?label=&message=eboot_string_patcher&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/eboot_string_patcher) |
| [![.NET C#](https://img.shields.io/static/v1?label=&message=C%23&color=512BD4&logo=dotnet&logoColor=FFFFFF)](https://github.com/mosamadeeb?tab=repositories&q=&type=&language=c%23&sort=) | [![RyuModManager](https://img.shields.io/static/v1?label=&message=RyuModManager&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/RyuModManager) [![ParToolShell](https://img.shields.io/static/v1?label=&message=ParToolShell&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/ParToolShell) [![MMXD-Mods](https://img.shields.io/static/v1?label=&message=MMXD-Mods&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/MMXD-Mods/tree/main/Tangerine) |
| [![C++](https://img.shields.io/static/v1?label=&message=C%2B%2B&color=00599C&logo=cplusplus&logoColor=FFFFFF)](https://github.com/mosamadeeb?tab=repositories&q=&type=&language=c%2B%2B&sort=) | [![Raytracer](https://img.shields.io/static/v1?label=&message=Raytracer&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/Raytracer) [![Transformer](https://img.shields.io/static/v1?label=&message=Transformer&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/Transformer) [![CpkPatcher](https://img.shields.io/static/v1?label=&message=CpkPatcher&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/CpkPatcher) |
| [![Rust](https://img.shields.io/static/v1?label=&message=Rust&color=000000&logo=rust&logoColor=FFFFFF)](https://github.com/mosamadeeb?tab=repositories&q=&type=&language=rust&sort=) | [![yagami-decryption-agency](https://img.shields.io/static/v1?label=&message=yagami-decryption-agency&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/yagami-decryption-agency) [![xfbin-nucc-binary](https://img.shields.io/static/v1?label=&message=xfbin-nucc-binary&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/xfbin-nucc-binary) |
| [![Blender](https://img.shields.io/static/v1?label=&message=Blender&color=E87D0D&logo=blender&logoColor=FFFFFF)](https://www.blender.org/) | [![yakuza-gmt-blender](https://img.shields.io/static/v1?label=&message=yakuza-gmt-blender&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/yakuza-gmt-blender) [![kurohyo_elpk_blender](https://img.shields.io/static/v1?label=&message=kurohyo_elpk_blender&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/kurohyo_elpk_blender) [![cc2_xfbin_blender](https://img.shields.io/static/v1?label=&message=cc2_xfbin_blender&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/mosamadeeb/cc2_xfbin_blender) |
<!-- END OF PROFILE STACK, DO NOT REMOVE -->

### Stats

<!-- https://github.com/vn7n24fzkq/github-profile-summary-cards -->
[![](https://raw.githubusercontent.com/mosamadeeb/mosamadeeb/main/profile-summary-card-output/github/0-profile-details.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)
[![](https://raw.githubusercontent.com/mosamadeeb/mosamadeeb/main/profile-summary-card-output/github/3-stats.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards) [![](https://raw.githubusercontent.com/mosamadeeb/mosamadeeb/main/profile-summary-card-output/github/1-repos-per-language.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)

<!-- https://github.com/yhype -->
![](https://hit.yhype.me/github/profile?user_id=52977072)
