# This file is part of the dune-xt project:
#   https://github.com/dune-community/dune-xt
# The copyright lies with the authors of this file (see below).
# License: BSD 2-Clause License (http://opensource.org/licenses/BSD-2-Clause)
# Authors:
#   Felix Schindler (2016)

set(modules
    DuneXtMacros.cmake
    DuneXtPybindxiUtils.cmake
    FindPythonLibsNew.cmake)

install(FILES ${modules} DESTINATION ${DUNE_INSTALL_MODULEDIR})
