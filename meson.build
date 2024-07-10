project('tableauhyperapi')

compiler = meson.get_compiler('cpp')
incdir = include_directories('include')

hyper_dep = declare_dependency(
    dependencies: [compiler.find_library('tableauhyperapi', dirs: meson.current_source_dir() / 'lib')],
    include_directories: [incdir],
)
