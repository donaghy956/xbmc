set(SOURCES KeyboardEasterEgg.cpp
            KeymapActionMap.cpp
)

set(HEADERS interfaces/IActionMap.h
            interfaces/IKeyboardHandler.h
            interfaces/IKeyboardInputProvider.h
            KeyboardEasterEgg.h
            KeymapActionMap.h
)

core_add_library(input_keyboard)
