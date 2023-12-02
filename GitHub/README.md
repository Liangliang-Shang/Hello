# Git
* Git is an open-source version control system (VCS)
# GitHub
* GitHub is a code hosting platform for version control and collaboration.
# Codespaces
* A codespace is a development environment that's hosted in the cloud.
![diagram](https://docs.github.com/assets/cb-77061/mw-1440/images/help/codespaces/codespaces-diagram.webp)
# Env
* [Your codespaces](https://github.com/codespaces)
* One of mine: [4-core • 16GB RAM • 32GB](https://vigilant-fortnight-wrjr7qxxj6jh9qqv.github.dev/)
    ```bash
    👋 Welcome to Codespaces! You are on our default image. 
    - It includes runtimes and tools for Python, Node.js, Docker, and more. See the full list here: https://aka.ms/ghcs-default-image
    - Want to use a custom image instead? Learn more here: https://aka.ms/configure-codespace

    🔍 To explore VS Code to its fullest, search using the Command Palette (Cmd/Ctrl + Shift + P or F1).

    📝 Edit away, run your app as usual, and we'll automatically make it available for you to access.
    ```
    ## Python
    ```Python
    @Liangliang-Shang ➜ ~ $ python -V
    Python 3.10.13
    @Liangliang-Shang ➜ ~ $ python
    Python 3.10.13 (main, Nov 16 2023, 19:48:55) [GCC 9.4.0] on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>> print("Hello, Python!")
    Hello, Python!
    >>>
    ```
    ## NodeJS
    ```js
    @Liangliang-Shang ➜ ~ $ node -v
    v20.9.0
    @Liangliang-Shang ➜ ~ $ node
    Welcome to Node.js v20.9.0.
    Type ".help" for more information.
    > console.log("Hello, NodeJS!")
    Hello, NodeJS!
    undefined
    > 
    ```
    ## Perl
    ```perl
    @Liangliang-Shang ➜ ~ $ perl -v

    This is perl 5, version 30, subversion 0 (v5.30.0) built for x86_64-linux-gnu-thread-multi
    (with 59 registered patches, see perl -V for more detail)

    Copyright 1987-2019, Larry Wall

    Perl may be copied only under the terms of either the Artistic License or the
    GNU General Public License, which may be found in the Perl 5 source kit.

    Complete documentation for Perl, including FAQ lists, should be found on
    this system using "man perl" or "perldoc perl".  If you have access to the
    Internet, point your browser at http://www.perl.org/, the Perl Home Page.

    @Liangliang-Shang ➜ ~ $ perl
    print "Hello, Perl!\n";
    Hello, Perl!
    ```
    ## C
    ```
    @Liangliang-Shang ➜ ~ $ gcc -v
    Using built-in specs.
    COLLECT_GCC=gcc
    COLLECT_LTO_WRAPPER=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper
    OFFLOAD_TARGET_NAMES=nvptx-none:hsa
    OFFLOAD_TARGET_DEFAULT=1
    Target: x86_64-linux-gnu
    Configured with: ../src/configure -v --with-pkgversion='Ubuntu 9.4.0-1ubuntu1~20.04.2' --with-bugurl=file:///usr/share/doc/gcc-9/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++,gm2 --prefix=/usr --with-gcc-major-version-only --program-suffix=-9 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib=auto --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none=/build/gcc-9-9QDOt0/gcc-9-9.4.0/debian/tmp-nvptx/usr,hsa --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu
    Thread model: posix
    gcc version 9.4.0 (Ubuntu 9.4.0-1ubuntu1~20.04.2) 
    ```
    # C++
    ```
    @Liangliang-Shang ➜ ~ $ g++ -v
    Using built-in specs.
    COLLECT_GCC=g++
    COLLECT_LTO_WRAPPER=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper
    OFFLOAD_TARGET_NAMES=nvptx-none:hsa
    OFFLOAD_TARGET_DEFAULT=1
    Target: x86_64-linux-gnu
    Configured with: ../src/configure -v --with-pkgversion='Ubuntu 9.4.0-1ubuntu1~20.04.2' --with-bugurl=file:///usr/share/doc/gcc-9/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++,gm2 --prefix=/usr --with-gcc-major-version-only --program-suffix=-9 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib=auto --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none=/build/gcc-9-9QDOt0/gcc-9-9.4.0/debian/tmp-nvptx/usr,hsa --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu
    Thread model: posix
    gcc version 9.4.0 (Ubuntu 9.4.0-1ubuntu1~20.04.2)
    ```
    ## Java
    ```
    @Liangliang-Shang ➜ ~ $ java --version
    openjdk 17.0.9 2023-10-17 LTS
    OpenJDK Runtime Environment Microsoft-8552009 (build 17.0.9+8-LTS)
    OpenJDK 64-Bit Server VM Microsoft-8552009 (build 17.0.9+8-LTS, mixed mode, sharing)
    ```
    ## Git
    ```bash
    @Liangliang-Shang ➜ ~ $ which git
    /usr/local/bin/git
    @Liangliang-Shang ➜ ~ $ git -v
    git version 2.42.1
    @Liangliang-Shang ➜ ~ $ git --version
    git version 2.42.1
    ```
    ## GitHubCLI
    ```bash
    @Liangliang-Shang ➜ ~ $ gh --version
    gh version 2.39.1 (2023-11-14)
    https://github.com/cli/cli/releases/tag/v2.39.1
    @Liangliang-Shang ➜ ~ $ gh codespace list
    NAME                                 DISPLAY NAME        REPOSITORY              BRANCH  STATE      CREATED AT       
    vigilant-fortnight-wrjr7qxxj6jh9qqv  vigilant fortnight  Liangliang-Shang/Hello  main*   Available  about 2 hours ago
    ```

