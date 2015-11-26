# debug-nodemon-error

Error while using debug library together with nodemon

This works as a charm
DEBUG=foo DEBUG_FD=3 node index.js 3> log

This provides an error
DEBUG=foo DEBUG_FD=3 nodemon index.js 3> log
