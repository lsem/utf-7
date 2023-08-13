add_library(skeeto_utf7 utf7.h utf7.c)
target_include_directories(skeeto_utf7 PUBLIC include/)
add_library(skeeto::utf7 ALIAS skeeto_utf7)