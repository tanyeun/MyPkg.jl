# MyPkg

[![Build Status](https://travis-ci.com/tanyeun/MyPkg.jl.svg?branch=main)](https://travis-ci.com/tanyeun/MyPkg.jl)
[![Build Status](https://ci.appveyor.com/api/projects/status/github/tanyeun/MyPkg.jl?svg=true)](https://ci.appveyor.com/project/tanyeun/MyPkg-jl)
[![Coverage](https://codecov.io/gh/tanyeun/MyPkg.jl/branch/main/graph/badge.svg)](https://codecov.io/gh/tanyeun/MyPkg.jl)
[![Coverage](https://coveralls.io/repos/github/tanyeun/MyPkg.jl/badge.svg?branch=main)](https://coveralls.io/github/tanyeun/MyPkg.jl?branch=main)

pkg> add PkgTemplates
> using PkgTemplates
> t = Template(;
         user="tanyeun",
         license="MIT",
         authors=["David Lee"],
         plugins=[
           TravisCI(),
           Codecov(),
           Coveralls(),
           AppVeyor(),
         ],
       )
# In Julia REPL, press ESC+Enter to edit next line
# press Enter will execute

> generate("MyPkg", t)
