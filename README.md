<img width="657" alt="image" src="https://github.com/Solvidia/GPU-graphic-stack/assets/166895578/13d9ea73-2268-46d6-958d-488a18405712">

# Solvidia GPU 

Research for an open source graphics stack for Apple M1.

## wrap

Build with the included makefile `make wrap.dylib`, and insert in any Metal application by setting the environment variable `DYLD_INSERT_LIBRARIES=/Users/bloom/gpu/wrap.dylib`.

## Contributors

* Alyssa Rosenzweig (`bloom`) on IRC, working on the command stream and ISA
* marcan, working on kernel side
