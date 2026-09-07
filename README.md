# win32-agent

A win32 CLI agent. Supposed to compile on C++ 6.0, but I cannot test that at this time.
OS Target: Vista minimum
WinHTTP to be used in modern Windows (10/11)

DPAPI to be used to encrypt the key at rest.

Must support usage like this:
`agent 'Five names for a cat'` (aka direct in terminal)
