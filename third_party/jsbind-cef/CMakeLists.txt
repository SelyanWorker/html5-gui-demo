set(JSBIND_CEF TRUE)
set(JSBIND_TARGET_NAME jsbind-cef)
set(JSBIND_JS_BACKEND_LIBS cefdll_wrapper)
include(../jsbind/code/jsbind.cmake)
set_target_properties(jsbind-cef PROPERTIES FOLDER "third_party")
