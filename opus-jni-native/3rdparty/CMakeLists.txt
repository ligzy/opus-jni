############
# Add Opus #
############

# Thanks to someone having an old CPU :)
set(AVX_SUPPORTED OFF CACHE BOOL "" FORCE)
set(OPUS_X86_MAY_HAVE_SSE OFF CACHE BOOL "" FORCE)
set(OPUS_X86_MAY_HAVE_SSE2 OFF CACHE BOOL "" FORCE)
set(OPUS_X86_MAY_HAVE_SSE4_1 OFF CACHE BOOL "" FORCE)
set(OPUS_X86_MAY_HAVE_AVX OFF CACHE BOOL "" FORCE)
set(OPUS_X86_PRESUME_SSE OFF CACHE BOOL "" FORCE)
set(OPUS_X86_PRESUME_SSE2 OFF CACHE BOOL "" FORCE)
set(OPUS_X86_MAY_HAVE_SSE4_1 OFF CACHE BOOL "" FORCE)
set(OPUS_X86_MAY_HAVE_AVX OFF CACHE BOOL "" FORCE)
set(OPUS_ENABLE_FLOAT_API ON CACHE BOOL "" FORCE)
set(OPUS_FIXED_POINT ON CACHE BOOL "" FORCE)
add_subdirectory(opus)
