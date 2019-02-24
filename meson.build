project('egl-registry', ['c'],   
         meson_version : '>= 0.49.0')




egl_registry_dep = declare_dependency(
  include_directories: include_directories('api')
)




install_subdir('api/EGL', install_dir : 'include')
install_subdir('api/KHR', install_dir : 'include')