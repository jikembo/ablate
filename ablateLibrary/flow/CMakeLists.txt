target_sources(ablateLibrary
        PUBLIC
        flow.hpp
        flow.cpp
        flowFieldDescriptor.hpp
        lowMachFlow.hpp
        lowMachFlow.cpp
        incompressibleFlow.hpp
        incompressibleFlow.cpp
        fvFlow.hpp
        fvFlow.cpp
        compressibleFlow.cpp
        compressibleFlow.hpp
        )

add_subdirectory(boundaryConditions)
add_subdirectory(fluxDifferencer)