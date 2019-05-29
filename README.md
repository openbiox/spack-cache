# spack-cache  <img src="https://raw.githubusercontent.com/openbiox/openbiox-wiki/master/static/img/logo-long.png" align="right" alt="openbiox" width="200"/>

<img src="https://img.shields.io/badge/lifecycle-experimental-orange.svg" alt="Life cycle: experimental"> <img src="https://img.shields.io/github/repo-size/openbiox/spack-cache.svg" alt="Repo size"/> <img src="https://img.shields.io/github/issues/openbiox/spack-cache.svg" alt="issues"/>

[spack-cache](https://github.com/openbiox/spack-cache) is a project to provide the cache files of [spack](https://github.com/spack/spack), a flexible package manager that supports multiple versions, configurations, platforms, and compilers.

Packages supported by [spack](https://github.com/spack/spack) are available [here](https://spack.readthedocs.io/en/latest/basic_usage.html#listing-available-packages).

Noteably, all cache files provided in this project (phase1: [weiyun](https://share.weiyun.com/5l7vgR7)) can directly be used by spack to perform downstream installtion steps. If you download all the files in this project, you will be able to deploy several useful data analysis environment locally and offline.

```bash
# 2019-05-29
abinit                    gslib              magics                         perl-net-ssleay                  seqtk
abyss                     gtkorvo-atl        magma                          perl-number-format               serf
ack                       gtkorvo-cercs-env  makedepend                     perl-object-insideout            sessreg
activeharmony             gtkorvo-dill       mallocmc                       perl-package-deprecationmanager  setxkbmap
acts-core                 gtkorvo-enet       manta                          perl-package-stash               sga
adept-utils               gtkplus            mapserver                      perl-package-stash-xs            shapeit
adios                     gts                margo                          perl-padwalker                   shared-mime-info
adios2                    guile              mariadb                        perl-parallel-forkmanager        shocklibs
adlbx                     h5part             mariadb-c-client               perl-params-util                 showfont
adol-c                    h5utils            masa                           perl-params-validate             shuffile
aida                      h5z-zfp            masurca                        perl-parse-recdescent            sickle
albert                    hadoop             matio                          perl-pdf-api2                    siesta
alglib                    hapcut2            maven                          perl-pegex                       signify
alquimia                  hapdip             maverick                       perl-perl4-corelibs              silo
alsa-lib                  haploview          mawk                           perl-perl6-slurp                 simgrid
amg                       harfbuzz           mbedtls                        perl-perlio-gzip                 simplemoc
amg2013                   hdf                mc                             perl-perlio-utf8-strict          simul
ampliconnoise             hdf5               mcl                            perl-readonly                    singularity
amrex                     help2man           mdtest                         perl-regexp-common               skilion-onedrive
amrvis                    hepmc              med                            perl-scalar-list-utils           sleef
andi                      heppdt             megahit                        perl-set-intspan                 slepc
angsd                     hic-pro            memaxes                        perl-statistics-basic            slurm
ant                       highfive           memkind                        perl-statistics-descriptive      smalt
antlr                     highwayhash        mercurial                      perl-statistics-pca              smproxy
ants                      hiop               mercury                        perl-sub-exporter                snakemake
applewmproto              hisat2             mesa                           perl-sub-exporter-progressive    snappy
appres                    hisea              mesa-glu                       perl-sub-identify                sniffles
apr                       hmmer              meshkit                        perl-sub-install                 snpeff
apr-util                  hpccg              meson                          perl-sub-name                    snptest
aragorn                   hpctoolkit         mesquite                       perl-sub-uplevel                 soapdenovo2
argobots                  hpcviewer          metabat                        perl-svg                         soapdenovo-trans
argp-standalone           hpgmg              metaphysicl                    perl-swissknife                  sofa-c
argtable                  hpl                metis                          perl-task-weaken                 somatic-sniper
armadillo                 hpx                microbiomeutil                 perl-term-readkey                sortmerna
arm-forge                 hsakmt             migrate                        perl-test-cleannamespaces        sowing
arpack-ng                 htop               minced                         perl-test-deep                   sox
arrow                     htslib             miniaero                       perl-test-differences            spades
asciidoc                  httpie             miniamr                        perl-test-exception              span-lite
asciidoctor               hugo               miniasm                        perl-test-fatal                  spark
aspcud                    hunspell           miniconda2                     perl-test-memory-cycle           sparsehash
aspect                    hwloc              miniconda3                     perl-test-most                   sparta
aspell                    hybpiper           minife                         perl-test-needs                  spdlog
aspell6-de                hydra              minigmg                        perl-test-requires               speex
aspell6-en                hydrogen           minimap2                       perl-test-requiresinternet       spglib
aspell6-es                hyphy              miniqmc                        perl-test-warn                   sph2pipe
aspera-cli                hypre              minisign                       perl-test-warnings               spherepack
assimp                    iceauth            minitri                        perl-text-csv                    spot
astral                    icet               minivite                       perl-text-diff                   sqlite
astyle                    ico                minuit                         perl-text-format                 sqlitebrowser
atk                       icu4c              mitofates                      perl-text-simpletable            squashfs
atlas                     id3lib             mixcr                          perl-text-soundex                squid
atom-dft                  idba               mkfontdir                      perl-text-unidecode              sra-toolkit
atompaw                   igraph             mkfontscale                    perl-time-hires                  ssht
atop                      igvtools           mlhka                          perl-time-piece                  sst-core
at-spi2-atk               ilmbase            mmg                            perl-try-tiny                    sst-dumpi
at-spi2-core              imake              moab                           perl-uri                         sst-macro
augustus                  imp                modern-wheel                   perl-uri-escape                  staden-io-lib
autoconf                  impute2            mongo-cxx-driver               perl-version                     star
autodock-vina             infernal           mono                           perl-want                        startup-notification
autogen                   inputproto         mosh                           perl-www-robotrules              stow
automaded                 intel              mothur                         perl-xml-parser                  strace
automake                  intel-daal         motif                          perl-xml-simple                  strelka
axel                      intel-gpu-tools    mount-point-attributes         perl-yaml                        stress
axl                       intel-mkl          mozjs                          perl-yaml-libyaml                stringtie
bamtools                  intel-mkl-dnn      mpark-variant                  petsc                            string-view-lite
bamutil                   intel-mpi          mpc                            pfft                             structure
barrnap                   intel-pin          mpdecimal                      pflotran                         strumpack
bash                      intel-tbb          mpe2                           pfunit                           subread
bash-completion           intel-xed          mpest                          pgdspider                        subversion
bats                      intltool           mpfr                           pgmath                           suite-sparse
bazel                     ior                mpibash                        phast                            sumaclust
bbmap                     iozone             mpich                          phasta                           sundials
bc                        iperf2             mpifileutils                   phist                            superlu
bcftools                  iperf3             mpileaks                       phylip                           superlu-dist
bdftopcf                  isaac              mpip                           picard                           superlu-mt
bdw-gc                    isaac-server       mpir                           picsarlite                       sw4lite
bear                      isl                mrbayes                        pidx                             swap-assembler
beast1                    itstool            mscgen                         pigz                             swarm
beast2                    itsx               msgpack-c                      pilon                            swfft
beast-tracer              jackcess           mshadow                        pindel                           swiftsim
bedops                    jags               msmc                           piranha                          swig
bedtools2                 jansson            multitail                      pixman                           symengine
beforelight               jasper             multitime                      pkgconf                          sympol
benchmark                 jbigkit            multiverso                     pkg-config                       sz
berkeley-db               jdk                mumps                          planck-likelihood                tabix
bertini                   jellyfish          munge                          plasma                           talloc
bigreqsproto              jemalloc           muparser                       platypus                         tantan
binutils                  jmol               muscle                         plink                            tar
bioawk                    jq                 muse                           plumed                           task
biobloom                  json-c             muster                         pmdk                             taskd
bismark                   jsoncpp            mxml                           pmix                             tasmanian
bison                     json-cwx           mysql                          pnfft                            tassel
bitmap                    json-glib          nano                           pngwriter                        tcl
blast2go                  judy               nanoflann                      pnmpi                            tclap
blast-plus                julia              nanopb                         poamsa                           tcl-itcl
blat                      k8                 nasm                           pocl                             tcl-tcllib
blaze                     kahip              nauty                          poppler                          tcl-tclxml
blis                      kaks-calculator    ncbi-magicblast                poppler-data                     tcptrace
bliss                     kallisto           ncbi-rmblastn                  portage                          tealeaf
blitz                     karma              nccl                           postgresql                       templight
bmake                     kbproto            nccmp                          ppl                              tetgen
bml                       kdiff3             ncdu                           pplacer                          tethex
bolt                      kentutils          ncftp                          prank                            texinfo
bookleaf-cpp              kibana             nco                            precice                          texlive
boost                     kim-api            ncurses                        presentproto                     tfel
boostmplcartesianproduct  kmergenie          ncview                         preseq                           thornado-mini
bowtie                    kokkos             ndiff                          price                            thrift
bowtie2                   kraken             nek5000                        primer3                          thrust
boxlib                    krb5               nekbone                        printproto                       tig
bpp-core                  krims              nekcem                         prng                             time
bpp-phyl                  kripke             nektar                         probconsrna                      tinyxml
bpp-seq                   kvtree             nest                           prodigal                         tinyxml2
bpp-suite                 ladot              netcdf                         proj                             tk
bracken                   lammps             netcdf-cxx                     protobuf                         tmalign
branson                   last               netcdf-cxx4                    proxymngr                        tmux
breseq                    lastz              netcdf-fortran                 pruners-ninja                    tmuxinator
bridger                   latte              netgauge                       pslib                            tophat
brigand                   launchmon          netgen                         ps-lite                          tracer
brotli                    lazyten            netlib-lapack                  psmc                             transdecoder
bsseeker2                 lbxproxy           netlib-scalapack               pugixml                          transposome
bucky                     lbzip2             netlib-xblas                   pumi                             transset
bumpversion               lcals              nettle                         pv                               trapproto
busco                     lcms               nextflow                       pvm                              tree
bwa                       ldc-bootstrap      nfft                           pxz                              treesub
byobu                     legion             nghttp2                        py-alabaster                     triangle
bzip2                     lemon              nginx                          py-argparse                      trilinos
cabana                    leveldb            ngmlr                          py-babel                         trimal
cairo                     lftp               ninja                          py-biopython                     trimgalore
cairomm                   libaec             ninja-fortran                  py-bottleneck                    trimmomatic
callpath                  libaio             nix                            py-bx-python                     trnascan-se
cantera                   libapplewm         nlohmann-json                  py-certifi                       tut
cap3                      libarchive         nlopt                          py-cffi                          twm
capstone                  libassuan          nmap                           py-chardet                       typhon
cares                     libatomic-ops      nnvm                           py-cutadapt                      typhonio
cask                      libbeagle          node-js                        py-cycler                        uberftp
casper                    libbsd             npb                            py-cython                        ucx
catch                     libbson            npm                            py-dateutil                      udunits2
cbench                    libcanberra        npth                           py-dlcpar                        umpire
cblas                     libcap             nspr                           py-docutils                      uncrustify
c-blosc                   libceed            numactl                        py-filelock                      unibilium
cdbfasta                  libcerf            numdiff                        py-functools32                   units
cddlib                    libcheck           nvptx-tools                    py-h5py                          unixodbc
cdhit                     libcint            nwchem                         py-idna                          unuran
ceres-solver              libcircle          nyancat                        py-imagesize                     unzip
cfitsio                   libconfig          occa                           py-jinja2                        util-linux
cgal                      libcroco           oce                            py-kiwisolver                    util-macros
cgm                       libctl             oclint                         py-lit                           uuid
cgns                      libdivsufsort      oclock                         py-mako                          uvw
chapel                    libdmx             octave                         py-mappy                         valgrind
charmpp                   libdrm             octave-optim                   py-markupsafe                    vardictjava
cityhash                  libdwarf           octave-splines                 py-matplotlib                    varscan
clapack                   libeatmydata       octave-struct                  py-mpi4py                        vc
clfft                     libedit            octopus                        py-natsort                       vcftools
clhep                     libelf             omega-h                        py-nose                          vcsh
c-lime                    libemos            ompt-openmp                    py-numexpr                       vdt
clingo                    libepoxy           oniguruma                      py-numpy                         vecgeom
clp                       libevent           ont-albacore                   py-ont-fast5-api                 veclibfort
cmake                     libevpath          opa-psm2                       py-packaging                     vegas2
codes                     libfabric          opari2                         py-pandas                        veloc
colm                      libffi             openbabel                      py-pillow                        velvet
commons-lang              libffs             openblas                       py-pip                           verilator
commons-logging           libfontenc         opencoarrays                   py-pkgconfig                     videoproto
compositeproto            libfs              openexr                        py-protobuf                      viewres
cppzmq                    libgcrypt          openfoam-com                   py-py2neo                        vigra
cryptopp                  libgd              openfoam-org                   py-pycparser                     vim
cubelib                   libgeotiff         openimageio                    py-pygments                      virtualgl
cubew                     libgit2            openjdk                        py-pyparsing                     vmatch
cuda                      libgpg-error       openjpeg                       py-pysam                         voropp
curl                      libgpuarray        openkim-models                 py-pysocks                       votca-tools
czmq                      libgridxc          openmpi                        py-pytables                      vsearch
damageproto               libgtextutils      opennurbs                      py-pytz                          vt
dbus                      libharu            openpa                         py-pyyaml                        vtkh
dealii                    libhio             openslide                      py-requests                      vtkm
diffutils                 libiberty          openssh                        py-scikit-learn                  wget
dmd                       libice             openssl                        py-scipy                         wgsim
dmlc-core                 libiconv           opium                          py-setuptools                    windowswmproto
dmxproto                  libidn2            optional-lite                  py-setuptools-scm                wireshark
docbook-xml               libint             opus                           py-six                           wordnet
docbook-xsl               libjpeg            orfm                           py-snowballstemmer               wt
double-conversion         libjpeg-turbo      orthofinder                    py-sphinx                        wtdbg2
doxygen                   libksba            orthomcl                       py-sphinxcontrib-websupport      wx
dri2proto                 liblbxutil         osmctools                      py-sphinx-rtd-theme              x11perf
dri3proto                 liblockfile        otf                            py-subprocess32                  xapian-core
dtcmp                     libmatheval        otf2                           pythia6                          xauth
dyninst                   libmaxminddb       p4est                          python                           xbacklight
eccodes                   libmesh            p7zip                          py-typing                        xbiff
eclipse-gcj-parser        libmng             pacbio-daligner                py-urllib3                       xbitmaps
ed                        libmongoc          pacbio-damasker                py-wrapt                         xbraid
editline                  libmonitor         pacbio-dazz-db                 py-xopen                         xcalc
eigen                     libnbc             pacbio-dextractor              py-zope-event                    xcb-demo
elfutils                  libnl              packmol                        qbox                             xcb-proto
emacs                     libnova            pacvim                         qca                              xcb-util
emboss                    libnsl             pagit                          qhull                            xcb-util-cursor
environment-modules       libogg             pagmo                          qjson                            xcb-util-errors
er                        liboldx            pal                            qmcpack                          xcb-util-image
erfa                      libpcap            paml                           qmd-progress                     xcb-util-keysyms
evieext                   libpciaccess       pandaseq                       qorts                            xcb-util-renderutil
exmcutils                 libpfm4            pango                          qrupdate                         xcb-util-wm
exonerate                 libpipeline        papi                           qt                               xcb-util-xrm
expat                     libplist           papyrus                        qt-creator                       xclip
exuberant-ctags           libpng             parallel                       qthreads                         xclipboard
fastme                    libpsl             parallel-netcdf                quantum-espresso                 xclock
fastphase                 libpthread-stubs   paraview                       qwt                              xcmiscproto
fastqc                    libquo             parmetis                       r                                xcmsdb
fastqvalidator            libseccomp         parmgridgen                    r3d                              xcompmgr
fasttree                  libsharp           parsimonator                   racon                            xconsole
fastx-toolkit             libsigcpp          parsplice                      ragel                            xcursorgen
fftw                      libsigsegv         partitionfinder                raja                             xdbedizzy
figtree                   libsm              patch                          randfold                         xditview
findutils                 libsodium          patchelf                       random123                        xdm
fixesproto                libspatialindex    pathfinder                     randrproto                       xdpyinfo
flac                      libspatialite      pax-utils                      range-v3                         xdriinfo
flatbuffers               libsplash          pbbam                          rankstr                          xedit
flatcc                    libssh             pcma                           rapidjson                        xerces-c
flex                      libssh2            pcre                           r-assertthat                     xeus
flux-core                 libsvm             pcre2                          ravel                            xev
flux-sched                libszip            pdf2svg                        raxml                            xextproto
fmt                       libtasn1           pdsh                           ray                              xeyes
fontcacheproto            libtermkey         pdt                            r-base64enc                      xf86bigfontproto
fontconfig                libtiff            pegtl                          r-biocgenerics                   xf86dga
fontsproto                libtirpc           pennant                        r-biom-utils                     xf86dgaproto
fonttosfnt                libtool            perl                           r-cli                            xf86driproto
font-util                 libunistring       perl-algorithm-diff            rclone                           xf86miscproto
font-xfree86-type1        libunwind          perl-app-cmd                   r-colorspace                     xf86rushproto
fpc                       libusb             perl-array-utils               r-corpcor                        xf86vidmodeproto
fqtrim                    libusbmuxd         perl-b-hooks-endofscope        r-crayon                         xfd
freebayes                 libuuid            perl-cairo                     r-dbi                            xfindproxy
freeglut                  libuv              perl-capture-tiny              r-dichromat                      xfontsel
freetype                  libvorbis          perl-carp-clan                 r-digest                         xfs
freexl                    libvterm           perl-class-data-inheritable    rdma-core                        xfsinfo
fslsfonts                 libwebsockets      perl-class-inspector           rdp-classifier                   xfwp
fstobdf                   libwindowswm       perl-class-load                re2c                             xgamma
ftgl                      libx11             perl-class-load-xs             readfq                           xgboost
fyba                      libxau             perl-clone                     readline                         xgc
fzf                       libxaw             perl-clone-choose              recordproto                      xhmm
g4abla                    libxaw3d           perl-compress-raw-bzip2        redis                            xhost
g4emlow                   libxc              perl-compress-raw-zlib         redset                           xineramaproto
g4ensdfstate              libxcb             perl-config-general            rempi                            xinit
g4ndl                     libxcomposite      perl-contextual-return         rename                           xinput
g4neutronxs               libxcursor         perl-cpan-meta-check           rendercheck                      xkbcomp
g4photonevaporation       libxdamage         perl-data-dumper               renderproto                      xkbdata
g4pii                     libxdmcp           perl-data-optlist              resourceproto                    xkbevd
g4radioactivedecay        libxevie           perl-data-stag                 r-expint                         xkbprint
g4saiddata                libxext            perl-dbd-sqlite                r-fansi                          xkbutils
g4tendl                   libxfixes          perl-dbfile                    r-ggplot2                        xkeyboard-config
gapbs                     libxfont           perl-dbi                       r-gtable                         xkill
gapcloser                 libxfont2          perl-devel-cycle               rhash                            xload
gasnet                    libxfontcache      perl-devel-globaldestruction   r-labeling                       xlogo
gatk                      libxft             perl-devel-overloadinfo        r-lazyeval                       xlsatoms
gawk                      libxi              perl-devel-stacktrace          rlwrap                           xlsclients
gblocks                   libxinerama        perl-digest-md5                r-magrittr                       xlsfonts
gcc                       libxkbcommon       perl-dist-checkconflicts       r-mass                           xmag
gccmakedep                libxkbfile         perl-encode-locale             rmats                            xman
gccxml                    libxkbui           perl-eval-closure              r-munsell                        xmessage
gconf                     libxml2            perl-exception-class           r-mvtnorm                        xmh
gcta                      libxmu             perl-exporter-tiny             rna-seqc                         xmlf90
gdal                      libxp              perl-extutils-config           rngstreams                       xmlto
gdb                       libxpm             perl-extutils-depends          rocksdb                          xmodmap
gdbm                      libxpresent        perl-extutils-helpers          ross                             xmore
gdk-pixbuf                libxprintapputil   perl-extutils-installpaths     routino                          xorg-cf-files
geant4                    libxprintutil      perl-extutils-makemaker        rpcsvc-proto                     xorg-docs
gemmlowp                  libxrandr          perl-extutils-pkgconfig        r-pillar                         xorg-server
genomefinisher            libxrender         perl-file-copy-recursive       r-pkgconfig                      xorg-sgml-doctools
geopm                     libxres            perl-file-homedir              r-plyr                           xphelloworld
geos                      libxscrnsaver      perl-file-listing              r-r6                             xplsprinters
gettext                   libxshmfence       perl-file-pushd                r-rcolorbrewer                   xpr
gflags                    libxslt            perl-file-sharedir-install     r-rcpp                           xprehashprinterlist
ghostscript-fonts         libxsmm            perl-file-slurper              r-reshape2                       xprop
giflib                    libxstream         perl-file-slurp-tiny           r-rjava                          xproto
git                       libxt              perl-file-which                r-rlang                          xproxymanagementprotocol
git-fat-git               libxtrap           perl-font-ttf                  r-rmysql                         xqilla
git-imerge                libxtst            perl-gd                        rsbench                          xrandr
git-lfs                   libxv              perl-gd-graph                  r-scales                         xrdb
gl2ps                     libxvmc            perl-gdgraph-histogram         rstart                           xrefresh
glew                      libxxf86dga        perl-gd-text                   r-stringi                        xrootd
glfmultiples              libxxf86misc       perl-graph                     r-stringr                        xrx
glib                      libxxf86vm         perl-graph-readwrite           rsync                            xsbench
glibmm                    libyaml            perl-hash-merge                rtags                            xscope
glimmer                   libyogrt           perl-html-parser               r-tibble                         xsd
glm                       libzip             perl-html-tagset               ruby                             xset
global                    lighttpd           perl-http-cookies              ruby-narray                      xsetmode
globalarrays              likwid             perl-http-daemon               ruby-ronn                        xsetpointer
globus-toolkit            linkphase3         perl-http-date                 ruby-rubyinline                  xsetroot
glog                      linux-headers      perl-http-message              ruby-terminal-table              xsimd
glpk                      listres            perl-http-negotiate            rust                             xsm
glproto                   llvm               perl-inline                    rust-bindgen                     xstdcmap
gmake                     llvm-openmp-ompt   perl-inline-c                  r-utf8                           xtensor
gmap-gsnap                lmdb               perl-intervaltree              r-viridislite                    xterm
gmime                     lmod               perl-io-html                   sabre                            xtl
gmodel                    lm-sensors         perl-io-sessiondata            sailfish                         xtrans
gmp                       lndir              perl-io-socket-ssl             salmon                           xtrap
gmsh                      log4cplus          perl-io-string                 samblaster                       xts
gnat                      log4cxx            perl-json                      samrai                           xvidtune
gnupg                     loki               perl-libwww-perl               samtools                         xvinfo
gnuplot                   lordec             perl-list-moreutils            sandbox                          xwd
gnutls                    lrslib             perl-log-log4perl              sas                              xwininfo
go                        lrzip              perl-lwp                       satsuma2                         xwud
gobject-introspection     ltrace             perl-lwp-mediatypes            saws                             xxhash
go-bootstrap              lua                perl-lwp-protocol-https        sbt                              xz
googletest                lua-bitlib         perl-math-bezier               scala                            yajl
gotcha                    lua-jit            perl-math-cdf                  scalasca                         yaml-cpp
gource                    lua-lpeg           perl-math-cephes               scallop                          yara
gperf                     lua-luafilesystem  perl-math-matrixreal           scalpel                          yasm
gperftools                lua-luaposix       perl-math-round                scons                            z3
gpgme                     lua-mpack          perl-math-vecstat              scotch                           zeromq
grackle                   luit               perl-module-build              scr                              zfp
gradle                    lulesh             perl-module-build-tiny         scripts                          zip
graph500                  lwgrp              perl-module-implementation     scrnsaverproto                   zlib
graphlib                  lz4                perl-module-runtime            sctk                             zoltan
graphmap                  lzma               perl-module-runtime-conflicts  sdl2                             zsh
graphviz                  lzo                perl-mozilla-ca                sdl2-image                       zstd
grass                     m4                 perl-mro-compat                sdsl-lite
grib-api                  macsio             perl-namespace-clean           sed
gromacs                   mad-numdiff        perl-net-http                  seqan
gsl                       mafft              perl-net-scp-expect            seqprep
```

## Extra packages

We also provides several extra source packages that have not been supported by spack: [link](https://share.weiyun.com/5Nw8dB4).

## Donate

Alipay: 

![donate](https://raw.githubusercontent.com/openbiox/openbiox-wiki/master/static/img/QRcode.png)

## Maintainer

- [@Jianfeng](https://github.com/Miachol)

## LICENSE

MIT
