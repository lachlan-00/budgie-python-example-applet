gnome = import('gnome')

install_data(
    'PyShowDesktop.plugin',
    install_dir: APPLET_INSTALL_DIR
)


install_data(
    'com.solus.budgie-showdesktop.gschema.xml',
    install_dir: join_paths(datadir, 'glib-2.0', 'schemas'),
)

meson.add_install_script('meson_post_install')
