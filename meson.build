project('linmath.h', 'c',
  version: '1.0',
  license: 'MIT')

linmath_dep = declare_dependency(
  compile_args: ['-funroll-loops'],
  link_args: ['-lm'],
  include_directories: './')

t = executable('linmath_test', ['linmath_test.c'], 
  c_args: ['-funroll-loops'],
  link_args: ['-lm'])
test('linmath test', t)
