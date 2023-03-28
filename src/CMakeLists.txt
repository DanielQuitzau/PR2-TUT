project(src)

## Dummy-Dateien können gelöscht werden, sobald neue Datien hier hinzugefügt wurden
set(SOURCE_FILES
        Dummy.cpp Dummy.h
        )

add_library(src STATIC ${SOURCE_FILES})