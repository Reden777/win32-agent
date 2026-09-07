# win32-agent

A win32 CLI agent. Supposed to compile on C++ 6.0, but I cannot test that at this time.
OS Target: Vista minimum
WinHTTP to be used.
Zero external dependencies

1. [ ] Must support usage like this: `agent 'Five names for a cat'` (aka direct in terminal)
2. [ ] After direct terminal usage is ready, add interactive chat sessions where you write messages and it types back, ana you can add files for it to edit.
3. [ ] DPAPI to be used to encrypt the key at rest.
4. [ ] Strict C++ 6.0 compatibility is not mandatory, Vista support takes precedence
