test
================
Janet Young

2026-07-30

Show .libPaths()

``` r
.libPaths()
```

    ## [1] "/home/jayoung/R/x86_64-pc-linux-gnu-library/4.5-apptainer"                                                                  
    ## [2] "/fh/fast/malik_h/user/jayoung/git_more_repos/janet_stuff_to_share/renv/library/linux-ubuntu-noble/R-4.5/x86_64-pc-linux-gnu"
    ## [3] "/usr/local/lib/R/site-library"                                                                                              
    ## [4] "/usr/local/lib/R/library"

Show environmental variables

``` r
Sys.getenv()
```

    ## _R_CHECK_EXCESSIVE_IMPORTS_
    ##                         20
    ## _R_CHECK_EXECUTABLES_   false
    ## _R_CHECK_EXECUTABLES_EXCLUSIONS_
    ##                         false
    ## _R_CHECK_LENGTH_1_CONDITION_
    ##                         package:_R_CHECK_PACKAGE_NAME_,abort,verbose
    ## _R_CHECK_LENGTH_1_LOGIC2_
    ##                         package:_R_CHECK_PACKAGE_NAME_,abort,verbose
    ## _R_CHECK_NEWS_IN_PLAIN_TEXT_
    ##                         true
    ## _R_CHECK_S3_METHODS_NOT_REGISTERED_
    ##                         true
    ## _R_CHECK_SUGGESTS_ONLY_
    ##                         true
    ## _R_CHECK_XREFS_MIND_SUSPECT_ANCHORS_
    ##                         true
    ## _R_CHECK_XREFS_NOTE_MISSING_PACKAGE_ANCHORS_
    ##                         true
    ## _R_COMPARE_LANG_OBJECTS
    ##                         eqonly
    ## _R_CXX_USE_NO_REMAP_    true
    ## _R_USE_STRICT_R_HEADERS_
    ##                         true
    ## BIOCONDUCTOR_DOCKER_VERSION
    ##                         3.22.3
    ## BIOCONDUCTOR_VERSION    3.22
    ## BIOCPARALLEL_WORKER_NUMBER
    ##                         4
    ## BROWSER                 /usr/lib/rstudio-server/bin/postback/rpostback-browser
    ## CLICOLOR_FORCE          1
    ## DISPLAY                 :0
    ## EDITOR                  vi
    ## GIT_ASKPASS             rpostback-askpass
    ## HOME                    /home/jayoung
    ## KMP_DEVICE_THREAD_LIMIT
    ##                         2
    ## KMP_TEAMS_THREAD_LIMIT
    ##                         2
    ## LANG                    en_US.UTF-8
    ## LD_LIBRARY_PATH         /usr/local/lib/R/lib:/usr/local/lib:/usr/lib/x86_64-linux-gnu:/usr/lib/jvm/java-21-openjdk-amd64/lib/server:/usr/local/lib/R/lib:/.singularity.d/libs:/lib:/usr/local/lib:/usr/lib/x86_64-linux-gnu:/usr/lib/jvm/java-21-openjdk-amd64/lib/server:/.singularity.d/libs
    ## LIBSBML_CFLAGS          -I/usr/include
    ## LIBSBML_LIBS            -lsbml
    ## LN_S                    ln -s
    ## LOGNAME                 jayoung
    ## MAKE                    make
    ## MANPATH                 /app/software/Apptainer/1.1.6/share/man:/app/lmod/lmod/share/man::
    ## MPLENGINE               tkAgg
    ## NOT_CRAN                true
    ## OMP_NUM_THREADS         2
    ## OMP_THREAD_LIMIT        2
    ## PAGER                   /usr/bin/pager
    ## PATH                    /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/lib/rstudio-server/bin/quarto/bin:/usr/lib/rstudio-server/bin/postback
    ## PWD                     /fh/fast/malik_h/user/jayoung/git_more_repos/janet_stuff_to_share/misc_tests
    ## R_ARCH                  
    ## R_BROWSER               xdg-open
    ## R_BZIPCMD               /usr/bin/bzip2
    ## R_CLI_HAS_HYPERLINK_IDE_HELP
    ##                         true
    ## R_CLI_HAS_HYPERLINK_IDE_RUN
    ##                         true
    ## R_CLI_HAS_HYPERLINK_IDE_VIGNETTE
    ##                         true
    ## R_DEFAULT_INTERNET_TIMEOUT
    ##                         600
    ## R_DOC_DIR               /usr/local/lib/R/doc
    ## R_GZIPCMD               /usr/bin/gzip
    ## R_HOME                  /usr/local/lib/R
    ## R_INCLUDE_DIR           /usr/local/lib/R/include
    ## R_LIBS                  /usr/local/lib/R/host-site-library:/fh/fast/malik_h/user/jayoung/git_more_repos/janet_stuff_to_share/renv/library/linux-ubuntu-noble/R-4.5/x86_64-pc-linux-gnu:/home/jayoung/.cache/R/renv/sandbox/linux-ubuntu-noble/R-4.5/x86_64-pc-linux-gnu/25ebdc09
    ## R_LIBS_SITE             /usr/local/lib/R/site-library
    ## R_LIBS_USER             /fh/fast/malik_h/user/jayoung/git_more_repos/janet_stuff_to_share/renv/library/linux-ubuntu-noble/R-4.5/x86_64-pc-linux-gnu
    ## R_PAPERSIZE             letter
    ## R_PAPERSIZE_USER        letter
    ## R_PDFVIEWER             /usr/bin/xdg-open
    ## R_PLATFORM              x86_64-pc-linux-gnu
    ## R_PRINTCMD              /usr/bin/lpr
    ## R_RD4PDF                times,inconsolata,hyper
    ## R_SESSION_TMPDIR        /tmp/RtmpSgB08E
    ## R_SHARE_DIR             /usr/local/lib/R/share
    ## R_STRIP_SHARED_LIB      strip --strip-unneeded
    ## R_STRIP_STATIC_LIB      strip --strip-debug
    ## R_TEXI2DVICMD           /usr/bin/texi2dvi
    ## R_UNZIPCMD              /usr/bin/unzip
    ## R_ZIPCMD                /usr/bin/zip
    ## RENV_DEFAULT_R_ENVIRON
    ##                         <NA>
    ## RENV_DEFAULT_R_ENVIRON_USER
    ##                         <NA>
    ## RENV_DEFAULT_R_LIBS     /usr/local/lib/R/host-site-library:
    ## RENV_DEFAULT_R_LIBS_SITE
    ##                         /usr/local/lib/R/site-library
    ## RENV_DEFAULT_R_LIBS_USER
    ##                         /home/jayoung/R/x86_64-pc-linux-gnu-library/4.5
    ## RENV_DEFAULT_R_PROFILE
    ##                         <NA>
    ## RENV_DEFAULT_R_PROFILE_USER
    ##                         <NA>
    ## RENV_PROJECT            /fh/fast/malik_h/user/jayoung/git_more_repos/janet_stuff_to_share
    ## RETICULATE_MINICONDA_PYTHON_ENVPATH
    ##                         /fh/fast/malik_h/user/jayoung/git_more_repos/janet_stuff_to_share/renv/python/r-reticulate
    ## RMARKDOWN_MATHJAX_PATH
    ##                         /usr/lib/rstudio-server/resources/mathjax-27
    ## RMARKDOWN_PREVIEW_DIR   /tmp/Rtmps6oxkw
    ## RS_RPOSTBACK_PATH       /usr/lib/rstudio-server/bin/rpostback
    ## RS_SERVER_RPC_SOCKET_PATH
    ##                         /tmp/59196500/1785460974/rstudio-rserver/session-server-rpc.socket
    ## RS_SESSION_TMP_DIR      /tmp/59196500/1785460974/rstudio-rsession
    ## RSTUDIO                 1
    ## RSTUDIO_CHILD_PROCESS_PANE
    ##                         render
    ## RSTUDIO_CLI_HYPERLINKS
    ##                         true
    ## RSTUDIO_CONSOLE_COLOR   256
    ## RSTUDIO_CONSOLE_WIDTH   70
    ## RSTUDIO_LONG_VERSION    2025.09.2+418
    ## RSTUDIO_PANDOC          /usr/lib/rstudio-server/bin/quarto/bin/tools/x86_64
    ## RSTUDIO_PROGRAM_MODE    server
    ## RSTUDIO_R_MODULE        
    ## RSTUDIO_R_PRELAUNCH_SCRIPT
    ##                         
    ## RSTUDIO_R_REPO          
    ## RSTUDIO_R_VERSION_LABEL
    ##                         
    ## RSTUDIO_SESSION_PID     30936
    ## RSTUDIO_SESSION_STREAM
    ##                         jayoung-d
    ## RSTUDIO_USER_IDENTITY   jayoung
    ## RSTUDIO_VERSION         2025.09.2.418
    ## RSTUDIOAPI_IPC_REQUESTS_FILE
    ##                         /tmp/Rtmps6oxkw/rstudio-ipc-requests-78d8e1f393c.rds
    ## RSTUDIOAPI_IPC_RESPONSE_FILE
    ##                         /tmp/Rtmps6oxkw/rstudio-ipc-response-78d81598e4a4.rds
    ## RSTUDIOAPI_IPC_SHARED_SECRET
    ##                         5314de20-ff26-4a57-b352-63c91beaac54
    ## SED                     /usr/bin/sed
    ## SF_PARTNER              posit_rstudio
    ## SHELL                   /bin/bash
    ## SHLVL                   0
    ## SPARK_CONNECT_USER_AGENT
    ##                         posit-rstudio
    ## SSH_ASKPASS             rpostback-askpass
    ## TAR                     /usr/bin/tar
    ## TERM                    xterm-256color
    ## USER                    jayoung

sessionInfo

``` r
sessionInfo()
```

    ## R version 4.5.2 (2025-10-31)
    ## Platform: x86_64-pc-linux-gnu
    ## Running under: Ubuntu 24.04.3 LTS
    ## 
    ## Matrix products: default
    ## BLAS:   /usr/lib/x86_64-linux-gnu/openblas-pthread/libblas.so.3 
    ## LAPACK: /usr/lib/x86_64-linux-gnu/openblas-pthread/libopenblasp-r0.3.26.so;  LAPACK version 3.12.0
    ## 
    ## locale:
    ##  [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C              
    ##  [3] LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8    
    ##  [5] LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8   
    ##  [7] LC_PAPER=en_US.UTF-8       LC_NAME=C                 
    ##  [9] LC_ADDRESS=C               LC_TELEPHONE=C            
    ## [11] LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       
    ## 
    ## time zone: Etc/UTC
    ## tzcode source: system (glibc)
    ## 
    ## attached base packages:
    ## [1] stats     graphics  grDevices utils     datasets  methods   base     
    ## 
    ## loaded via a namespace (and not attached):
    ##  [1] compiler_4.5.2    fastmap_1.2.0     cli_3.6.5         ragg_1.5.0       
    ##  [5] htmltools_0.5.8.1 tools_4.5.2       rstudioapi_0.17.1 yaml_2.3.10      
    ##  [9] rmarkdown_2.30    knitr_1.50        digest_0.6.37     xfun_0.57        
    ## [13] textshaping_1.0.4 lifecycle_1.0.5   systemfonts_1.3.1 rlang_1.2.0      
    ## [17] evaluate_1.0.5
