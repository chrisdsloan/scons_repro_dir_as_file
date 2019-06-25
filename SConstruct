base_env = Environment()
Progress('Evaluating $TARGET\n')

env = base_env.Clone(src_subdirs = ['subdir_1'])
Export('env')
SConscript('src/SConscript', variant_dir = 'build/variant_1', duplicate = 0)

env = base_env.Clone(src_subdirs = ['subdir_2'])
Export('env')
SConscript('src/SConscript', variant_dir = 'build/variant_2', duplicate = 0)
