add_subdirectory( IlmCtl )
add_subdirectory( IlmCtlMath )
add_subdirectory( IlmCtlSimd )

if ( OpenEXR_FOUND )
  endif()

add_subdirectory( dpx )

add_custom_target( CTL DEPENDS IlmCtl IlmCtlMath IlmCtlSimd )

### TODO: Add install, pkgconfig stuff
