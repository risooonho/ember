add_library(lua OBJECT
        LuaHelper.cpp LuaScriptingProvider.cpp luaobject.cpp LuaScriptingCallContext.cpp Connectors.cpp Connector.cpp LuaConsoleObject.cpp
        Connectors_impl.h embertolua++.h)


wf_generate_lua_bindings(bindings/lua/Lua)
