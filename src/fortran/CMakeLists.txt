add_executable(stokes_dynamic_fortran stokes_dynamic.F90)

target_link_libraries(stokes_dynamic_fortran PRIVATE opencmisslibs mpi)

install(TARGETS stokes_dynamic_fortran DESTINATION bin)
