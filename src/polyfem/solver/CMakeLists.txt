set(SOURCES
	ALSolver.cpp
	ALSolver.hpp
	GarmentNLProblem.cpp
	GarmentNLProblem.hpp
	FullNLProblem.cpp
	FullNLProblem.hpp
)

source_group(TREE "${CMAKE_CURRENT_SOURCE_DIR}" PREFIX "Source Files" FILES ${SOURCES})
target_sources(polyfem PRIVATE ${SOURCES})

# ###############################################################################
# Subfolders
# ###############################################################################
add_subdirectory(forms)
