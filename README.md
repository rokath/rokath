### Hi there 👋

<!--
**rokath/rokath** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...


[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=rokath)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=rokath)](https://github.com/anuraghazra/github-readme-stats)

-->

## Embedded Programming is my passion

* [ ] Still sticking with C (liking function pointer arrays) in micro-controllers.

## My favorite PC language is [Go](https://go.dev)

### Why?

* Go is **open source**, sponsored, professionally developed and used by Google.
* Go is a **multi-purpose** language.
    * It supports graphics not directly but [GUI frameworks](https://blog.logrocket.com/best-gui-frameworks-go/) are around.
* Go is **object oriented**.
    * Go uses **composition** instead of inheritance - programs get cleaner this way.
* In Go **interfaces are implicit** - they need no explicit declaration.
    * This allows clean and simple APIs in your code without unneeded dependencies.
* Go is easy to learn, to use and gives quick programming success.
    * [x] [OSCON 2010: Rob Pike, "Public Static Void"](https://youtu.be/5kj5ApnhPAE)
    * [x] [dotGo 2015 - Rob Pike - Simplicity is Complicated](https://youtu.be/rFejpH_tAHM)
    * [ ] [Expressiveness of Go PDF](https://go.dev/talks/2010/ExpressivenessOfGo-2010.pdf)
* Go is a **compiled language**, therefore checks a lot before building the code.
    * You get most **errors at compile-time and not at run-time** as with scripting languages (like Python).
     The Go [compiler itself is fast](https://www.youtube.com/shorts/DUm6U201o4w). It allows script like usage of Go as well.
    * The [Go program execution is fast](https://www.youtube.com/shorts/Tf90fKykNDM).
        * Could be about half speed of a well written C program - not relevant for normal use cases. To get an equivalent "well written C programm" takes much longer than getting the Go program for a specific task.
* Go is a managed language making **memory leaks impossible**.
    * No explicit memory *allocation* and *free*.
* Go supports **slices**, a very light array management struct.
* Go has **pointers** but **no pointer arithmetic**, making code  more reliable this way.
* Go is designed to use **multi-core** machines and **single-core** ones and allows **easy multi-threading and inter-process communication**.
  * **Concurrent programming** using Go rotines and channels allow **efficient program structures**.
  * **Parallel execution** allows to use the full multicore power of modern systems easyly.
  * [x] [Concurrency is not Parallelism by Rob Pike ](https://youtu.be/oV9rvDllKEg)
* The **auto-formatting** as languge part is very comfortable.
    * This allows a bunch of helper tools.
* A **testing environment** comes with the language. Fuzzying is supported.
    * Simply create `my_test.go` files inside your Go package and run `go test ./...` in the project root.
* You get a **stand-alone runnable** without libraries dependencies.
    * No *missing library* anymore.
    * No *install ...* before running an executable.
* **Many platforms** are supprted, also **mobile** development.
* Go has an **integrated documentation** System.
    * Just add comments to your functions.
* **Easy Visibility control**: Packages export *UppercaseFunction* and hide *lowerCaseFunction*.
* Go can use **C/C++-code** and vice versa, but crossing the border takes time, so avoid that in loops.
    * [CGO](https://pkg.go.dev/cmd/cgo)
    * [SWIG](https://www.swig.org/Doc3.0/Go.html)
* **Compatibility**: Legacy Go code runs on new Go versions.
* Go has **generics** now.


## Disadvantages? 

* Not made for small microcontrollers.
    * BUT: There is [TinyGo](https://tinygo.org/docs/reference/microcontrollers/).
* Not well suited for fast hard real-time applications on sub-millisecond level because of the stop-the-world garbage collector.
  * BUT: The GC gets better and better with new Go versions AND avoiding that Go uses the heap heavily, avoids GC at all.

### More Information

* [ ] [Should you learn Go in 2023?](https://youtu.be/U2PpMZ7hWpg?si=CmkDul7WxLbv14vO)
* [ ] [Google I/O 2010 - Go Programming](https://youtu.be/jgVhBThJdXc?si=cgeMbr-R0dRl3W2w)
* [ ] [Understanding the Go Compiler - Jesús Espino](https://youtu.be/qnmoAA0WRgE?si=xRaZIbB17BlMvxy9)
* [ ] [Learn GO Fast: Full Tutoria (Go in 1 hour)](https://youtu.be/8uiZC0l4Ajw?si=MtEmaELLI_Ksqa6K)
* [ ] [Learn Go Programming - Golang Tutorial for Beginners (Golang in 7 hours)](https://youtu.be/YS4e4q9oBaU?si=i-A64dgltpyteU4i)
* [ ] [7 common mistakes in Go and when to avoid them by Steve Francia (Docker)](https://youtu.be/29LLRKIL_TI)
* [ ] [Gorilla Toolkit for Golang is revived! But is it too late?](https://youtu.be/v6gnINA1d6k)
* [ ] [Build a REST API from scratch with Go, Docker & Postgres | Go Tutorial](https://youtu.be/p08c0-99SyU)
* [ ] [The Go Language: What Makes it Different?](https://youtu.be/FEFXjRoac_U)
* [ ] [Top 3 Programming Languages for 2019](https://youtu.be/_00HnjEMyew)
* [ ] [Reasons Why Golang is Better Than Other Programming Languages](https://productcoalition.com/reasons-why-golang-is-better-than-other-programming-languages-4714082bb1b1)
* [ ] [Watch "5 Reasons Why Golang is The Best Programming Language to Learn in 2021 (including golang drawbacks)" on YouTube](https://youtu.be/Xi779UBOGGM)
* [ ] [A curated list of awesome Go frameworks, libraries and software](https://pkg.go.dev/github.com/ik5/awesome-go?tab=overview#logging)
* [ ] [Golang For Mobile Development](https://medium.com/@ReemiShirsath/golang-for-mobile-development-c7391e690f71)

### Some Details

* [ ] [GitHub Go](https://github.com/golang)
* [ ] [The Go playground](https://play.golang.org/p/lYGWRHhT6Tm)
* [ ] [Concurrency in Go](https://youtu.be/LvgVSSpwND8)
* [ ] [Managing dependencies](https://golang.org/doc/modules/managing-dependencies)
* [ ] [Why are interfaces needed in Golang?](https://stackoverflow.com/questions/39092925/why-are-interfaces-needed-in-golang)
* [ ] [Implementing Golang Interfaces](https://link.medium.com/W5oEMjLEF8)
* [ ] [Testing Techniques](https://talks.golang.org/2014/testing.slide#1)
* [ ] [Arrays, slices (and strings)](https://blog.golang.org/slices)

### Examples

* [ ] [Golang: File Tree Traversal (filepath.Walk)](https://xojoc.pw/blog/golang-file-tree-traversal)
* [ ] [Simple golang expirement with ANSI colors · GitHub](https://gist.github.com/ik5/d8ecde700972d4378d87)
* [ ] [Binary Search Algorithm Implemented in Go](https://flaviocopes.com/golang-algorithms-binary-search/)
* [ ] [A Go unikernel running on x86 bare metal](https://github.com/icexin/eggos)

### Learning

* [x] [The Go Programming Language by Alan A. A. Donovan & Brian W. Kernighan](https://www.amazon.de/-/en/Alan-Donovan/dp/0134190440)
<!--
* [ ] [techtarget](https://www.techtarget.com/searchitoperations/definition/Go-programming-language)
* [ ] https://gitlab.com/teaage/gospace/blob/master/books/MasteringGo_CreateGolang_production_applications.pdf
* [ ] https://gitlab.com/teaage/gospace/

## Tools I like and use

### Git

* [ ] [Git bash](https://gitforwindows.org/)
* [ ] [Legendary GitKraken Client](https://www.gitkraken.com/)
* [ ] [git large file storage](https://git-lfs.github.com/)
* [ ] [GitHub](https://github.com/)
* [ ] [GitLab](https://gitlab.com/)

<!-- * [ ] https://gitlab.com/baumtec/meta/wikis/GitPcSetup 

### Code

* [ ] [PC-Lint](https://web.archive.org/web/20180830042445/http://www.gimpel.com/html/ptch90.htm)
* [ ] [Doxygen](https://doxygen.nl/)
* [ ] [J-Link Software and Documentation Pack](https://www.segger.com/downloads/jlink/#J-LinkSoftwareAndDocumentationPack)
* [ ] [STM32 CubeMX initialization code generator](https://www.st.com/en/development-tools/stm32cubemx.html)
* [ ] [ARM Keil IDE (free for any M0/M0+ up to 32KB, STM32 M0/M0+ up to 256 KB)](https://www2.keil.com/mdk5)
* [ ] [TDM-GCC](https://jmeubank.github.io/tdm-gcc/)

### Edit

* [ ] [Beyond Compare](https://www.scootersoftware.com/)
* [ ] https://unicode-table.com/en/
* [ ] [vscode](https://code.visualstudio.com/)
* [ ] [notepad++ especially for block editing](https://notepad-plus-plus.org/downloads/)
* [ ] [Screen to GIF](https://www.screentogif.com/)
* [ ] [draw.io](https://github.com/jgraph/drawio-desktop/releases/)

### Viewer

* [ ] [Sumatra PDF, eBook (epub, mobi), comic book (cbz/cbr), DjVu, XPS, CHM, image viewer for Windows](https://www.sumatrapdfreader.org/free-pdf-reader)

### Communication

* [ ] [Tera Term](https://ttssh2.osdn.jp/index.html.en)
* [ ] [PuTTY](https://www.putty.org/)

### Misc

* [ ] [7-Zip](https://www.7-zip.org/)
* [ ] Windows Subsystem for Linux (debian image and additionally the gcc compiler)

<!--

-->

### What I use Go for?

* The **Trice** tool is written in Go.
* Test tools stimulating embedded devices under test.

