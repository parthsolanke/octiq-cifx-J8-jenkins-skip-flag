# CI detection fixture

Python repo. `pytest --collect-only` collects but runs nothing, so the skip list must reject it before the test patterns match.

Expected verdict line in the Octiq chat:

    anything EXCEPT 'Tests required'
