# spack-cache  <img src="https://raw.githubusercontent.com/openbiox/openbiox-wiki/master/static/img/logo-long.png" align="right" alt="openbiox" width="200"/>

<img src="https://img.shields.io/badge/lifecycle-experimental-orange.svg" alt="Life cycle: experimental"> <img src="https://img.shields.io/github/repo-size/openbiox/spack-cache.svg" alt="Repo size"/> <img src="https://img.shields.io/github/issues/openbiox/spack-cache.svg" alt="issues"/>

[spack-cache](https://github.com/openbiox/spack-cache) is a project to provide the cache files of [spack](https://github.com/spack/spack), a flexible package manager that supports multiple versions, configurations, platforms, and compilers.

Packages supported by [spack](https://github.com/spack/spack) are available [here](https://spack.readthedocs.io/en/latest/basic_usage.html#listing-available-packages).

Noteably, all cache files provided in this project (phase1: [weiyun](https://share.weiyun.com/5l7vgR7)) can directly be used by spack to perform downstream installtion steps. If you download all the files in this project, you will be able to deploy several useful data analysis environment locally and offline.

```bash
# 2019-05-21
abinit                    g4tendl                libbeagle          med                          proj
abyss                     gapbs                  libbsd             megahit                      protobuf
ack                       gapcloser              libbson            memaxes                      py-argparse
activeharmony             gasnet                 libcanberra        memkind                      py-biopython
acts-core                 gatk                   libcap             mercurial                    py-bottleneck
adept-utils               gawk                   libceed            mercury                      py-bx-python
adios                     gblocks                libcerf            mesa                         py-certifi
adios2                    gcc                    libcheck           mesa-glu                     py-cffi
adlbx                     gccmakedep             libcint            meshkit                      py-cycler
adol-c                    gccxml                 libcircle          meson                        py-cython
aida                      gconf                  libconfig          mesquite                     py-dateutil
albert                    gcta                   libcroco           metabat                      py-docutils
alglib                    gdal                   libctl             metaphysicl                  py-filelock
alsa-lib                  gdbm                   libdivsufsort      metis                        py-functools32
amg                       geant4                 libdmx             microbiomeutil               py-kiwisolver
amg2013                   gemmlowp               libdrm             migrate                      py-lit
ampliconnoise             genomefinisher         libdwarf           minced                       py-mako
amrex                     geopm                  libeatmydata       miniaero                     py-mappy
amrvis                    geos                   libedit            miniamr                      py-markupsafe
andi                      gettext                libelf             miniasm                      py-matplotlib
angsd                     gflags                 libemos            miniconda2                   py-mpi4py
ant                       ghostscript-fonts      libepoxy           miniconda3                   py-natsort
antlr                     giflib                 libevent           minife                       py-numexpr
ants                      git                    libevpath          minigmg                      py-numpy
applewmproto              git-fat-git            libfabric          minimap2                     py-pandas
appres                    git-imerge             libffi             miniqmc                      py-pillow
apr                       git-lfs                libffs             minisign                     py-protobuf
apr-util                  glew                   libfontenc         minitri                      py-py2neo
aragorn                   glfmultiples           libfs              minivite                     py-pycparser
argobots                  glib                   libgcrypt          minuit                       py-pygments
argp-standalone           glibmm                 libgd              mitofates                    py-pyparsing
argtable                  glimmer                libgeotiff         mixcr                        py-pysam
armadillo                 glm                    libgit2            mkfontdir                    py-pysocks
arm-forge                 global                 libgpg-error       mkfontscale                  py-pytz
arpack-ng                 globalarrays           libgpuarray        mlhka                        py-pyyaml
arrow                     globus-toolkit         libgridxc          mmg                          py-requests
asciidoc                  glog                   libgtextutils      moab                         py-scipy
asciidoctor               glpk                   libharu            modern-wheel                 py-setuptools
aspcud                    glproto                libhio             mongo-cxx-driver             py-setuptools-scm
aspect                    gmake                  libiberty          mono                         py-six
aspell                    gmap-gsnap             libice             mosh                         py-subprocess32
aspell6-de                gmime                  libiconv           mothur                       python
aspell6-en                gmodel                 libidn2            motif                        py-zope-event
aspell6-es                gmp                    libint             mount-point-attributes       qhull
aspera-cli                gmsh                   libjpeg            mozjs                        qjson
assimp                    gnat                   libjpeg-turbo      mpark-variant                qmcpack
astral                    gnupg                  libksba            mpc                          qmd-progress
astyle                    gnuplot                liblbxutil         mpdecimal                    qorts
atlas                     gnutls                 liblockfile        mpe2                         qrupdate
at-spi2-core              go                     libmatheval        mpest                        qt
augustus                  gobject-introspection  libmaxminddb       mpfr                         qt-creator
autoconf                  go-bootstrap           libmng             mpibash                      qthreads
automake                  googletest             libmongoc          mpich                        quantum-espresso
axel                      gotcha                 libmonitor         mpifileutils                 qwt
bamtools                  gource                 libnbc             mpileaks                     r
bash                      gperf                  libnl              mpip                         r3d
bash-completion           gperftools             libnova            mpir                         racon
bcftools                  gpgme                  libnsl             mrbayes                      ragel
bdw-gc                    grackle                libogg             mscgen                       raja
beast1                    gradle                 liboldx            msgpack-c                    randfold
beast2                    graph500               libpcap            mshadow                      random123
bedops                    graphlib               libpciaccess       msmc                         randrproto
bedtools2                 graphmap               libpfm4            multitail                    range-v3
beforelight               graphviz               libpipeline        multitime                    rankstr
benchmark                 grass                  libplist           multiverso                   rapidjson
berkeley-db               grib-api               libpng             mumps                        r-assertthat
bertini                   gromacs                libpsl             munge                        ravel
bigreqsproto              gsl                    libpthread-stubs   muparser                     raxml
binutils                  gslib                  libquo             muscle                       ray
bioawk                    gtkorvo-atl            libseccomp         muse                         r-base64enc
biobloom                  gtkorvo-cercs-env      libsharp           muster                       r-biocgenerics
bismark                   gtkorvo-dill           libsigcpp          mxml                         r-biom-utils
bison                     gtkorvo-enet           libsigsegv         mysql                        rclone
bitmap                    gts                    libsm              nano                         r-crayon
blast2go                  guile                  libsodium          nanoflann                    r-dbi
blast-plus                h5part                 libspatialindex    nanopb                       rdma-core
blat                      h5utils                libspatialite      nasm                         rdp-classifier
blaze                     h5z-zfp                libsplash          nauty                        re2c
blis                      hadoop                 libssh             ncbi-magicblast              readfq
bliss                     hapcut2                libssh2            ncbi-rmblastn                readline
blitz                     hapdip                 libsvm             nccl                         recordproto
bmake                     haploview              libszip            nccmp                        redis
bml                       harfbuzz               libtasn1           ncdu                         redset
bolt                      hdf                    libtermkey         ncftp                        rempi
bookleaf-cpp              hdf5                   libtiff            nco                          rename
boost                     help2man               libtirpc           ncurses                      rendercheck
boostmplcartesianproduct  hepmc                  libtool            ncview                       renderproto
bowtie                    heppdt                 libunistring       ndiff                        resourceproto
bowtie2                   highfive               libunwind          nek5000                      r-expint
boxlib                    highwayhash            libusb             nekbone                      rhash
bpp-core                  hiop                   libusbmuxd         nekcem                       rlwrap
bpp-phyl                  hisat2                 libuuid            nektar                       rmats
bpp-seq                   hisea                  libuv              nest                         rna-seqc
bpp-suite                 hmmer                  libvorbis          netcdf                       rngstreams
bracken                   hpctoolkit             libvterm           netcdf-cxx                   rocksdb
branson                   hpcviewer              libwebsockets      netcdf-cxx4                  routino
breseq                    hpgmg                  libwindowswm       netcdf-fortran               rpcsvc-proto
bridger                   hpl                    libx11             netgauge                     r-rcpp
brigand                   hpx                    libxau             netgen                       r-rjava
brotli                    hsakmt                 libxaw             netlib-lapack                r-rmysql
bsseeker2                 htop                   libxaw3d           netlib-scalapack             rsbench
bucky                     htslib                 libxc              netlib-xblas                 rstart
bumpversion               httpie                 libxcb             nettle                       rsync
busco                     hugo                   libxcomposite      nextflow                     ruby
bwa                       hunspell               libxcursor         nfft                         ruby-ronn
byobu                     hwloc                  libxdamage         nghttp2                      rust
bzip2                     hybpiper               libxdmcp           nginx                        sailfish
cabana                    hydra                  libxevie           ngmlr                        salmon
cairo                     hydrogen               libxext            ninja                        samtools
cairomm                   hyphy                  libxfixes          ninja-fortran                scons
callpath                  hypre                  libxfont           nix                          scotch
c-blosc                   iceauth                libxfont2          nlohmann-json                scrnsaverproto
cdbfasta                  icet                   libxfontcache      nlopt                        sdl2
cfitsio                   ico                    libxft             nmap                         sdl2-image
cgal                      icu4c                  libxi              nnvm                         sdsl-lite
cgm                       id3lib                 libxinerama        node-js                      serf
cgns                      idba                   libxkbcommon       npb                          silo
chapel                    igraph                 libxkbfile         npm                          slepc
charmpp                   ilmbase                libxkbui           npth                         slurm
cityhash                  imake                  libxml2            nspr                         snappy
clapack                   imp                    libxmu             numactl                      sniffles
clfft                     impute2                libxp              numdiff                      snpeff
clhep                     infernal               libxpm             nvptx-tools                  snptest
c-lime                    inputproto             libxpresent        nwchem                       soapdenovo2
clingo                    intel-daal             libxprintapputil   nyancat                      soapdenovo-trans
cmake                     intel-gpu-tools        libxprintutil      occa                         sofa-c
colm                      intel-mkl              libxrandr          oce                          somatic-sniper
commons-lang              intel-mpi              libxrender         oclint                       sortmerna
commons-logging           intel-pin              libxres            oclock                       sowing
compositeproto            intel-tbb              libxscrnsaver      octave                       spades
cuda                      intel-xed              libxshmfence       octave-optim                 sparsehash
curl                      intltool               libxslt            octave-splines               sqlite
czmq                      ior                    libxsmm            octave-struct                squid
damageproto               iozone                 libxstream         octopus                      subversion
dbus                      iperf2                 libxt              oniguruma                    suite-sparse
dealii                    iperf3                 libxtrap           openblas                     sundials
diffutils                 isaac                  libxtst            openfoam-com                 superlu
dmd                       isaac-server           libxv              openjdk                      superlu-dist
dmlc-core                 isl                    libxvmc            openjpeg                     swig
dmxproto                  itstool                libxxf86dga        openmpi                      sz
docbook-xml               itsx                   libxxf86misc       openpa                       tabix
docbook-xsl               jackcess               libxxf86vm         openssl                      tar
double-conversion         jags                   libyaml            otf                          tcl
doxygen                   jansson                libyogrt           otf2                         tetgen
dri2proto                 jasper                 libzip             p4est                        tethex
dri3proto                 jbigkit                lighttpd           pal                          texinfo
dtcmp                     jdk                    likwid             paml                         texlive
dyninst                   jellyfish              linkphase3         pandaseq                     tk
eccodes                   jemalloc               linux-headers      pango                        tmux
editline                  jmol                   listres            papi                         tophat
eigen                     jq                     llvm               papyrus                      trapproto
elfutils                  json-c                 llvm-openmp-ompt   parallel                     trilinos
environment-modules       jsoncpp                lmdb               parallel-netcdf              typhon
erfa                      json-cwx               lmod               parmetis                     udunits2
evieext                   json-glib              lm-sensors         pbbam                        unibilium
exmcutils                 judy                   lndir              pcre                         unzip
exonerate                 julia                  log4cplus          pcre2                        util-macros
expat                     k8                     log4cxx            perl                         varscan
exuberant-ctags           kahip                  loki               perl-capture-tiny            vcftools
fastphase                 kaks-calculator        lordec             perl-data-dumper             videoproto
fastqc                    kallisto               lrslib             perl-encode-locale           vsearch
fastqvalidator            karma                  lrzip              perl-exporter-tiny           vt
fasttree                  kbproto                ltrace             perl-extutils-makemaker      wget
fastx-toolkit             kdiff3                 lua                perl-extutils-pkgconfig      windowswmproto
fftw                      kentutils              lua-bitlib         perl-file-copy-recursive     wtdbg2
findutils                 kibana                 lua-jit            perl-file-sharedir-install   xbitmaps
fixesproto                kim-api                lua-lpeg           perl-gd                      xcb-proto
flatbuffers               kmergenie              lua-luafilesystem  perl-gd-graph                xcb-util
flex                      kokkos                 lua-luaposix       perl-gdgraph-histogram       xcb-util-image
flux-core                 kraken                 lua-mpack          perl-gd-text                 xcb-util-keysyms
flux-sched                krb5                   luit               perl-http-date               xcb-util-renderutil
fmt                       krims                  lulesh             perl-inline                  xcb-util-wm
fontcacheproto            kripke                 lwgrp              perl-inline-c                xcmiscproto
fontconfig                kvtree                 lz4                perl-list-moreutils          xerces-c
fontsproto                ladot                  lzma               perl-math-cdf                xextproto
fonttosfnt                lammps                 lzo                perl-math-cephes             xf86dgaproto
font-util                 last                   m4                 perl-module-build            xf86driproto
font-xfree86-type1        lastz                  mad-numdiff        perl-parallel-forkmanager    xf86miscproto
fpc                       latte                  mafft              perl-parse-recdescent        xf86vidmodeproto
fqtrim                    launchmon              magics             perl-pegex                   xineramaproto
freebayes                 lazyten                magma              perl-perl6-slurp             xkbcomp
freetype                  lbxproxy               makedepend         perl-statistics-descriptive  xkbdata
freexl                    lbzip2                 mallocmc           perl-sub-uplevel             xorg-server
fslsfonts                 lcals                  manta              perl-test-exception          xproto
fstobdf                   lcms                   mapserver          perl-test-needs              xproxymanagementprotocol
fyba                      ldc-bootstrap          mariadb            perl-test-warn               xtrans
fzf                       legion                 mariadb-c-client   perl-uri                     xz
g4abla                    lemon                  masa               perl-xml-parser              yaml-cpp
g4emlow                   leveldb                matio              perl-yaml-libyaml            yasm
g4ensdfstate              lftp                   maven              petsc                        zeromq
g4ndl                     libaec                 maverick           pixman                       zfp
g4neutronxs               libaio                 mawk               pkgconf                      zip
g4photonevaporation       libapplewm             mbedtls            pngwriter                    zlib
g4pii                     libarchive             mc                 pocl                         zsh
g4radioactivedecay        libassuan              mcl                presentproto                 zstd
g4saiddata                libatomic-ops          mdtest             printproto
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
