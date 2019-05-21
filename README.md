# spack-cache  <img src="https://raw.githubusercontent.com/openbiox/openbiox-wiki/master/static/img/logo-long.png" align="right" alt="openbiox" width="200"/>

<img src="https://img.shields.io/badge/lifecycle-experimental-orange.svg" alt="Life cycle: experimental"> <img src="https://img.shields.io/github/repo-size/openbiox/spack-cache.svg" alt="Repo size"/> <img src="https://img.shields.io/github/issues/openbiox/spack-cache.svg" alt="issues"/>

[spack-cache](https://github.com/openbiox/spack-cache) is a project to provide the cache files of [spack](https://github.com/spack/spack), a flexible package manager that supports multiple versions, configurations, platforms, and compilers.

Packages supported by [spack](https://github.com/spack/spack) are available [here](https://spack.readthedocs.io/en/latest/basic_usage.html#listing-available-packages).

Noteably, all cache files provided in this project (phase1: [weiyun](https://share.weiyun.com/5N0BRKn)) can directly be used by spack to perform downstream installtion steps. If you download all the files in this project, you will be able to deploy several useful data analysis environment locally and offline.

```bash
# 2019-05-21
abinit                    dealii                 gts              libpfm4                 netcdf                       r
abyss                     diffutils              guile            libpng                  netcdf-cxx                   r3d
ack                       dmd                    h5part           libpthread-stubs        netgauge                     racon
activeharmony             docbook-xml            h5utils          libsigcpp               netgen                       ragel
acts-core                 docbook-xsl            h5z-zfp          libsigsegv              netlib-scalapack             raja
adept-utils               double-conversion      hadoop           libsm                   nettle                       randfold
adios                     doxygen                hapcut2          libsodium               ninja                        random123
adios2                    dtcmp                  hapdip           libsvm                  node-js                      randrproto
adlbx                     dyninst                haploview        libtiff                 npm                          range-v3
adol-c                    eigen                  harfbuzz         libtool                 npth                         rankstr
aida                      elfutils               hdf              libunistring            nspr                         rapidjson
albert                    environment-modules    hdf5             libunwind               numactl                      r-assertthat
alglib                    erfa                   help2man         libuuid                 oce                          ravel
alsa-lib                  exmcutils              hepmc            libuv                   oniguruma                    raxml
amg                       exonerate              heppdt           libx11                  openblas                     ray
amg2013                   expat                  highfive         libxau                  openjdk                      r-base64enc
ampliconnoise             exuberant-ctags        highwayhash      libxaw                  openjpeg                     r-biocgenerics
amrex                     fastphase              hiop             libxc                   openmpi                      r-biom-utils
amrvis                    fastqc                 hisat2           libxcb                  openpa                       rclone
andi                      fastqvalidator         hisea            libxcomposite           openssl                      r-crayon
angsd                     fasttree               hmmer            libxdamage              otf                          r-dbi
ant                       fastx-toolkit          hpctoolkit       libxdmcp                otf2                         rdma-core
antlr                     fftw                   hpcviewer        libxext                 p4est                        rdp-classifier
ants                      findutils              hpgmg            libxfixes               pal                          re2c
applewmproto              fixesproto             hpl              libxft                  paml                         readfq
appres                    flatbuffers            hpx              libxkbcommon            pandaseq                     readline
apr                       flex                   hsakmt           libxkbfile              pango                        recordproto
apr-util                  flux-core              htop             libxml2                 papi                         redis
aragorn                   flux-sched             htslib           libxmu                  papyrus                      redset
argobots                  fontcacheproto         httpie           libxpm                  parallel                     rempi
argp-standalone           fontconfig             hugo             libxrender              parallel-netcdf              rename
argtable                  fontsproto             hunspell         libxscrnsaver           parmetis                     rendercheck
armadillo                 fonttosfnt             hwloc            libxshmfence            pbbam                        renderproto
arm-forge                 font-util              hybpiper         libxslt                 pcre                         r-expint
arpack-ng                 font-xfree86-type1     hydra            libxt                   pcre2                        rhash
arrow                     fpc                    hydrogen         libxv                   perl                         rlwrap
asciidoc                  fqtrim                 hyphy            libxvmc                 perl-capture-tiny            r-rcpp
asciidoctor               freebayes              hypre            libzip                  perl-data-dumper             r-rjava
aspcud                    freetype               iceauth          llvm                    perl-encode-locale           r-rmysql
aspect                    freexl                 icet             llvm-openmp-ompt        perl-exporter-tiny           rsbench
aspell                    fslsfonts              ico              lmdb                    perl-extutils-makemaker      rsync
aspell6-de                fstobdf                icu4c            lua                     perl-extutils-pkgconfig      ruby
aspell6-en                fyba                   id3lib           lua-luaposix            perl-file-copy-recursive     ruby-ronn
aspell6-es                fzf                    idba             lwgrp                   perl-file-sharedir-install   rust
aspera-cli                g4abla                 igraph           lz4                     perl-gd                      sailfish
assimp                    g4emlow                ilmbase          lzo                     perl-gd-graph                salmon
augustus                  g4ensdfstate           imake            m4                      perl-gdgraph-histogram       samtools
autoconf                  g4ndl                  imp              mariadb                 perl-gd-text                 scons
automake                  g4neutronxs            impute2          matio                   perl-http-date               scotch
axel                      g4photonevaporation    infernal         mercurial               perl-inline                  scrnsaverproto
bamtools                  g4pii                  inputproto       mercury                 perl-inline-c                sdl2
bash                      g4radioactivedecay     intel-daal       mesa                    perl-list-moreutils          sdl2-image
bcftools                  g4saiddata             intel-gpu-tools  mesa-glu                perl-math-cdf                sdsl-lite
bdw-gc                    g4tendl                intel-tbb        meshkit                 perl-math-cephes             serf
beast1                    gapbs                  intel-xed        meson                   perl-module-build            slepc
beast2                    gapcloser              isl              mesquite                perl-parallel-forkmanager    slurm
bedops                    gasnet                 jansson          metabat                 perl-parse-recdescent        snappy
bedtools2                 gatk                   jasper           metaphysicl             perl-pegex                   sniffles
beforelight               gawk                   jbigkit          metis                   perl-perl6-slurp             snpeff
benchmark                 gblocks                jdk              microbiomeutil          perl-statistics-descriptive  snptest
berkeley-db               gcc                    jellyfish        migrate                 perl-sub-uplevel             soapdenovo2
bertini                   gccmakedep             jemalloc         minced                  perl-test-exception          soapdenovo-trans
bigreqsproto              gccxml                 jmol             miniaero                perl-test-needs              sofa-c
binutils                  gconf                  jq               miniamr                 perl-test-warn               somatic-sniper
bioawk                    gcta                   json-c           miniasm                 perl-uri                     sortmerna
biobloom                  gdal                   jsoncpp          miniconda2              perl-xml-parser              sowing
bismark                   gdbm                   json-cwx         miniconda3              perl-yaml-libyaml            spades
bison                     geant4                 json-glib        minife                  petsc                        sparsehash
bitmap                    gemmlowp               judy             minigmg                 pixman                       sqlite
blast2go                  genomefinisher         julia            minimap2                pkgconf                      squid
blast-plus                geopm                  k8               miniqmc                 pocl                         subversion
blat                      geos                   kahip            minisign                presentproto                 suite-sparse
blaze                     gettext                kaks-calculator  minitri                 proj                         sundials
blis                      gflags                 karma            minivite                protobuf                     superlu
bliss                     ghostscript-fonts      kbproto          minuit                  py-argparse                  superlu-dist
blitz                     giflib                 kentutils        mitofates               py-biopython                 swig
bmake                     git                    kibana           mixcr                   py-bottleneck                sz
bml                       git-fat-git            kim-api          mkfontdir               py-bx-python                 tabix
bolt                      git-imerge             kmergenie        mkfontscale             py-certifi                   tar
bookleaf-cpp              git-lfs                kokkos           mlhka                   py-cffi                      tcl
boost                     glew                   kraken           mmg                     py-cycler                    tetgen
boostmplcartesianproduct  glfmultiples           krb5             moab                    py-cython                    tethex
bowtie                    glib                   krims            modern-wheel            py-dateutil                  texinfo
bowtie2                   glibmm                 kripke           mongo-cxx-driver        py-docutils                  texlive
boxlib                    glimmer                kvtree           mono                    py-filelock                  tk
bpp-core                  glm                    ladot            mosh                    py-functools32               tmux
bpp-phyl                  global                 lcms             mothur                  py-kiwisolver                tophat
bpp-seq                   globalarrays           ldc-bootstrap    motif                   py-lit                       trapproto
bpp-suite                 globus-toolkit         libaio           mount-point-attributes  py-mako                      trilinos
bracken                   glog                   libarchive       mozjs                   py-mappy                     typhon
branson                   glpk                   libassuan        mpark-variant           py-markupsafe                udunits2
breseq                    glproto                libatomic-ops    mpc                     py-matplotlib                unzip
bridger                   gmake                  libbeagle        mpdecimal               py-mpi4py                    util-macros
brigand                   gmap-gsnap             libbsd           mpe2                    py-natsort                   varscan
brotli                    gmime                  libbson          mpest                   py-numexpr                   vcftools
bsseeker2                 gmodel                 libcerf          mpfr                    py-numpy                     videoproto
bucky                     gmp                    libcircle        mpibash                 py-pandas                    vsearch
bumpversion               gmsh                   libconfig        mpich                   py-pillow                    vt
busco                     gnat                   libdivsufsort    mpifileutils            py-protobuf                  wget
bwa                       gnupg                  libdrm           mpileaks                py-py2neo                    wtdbg2
byobu                     gnuplot                libdwarf         mpip                    py-pycparser                 xbitmaps
bzip2                     gnutls                 libedit          mpir                    py-pygments                  xcb-proto
cabana                    go                     libevent         mrbayes                 py-pyparsing                 xcb-util
cairo                     gobject-introspection  libfabric        mscgen                  py-pysam                     xcb-util-image
cairomm                   go-bootstrap           libffi           msgpack-c               py-pysocks                   xcb-util-keysyms
callpath                  googletest             libfontenc       mshadow                 py-pytz                      xcb-util-renderutil
c-blosc                   gotcha                 libfs            msmc                    py-pyyaml                    xcb-util-wm
cdbfasta                  gource                 libgcrypt        multitail               py-requests                  xerces-c
cfitsio                   gperf                  libgd            multitime               py-scipy                     xextproto
cgm                       gperftools             libgeotiff       multiverso              py-setuptools                xkbcomp
cgns                      gpgme                  libgpg-error     mumps                   py-setuptools-scm            xkbdata
chapel                    grackle                libgtextutils    munge                   py-six                       xproto
charmpp                   gradle                 libharu          muparser                py-subprocess32              xtrans
cityhash                  graph500               libhio           muscle                  python                       xz
clapack                   graphlib               libiberty        muse                    py-zope-event                yaml-cpp
clfft                     graphmap               libice           muster                  qhull                        yasm
clhep                     graphviz               libiconv         mxml                    qjson                        zeromq
c-lime                    grass                  libidn2          mysql                   qmcpack                      zfp
clingo                    grib-api               libjpeg-turbo    nano                    qmd-progress                 zlib
cmake                     gromacs                libksba          nanoflann               qorts                        zsh
colm                      gsl                    libmaxminddb     nanopb                  qrupdate                     zstd
compositeproto            gslib                  libmng           nasm                    qt
cuda                      gtkorvo-atl            libmongoc        nauty                   qt-creator
curl                      gtkorvo-cercs-env      libmonitor       ncbi-magicblast         qthreads
czmq                      gtkorvo-dill           libnl            ncbi-rmblastn           quantum-espresso
damageproto               gtkorvo-enet           libpciaccess     ncurses                 qwt
```

## Donate

Alipay: 

![donate](https://raw.githubusercontent.com/openbiox/openbiox-wiki/master/static/img/QRcode.png)

## Maintainer

- [@Jianfeng](https://github.com/Miachol)

## LICENSE

MIT
