# ttyd - Share your terminal over the web

ttyd is a simple command-line tool for sharing terminal over the web.  
This repo offers an automatic build on latest version that includes `JetBrains NerdFont``, and the Chinese font `Sarasa Mono SC`.  

## Installation

Install [ttyd](https://github.com/tsl0922/ttyd) the usual way, to include all dependencies.  
Download the [latest version](https://github.com/Lanjelin/nerd-ttyd/releases/latest) of the patched binary from releases, and make it executable.

`wget -q -O /usr/sbin/ttyd.nerd https://github.com/Lanjelin/nerd-ttyd/releases/download/1.7.7/ttyd.x86_64 && chmod +x /usr/sbin/ttyd.nerd`

Run the modified binary with the following flag to set desired font: `ttyd.nerd -t fontFamily="JetBrains, SarasaMono"`  

![screenshot](https://github.com/tsl0922/ttyd/raw/main/screenshot.gif)
