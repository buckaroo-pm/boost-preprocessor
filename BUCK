load('//:subdir_glob.bzl', 'subdir_glob')

prebuilt_cxx_library(
  name = 'preprocessor',
  header_namespace = 'boost',
  header_only = True,
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
)
