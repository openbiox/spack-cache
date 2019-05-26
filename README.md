# spack-cache  <img src="https://raw.githubusercontent.com/openbiox/openbiox-wiki/master/static/img/logo-long.png" align="right" alt="openbiox" width="200"/>

<img src="https://img.shields.io/badge/lifecycle-experimental-orange.svg" alt="Life cycle: experimental"> <img src="https://img.shields.io/github/repo-size/openbiox/spack-cache.svg" alt="Repo size"/> <img src="https://img.shields.io/github/issues/openbiox/spack-cache.svg" alt="issues"/>

[spack-cache](https://github.com/openbiox/spack-cache) is a project to provide the cache files of [spack](https://github.com/spack/spack), a flexible package manager that supports multiple versions, configurations, platforms, and compilers.

Packages supported by [spack](https://github.com/spack/spack) are available [here](https://spack.readthedocs.io/en/latest/basic_usage.html#listing-available-packages).

Noteably, all cache files provided in this project (phase1: [weiyun](https://share.weiyun.com/5l7vgR7)) can directly be used by spack to perform downstream installtion steps. If you download all the files in this project, you will be able to deploy several useful data analysis environment locally and offline.

```bash
# 2019-05-21
abinit                    gccmakedep             libjpeg                 ndiff                        r-digest
abyss                     gccxml                 libjpeg-turbo           nek5000                      rdma-core
ack                       gconf                  libksba                 nekbone                      rdp-classifier
activeharmony             gcta                   liblbxutil              nekcem                       re2c
acts-core                 gdal                   liblockfile             nektar                       readfq
adept-utils               gdb                    libmatheval             nest                         readline
adios                     gdbm                   libmaxminddb            netcdf                       recordproto
adios2                    gdk-pixbuf             libmesh                 netcdf-cxx                   redis
adlbx                     geant4                 libmng                  netcdf-cxx4                  redset
adol-c                    gemmlowp               libmongoc               netcdf-fortran               rempi
aida                      genomefinisher         libmonitor              netgauge                     rename
albert                    geopm                  libnbc                  netgen                       rendercheck
alglib                    geos                   libnl                   netlib-lapack                renderproto
alsa-lib                  gettext                libnova                 netlib-scalapack             resourceproto
amg                       gflags                 libnsl                  netlib-xblas                 r-expint
amg2013                   ghostscript-fonts      libogg                  nettle                       r-fansi
ampliconnoise             giflib                 liboldx                 nextflow                     r-ggplot2
amrex                     git                    libpcap                 nfft                         r-gtable
amrvis                    git-fat-git            libpciaccess            nghttp2                      rhash
andi                      git-imerge             libpfm4                 nginx                        r-labeling
angsd                     git-lfs                libpipeline             ngmlr                        r-lazyeval
ant                       gl2ps                  libplist                ninja                        rlwrap
antlr                     glew                   libpng                  ninja-fortran                r-magrittr
ants                      glfmultiples           libpsl                  nix                          r-mass
applewmproto              glib                   libpthread-stubs        nlohmann-json                rmats
appres                    glibmm                 libquo                  nlopt                        r-munsell
apr                       glimmer                libseccomp              nmap                         rna-seqc
apr-util                  glm                    libsharp                nnvm                         rngstreams
aragorn                   global                 libsigcpp               node-js                      rocksdb
argobots                  globalarrays           libsigsegv              npb                          routino
argp-standalone           globus-toolkit         libsm                   npm                          rpcsvc-proto
argtable                  glog                   libsodium               npth                         r-pillar
armadillo                 glpk                   libspatialindex         nspr                         r-pkgconfig
arm-forge                 glproto                libspatialite           numactl                      r-plyr
arpack-ng                 gmake                  libsplash               numdiff                      r-r6
arrow                     gmap-gsnap             libssh                  nvptx-tools                  r-rcolorbrewer
asciidoc                  gmime                  libssh2                 nwchem                       r-rcpp
asciidoctor               gmodel                 libsvm                  nyancat                      r-reshape2
aspcud                    gmp                    libszip                 occa                         r-rjava
aspect                    gmsh                   libtasn1                oce                          r-rlang
aspell                    gnat                   libtermkey              oclint                       r-rmysql
aspell6-de                gnupg                  libtiff                 oclock                       rsbench
aspell6-en                gnuplot                libtirpc                octave                       r-scales
aspell6-es                gnutls                 libtool                 octave-optim                 rstart
aspera-cli                go                     libunistring            octave-splines               r-stringi
assimp                    gobject-introspection  libunwind               octave-struct                r-stringr
astral                    go-bootstrap           libusb                  octopus                      rsync
astyle                    googletest             libusbmuxd              omega-h                      rtags
atk                       gotcha                 libuuid                 ompt-openmp                  r-tibble
atlas                     gource                 libuv                   oniguruma                    ruby
atom-dft                  gperf                  libvorbis               ont-albacore                 ruby-narray
atompaw                   gperftools             libvterm                opa-psm2                     ruby-ronn
atop                      gpgme                  libwebsockets           opari2                       ruby-rubyinline
at-spi2-atk               grackle                libwindowswm            openbabel                    ruby-terminal-table
at-spi2-core              gradle                 libx11                  openblas                     rust
augustus                  graph500               libxau                  opencoarrays                 rust-bindgen
autoconf                  graphlib               libxaw                  openexr                      r-utf8
autodock-vina             graphmap               libxaw3d                openfoam-com                 r-viridislite
autogen                   graphviz               libxc                   openfoam-org                 sabre
automaded                 grass                  libxcb                  openimageio                  sailfish
automake                  grib-api               libxcomposite           openjdk                      salmon
axel                      gromacs                libxcursor              openjpeg                     samblaster
axl                       gsl                    libxdamage              openkim-models               samrai
bamtools                  gslib                  libxdmcp                openmpi                      samtools
bamutil                   gtkorvo-atl            libxevie                opennurbs                    sandbox
barrnap                   gtkorvo-cercs-env      libxext                 openpa                       sas
bash                      gtkorvo-dill           libxfixes               openslide                    satsuma2
bash-completion           gtkorvo-enet           libxfont                openssh                      saws
bats                      gtkplus                libxfont2               openssl                      sbt
bazel                     gts                    libxfontcache           opium                        scala
bbmap                     guile                  libxft                  optional-lite                scalasca
bc                        h5part                 libxi                   opus                         scallop
bcftools                  h5utils                libxinerama             orfm                         scalpel
bdftopcf                  h5z-zfp                libxkbcommon            orthofinder                  scons
bdw-gc                    hadoop                 libxkbfile              orthomcl                     scotch
bear                      hapcut2                libxkbui                osmctools                    scr
beast1                    hapdip                 libxml2                 otf                          scripts
beast2                    haploview              libxmu                  otf2                         scrnsaverproto
beast-tracer              harfbuzz               libxp                   p4est                        sctk
bedops                    hdf                    libxpm                  p7zip                        sdl2
bedtools2                 hdf5                   libxpresent             pacbio-daligner              sdl2-image
beforelight               help2man               libxprintapputil        pacbio-damasker              sdsl-lite
benchmark                 hepmc                  libxprintutil           pacbio-dazz-db               sed
berkeley-db               heppdt                 libxrandr               pacbio-dextractor            seqan
bertini                   hic-pro                libxrender              packmol                      seqprep
bigreqsproto              highfive               libxres                 pacvim                       seqtk
binutils                  highwayhash            libxscrnsaver           pagit                        serf
bioawk                    hiop                   libxshmfence            pagmo                        sessreg
biobloom                  hisat2                 libxslt                 pal                          setxkbmap
bismark                   hisea                  libxsmm                 paml                         sga
bison                     hmmer                  libxstream              pandaseq                     shapeit
bitmap                    hpccg                  libxt                   pango                        shared-mime-info
blast2go                  hpctoolkit             libxtrap                papi                         shocklibs
blast-plus                hpcviewer              libxtst                 papyrus                      showfont
blat                      hpgmg                  libxv                   parallel                     shuffile
blaze                     hpl                    libxvmc                 parallel-netcdf              sickle
blis                      hpx                    libxxf86dga             paraview                     siesta
bliss                     hsakmt                 libxxf86misc            parmetis                     signify
blitz                     htop                   libxxf86vm              patch                        silo
bmake                     htslib                 libyaml                 pbbam                        simgrid
bml                       httpie                 libyogrt                pcre                         simplemoc
bolt                      hugo                   libzip                  pcre2                        simul
bookleaf-cpp              hunspell               lighttpd                pdsh                         singularity
boost                     hwloc                  likwid                  perl                         skilion-onedrive
boostmplcartesianproduct  hybpiper               linkphase3              perl-capture-tiny            sleef
bowtie                    hydra                  linux-headers           perl-data-dumper             slepc
bowtie2                   hydrogen               listres                 perl-encode-locale           slurm
boxlib                    hyphy                  llvm                    perl-exporter-tiny           smalt
bpp-core                  hypre                  llvm-openmp-ompt        perl-extutils-makemaker      smproxy
bpp-phyl                  iceauth                lmdb                    perl-extutils-pkgconfig      snakemake
bpp-seq                   icet                   lmod                    perl-file-copy-recursive     snappy
bpp-suite                 ico                    lm-sensors              perl-file-sharedir-install   sniffles
bracken                   icu4c                  lndir                   perl-gd                      snpeff
branson                   id3lib                 log4cplus               perl-gd-graph                snptest
breseq                    idba                   log4cxx                 perl-gdgraph-histogram       soapdenovo2
bridger                   igraph                 loki                    perl-gd-text                 soapdenovo-trans
brigand                   igvtools               lordec                  perl-http-date               sofa-c
brotli                    ilmbase                lrslib                  perl-inline                  somatic-sniper
bsseeker2                 imake                  lrzip                   perl-inline-c                sortmerna
bucky                     imp                    ltrace                  perl-list-moreutils          sowing
bumpversion               impute2                lua                     perl-math-cdf                sox
busco                     infernal               lua-bitlib              perl-math-cephes             spades
bwa                       inputproto             lua-jit                 perl-module-build            span-lite
byobu                     intel                  lua-lpeg                perl-parallel-forkmanager    spark
bzip2                     intel-daal             lua-luafilesystem       perl-parse-recdescent        sparsehash
cabana                    intel-gpu-tools        lua-luaposix            perl-pegex                   sparta
cairo                     intel-mkl              lua-mpack               perl-perl4-corelibs          spdlog
cairomm                   intel-mkl-dnn          luit                    perl-perl6-slurp             speex
callpath                  intel-mpi              lulesh                  perl-statistics-descriptive  spglib
cantera                   intel-pin              lwgrp                   perl-sub-uplevel             sph2pipe
cap3                      intel-tbb              lz4                     perl-test-exception          spherepack
capstone                  intel-xed              lzma                    perl-test-needs              spot
cares                     intltool               lzo                     perl-test-warn               sqlite
cask                      ior                    m4                      perl-uri                     sqlitebrowser
casper                    iozone                 macsio                  perl-xml-parser              squashfs
catch                     iperf2                 mad-numdiff             perl-yaml-libyaml            squid
cbench                    iperf3                 mafft                   petsc                        sra-toolkit
cblas                     isaac                  magics                  pixman                       ssht
c-blosc                   isaac-server           magma                   pkgconf                      sst-core
cdbfasta                  isl                    makedepend              pngwriter                    sst-dumpi
cdhit                     itstool                mallocmc                pocl                         sst-macro
cfitsio                   itsx                   manta                   presentproto                 staden-io-lib
cgal                      jackcess               mapserver               printproto                   star
cgm                       jags                   mariadb                 proj                         startup-notification
cgns                      jansson                mariadb-c-client        protobuf                     stow
chapel                    jasper                 masa                    py-alabaster                 strace
charmpp                   jbigkit                matio                   py-argparse                  strelka
cityhash                  jdk                    maven                   py-babel                     stress
clapack                   jellyfish              maverick                py-biopython                 stringtie
clfft                     jemalloc               mawk                    py-bottleneck                string-view-lite
clhep                     jmol                   mbedtls                 py-bx-python                 structure
c-lime                    jq                     mc                      py-certifi                   strumpack
clingo                    json-c                 mcl                     py-cffi                      subread
clp                       jsoncpp                mdtest                  py-chardet                   subversion
cmake                     json-cwx               med                     py-cycler                    suite-sparse
colm                      json-glib              megahit                 py-cython                    sumaclust
commons-lang              judy                   memaxes                 py-dateutil                  sundials
commons-logging           julia                  memkind                 py-dlcpar                    superlu
compositeproto            k8                     mercurial               py-docutils                  superlu-dist
cubelib                   kahip                  mercury                 py-filelock                  superlu-mt
cubew                     kaks-calculator        mesa                    py-functools32               sw4lite
cuda                      kallisto               mesa-glu                py-h5py                      swap-assembler
curl                      karma                  meshkit                 py-idna                      swarm
czmq                      kbproto                meson                   py-imagesize                 swfft
damageproto               kdiff3                 mesquite                py-jinja2                    swiftsim
dbus                      kentutils              metabat                 py-kiwisolver                swig
dealii                    kibana                 metaphysicl             py-lit                       symengine
diffutils                 kim-api                metis                   py-mako                      sympol
dmd                       kmergenie              microbiomeutil          py-mappy                     sz
dmlc-core                 kokkos                 migrate                 py-markupsafe                tabix
dmxproto                  kraken                 minced                  py-matplotlib                talloc
docbook-xml               krb5                   miniaero                py-mpi4py                    tantan
docbook-xsl               krims                  miniamr                 py-natsort                   tar
double-conversion         kripke                 miniasm                 py-nose                      task
doxygen                   kvtree                 miniconda2              py-numexpr                   taskd
dri2proto                 ladot                  miniconda3              py-numpy                     tasmanian
dri3proto                 lammps                 minife                  py-ont-fast5-api             tassel
dtcmp                     last                   minigmg                 py-packaging                 tcl
dyninst                   lastz                  minimap2                py-pandas                    tclap
eccodes                   latte                  miniqmc                 py-pillow                    tcl-itcl
ed                        launchmon              minisign                py-pip                       tcl-tcllib
editline                  lazyten                minitri                 py-pkgconfig                 tcl-tclxml
eigen                     lbxproxy               minivite                py-protobuf                  tcptrace
elfutils                  lbzip2                 minuit                  py-py2neo                    tealeaf
emacs                     lcals                  mitofates               py-pycparser                 tetgen
environment-modules       lcms                   mixcr                   py-pygments                  tethex
erfa                      ldc-bootstrap          mkfontdir               py-pyparsing                 texinfo
evieext                   legion                 mkfontscale             py-pysam                     texlive
exmcutils                 lemon                  mlhka                   py-pysocks                   tk
exonerate                 leveldb                mmg                     py-pytz                      tmux
expat                     lftp                   moab                    py-pyyaml                    tophat
exuberant-ctags           libaec                 modern-wheel            py-requests                  trapproto
fastme                    libaio                 mongo-cxx-driver        py-scipy                     trilinos
fastphase                 libapplewm             mono                    py-setuptools                typhon
fastqc                    libarchive             mosh                    py-setuptools-scm            udunits2
fastqvalidator            libassuan              mothur                  py-six                       unibilium
fasttree                  libatomic-ops          motif                   py-snowballstemmer           unixodbc
fastx-toolkit             libbeagle              mount-point-attributes  py-sphinx                    unzip
fftw                      libbsd                 mozjs                   py-sphinxcontrib-websupport  util-macros
findutils                 libbson                mpark-variant           py-sphinx-rtd-theme          varscan
fixesproto                libcanberra            mpc                     py-subprocess32              vcftools
flac                      libcap                 mpdecimal               python                       videoproto
flatbuffers               libceed                mpe2                    py-typing                    vsearch
flex                      libcerf                mpest                   py-urllib3                   vt
flux-core                 libcheck               mpfr                    py-wrapt                     wget
flux-sched                libcint                mpibash                 py-zope-event                windowswmproto
fmt                       libcircle              mpich                   qhull                        wtdbg2
fontcacheproto            libconfig              mpifileutils            qjson                        wx
fontconfig                libcroco               mpileaks                qmcpack                      xbitmaps
fontsproto                libctl                 mpip                    qmd-progress                 xcb-proto
fonttosfnt                libdivsufsort          mpir                    qorts                        xcb-util
font-util                 libdmx                 mrbayes                 qrupdate                     xcb-util-image
font-xfree86-type1        libdrm                 mscgen                  qt                           xcb-util-keysyms
fpc                       libdwarf               msgpack-c               qt-creator                   xcb-util-renderutil
fqtrim                    libeatmydata           mshadow                 qthreads                     xcb-util-wm
freebayes                 libedit                msmc                    quantum-espresso             xcmiscproto
freeglut                  libelf                 multitail               qwt                          xerces-c
freetype                  libemos                multitime               r                            xextproto
freexl                    libepoxy               multiverso              r3d                          xf86dgaproto
fslsfonts                 libevent               mumps                   racon                        xf86driproto
fstobdf                   libevpath              munge                   ragel                        xf86miscproto
ftgl                      libfabric              muparser                raja                         xf86vidmodeproto
fyba                      libffi                 muscle                  randfold                     xineramaproto
fzf                       libffs                 muse                    random123                    xkbcomp
g4abla                    libfontenc             muster                  randrproto                   xkbdata
g4emlow                   libfs                  mxml                    range-v3                     xmlf90
g4ensdfstate              libgcrypt              mysql                   rankstr                      xorg-server
g4ndl                     libgd                  nano                    rapidjson                    xproto
g4neutronxs               libgeotiff             nanoflann               r-assertthat                 xproxymanagementprotocol
g4photonevaporation       libgit2                nanopb                  ravel                        xrandr
g4pii                     libgpg-error           nasm                    raxml                        xtrans
g4radioactivedecay        libgpuarray            nauty                   ray                          xz
g4saiddata                libgridxc              ncbi-magicblast         r-base64enc                  yaml-cpp
g4tendl                   libgtextutils          ncbi-rmblastn           r-biocgenerics               yasm
gapbs                     libharu                nccl                    r-biom-utils                 zeromq
gapcloser                 libhio                 nccmp                   r-cli                        zfp
gasnet                    libiberty              ncdu                    rclone                       zip
gatk                      libice                 ncftp                   r-colorspace                 zlib
gawk                      libiconv               nco                     r-crayon                     zoltan
gblocks                   libidn2                ncurses                 r-dbi                        zsh
gcc                       libint                 ncview                  r-dichromat                  zstd
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
