cmake_minimum_required(VERSION 4.0)
project(TP_ARBRES C)

set(CMAKE_C_STANDARD 23)

add_executable(
        TP_ARBRES exerciceArbres/main.c
        structure.h
        exerciceArbres/exerciceArbres.c
        exerciceArbres/fonctionArbre.c
)

add_executable(
        TP_TAS exerciceTas/main.c
        structure.h
        exerciceArbres/exerciceArbres.c
        exerciceArbres/fonctionArbre.c
        exerciceTas/exerciceTas.c
        exerciceTas/main.c
)
