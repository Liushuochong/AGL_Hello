boost_dep = dependency(modules : ['system' ])
cxx = meson.get_compiler('cpp')

src =  ['main.cpp']
executable('agl-service-helloworld',
           src,
           dependencies: [systemd_dep],
           install: true,
           install_dir : get_option('sbindir'))
