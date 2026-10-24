project('SourceTabs', 'c',
        version : '1.0.0',
        default_options : ['warning_level=3', 'c_std=c99'])

sdl3_dep = dependency('sdl3')

SourceTabs = executable('SourceTabs', 'main.c',
                        dependencies : sdl3_dep,
                        install : true)

test('test', SourceTabs)