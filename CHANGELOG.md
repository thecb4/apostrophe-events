### 2.1.0

Added `start` and `and` cursor filters.

### 2.0.2

Added `year`, `month` and `day` cursor filters, which are suitable for use with the `piecesFilters` option.

### 2.0.1

Fixed a significant performance bug. The events widget was fetching *every* widget rather than just those with the appropriate IDs. The set of results was then being winnowed by the algorithm for handling many widgets with one query, but not before considerable resources were spent fetching areas for those events, etc.
