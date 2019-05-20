# spack-cache  <img src="https://raw.githubusercontent.com/openbiox/openbiox-wiki/master/static/img/logo-long.png" align="right" alt="openbiox" width="200"/>

<img src="https://img.shields.io/badge/lifecycle-experimental-orange.svg" alt="Life cycle: experimental"> <img src="https://img.shields.io/github/repo-size/openbiox/spack-cache.svg" alt="Repo size"/> <img src="https://img.shields.io/github/issues/openbiox/spack-cache.svg" alt="issues"/>

[spack-cache](https://github.com/openbiox/spack-cache) is a project to provide the cache files of [spack](https://github.com/spack/spack), a flexible package manager that supports multiple versions, configurations, platforms, and compilers.

Packages supported by [spack](https://github.com/spack/spack) are available [here](https://spack.readthedocs.io/en/latest/basic_usage.html#listing-available-packages).

Noteably, all cache files provided in this project (phase1: [weiyun](https://share.weiyun.com/5N0BRKn)) can directly be used by spack to perform downstream installtion steps. If you download all the files in this project, you will be able to deploy several useful data analysis environment locally and offline.

```bash
# 2019-05-20
abinit                    bpp-phyl             glib                   libice            ninja                        readline
abyss                     bpp-seq              glm                    libiconv          node-js                      renderproto
ack                       bpp-suite            glproto                libidn2           npm                          r-expint
activeharmony             bracken              gmake                  libjpeg-turbo     numactl                      rhash
acts-core                 branson              gmp                    libmaxminddb      oce                          rlwrap
adept-utils               breseq               gmsh                   libmng            oniguruma                    r-rcpp
adios                     bridger              gnuplot                libpciaccess      openblas                     r-rjava
adios2                    brigand              gnutls                 libpng            openjdk                      r-rmysql
adlbx                     brotli               go                     libpthread-stubs  openmpi                      rsbench
adol-c                    bwa                  gobject-introspection  libsigsegv        openpa                       rsync
aida                      bzip2                go-bootstrap           libsm             openssl                      ruby
albert                    cairo                gperf                  libsodium         p4est                        rust
alglib                    c-blosc              graphviz               libsvm            pal                          sailfish
alsa-lib                  cfitsio              gsl                    libtiff           paml                         salmon
amg                       cgm                  gslib                  libtool           pandaseq                     samtools
amg2013                   cgns                 gtkorvo-atl            libunistring      pango                        scons
ampliconnoise             chapel               gtkorvo-cercs-env      libuuid           papi                         scrnsaverproto
amrex                     cityhash             gtkorvo-dill           libuv             papyrus                      sdsl-lite
amrvis                    clapack              gtkorvo-enet           libx11            parallel                     serf
andi                      clingo               haploview              libxau            parallel-netcdf              slepc
angsd                     cmake                harfbuzz               libxaw            parmetis                     slurm
ant                       compositeproto       hdf5                   libxc             pbbam                        snappy
antlr                     cuda                 help2man               libxcb            pcre                         sniffles
ants                      curl                 hisat2                 libxcomposite     pcre2                        snpeff
applewmproto              czmq                 hmmer                  libxdamage        perl                         snptest
appres                    damageproto          htslib                 libxdmcp          perl-capture-tiny            soapdenovo2
apr                       dealii               hwloc                  libxext           perl-data-dumper             soapdenovo-trans
apr-util                  diffutils            hypre                  libxfixes         perl-encode-locale           sofa-c
aragorn                   docbook-xml          icu4c                  libxft            perl-exporter-tiny           somatic-sniper
argobots                  docbook-xsl          id3lib                 libxkbcommon      perl-extutils-makemaker      sortmerna
argp-standalone           double-conversion    inputproto             libxkbfile        perl-extutils-pkgconfig      sowing
argtable                  doxygen              intel-tbb              libxml2           perl-gd                      sparsehash
armadillo                 eigen                isl                    libxmu            perl-gd-graph                sqlite
arm-forge                 environment-modules  jansson                libxpm            perl-gdgraph-histogram       subversion
arpack-ng                 erfa                 jasper                 libxrender        perl-gd-text                 suite-sparse
arrow                     exmcutils            jbigkit                libxscrnsaver     perl-http-date               sundials
asciidoc                  expat                jdk                    libxshmfence      perl-list-moreutils          superlu
asciidoctor               fastphase            jellyfish              libxslt           perl-math-cdf                superlu-dist
aspcud                    fastqc               jemalloc               libxt             perl-module-build            swig
aspect                    fastqvalidator       jmol                   libxv             perl-parallel-forkmanager    sz
aspell                    fasttree             jq                     libxvmc           perl-statistics-descriptive  tar
aspell6-de                fastx-toolkit        json-c                 libzip            perl-sub-uplevel             tcl
aspell6-en                fftw                 jsoncpp                llvm              perl-test-exception          tetgen
aspell6-es                fixesproto           json-cwx               llvm-openmp-ompt  perl-test-needs              tethex
aspera-cli                flatbuffers          json-glib              lmdb              perl-uri                     texinfo
assimp                    flex                 judy                   lua               perl-xml-parser              texlive
augustus                  flux-core            julia                  lua-luaposix      petsc                        tk
autoconf                  flux-sched           k8                     lz4               pixman                       tmux
automake                  fontcacheproto       kahip                  lzo               pkgconf                      tophat
axel                      fontconfig           kaks-calculator        m4                presentproto                 trapproto
bamtools                  fontsproto           karma                  mariadb           proj                         trilinos
bash                      fonttosfnt           kbproto                matio             py-argparse                  typhon
bcftools                  font-util            kentutils              mercurial         py-certifi                   udunits2
beast1                    font-xfree86-type1   kibana                 mercury           py-cffi                      unzip
beast2                    fpc                  kim-api                mesa              py-cython                    util-macros
bedops                    fqtrim               kmergenie              mesa-glu          py-docutils                  varscan
bedtools2                 freebayes            kokkos                 meshkit           py-filelock                  vcftools
beforelight               freetype             kraken                 meson             py-lit                       videoproto
benchmark                 freexl               krb5                   mesquite          py-mako                      vsearch
berkeley-db               fslsfonts            krims                  metabat           py-mappy                     vt
bertini                   fstobdf              kripke                 metaphysicl       py-markupsafe                wget
bigreqsproto              fyba                 kvtree                 metis             py-mpi4py                    wtdbg2
binutils                  fzf                  ladot                  miniconda3        py-numpy                     xbitmaps
bioawk                    g4abla               lcms                   minigmg           py-py2neo                    xcb-proto
biobloom                  g4emlow              ldc-bootstrap          mixcr             py-pycparser                 xcb-util
bismark                   g4ensdfstate         libaio                 mkfontdir         py-pygments                  xcb-util-image
bison                     g4ndl                libarchive             mkfontscale       py-pysam                     xcb-util-keysyms
bitmap                    g4neutronxs          libbeagle              moab              py-pyyaml                    xcb-util-renderutil
blast2go                  g4photonevaporation  libbsd                 motif             py-setuptools                xcb-util-wm
blast-plus                g4pii                libcerf                mpc               py-setuptools-scm            xextproto
blat                      g4radioactivedecay   libconfig              mpfr              py-six                       xkbcomp
blaze                     g4saiddata           libdivsufsort          mumps             python                       xkbdata
blis                      g4tendl              libedit                munge             py-zope-event                xproto
bliss                     gapbs                libevent               muparser          qhull                        xtrans
blitz                     gapcloser            libfabric              mysql             qjson                        xz
bmake                     gasnet               libffi                 nanoflann         qt                           yaml-cpp
bml                       gawk                 libfontenc             nasm              quantum-espresso             zeromq
bolt                      gblocks              libfs                  ncbi-rmblastn     r                            zfp
bookleaf-cpp              gcc                  libgcrypt              ncurses           rapidjson                    zlib
boost                     gccmakedep           libgd                  netcdf            r-assertthat                 zsh
boostmplcartesianproduct  gdal                 libgeotiff             netcdf-cxx        r-base64enc                  zstd
bowtie                    gdbm                 libgpg-error           netgauge          r-biom-utils
bowtie2                   geos                 libgtextutils          netgen            r-crayon
boxlib                    gettext              libharu                netlib-scalapack  r-dbi
bpp-core                  git                  libhio                 nettle            re2c
```

## Donate

Alipay: 

![donate](https://raw.githubusercontent.com/openbiox/openbiox-wiki/master/static/img/QRcode.png)

## Maintainer

- [@Jianfeng](https://github.com/Miachol)

## LICENSE

MIT
