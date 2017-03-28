include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'lockfree', 
  header_namespace = 'boost/lockfree',
  exported_headers = subdir_glob([
    ('include/boost/lockfree', '**/*.hpp'),
  ]),
  visbility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
