# lua-jit-tcp-srv
create "jit-tcp-srv" directory in modules directory to keep this files.<br /><br />
Репозиторий не рабочий без разкомментирования:<br />
--[[ local ffi = require "ffi" --]] <br />
.. т.к. у меня ФФИ  сидит в глобале, <br />
и там еще кое-что я правил, что у других работать не будет.<br />

run:<br />
lua:LE(require("jit-tcp-srv.lib_util"))<br />
<img src="Capture.JPG" />
