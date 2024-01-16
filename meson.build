project(
    'printf',
    'c',
    default_options: ['default_library=static'],
)

printf_inc = include_directories('.')

printf_src = ['printf.c']

printf_lib = library(
    'printf',
    sources: printf_src,
    include_directories: printf_inc,
    install: false,
)

printf_dep = declare_dependency(
    include_directories: printf_inc,
    link_with: printf_lib,
)
