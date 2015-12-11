## consenus.final()
This function is passed a matrix named *data* where each column is an item and each row is a membership vector corresponding to a partition of the items according to a clustering method. The elements (numbers) composing each row have no meaning other than indicating membership and are recycled from row to row. The function returns the majority vote partition. When no consensus exists for a particular item, the partition given by the first row wins. Within the framework of graph mining, this allows the partition maximizing the modularity function to win if the partitions are ordered by decreasing values of modularity in the matrix.

## Examples
This file contains examples for the abovelisted functions.
