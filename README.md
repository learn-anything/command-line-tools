# Command line tools

[![Lists](https://img.shields.io/badge/-more%20lists-0a0a0a.svg?style=flat&colorA=0a0a0a)](https://github.com/learn-anything/curated-lists#readme)
[![Contribute](https://img.shields.io/badge/-contribute-0a0a0a.svg?style=flat&colorA=0a0a0a)](CONTRIBUTING.md#readme)

---

#### Contents

- [Core utils](#core-utils)
- [Core utils reimplemented](#core-utils-reimplemented)
- [CSV](#csv)
- [File system](#file-system)
- [Fun](#fun)
- [Games](#games)
- [Git](#git)
- [Go](#go)
- [Java](#java)
- [Lua](#lua)
- [macOS](#macos)
- [Networking](#networking)
- [Nix](#nix)
- [Package managers](#package-managers)
- [Python](#python)
- [Ruby](#ruby)
- [Rust](#rust)
- [Static website engines](#static-website-engines)
- [Text editors](#text-editors)
- [Web](#web)
- [Other](#other)
- [Related](#related)

---

## Core utils

- [ack](https://beyondgrep.com/documentation/) - Grep-like text finder.
- [alias](https://www.explainshell.com/explain/alias) - Define or display aliases.
- [apropos](https://www.explainshell.com/explain/apropos) - Search the manual page names and descriptions.
- [awk](https://www.explainshell.com/explain?cmd=awk) - Pattern-directed scanning and processing language.
- [bc](https://www.explainshell.com/explain/1/bc) - Arbitrary precision calculator language.
- [cat](https://www.explainshell.com/explain/cat) - Concatenate and print files.
- [cd](https://www.explainshell.com/explain/cd) - Change Directory.
- [chmod](https://www.explainshell.com/explain/chmod) - Change file mode bits.
- [cp](https://www.explainshell.com/explain/cp) - Copy files and directories.
- [cron](https://www.explainshell.com/explain/8/cron) - Daemon to execute scheduled commands.
- [cut](https://www.explainshell.com/explain/cut) - Cut out selected portions of each line of a file.
- [diff](https://www.explainshell.com/explain/1/diff) - Compare files line by line.
- [echo](https://www.explainshell.com/explain/echo) - Write arguments to the standard output.
- [env](https://www.explainshell.com/explain/env) - Set environment and execute command, or print environment.
- [file](https://www.explainshell.com/explain/file) - Determine file type.
- [find](https://www.explainshell.com/explain/1/find) - Walk a file hierarchy.
- [gnuplot](https://www.explainshell.com/explain/1/gnuplot) - Generate two and three dimensional plots of data.
- [grep](https://www.explainshell.com/explain/1/grep) - File pattern searcher.
- [head](https://www.explainshell.com/explain/head) - Output the first part of files.
- [jobs](https://ss64.com/bash/jobs.html) - Display status of jobs in the current session.
- [join](https://www.explainshell.com/explain/1/join) - Join lines of two files on a common field.
- [kill](https://www.explainshell.com/explain/1/kill) - Send a signal to a process.
- [killall](https://www.explainshell.com/explain/killall) - Kill processes by name.
- [ln](https://www.explainshell.com/explain/ln) - Create symbolic links.
- [ls](https://www.explainshell.com/explain/ls) - List directory contents.
- [lsof](https://www.explainshell.com/explain/lsof) - List open files.
- [man](https://www.explainshell.com/explain/1/man) - Open manual pages.
- [mv](https://www.explainshell.com/explain/mv) - Move (rename) files.
- [nice](https://www.explainshell.com/explain/1/nice) - Execute a utility with an altered scheduling priority.
- [nohup](https://www.explainshell.com/explain/nohup) - Run a command immune to hangups, with output to a non-tty.
- [paste](https://www.explainshell.com/explain/paste) - Merge lines of files.
- [rm](https://www.explainshell.com/explain/rm) - Remove directory entries.
- [rmdir](https://www.explainshell.com/explain/rmdir) - Remove empty directories.
- [scp](https://www.explainshell.com/explain/1/scp) - Secure copy (remote file copy program).
- [screen](https://www.explainshell.com/explain/1/screen) - Screen manager.
- [sed](https://www.explainshell.com/explain/sed) - Stream editor.
- [set](https://www.explainshell.com/explain/set) - Set or unset options and positional parameters.
- [sort](https://www.explainshell.com/explain/1/sort) - Put the lines of a text file in alphanumeric order.
- [split](https://www.explainshell.com/explain/1/split) - Split a file into pieces.
- [ssh](https://www.explainshell.com/explain/1/ssh) - Remote login.
- [strings](https://www.explainshell.com/explain/strings) - Print the strings of printable characters in files.
- [tail](https://www.explainshell.com/explain/tail) - Output the last part of files.
- [top](https://www.explainshell.com/explain/1/top) - Display and update sorted information about processes.
- [touch](https://www.explainshell.com/explain/touch) - Change file timestamps.
- [tr](https://www.explainshell.com/explain/tr) - Translate or delete characters.
- [tree](https://www.explainshell.com/explain/tree) - List contents of directories in a tree-like format.
- [type](https://www.explainshell.com/explain?cmd=type) - Describe a command.
- [uniq](https://www.explainshell.com/explain/uniq) - Report or omit repeated lines.
- [uptime](https://www.explainshell.com/explain/uptime) - Tell how long the system has been running.
- [wc](https://www.explainshell.com/explain/wc) - Print newline, word, and byte counts for each file.
- [whoami](https://www.explainshell.com/explain/whoami) - Print effective userid.
- [whois](https://www.explainshell.com/explain/whois) - Client for the whois directory service.

## Core utils reimplemented

- [exa](https://github.com/ogham/exa) - Replacement for ls written in Rust.
- [sd](https://github.com/chmln/sd) - Intuitive find & replace CLI.

## CSV

- [xsv](https://github.com/BurntSushi/xsv) - Fast CSV command line toolkit written in Rust.

## File system

- [modd](https://github.com/cortesi/modd) - Flexible tool for responding to filesystem changes.
- [reflex](https://github.com/cespare/reflex) - Run a command when files change.

## Fun

- [primitive](primitive) - reproducing images with geometric primitives.

## Games

- [love](https://love2d.org/) - Framework to make 2D games in Lua.

## Git

- [fac](https://github.com/mkchoi212/fac) - Easy-to-use CUI for fixing git conflicts.
- [git](https://www.explainshell.com/explain/git) - The stupid content tracker.
- [hub](https://github.com/github/hub) - Wrapper aroud Git to extend it with features.
- [tig](https://jonas.github.io/tig/) - Text-mode interface for git.

## Go

- [dep](https://github.com/golang/dep) - Go dependency management tool.
- [go](https://golang.org/doc/cmd) - Manage go source code.
- [playgo](https://github.com/plutov/playgo) - Send .go file to the Go Playground.
- [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.

## Java

- [ant](https://www.explainshell.com/explain/ant) - Java based make tool.
- [java-repl](https://github.com/albertlatacz/java-repl) - Read Eval Print Loop for Java.

## Lua

- [lua](https://www.explainshell.com/explain/lua) - Lua interpreter.
- [luajit](https://www.explainshell.com/explain/luajit) - Just-in-time compiler for the lua language.

## macOS

- [asr](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man8/asr.8.html) - Apple Software Restore; copy volumes (e.g. from disk images).
- [defaults](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/defaults.1.html) - Access user's defaults.
- [do-not-disturb](https://github.com/sindresorhus/do-not-disturb-cli) - Control the macOS `Do Not Disturb` feature.
- [kexstat](https://developer.apple.com/library/archive/documentation/Darwin/Conceptual/KEXTConcept/Articles/command_line_tools.html) - Display status of loaded kernel extensions.
- [m-cli](https://github.com/rgcr/m-cli) - Swiss Army Knife for macOS.
- [PlistBuddy](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man8/PlistBuddy.8.html) - Read and write values to plists.
- [softwareupdate](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man8/softwareupdate.8.html) - System software update tool.
- [time](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/time.1.html)

## Networking

- [sshfs](https://github.com/libfuse/sshfs) - Network filesystem client to connect to SSH servers.
- [telnet](https://www.explainshell.com/explain/telnet) - User interface to the TELNET protocol.

## Nix

- [nix-env](https://nixos.org/releases/nix/nix-1.7/manual/) - Manipulate or query Nix user environments.
- [nix-shell](https://nixos.org/nix/manual/) - Start an interactive shell based on a Nix expression.
- [nox](nhttps://github.com/madjar/nox) - Tools to make nix nicer to use.

## Package managers

- [brew](http://docs.brew.sh/) - Package manager for macOS.
- [npm](http://manpages.ubuntu.com/manpages/precise/en/man1/npm.1.html) - Package manager for javascript.
- [yarn](https://yarnpkg.com/lang/en/docs/) - Package manager for javascript.

## Python

- [livepython](https://github.com/agermanidis/livepython) - Visually trace python code in real-time.

## Ruby

- [rbenv](https://github.com/rbenv/rbenv) - Groom your app’s Ruby environment.
- [ruby-build](https://github.com/rbenv/ruby-build) - Compile and install Ruby.

## Rust

- [project init](https://github.com/vmchale/project-init) - Project templates in rust.
- [rustup](https://github.com/rust-lang-nursery/rustup.rs) - Rust toolchain installer.

## Static website engines

- [hugo](https://gohugo.io/overview/introduction/) - Static site generator written in go.
- [jekyll](https://jekyllrb.com/docs/home/) - Static site generator written in ruby.

## Text editors

- [kakoune](https://github.com/mawww/kakoune) - Modal editor with multi selections.
- [micro](https://github.com/zyedidia/micro) - Modern and intuitive terminal-based text editor.
- [nvim](https://github.com/neovim/neovim) - Vim-fork focused on extensibility and usability.
- [vim](https://github.com/vim/vim) - Modal text editor.

## Web

- [create-react-app](https://github.com/facebookincubator/create-react-app) - Create React apps with no build configuration.
- [preact](https://github.com/developit/preact-cli) - Create preact app.
- [up](https://github.com/apex/up) - Deploy infinitely scalable serverless apps, apis, and sites in seconds to AWS.

## Other

- [cbf](https://github.com/joshuatvernon/cbf) - Build custom CLI apps with only a json or yaml file.
- [rga](https://github.com/phiresky/ripgrep-all) - Ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc.
- [hunter](https://github.com/rabite0/hunter) - Ranger-like file browser written in rust.
- [gotop](https://github.com/cjbassi/gotop) - Terminal based graphical activity monitor inspired by gtop and vtop.
- [noti](https://github.com/variadico/noti) - Monitor a process and trigger a notification.
- [red](https://github.com/antonmedv/red) - Terminal log analysis tools.
- [ffsend](https://github.com/timvisee/ffsend) - Easily and securely share files from the command line. A fully featured Firefox Send client.
- [adns](https://www.gnu.org/software/adns/) - Advanced, easy to use, asynchronous-capable DNS client library and utilities.
- [advancecomp](https://github.com/amadvance/advancecomp) - Collection of recompression utilities for your .ZIP archives, .PNG snapshots, .MNG video clips and .GZ files.
- [ag](https://github.com/ggreer/the_silver_searcher) - Recursively search for pattern.
- [Antibody](https://github.com/getantibody/antibody) - Fastest shell plugin manager.
- [aria2A](https://github.com/aria2/aria2) - Lightweight multi-protocol & multi-source, cross platform download utility.
- [asciinema](https://asciinema.org/docs/usage) - Terminal session recorder.
- [asdf](https://github.com/asdf-vm/asdf) - Extendable version manager with support for Ruby, Node.js, Elixir, Erlang & more.
- [aspcud](https://potassco.org/aspcud/) - Solver for package dependencies.
- [automake](https://www.explainshell.com/explain/automake) - Automatically create Makefile.in's from Makefile.am's.
- [basename](https://www.explainshell.com/explain/basename) - Strip directory and suffix from filenames.
- [bash](https://www.explainbshell.com/explain/bash) - GNU Bourne-Again SHell.
- [camlp4](https://github.com/ocaml/camlp4) - Software system for writing extensible parsers for programming languages.
- [ccat](https://github.com/jingweno/ccat) - Colorizing `cat`.
- [chroma](https://github.com/alecthomas/chroma) - General purpose syntax highlighter in pure Go.
- [chrome-cli](https://github.com/prasmussen/chrome-cli) - Control Google Chrome from the command line.
- [cmake](https://www.explainshell.com/explain/1/cmake) - Cross-platform makefile generator.
- [cowyo](https://github.com/schollz/cowyo) - Feature rich wiki webserver for minimalists.
- [croc](https://github.com/schollz/croc) - Easily get things from one computer to another.
- [ctop](https://github.com/bcicen/ctop) - Container metric viewer.
- [curl](https://www.explainshell.com/explain/curl) - Transfer a URL.
- [direnv](https://github.com/direnv/direnv) - Unclutter your .profile.
- [dirname](https://www.explainshell.com/explain/dirname) - Strip last component from file name.
- [docker](https://docs.docker.com/) - Self-sufficient runtime for containers.
- [entr](http://entrproject.org/) - Run arbitrary commands when files change.
- [eisd](https://github.com/guidojo/eisd) - Execute your favorite command in SubDirectories.
- [fasd](https://github.com/clvv/fasd) - Quick access to files and directories.
- [fd](https://github.com/sharkdp/fd) - Simple, fast and user-friendly alternative to 'find'.
- [ffmpeg](https://www.explainshell.com/explain/ffmpeg) - Video converter.
- [fkill](https://github.com/sindresorhus/fkill-cli) - Kill processes.
- [friendly-find](https://github.com/sjl/friendly-find) - Usable replacement for find.
- [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder.
- [fzy](https://github.com/jhawthorn/fzy) - Better fuzzy finder.
- [gdbm](https://www.gnu.org.ua/software/gdbm/) - Library of database functions that use extensible hashing and work similar to the standard UNIX dbm.
- [gifski](https://github.com/ImageOptim/gifski) - GIF encoder. Squeezes maximum possible quality from the awful GIF format.
- [goaccess](https://github.com/allinurl/goaccess) - Real-time web log analyzer and interactive viewer that runs in a terminal in nix systems or through your browser.
- [gotty](https://github.com/yudai/gotty) - Share your terminal as a web application.
- [GraphicsMagick](http://www.graphicsmagick.org/) - Swiss army knife of image processing.
- [hask-replace](https://github.com/vmchale/hask-replace) - Command-line tool to rename modules in Haskell projects.
- [hexyl](https://github.com/sharkdp/hexyl) - Command-line hex viewer.
- [htttpie](https://httpie.org/) - HTTP client.
- [hyperfine](https://github.com/sharkdp/hyperfine) - Command-line benchmarking tool.
- [imgur-screenshot](https://github.com/jomo/imgur-screenshot) - Take screenshot selection, upload to Imgur. + more cool things.
- [iStats](https://github.com/Chris911/iStats) - Mac stats.
- [jq](https://stedolan.github.io/jq/) - Lightweight and flexible command-line JSON processor.
- [jump](https://github.com/gsamokovarov/jump) - Helps you navigate faster by learning your habits.
- [just](https://github.com/casey/just) - Handy way to save and run project-specific commands.
- [kubectl](https://kubernetes.io/docs/user-guide/kubectl-overview/) - Kubernetes cluster manager.
- [less](http://www.greenwoodsoftware.com/less/index.html) - Free, open-source file pager.
- [license-up](https://github.com/nikitavoloboev/license-up) - Create a license quickly for a given name.
- [LicGD](https://libgd.github.io/) - Open source code library for the dynamic creation of images by programmers.
- [loc](https://github.com/cgag/loc) - Count lines of code quickly.
- [mackup](https://github.com/lra/mackup) - Keep your application settings in sync (OS X/Linux).
- [make](https://www.explainshell.com/explain/make) - GNU make utility to maintain groups of programs.
- [mas](https://github.com/mas-cli/mas) - Command line interface for the Mac App Store.
- [massren](https://github.com/laurent22/massren) - Easily rename multiple files using your text editor.
- [mediumexporter](https://github.com/xdamman/mediumexporter) - Export medium.com articles to markdown.
- [moreutils](https://joeyh.name/code/moreutils/) - Growing collection of the unix tools that nobody thought to write long ago when unix was young.
- [mycli](https://github.com/dbcli/mycli) - Terminal Client for MySQL with AutoCompletion and Syntax Highlighting.
- [ncdu](https://dev.yorhel.nl/ncdu) - Disk usage analyzer with an ncurses interface.
- [neofetch](https://github.com/dylanaraps/neofetch) - Displays information about your operating system, software and hardware in an aesthetic and visually pleasing way.
- [ninja](https://ninja-build.org/) - Small build system with a focus on speed.
- [nm](https://www.explainshell.com/explain/nm) - Display name list (symbol table).
- [npam](https://nmap.org/) - Network mapper.
- [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting.
- [pkg](https://github.com/zeit/pkg) - Package your node.js project into an executable.
- [pngquant](https://pngquant.org/) - Command-line utility and a library for lossy compression of PNG images.
- [pspg](https://github.com/okbob/pspg) - Postgres Pager.
- [pv](https://github.com/icetee/pv) - Pipe Viewer.
- [rclone](https://rclone.org/docs/) - Rsync for cloud storage.
- [rename](http://plasmasturm.org/code/rename/) - Renames files according to modification rules specified on the command line.
- [rq](https://github.com/rq/rq) - Simple job queues for Python.
- [scipy](https://github.com/scipy/scipy) - Open-source software for mathematics, science, and engineering.
- [scons](https://github.com/SCons/scons) - Software construction tool.
- [skim](https://github.com/lotabout/skim) - Fuzzy Finder in rust.
- [snallygaster](https://github.com/hannob/snallygaster) - Tool to scan for secret files on HTTP servers.
- [snapterm](https://github.com/jorgegonzalez/snapterm) - Take beautiful screenshots of your terminal.
- [spark](https://zachholman.com/spark/) - Sparklines for your shell.
- [spotify-ripper](https://github.com/tmerten/spotify-ripper) - Rip Spotify URIs to MP3 files.
- [static-docs](https://github.com/apex/static) - General-purpose library, purpose-built commands for various domains.
- [stow](https://github.com/aspiers/stow) - Symlink farm manager program.
- [svgcleaner](https://github.com/RazrFalcon/svgcleaner) - Clean up your SVG files from the unnecessary data.
- [tar](https://www.explainshell.com/explain/tar) - Manipulate tape archives.
- [tin-summer](https://github.com/vmchale/tin-summer) - Find build artifacts that are taking up disk space.
- [tokei](https://github.com/Aaronepower/tokei) - Display statistics about your code.
- [visidata](https://github.com/saulpw/visidata) - Terminal spreadsheet multitool for discovering and arranging data.
- [vsce](https://code.visualstudio.com/docs/extensions/publish-extension) - Publish VS Code extensions.
- [warp](https://github.com/spolu/warp?attempt=8) - Secure and simple terminal sharing.
- [weather](https://github.com/jessfraz/weather) - Weather via the command line.
- [wego](https://github.com/schachmat/wego) - Weather app for the terminal.
- [wifi-password](https://github.com/rauchg/wifi-password) - Get wifi pass.
- [you-get](https://github.com/soimort/you-get#readme) - Dumb downloader that scrapes the web.
- [dust](https://github.com/bootandy/dust) - More intuitive version of du in rust.
- [mdcat](https://github.com/lunaryorn/mdcat) - `cat` for Markdown.

## Related

- [Awesome CLI apps](https://github.com/aharris88/awesome-cli-apps#readme)
- [Awesome command line apps](https://github.com/herrbischoff/awesome-command-line-apps#readme)
- [Awesome shell](https://github.com/alebcay/awesome-shell#readme)
- [Structured text tools](https://github.com/dbohdan/structured-text-tools#readme) - List of text-based file formats and command line tools for manipulating each.

---

[![CC0](https://img.shields.io/badge/license-CC0-0a0a0a.svg?style=flat&colorA=0a0a0a)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Lists](https://img.shields.io/badge/-more%20lists-0a0a0a.svg?style=flat&colorA=0a0a0a)](https://github.com/learn-anything/curated-lists#readme)
[![Contribute](https://img.shields.io/badge/-contribute-0a0a0a.svg?style=flat&colorA=0a0a0a)](CONTRIBUTING.md#readme)
