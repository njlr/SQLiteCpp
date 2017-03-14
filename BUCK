cxx_library(
  name = 'sqlite3',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('sqlite3', '*.h'),
  ]),
  srcs = glob([
    'sqlite3/*.c',
  ]),
)

cxx_library(
  name = 'sqlitecpp',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('src', '*.h'),
  ]),
  srcs = glob([
    'src/*.cpp',
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = [
    ':sqlite3',
  ],
)
