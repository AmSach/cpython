bdb: Fix :meth:`bdb.Bdb.clear_all_file_breaks` to not skip breakpoints when multiple
breakpoints share the same file and line. Patch by Aman Sachan.

.. bpo-149015.

http.cookies: Replace potentially backtracking regex with linear-time pattern to prevent ReDoS. GH-149028.

urllib.robotparser: Fix ``can_fetch()`` to use most specific matching rule (longest path) per the robots.txt specification.
